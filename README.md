# KInspector

[![Join the chat at https://kentico-community.slack.com](https://img.shields.io/badge/join-slack-E6186D.svg)](https://kentico-community.slack.com)
[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-ASK%20NOW-FE7A16.svg?logo=stackoverflow&logoColor=white)](https://stackoverflow.com/tags/kentico-cloud)
[![Build status](https://ci.appveyor.com/api/projects/status/udykjx510v83w9y6?svg=true)](https://ci.appveyor.com/project/kentico/kinspector)
[![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](http://www.firsttimersonly.com/)
[![Github All Releases](https://img.shields.io/github/downloads/kentico/kinspector/total.svg)](https://github.com/Kentico/KInspector/releases)

KInspector is an application for analyzing health, performance and security of your **Kentico** solution. 

KInspector was developed by the consulting department in Kentico to improve the web sites of our customers. Initially, it was an internal application, but we think that every Kentico user can benefit from this app and that's why we made it an open source. 

The application contains three types of modules:
- **Setup** modules help you prepare your instance for testing. You can disable SMTP servers, web farm servers, add a localhost license and so on.
- **Analysis** modules check health and performance. These modules test the database for consistency issues, display common event log errors and recommend some best practices.
- **Security** modules scan for potential security issues, like XSS or SQL injection, throughout the system.

The best thing about KInspector is that it can analyze **any version** of Kentico. 

## Get the application

Download the [latest release](https://github.com/Kentico/KInspector/releases/latest) zip package, unpack it and run the ```Start.cmd```. It automatically opens a new browser window with the [target setup](http://i.imgur.com/D5C0Tbn.png) page. 
> Make sure that you provide all fields with correct values. Some modules work with the database and some with the code. If you don't fill the values correctly, the application will probably throw an error.

Once you pass the setup page, you're ready to start the analysis. On the [main menu](http://i.imgur.com/H7zBQOZ.png) page, select the ```Analysis``` category and run the modules. You will see a page similar to this one:

[![Module results](http://i.imgur.com/UUdTlNL.png)](http://i.imgur.com/Vti1Fo7.png)

Now you can start implementing the suggested improvements.

## Contributing
Want to improve the KInspector? Great! Read the [contributing guidelines](https://github.com/Kentico/KInspector/blob/master/CONTRIBUTING.md) and then [write your first module](https://github.com/Kentico/KInspector/wiki/Writing-a-custom-module) or improve an existing one.

### Watch how to contribute to KInspector on YouTube
[![Check out KInspector on YouTube!](http://img.youtube.com/vi/ixGakcfITe8/0.jpg)](http://www.youtube.com/watch?v=ixGakcfITe8)

If anything feels wrong or incomplete, please let us know. Create a new [issue](https://github.com/Kentico/KInspector/issues/new) or submit a [pull request](https://help.github.com/articles/using-pull-requests/).

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/KInspector?pixel)
