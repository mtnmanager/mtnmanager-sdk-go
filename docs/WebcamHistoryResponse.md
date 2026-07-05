# WebcamHistoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WebcamUuid** | **string** |  | 
**Frames** | [**[]WebcamHistoryFrame**](WebcamHistoryFrame.md) | Newest first. | 

## Methods

### NewWebcamHistoryResponse

`func NewWebcamHistoryResponse(webcamUuid string, frames []WebcamHistoryFrame, ) *WebcamHistoryResponse`

NewWebcamHistoryResponse instantiates a new WebcamHistoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebcamHistoryResponseWithDefaults

`func NewWebcamHistoryResponseWithDefaults() *WebcamHistoryResponse`

NewWebcamHistoryResponseWithDefaults instantiates a new WebcamHistoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWebcamUuid

`func (o *WebcamHistoryResponse) GetWebcamUuid() string`

GetWebcamUuid returns the WebcamUuid field if non-nil, zero value otherwise.

### GetWebcamUuidOk

`func (o *WebcamHistoryResponse) GetWebcamUuidOk() (*string, bool)`

GetWebcamUuidOk returns a tuple with the WebcamUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebcamUuid

`func (o *WebcamHistoryResponse) SetWebcamUuid(v string)`

SetWebcamUuid sets WebcamUuid field to given value.


### GetFrames

`func (o *WebcamHistoryResponse) GetFrames() []WebcamHistoryFrame`

GetFrames returns the Frames field if non-nil, zero value otherwise.

### GetFramesOk

`func (o *WebcamHistoryResponse) GetFramesOk() (*[]WebcamHistoryFrame, bool)`

GetFramesOk returns a tuple with the Frames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrames

`func (o *WebcamHistoryResponse) SetFrames(v []WebcamHistoryFrame)`

SetFrames sets Frames field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


