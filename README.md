# 2FA-TFB
Register google authenticator
npm i express speakeasy uuid node-json-db
npm i -D nodemon

npm start

http://localhost:9000/api

POST
http://localhost:9000/api/register

JSON
http://localhost:9000/api/verify
{
    "userId":"462abd2a-6798-4066-a6aa-ef17517561b1",
    "token": "294739"
}



JSON
http://localhost:9000/api/validate
{
    "userId":"3f6b26ca-24c9-4896-9725-399c82dd4ad2",
    "token":"992064"
}

API
https://blog.logrocket.com/implementing-two-factor-authentication-using-speakeasy/

android
https://developer.android.com/training/sync-adapters/creating-authenticator#java


price
https://cloud.google.com/identity-platform/pricing


https://www.youtube.com/watch?v=KQya9i6czhM&ab_channel=TraversyMedia
