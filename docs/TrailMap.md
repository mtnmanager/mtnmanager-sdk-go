# TrailMap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Slug** | **string** |  | 
**BackgroundImageUrl** | **string** |  | 
**Resort** | [**ResortInfo**](ResortInfo.md) |  | 
**Elements** | [**[]TrailMapElement**](TrailMapElement.md) |  | 
**GeoControlPoints** | Pointer to [**[]GeoControlPoint**](GeoControlPoint.md) |  | [optional] 

## Methods

### NewTrailMap

`func NewTrailMap(uuid string, name string, slug string, backgroundImageUrl string, resort ResortInfo, elements []TrailMapElement, ) *TrailMap`

NewTrailMap instantiates a new TrailMap object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapWithDefaults

`func NewTrailMapWithDefaults() *TrailMap`

NewTrailMapWithDefaults instantiates a new TrailMap object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *TrailMap) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMap) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMap) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *TrailMap) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TrailMap) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TrailMap) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *TrailMap) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *TrailMap) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *TrailMap) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetBackgroundImageUrl

`func (o *TrailMap) GetBackgroundImageUrl() string`

GetBackgroundImageUrl returns the BackgroundImageUrl field if non-nil, zero value otherwise.

### GetBackgroundImageUrlOk

`func (o *TrailMap) GetBackgroundImageUrlOk() (*string, bool)`

GetBackgroundImageUrlOk returns a tuple with the BackgroundImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackgroundImageUrl

`func (o *TrailMap) SetBackgroundImageUrl(v string)`

SetBackgroundImageUrl sets BackgroundImageUrl field to given value.


### GetResort

`func (o *TrailMap) GetResort() ResortInfo`

GetResort returns the Resort field if non-nil, zero value otherwise.

### GetResortOk

`func (o *TrailMap) GetResortOk() (*ResortInfo, bool)`

GetResortOk returns a tuple with the Resort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResort

`func (o *TrailMap) SetResort(v ResortInfo)`

SetResort sets Resort field to given value.


### GetElements

`func (o *TrailMap) GetElements() []TrailMapElement`

GetElements returns the Elements field if non-nil, zero value otherwise.

### GetElementsOk

`func (o *TrailMap) GetElementsOk() (*[]TrailMapElement, bool)`

GetElementsOk returns a tuple with the Elements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElements

`func (o *TrailMap) SetElements(v []TrailMapElement)`

SetElements sets Elements field to given value.


### GetGeoControlPoints

`func (o *TrailMap) GetGeoControlPoints() []GeoControlPoint`

GetGeoControlPoints returns the GeoControlPoints field if non-nil, zero value otherwise.

### GetGeoControlPointsOk

`func (o *TrailMap) GetGeoControlPointsOk() (*[]GeoControlPoint, bool)`

GetGeoControlPointsOk returns a tuple with the GeoControlPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeoControlPoints

`func (o *TrailMap) SetGeoControlPoints(v []GeoControlPoint)`

SetGeoControlPoints sets GeoControlPoints field to given value.

### HasGeoControlPoints

`func (o *TrailMap) HasGeoControlPoints() bool`

HasGeoControlPoints returns a boolean if a field has been set.

### SetGeoControlPointsNil

`func (o *TrailMap) SetGeoControlPointsNil(b bool)`

 SetGeoControlPointsNil sets the value for GeoControlPoints to be an explicit nil

### UnsetGeoControlPoints
`func (o *TrailMap) UnsetGeoControlPoints()`

UnsetGeoControlPoints ensures that no value is present for GeoControlPoints, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


