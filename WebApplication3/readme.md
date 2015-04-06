# Readme.md


Tutorial:

Create empty webAPI project in VS 2013
install swashbuckle nuget 
Add this in web.config:
<appSettings>
    <add key="vs:EnableBrowserLink" value="false" />
  </appSettings>
host on iis and browse to:  http://localhost/WebApplication3/swagger/ui/index
Next create a simple controller
Build and run the project on iis
browse to http://localhost/WebApplication3/swagger/


ref: https://discventionstech.wordpress.com/2015/04/06/getting-started-with-swashbuckle/