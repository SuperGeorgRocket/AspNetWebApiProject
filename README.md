# ASP.Net WebApi2 Application with OWIN

Repository contains ready to use preconfigured project to create fully functional production ready RESTful services.

The template uses the 4.7.1 version of .Net Framework. Make sure that you have it installed before use the template.

**Contains**

- CORS enabled
- preconfigured HTTP OPTIONS handler
- Cache-Control header preconfigured
- Autofac as a DI-container
- Content formatter configured to use Json.Net
- AutoMapper
- Unhandled exceptions handler
- Unhandled exceptions logger
- Serilog as a default logger preconfigured to save logs to %AppData%/Logs folder
- Swagger for API documentation
- JWT-Bearer authentication to protect your API with IdentityModel
- Ability to use environment variables in configuration options (web.config)
- Support .env files to easy switching between different environments (DotNetEnv)
- ... and some other boilerplate code

**Getting Started**
1. Restart Visual Studio
1. Click on "File/New Project..." menu item
1. Type "webapi" on the right pane
1. Select "APS.Net WebAPI Application With OWIN" and click OK button.
1. Run the service
1. Open a browser and navigate to http://localhost:5000/swagger/ui/index to see API documentation
1. Play around with the API

Any suggestions and bug reports are very appeciated.
