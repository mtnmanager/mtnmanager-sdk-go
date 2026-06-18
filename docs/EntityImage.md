# EntityImage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Full public URL to the image. | 
**ThumbHash** | **string** | Base64-encoded ThumbHash for placeholder rendering. | 

## Methods

### NewEntityImage

`func NewEntityImage(url string, thumbHash string, ) *EntityImage`

NewEntityImage instantiates a new EntityImage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityImageWithDefaults

`func NewEntityImageWithDefaults() *EntityImage`

NewEntityImageWithDefaults instantiates a new EntityImage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *EntityImage) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *EntityImage) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *EntityImage) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetThumbHash

`func (o *EntityImage) GetThumbHash() string`

GetThumbHash returns the ThumbHash field if non-nil, zero value otherwise.

### GetThumbHashOk

`func (o *EntityImage) GetThumbHashOk() (*string, bool)`

GetThumbHashOk returns a tuple with the ThumbHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbHash

`func (o *EntityImage) SetThumbHash(v string)`

SetThumbHash sets ThumbHash field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


