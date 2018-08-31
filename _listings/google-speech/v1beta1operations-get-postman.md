{
  "info": {
    "name": "Google Cloud Speech API Get Operations",
    "_postman_id": "c114c047-945b-4de8-b213-c4f83c56867a",
    "description": "Lists operations that match the specified filter in the request. If the\nserver doesn't support this method, it returns `UNIMPLEMENTED`.\n\nNOTE: the `name` binding below allows API services to override the binding\nto use different resource name schemes, such as `users/*/operations`.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Operation",
      "item": [
        {
          "id": "c74e4ce4-b791-496f-8ad8-6b6fbca94697",
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
              "id": "6ecc56cc-c64d-4b22-8cec-aacabbc4efb2"
            }
          ]
        }
      ]
    }
  ]
}