# SpringRESTFull_api_UsingOAuth2

Secure Spring REST API using OAuth2


POST  http://localhost:8080/SpringRESTFull_api_UsingOAuth2/oauth/token?grant_type=password&username=hardik&password=123
      
Authorization     :     Basic bXktdHJ1c3RlZC1jbGllbnQ6c2VjcmV0 
                        
                        {Here, "my-trusted-client:secret" encoded version ="bXktdHJ1c3RlZC1jbGllbnQ6c2VjcmV0"}

Accept            :     application/json

http://localhost:8080/SpringRESTFull_api_UsingOAuth2/oauth/token?grant_type=refresh_token&refresh_token=
      
      
      
      
GET   http://localhost:8080/SpringRESTFull_api_UsingOAuth2/user/?access_token="insert Token Here"

GET   http://localhost:8080/SpringRESTFull_api_UsingOAuth2/user/2/?access_token=

---------------------------------------------------------------------------------------------------------------------
Reference:  1.http://websystique.com/spring-security/secure-spring-rest-api-using-oauth2/

            2.https://www.base64decode.org/

