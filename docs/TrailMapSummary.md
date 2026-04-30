# TrailMapSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Season** | [**SeasonType**](SeasonType.md) |  | 
**DisplayOrder** | **int64** |  | 
**HostedUrl** | **string** |  | 
**GeoBounds** | Pointer to [**NullableGeoBounds**](GeoBounds.md) | Lat/lng bounding box of this map&#39;s georeferenced area, plus the  centroid of its control points (used for tie-breaking when multiple  maps cover the same point). Omitted when the map has no georeferencing. | [optional] 
**EntityUuids** | **[]string** | Deduplicated UUIDs of every entity (lift, run, terrain park,  summer trail, amenity, parking lot) referenced by this map&#39;s elements. | 

## Methods

### NewTrailMapSummary

`func NewTrailMapSummary(uuid string, name string, season SeasonType, displayOrder int64, hostedUrl string, entityUuids []string, ) *TrailMapSummary`

NewTrailMapSummary instantiates a new TrailMapSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapSummaryWithDefaults

`func NewTrailMapSummaryWithDefaults() *TrailMapSummary`

NewTrailMapSummaryWithDefaults instantiates a new TrailMapSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *TrailMapSummary) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapSummary) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapSummary) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *TrailMapSummary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TrailMapSummary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TrailMapSummary) SetName(v string)`

SetName sets Name field to given value.


### GetSeason

`func (o *TrailMapSummary) GetSeason() SeasonType`

GetSeason returns the Season field if non-nil, zero value otherwise.

### GetSeasonOk

`func (o *TrailMapSummary) GetSeasonOk() (*SeasonType, bool)`

GetSeasonOk returns a tuple with the Season field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeason

`func (o *TrailMapSummary) SetSeason(v SeasonType)`

SetSeason sets Season field to given value.


### GetDisplayOrder

`func (o *TrailMapSummary) GetDisplayOrder() int64`

GetDisplayOrder returns the DisplayOrder field if non-nil, zero value otherwise.

### GetDisplayOrderOk

`func (o *TrailMapSummary) GetDisplayOrderOk() (*int64, bool)`

GetDisplayOrderOk returns a tuple with the DisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayOrder

`func (o *TrailMapSummary) SetDisplayOrder(v int64)`

SetDisplayOrder sets DisplayOrder field to given value.


### GetHostedUrl

`func (o *TrailMapSummary) GetHostedUrl() string`

GetHostedUrl returns the HostedUrl field if non-nil, zero value otherwise.

### GetHostedUrlOk

`func (o *TrailMapSummary) GetHostedUrlOk() (*string, bool)`

GetHostedUrlOk returns a tuple with the HostedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostedUrl

`func (o *TrailMapSummary) SetHostedUrl(v string)`

SetHostedUrl sets HostedUrl field to given value.


### GetGeoBounds

`func (o *TrailMapSummary) GetGeoBounds() GeoBounds`

GetGeoBounds returns the GeoBounds field if non-nil, zero value otherwise.

### GetGeoBoundsOk

`func (o *TrailMapSummary) GetGeoBoundsOk() (*GeoBounds, bool)`

GetGeoBoundsOk returns a tuple with the GeoBounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeoBounds

`func (o *TrailMapSummary) SetGeoBounds(v GeoBounds)`

SetGeoBounds sets GeoBounds field to given value.

### HasGeoBounds

`func (o *TrailMapSummary) HasGeoBounds() bool`

HasGeoBounds returns a boolean if a field has been set.

### SetGeoBoundsNil

`func (o *TrailMapSummary) SetGeoBoundsNil(b bool)`

 SetGeoBoundsNil sets the value for GeoBounds to be an explicit nil

### UnsetGeoBounds
`func (o *TrailMapSummary) UnsetGeoBounds()`

UnsetGeoBounds ensures that no value is present for GeoBounds, not even an explicit nil
### GetEntityUuids

`func (o *TrailMapSummary) GetEntityUuids() []string`

GetEntityUuids returns the EntityUuids field if non-nil, zero value otherwise.

### GetEntityUuidsOk

`func (o *TrailMapSummary) GetEntityUuidsOk() (*[]string, bool)`

GetEntityUuidsOk returns a tuple with the EntityUuids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityUuids

`func (o *TrailMapSummary) SetEntityUuids(v []string)`

SetEntityUuids sets EntityUuids field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


