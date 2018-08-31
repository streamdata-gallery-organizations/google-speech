{
  "info": {
    "name": "Google Cloud Speech API Cancel Operation",
    "_postman_id": "09efb8c3-b92c-4583-b540-2e0289183f05",
    "description": "Starts asynchronous cancellation on a long-running operation.  The server\nmakes a best effort to cancel the operation, but success is not\nguaranteed.  If the server doesn't support this method, it returns\n`google.rpc.Code.UNIMPLEMENTED`.  Clients can use\nOperations.GetOperation or\nother methods to check whether the cancellation succeeded or whether the\noperation completed despite cancellation. On successful cancellation,\nthe operation is not deleted; instead, it becomes an operation with\nan Operation.error value with a google.rpc.Status.code of 1,\ncorresponding to `Code.CANCELLED`.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Operation",
      "item": [
        {
          "id": "5de9c388-1270-4ed1-9ae9-179dbd95f93e",
          "name": "speech.operations.list",
          "request": {
            "url": "http://speech.googleapis.com/v1beta1/operations?filter=%7B%7D&name=%7B%7D&pageSize=%7B%7D&pageToken=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists operations that match the specified filter in the request. If the\nserver doesn't support this method, it returns `UNIMPLEMENTED`.\n\nNOTE: the `name` binding below allows API services to override the binding\nto use different resource name schemes, such as `users/*/operations`."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff350626-383a-44bf-8290-15980eeec0e4"
            }
          ]
        },
        {
          "id": "9a613008-19fb-4213-a175-b83dbd5a4c4f",
          "name": "speech.operations.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "speech.googleapis.com",
              "path": [
                "v1beta1/operations/:name"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the latest state of a long-running operation.  Clients can use this\nmethod to poll the operation result at intervals as recommended by the API\nservice."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b67d8d6d-f741-4403-84f2-00ccb49f274c"
            }
          ]
        },
        {
          "id": "02d9c4cd-9695-464e-a501-1d6e32df4204",
          "name": "speech.operations.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "speech.googleapis.com",
              "path": [
                "v1beta1/operations/:name"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a long-running operation. This method indicates that the client is\nno longer interested in the operation result. It does not cancel the\noperation. If the server doesn't support this method, it returns\n`google.rpc.Code.UNIMPLEMENTED`."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbed7403-8552-4047-b3e0-b6058f20ad29"
            }
          ]
        },
        {
          "id": "c49a158c-d571-4d7b-bb13-e13b3d7928b0",
          "name": "speech.operations.cancel",
          "request": {
            "url": {
              "protocol": "http",
              "host": "speech.googleapis.com",
              "path": [
                "v1beta1/operations/:name:cancel"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Starts asynchronous cancellation on a long-running operation.  The server\nmakes a best effort to cancel the operation, but success is not\nguaranteed.  If the server doesn't support this method, it returns\n`google.rpc.Code.UNIMPLEMENTED`.  Clients can use\nOperations.GetOperation or\nother methods to check whether the cancellation succeeded or whether the\noperation completed despite cancellation. On successful cancellation,\nthe operation is not deleted; instead, it becomes an operation with\nan Operation.error value with a google.rpc.Status.code of 1,\ncorresponding to `Code.CANCELLED`."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4648413-23de-42e9-a126-f0494115149b"
            }
          ]
        }
      ]
    }
  ]
}