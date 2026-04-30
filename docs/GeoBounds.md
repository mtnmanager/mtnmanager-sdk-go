# GeoBounds

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MinLat** | **float64** |  | 
**MaxLat** | **float64** |  | 
**MinLng** | **float64** |  | 
**MaxLng** | **float64** |  | 
**Center** | [**GeoPoint**](GeoPoint.md) |  | 

## Methods

### NewGeoBounds

`func NewGeoBounds(minLat float64, maxLat float64, minLng float64, maxLng float64, center GeoPoint, ) *GeoBounds`

NewGeoBounds instantiates a new GeoBounds object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoBoundsWithDefaults

`func NewGeoBoundsWithDefaults() *GeoBounds`

NewGeoBoundsWithDefaults instantiates a new GeoBounds object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMinLat

`func (o *GeoBounds) GetMinLat() float64`

GetMinLat returns the MinLat field if non-nil, zero value otherwise.

### GetMinLatOk

`func (o *GeoBounds) GetMinLatOk() (*float64, bool)`

GetMinLatOk returns a tuple with the MinLat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLat

`func (o *GeoBounds) SetMinLat(v float64)`

SetMinLat sets MinLat field to given value.


### GetMaxLat

`func (o *GeoBounds) GetMaxLat() float64`

GetMaxLat returns the MaxLat field if non-nil, zero value otherwise.

### GetMaxLatOk

`func (o *GeoBounds) GetMaxLatOk() (*float64, bool)`

GetMaxLatOk returns a tuple with the MaxLat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLat

`func (o *GeoBounds) SetMaxLat(v float64)`

SetMaxLat sets MaxLat field to given value.


### GetMinLng

`func (o *GeoBounds) GetMinLng() float64`

GetMinLng returns the MinLng field if non-nil, zero value otherwise.

### GetMinLngOk

`func (o *GeoBounds) GetMinLngOk() (*float64, bool)`

GetMinLngOk returns a tuple with the MinLng field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLng

`func (o *GeoBounds) SetMinLng(v float64)`

SetMinLng sets MinLng field to given value.


### GetMaxLng

`func (o *GeoBounds) GetMaxLng() float64`

GetMaxLng returns the MaxLng field if non-nil, zero value otherwise.

### GetMaxLngOk

`func (o *GeoBounds) GetMaxLngOk() (*float64, bool)`

GetMaxLngOk returns a tuple with the MaxLng field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLng

`func (o *GeoBounds) SetMaxLng(v float64)`

SetMaxLng sets MaxLng field to given value.


### GetCenter

`func (o *GeoBounds) GetCenter() GeoPoint`

GetCenter returns the Center field if non-nil, zero value otherwise.

### GetCenterOk

`func (o *GeoBounds) GetCenterOk() (*GeoPoint, bool)`

GetCenterOk returns a tuple with the Center field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCenter

`func (o *GeoBounds) SetCenter(v GeoPoint)`

SetCenter sets Center field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


