# Demo REST API
This module follows the instructions on this [DO page](https://www.drupal.org/docs/8/api/restful-web-services-api/custom-rest-resources) to set up a custom REST resource to be available via API.

## Requirements
The following modules need to be enabled:
  - RESTful Web Services (rest)
  - REST UI (restui) - optional - only needed if you want to export configuration via the UI instead of writing your own.

## Demo
Install the module. Try accessing the url `http://local.d8-blt.com/demo_rest_api/demo_resource?_format=json` from your favourite client.

You should see the following result:
```json
{
  "message": "Hello, this is a rest service"
}
```
