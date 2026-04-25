# OverviewTerrainParks

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Open** | Pointer to **NullableInt64** | Number of terrain parks currently open.  Not included if the terrain parks status feature is disabled. | [optional] 
**Total** | **int64** | Total number of terrain parks at the resort. | 
**UpdatedAt** | **time.Time** | When the most recent update to terrain park status was made. | 

## Methods

### NewOverviewTerrainParks

`func NewOverviewTerrainParks(total int64, updatedAt time.Time, ) *OverviewTerrainParks`

NewOverviewTerrainParks instantiates a new OverviewTerrainParks object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewTerrainParksWithDefaults

`func NewOverviewTerrainParksWithDefaults() *OverviewTerrainParks`

NewOverviewTerrainParksWithDefaults instantiates a new OverviewTerrainParks object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOpen

`func (o *OverviewTerrainParks) GetOpen() int64`

GetOpen returns the Open field if non-nil, zero value otherwise.

### GetOpenOk

`func (o *OverviewTerrainParks) GetOpenOk() (*int64, bool)`

GetOpenOk returns a tuple with the Open field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpen

`func (o *OverviewTerrainParks) SetOpen(v int64)`

SetOpen sets Open field to given value.

### HasOpen

`func (o *OverviewTerrainParks) HasOpen() bool`

HasOpen returns a boolean if a field has been set.

### SetOpenNil

`func (o *OverviewTerrainParks) SetOpenNil(b bool)`

 SetOpenNil sets the value for Open to be an explicit nil

### UnsetOpen
`func (o *OverviewTerrainParks) UnsetOpen()`

UnsetOpen ensures that no value is present for Open, not even an explicit nil
### GetTotal

`func (o *OverviewTerrainParks) GetTotal() int64`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OverviewTerrainParks) GetTotalOk() (*int64, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OverviewTerrainParks) SetTotal(v int64)`

SetTotal sets Total field to given value.


### GetUpdatedAt

`func (o *OverviewTerrainParks) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OverviewTerrainParks) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OverviewTerrainParks) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


