{
  "info": {
    "name": "Google Cloud Speech API Delete Operation",
    "_postman_id": "23dbc03a-b10a-4110-8ed0-423cb95082d9",
    "description": "Deletes a long-running operation. This method indicates that the client is\nno longer interested in the operation result. It does not cancel the\noperation. If the server doesn't support this method, it returns\n`google.rpc.Code.UNIMPLEMENTED`.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Operation",
      "item": [
        {
          "id": "ac1696b5-fbd4-4ba5-9105-0a98a8f563e9",
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
              "id": "08404954-6fb4-41ea-92ba-2216efd4ab62"
            }
          ]
        },
        {
          "id": "ad941600-9ed4-4a2f-8733-f6e07e8ffbbe",
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
              "id": "60b6f301-414b-465d-b999-adfdf4fde73d"
            }
          ]
        }
      ]
    }
  ]
}