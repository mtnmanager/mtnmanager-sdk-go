# Webcam

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**AreaUuid** | Pointer to **NullableString** |  | [optional] 
**AreaName** | Pointer to **NullableString** |  | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** |  | [optional] 
**LatestImageUrl** | **string** | URL of the newest frame (refreshes within ~60s via the edge cache). | 
**LatestDaylightImageUrl** | **string** | URL of the last daylight frame. | 
**LatestThumbUrl** | **string** |  | 
**LatestDaylightThumbUrl** | **string** |  | 
**LatestThumbhash** | **string** | ThumbHash of the &#x60;latest&#x60; frame (standard base64) — a compact blur  placeholder to render while the image loads. Empty string until the first  frame (or on cameras predating the feature). | 
**LatestDaylightThumbhash** | **string** | ThumbHash of the &#x60;latest-daylight&#x60; frame (standard base64). Empty string  until the first daylight frame. | 
**HasHistory** | **bool** | Whether this camera archives frames — i.e. whether its history endpoint  returns anything. When &#x60;false&#x60;, don&#39;t call the history API for it. | 
**ElevationFt** | Pointer to **NullableInt32** | Camera elevation in both units; omitted when unset. | [optional] 
**ElevationM** | Pointer to **NullableInt32** |  | [optional] 
**LastFrameAt** | Pointer to **NullableString** | Time of the most recently published frame; omitted until the first frame. | [optional] 

## Methods

### NewWebcam

`func NewWebcam(uuid string, name string, latestImageUrl string, latestDaylightImageUrl string, latestThumbUrl string, latestDaylightThumbUrl string, latestThumbhash string, latestDaylightThumbhash string, hasHistory bool, ) *Webcam`

NewWebcam instantiates a new Webcam object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebcamWithDefaults

`func NewWebcamWithDefaults() *Webcam`

NewWebcamWithDefaults instantiates a new Webcam object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *Webcam) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Webcam) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Webcam) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *Webcam) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Webcam) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Webcam) SetName(v string)`

SetName sets Name field to given value.


### GetAreaUuid

`func (o *Webcam) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *Webcam) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *Webcam) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *Webcam) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *Webcam) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *Webcam) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *Webcam) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *Webcam) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *Webcam) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *Webcam) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *Webcam) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *Webcam) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *Webcam) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *Webcam) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *Webcam) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *Webcam) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *Webcam) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *Webcam) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetLatestImageUrl

`func (o *Webcam) GetLatestImageUrl() string`

GetLatestImageUrl returns the LatestImageUrl field if non-nil, zero value otherwise.

### GetLatestImageUrlOk

`func (o *Webcam) GetLatestImageUrlOk() (*string, bool)`

GetLatestImageUrlOk returns a tuple with the LatestImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestImageUrl

`func (o *Webcam) SetLatestImageUrl(v string)`

SetLatestImageUrl sets LatestImageUrl field to given value.


### GetLatestDaylightImageUrl

`func (o *Webcam) GetLatestDaylightImageUrl() string`

GetLatestDaylightImageUrl returns the LatestDaylightImageUrl field if non-nil, zero value otherwise.

### GetLatestDaylightImageUrlOk

`func (o *Webcam) GetLatestDaylightImageUrlOk() (*string, bool)`

GetLatestDaylightImageUrlOk returns a tuple with the LatestDaylightImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestDaylightImageUrl

`func (o *Webcam) SetLatestDaylightImageUrl(v string)`

SetLatestDaylightImageUrl sets LatestDaylightImageUrl field to given value.


### GetLatestThumbUrl

`func (o *Webcam) GetLatestThumbUrl() string`

GetLatestThumbUrl returns the LatestThumbUrl field if non-nil, zero value otherwise.

### GetLatestThumbUrlOk

`func (o *Webcam) GetLatestThumbUrlOk() (*string, bool)`

GetLatestThumbUrlOk returns a tuple with the LatestThumbUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestThumbUrl

`func (o *Webcam) SetLatestThumbUrl(v string)`

SetLatestThumbUrl sets LatestThumbUrl field to given value.


### GetLatestDaylightThumbUrl

`func (o *Webcam) GetLatestDaylightThumbUrl() string`

GetLatestDaylightThumbUrl returns the LatestDaylightThumbUrl field if non-nil, zero value otherwise.

### GetLatestDaylightThumbUrlOk

`func (o *Webcam) GetLatestDaylightThumbUrlOk() (*string, bool)`

GetLatestDaylightThumbUrlOk returns a tuple with the LatestDaylightThumbUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestDaylightThumbUrl

`func (o *Webcam) SetLatestDaylightThumbUrl(v string)`

SetLatestDaylightThumbUrl sets LatestDaylightThumbUrl field to given value.


### GetLatestThumbhash

`func (o *Webcam) GetLatestThumbhash() string`

GetLatestThumbhash returns the LatestThumbhash field if non-nil, zero value otherwise.

### GetLatestThumbhashOk

`func (o *Webcam) GetLatestThumbhashOk() (*string, bool)`

GetLatestThumbhashOk returns a tuple with the LatestThumbhash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestThumbhash

`func (o *Webcam) SetLatestThumbhash(v string)`

SetLatestThumbhash sets LatestThumbhash field to given value.


### GetLatestDaylightThumbhash

`func (o *Webcam) GetLatestDaylightThumbhash() string`

GetLatestDaylightThumbhash returns the LatestDaylightThumbhash field if non-nil, zero value otherwise.

### GetLatestDaylightThumbhashOk

`func (o *Webcam) GetLatestDaylightThumbhashOk() (*string, bool)`

GetLatestDaylightThumbhashOk returns a tuple with the LatestDaylightThumbhash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestDaylightThumbhash

`func (o *Webcam) SetLatestDaylightThumbhash(v string)`

SetLatestDaylightThumbhash sets LatestDaylightThumbhash field to given value.


### GetHasHistory

`func (o *Webcam) GetHasHistory() bool`

GetHasHistory returns the HasHistory field if non-nil, zero value otherwise.

### GetHasHistoryOk

`func (o *Webcam) GetHasHistoryOk() (*bool, bool)`

GetHasHistoryOk returns a tuple with the HasHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasHistory

`func (o *Webcam) SetHasHistory(v bool)`

SetHasHistory sets HasHistory field to given value.


### GetElevationFt

`func (o *Webcam) GetElevationFt() int32`

GetElevationFt returns the ElevationFt field if non-nil, zero value otherwise.

### GetElevationFtOk

`func (o *Webcam) GetElevationFtOk() (*int32, bool)`

GetElevationFtOk returns a tuple with the ElevationFt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElevationFt

`func (o *Webcam) SetElevationFt(v int32)`

SetElevationFt sets ElevationFt field to given value.

### HasElevationFt

`func (o *Webcam) HasElevationFt() bool`

HasElevationFt returns a boolean if a field has been set.

### SetElevationFtNil

`func (o *Webcam) SetElevationFtNil(b bool)`

 SetElevationFtNil sets the value for ElevationFt to be an explicit nil

### UnsetElevationFt
`func (o *Webcam) UnsetElevationFt()`

UnsetElevationFt ensures that no value is present for ElevationFt, not even an explicit nil
### GetElevationM

`func (o *Webcam) GetElevationM() int32`

GetElevationM returns the ElevationM field if non-nil, zero value otherwise.

### GetElevationMOk

`func (o *Webcam) GetElevationMOk() (*int32, bool)`

GetElevationMOk returns a tuple with the ElevationM field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElevationM

`func (o *Webcam) SetElevationM(v int32)`

SetElevationM sets ElevationM field to given value.

### HasElevationM

`func (o *Webcam) HasElevationM() bool`

HasElevationM returns a boolean if a field has been set.

### SetElevationMNil

`func (o *Webcam) SetElevationMNil(b bool)`

 SetElevationMNil sets the value for ElevationM to be an explicit nil

### UnsetElevationM
`func (o *Webcam) UnsetElevationM()`

UnsetElevationM ensures that no value is present for ElevationM, not even an explicit nil
### GetLastFrameAt

`func (o *Webcam) GetLastFrameAt() string`

GetLastFrameAt returns the LastFrameAt field if non-nil, zero value otherwise.

### GetLastFrameAtOk

`func (o *Webcam) GetLastFrameAtOk() (*string, bool)`

GetLastFrameAtOk returns a tuple with the LastFrameAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastFrameAt

`func (o *Webcam) SetLastFrameAt(v string)`

SetLastFrameAt sets LastFrameAt field to given value.

### HasLastFrameAt

`func (o *Webcam) HasLastFrameAt() bool`

HasLastFrameAt returns a boolean if a field has been set.

### SetLastFrameAtNil

`func (o *Webcam) SetLastFrameAtNil(b bool)`

 SetLastFrameAtNil sets the value for LastFrameAt to be an explicit nil

### UnsetLastFrameAt
`func (o *Webcam) UnsetLastFrameAt()`

UnsetLastFrameAt ensures that no value is present for LastFrameAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


