## About this repository
This repository is personal practice that build authentication API.  
Using **Rails** with **devise**,**devise_token_auth**.

#### Reference
[devise_token_auth Tutorial](http://www.developingandrails.com/2015/02/api-authentication-with-devisetokenauth.html "devise_token_auth tutorial")

#### Getting Start  
Move directory and execute follow commands in terminal.  
`$bundle install --path vendor/bundle`  
`$rake db:migrate`  
`$rails s`  

#### Registration Test
`curl -XPOST -H 'Content-Type: application/json' http://localhost:3000/api/v1/auth -d '{"email": "test1234@test.com", "password": "12345678", "password_confirmation" : "12345678" }'`

#### TODO
TODO: ng_token_auth  
TODO: doorkeeper  
TODO: cancancan  
