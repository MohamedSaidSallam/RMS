# RMS

Recipe Management System: a software that aids and organises the cooking and preparing of recipes.

This is the index repo which points to all of the other components of the software.

## **Disclaimer**

> First Large Project. So feedback is appreciated.

## Important Files

- [FAQ.md](FAQ.md)
- [CONTRIBUTORS.md](CONTRIBUTORS.md)

## Repositories

### [RMS_DB]

The database schema, non-recipe data and documentation.

Written for: MS SQL Server

### [RMS_API]

The REST API that provides an interface for the database and useful functionality.

Written in: Python, Flask

### Wrappers

#### [RMS_C#Lib]

A wrapper C# dll for the API functions that provides easy way to interact with the API.

#### [RMS_PyWrapper]

A wrapper python module for the API functions that provides easy way to interact with the API.

### Apps/Clients

| Name             | Platform | Brief Description                                            |
| ---------------- | :------: | ------------------------------------------------------------ |
| [RMS_DesktopApp] | Windows* | A C# desktop GUI App to easly access the API and perform.    |
| [RMS_AndroidApp] | Android  | An Android app that allows easy access to the API.           |
| [RMS_WebApp]     |   Web    | A web interface for the API accessable from any web browser. |

*: I'm willing to experiment with .net core cross platform capabilities in the future.

[RMS_DB]:           https://github.com/TheDigitalPhoenixX/RMS_DB
[RMS_API]:          https://github.com/TheDigitalPhoenixX/RMS_API
[RMS_C#Lib]:        https://github.com/TheDigitalPhoenixX/RMS_C#Lib
[RMS_PyWrapper]:    https://github.com/TheDigitalPhoenixX/RMS_PyWrapper
[RMS_DesktopApp]:   https://github.com/TheDigitalPhoenixX/RMS_DesktopApp
[RMS_AndroidApp]:   https://github.com/TheDigitalPhoenixX/RMS_AndroidApp
[RMS_WebApp]:       https://github.com/TheDigitalPhoenixX/RMS_WebApp
