## 路由
  this.$router 访问路由器
  this.$route 访问当前路由
### $route.params
|模式|匹配路径|$route.params|
|:-|:-:|-:|
|/user/:username|/user/evan|{ username: 'evan' }|
|/user/:username/post/:post_id|/user/evan/post/123|{ username: 'evan', post_id: '123' }|
### $route.query
```
/user?id = 123 & age= 12
```
    获取 this.$route.query