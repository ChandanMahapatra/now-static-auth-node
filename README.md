Example repo for [Now](https://now.sh) static site with basic auth. Based on https://github.com/flawyte/now-basic-auth and https://github.com/wzulfikar/now-static-auth-node

To set env var `AUTH_USERS`, you can either:

1. use `now secret` command: `now secret add auth_users 'user1:user1,user2:user2'`
2. change the value in now.json file of 'AUTH_USERS'

Live demo: https://now-static-auth-node.chandanmahapatra.now.sh/

user: `user1`  \
pass: `user1`
