---
name: Google Speech
x-slug: google-speech
description: Google Cloud Speech API enables developers to convert audio to text by
  applying powerful neural network models in an easy to use API. The API recognizes
  over 80 languages and variants, to support your global user base. You can transcribe
  the text of users dictating to an application&rsquo;s microphone, enable command-and-control
  through voice, or transcribe audio files, among many other use cases. Recognize
  audio uploaded in the request, and integrate with your audio storage on Google Cloud
  Storage, by using the same technology Google uses to power its own products.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
x-kinRank: "9"
x-alexaRank: ""
tags: Google Speech
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Speech API Get Operations
  x-api-slug: google-cloud-speech-api
  description: |-
    Lists operations that match the specified filter in the request. If the
    server doesn't support this method, it returns `UNIMPLEMENTED`.

    NOTE: the `name` binding below allows API services to override the binding
    to use different resource name schemes, such as `users/*/operations`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com////v1beta1/operations
  tags: Operation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operations-get-openapi.md
- name: Google Cloud Speech API Delete Operation
  x-api-slug: google-cloud-speech-api
  description: |-
    Deletes a long-running operation. This method indicates that the client is
    no longer interested in the operation result. It does not cancel the
    operation. If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com////v1beta1/operations/{name}
  tags: Operation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operationsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operationsname-delete-openapi.md
- name: Google Cloud Speech API Delete Operation
  x-api-slug: google-cloud-speech-api
  description: |-
    Gets the latest state of a long-running operation.  Clients can use this
    method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com////v1beta1/operations/{name}
  tags: Operation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operationsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operationsname-get-openapi.md
- name: Google Cloud Speech API Cancel Operation
  x-api-slug: google-cloud-speech-api
  description: |-
    Starts asynchronous cancellation on a long-running operation.  The server
    makes a best effort to cancel the operation, but success is not
    guaranteed.  If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.  Clients can use
    Operations.GetOperation or
    other methods to check whether the cancellation succeeded or whether the
    operation completed despite cancellation. On successful cancellation,
    the operation is not deleted; instead, it becomes an operation with
    an Operation.error value with a google.rpc.Status.code of 1,
    corresponding to `Code.CANCELLED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com////v1beta1/operations/{name}:cancel
  tags: Operation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operationsnamecancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1operationsnamecancel-post-openapi.md
- name: Google Cloud Speech API Perform Asynchronous Speech Recognition
  x-api-slug: google-cloud-speech-api
  description: |-
    Performs asynchronous speech recognition: receive results via the
    [google.longrunning.Operations]
    (/speech/reference/rest/v1beta1/operations#Operation)
    interface. Returns either an
    `Operation.error` or an `Operation.response` which contains
    an `AsyncRecognizeResponse` message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com////v1beta1/speech:asyncrecognize
  tags: Speech Recognition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1speechasyncrecognize-post-openapi.md
- name: Google Cloud Speech API Perform Synchronous Speech Recognition
  x-api-slug: google-cloud-speech-api
  description: |-
    Performs synchronous speech recognition: receive results after all audio
    has been sent and processed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com////v1beta1/speech:syncrecognize
  tags: Speech Recognition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/v1beta1speechsyncrecognize-post-openapi.md
- name: Google Cloud Speech API
  x-api-slug: google-cloud-speech-api
  description: Google Cloud Speech API enables developers to convert audio to text
    by applying powerful neural network models in an easy to use API. The API recognizes
    over 80 languages and variants, to support your global user base. You can transcribe
    the text of users dictating to an application&rsquo;s microphone, enable command-and-control
    through voice, or transcribe audio files, among many other use cases. Recognize
    audio uploaded in the request, and integrate with your audio storage on Google
    Cloud Storage, by using the same technology Google uses to power its own products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google Speech
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-speech/master/_listings/google-speech/openapi.md
x-common:
- type: x-code
  url: https://cloud.google.com/speech/docs/reference/libraries
- type: x-concepts
  url: https://cloud.google.com/speech/docs/best-practices
- type: x-documentation
  url: https://cloud.google.com/speech/docs/
- type: x-getting-started
  url: https://cloud.google.com/speech/docs/getting-started
- type: x-guides
  url: https://cloud.google.com/speech/docs/common/auth
- type: x-pricing
  url: https://cloud.google.com/speech/pricing
- type: x-rate-limits
  url: https://cloud.google.com/speech/limits
- type: x-samples
  url: https://cloud.google.com/speech/docs/samples
- type: x-website
  url: https://cloud.google.com/speech/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---