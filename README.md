# SwashbuckleWebAPIDemo


Tutorial:

* Create empty webAPI project in VS 2013
* install swashbuckle nuget 
* Add this in web.config:

```XML
<appSettings>
    <add key="vs:EnableBrowserLink" value="false" />
  </appSettings>
  ```
* host on iis and browse to:  http://localhost/WebApplication3/swagger/ui/index
* Next create a simple controller
* Build and run the project on iis
* browse to http://localhost/WebApplication3/swagger/. This will redirect to the swagger-UI: http://localhost/WebApplication3/swagger/ui/index
* To view the Swagger Doc for your API, go to: http://localhost:80/WebApplication3/swagger/docs/v1
* Swagger Doc can be used for clients to generate client side code ie proxy, for consuming your API
* Eg. To generate c# client code for say Java, go to http://editor.swagger.io/#/ and in the LHS paste the output from http://localhost:80/WebApplication3/swagger/docs/v1. Next in Menu, clk on Generate Client and select Java
* Note that the above tools doesn't give option to generate c# client code. For that use https://github.com/TimSchlechter/Swagger.Codegen.Net OR https://github.com/catch-software/EnterpriseTester-API-Examples/tree/master/CSharp/ApiClient



ref: https://discventionstech.wordpress.com/2015/04/06/getting-started-with-swashbuckle/
