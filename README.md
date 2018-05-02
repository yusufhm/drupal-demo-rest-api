# Demo REST API
This module follows the instructions on this [DO page](https://www.drupal.org/docs/8/api/restful-web-services-api/custom-rest-resources) to set up a custom REST resource to be available via API.

## Requirements
The following modules need to be enabled:
  - RESTful Web Services (rest)
  - REST UI (restui) - optional - only needed if you want to export configuration via the UI instead of writing your own.

## Demo
Install the module.

If you want anonymous access to the resource, go to `/admin/people/permissions` and set the correct access for the `Access GET on Demo Resource resource` permission.

Try accessing the url `/demo_rest_api/demo_resource?_format=json` from your favourite client.

You should see the following result:
```json
{
  "message": "Hello, this is a rest service"
}
```
