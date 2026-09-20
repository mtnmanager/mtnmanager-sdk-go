# TrailMapStaticPath

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Trail map UUID | 
**Version** | **int64** | The map version being requested (from &#x60;TrailMapSummary.version&#x60;) | 

## Methods

### NewTrailMapStaticPath

`func NewTrailMapStaticPath(uuid string, version int64, ) *TrailMapStaticPath`

NewTrailMapStaticPath instantiates a new TrailMapStaticPath object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapStaticPathWithDefaults

`func NewTrailMapStaticPathWithDefaults() *TrailMapStaticPath`

NewTrailMapStaticPathWithDefaults instantiates a new TrailMapStaticPath object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *TrailMapStaticPath) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapStaticPath) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapStaticPath) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetVersion

`func (o *TrailMapStaticPath) GetVersion() int64`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *TrailMapStaticPath) GetVersionOk() (*int64, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *TrailMapStaticPath) SetVersion(v int64)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


