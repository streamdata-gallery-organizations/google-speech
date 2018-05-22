{
  "info": {
    "name": "Google Cloud Speech API Delete Operation",
    "_postman_id": "48ca9b2a-e851-4ce6-adfd-5e792348ebbf",
    "description": "Gets the latest state of a long-running operation.  Clients can use this\nmethod to poll the operation result at intervals as recommended by the API\nservice.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Operation",
      "item": [
        {
          "id": "70497471-663c-4eae-bb82-58a2f6ef6647",
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
              "id": "b6761988-d2c6-4923-94eb-8bfeb27286a1"
            }
          ]
        },
        {
          "id": "6f2fe9e5-ac7c-452e-bba6-5063e0e95ab1",
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
              "id": "106370ca-54a8-406c-b94f-9584c6cad8c8"
            }
          ]
        },
        {
          "id": "ebec09bb-6927-4e06-b9cf-98c4282a7a74",
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
              "id": "b0c64eab-0643-4952-8462-712b793dc96d"
            }
          ]
        }
      ]
    }
  ]
}