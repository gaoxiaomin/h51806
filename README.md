# 职位管理系统
>基于express+mongodb的后台职位管理系统
##业务
1.用户注册
2.用户登录
3.注销
4.职位的添加，修改，查询，删除
##前后端分离
前端：
UI
将前端ui放置到public目录下
后端：
API--CRUD
用户注册：
url:"/api/register"
method:'post'
param:
username
password
email
return :JSON
{
  res_code:1,
  res_error:'',
  res_body:{
    data:{
      usename:'xxx'
    }
  }
}
用户登录：
url:"/api/login"
method:'post'
param:
username
password
email
return :JSON
{
  res_code:1,
  res_error:'',
  res_body:{
    data:{
      usename:'xxx'
    }
  }
}
用户注销：
url:"/api/logout"
method:'post'
param:
username
password
email
return :JSON
{
  res_code:1,
  res_error:'',
  res_body:{
    data:{
      status:'success'
    }
  }
}