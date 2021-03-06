### SDK Features

### SDK Enhancements
* `private/protocol`: Loosen endpoint validation to allow customer specify port number ([#3730](https://github.com/aws/aws-sdk-go/pull/3730))
    * Updates SDK's endpoint validation of the hostname to allow ports to be specified.
* `service/s3/s3manager`: Add ETag field to UploadOutput ([#3733](https://github.com/aws/aws-sdk-go/pull/3733))
  * Adds the ETag field to the Uploader's UploadOutput return value.
  * Fixes [#2764](https://github.com/aws/aws-sdk-go/issues/2764)
* `aws`: Add `WithLowerCaseHeaderMaps` and `WithDisableRestProtocolURICleaning` to `aws.Config`. ([#3671](https://github.com/aws/aws-sdk-go/pull/3671))

### SDK Bugs
* `aws`: Fixed a case where `LowerCaseHeaderMaps` would not be merged when merging`aws.Config` types. ([#3671](https://github.com/aws/aws-sdk-go/pull/3671))
