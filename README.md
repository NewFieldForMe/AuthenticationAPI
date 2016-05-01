## 概要
認証APIサーバ  
TODO: ng_token_auth
TODO: doorkeeper

#### 参考
[devise_token_authのチュートリアル](http://www.developingandrails.com/2015/02/api-authentication-with-devisetokenauth.html "devise_token_auth tutorial")

#### 登録テスト
`curl -XPOST -H 'Content-Type: application/json' http://localhost:3000/api/v1/auth -d '{"email": "test1234@test.com", "password": "12345678", "password_confirmation" : "12345678" }'`
