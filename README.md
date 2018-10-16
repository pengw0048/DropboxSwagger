# DropboxSwagger

Swagger v2.0 (a.k.a. OpenAPI 2.0) definitions and instructions on generating them from Stone API specs

## Why Swagger?

Many third-party platforms use Dropbox APIs to automate their workflows. Microsoft Flow is a popular service where non-programmers can compose logic that interacts with the APIs of different service providers.

However, there is only official support for a set of basic functionalities of Dropbox APIs on Microsoft Flow. They mainly consist of file operations. Dropbox has already launched APIv2 which provides a much richer collection of endpoints. Users have to build their own connectors to use them on Flow.

This project originated from a hack week project and aimed to provide connectors of Dropbox APIv2. It is still much of a proof-of-concept and may be unsupported - use it at your own risk!

## Swagger files

Swagger is specification of RESTful APIs. It is widely accepted, and specifically, can be used directly to create custom connectors on Microsoft Flow.

This repo contains the lastest collection of Swaggers that contain most of Dropbox APIv2 endpoints. They are auto-generated from Dropbox's official, language-neutral API specs, details to come later.

Here is a list of Swagger files we have here (more to come soon):

```
- swaggers/             <- where all Swagger files live
  - user_v2.json        <- specs for all user endpoints
  - team_v2.json        <- specs for all business endpoints
```

* user endpoints: https://www.dropbox.com/developers/documentation/http/documentation
* business endpoints: https://www.dropbox.com/developers/documentation/http/teams


