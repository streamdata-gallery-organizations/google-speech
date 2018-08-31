---
swagger: "2.0"
x-collection-name: Google Speech
x-complete: 0
info:
  title: Google Cloud Speech API Delete Operation
  description: |-
    Deletes a long-running operation. This method indicates that the client is
    no longer interested in the operation result. It does not cancel the
    operation. If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.
  contact:
    name: Google
    url: https://google.com
  version: v1beta1
host: speech.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1beta1/operations:
    get:
      summary: Get Operations
      description: |-
        Lists operations that match the specified filter in the request. If the
        server doesn't support this method, it returns `UNIMPLEMENTED`.

        NOTE: the `name` binding below allows API services to override the binding
        to use different resource name schemes, such as `users/*/operations`.
      operationId: speech.operations.list
      x-api-path-slug: v1beta1operations-get
      parameters:
      - in: query
        name: filter
        description: The standard list filter
      - in: query
        name: name
        description: The name of the operation collection
      - in: query
        name: pageSize
        description: The standard list page size
      - in: query
        name: pageToken
        description: The standard list page token
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1beta1/operations/{name}:
    delete:
      summary: Delete Operation
      description: |-
        Deletes a long-running operation. This method indicates that the client is
        no longer interested in the operation result. It does not cancel the
        operation. If the server doesn't support this method, it returns
        `google.rpc.Code.UNIMPLEMENTED`.
      operationId: speech.operations.delete
      x-api-path-slug: v1beta1operationsname-delete
      parameters:
      - in: path
        name: name
        description: The name of the operation resource to be deleted
      responses:
        200:
          description: OK
      tags:
      - Operation
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---