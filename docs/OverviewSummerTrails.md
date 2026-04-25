# OverviewSummerTrails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Open** | Pointer to **NullableInt64** | Number of summer trails currently open.  Not included if the summer trails status feature is disabled. | [optional] 
**Total** | **int64** | Total number of summer trails at the resort. | 
**UpdatedAt** | **time.Time** | When the most recent update to summer trail status was made. | 

## Methods

### NewOverviewSummerTrails

`func NewOverviewSummerTrails(total int64, updatedAt time.Time, ) *OverviewSummerTrails`

NewOverviewSummerTrails instantiates a new OverviewSummerTrails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewSummerTrailsWithDefaults

`func NewOverviewSummerTrailsWithDefaults() *OverviewSummerTrails`

NewOverviewSummerTrailsWithDefaults instantiates a new OverviewSummerTrails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOpen

`func (o *OverviewSummerTrails) GetOpen() int64`

GetOpen returns the Open field if non-nil, zero value otherwise.

### GetOpenOk

`func (o *OverviewSummerTrails) GetOpenOk() (*int64, bool)`

GetOpenOk returns a tuple with the Open field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpen

`func (o *OverviewSummerTrails) SetOpen(v int64)`

SetOpen sets Open field to given value.

### HasOpen

`func (o *OverviewSummerTrails) HasOpen() bool`

HasOpen returns a boolean if a field has been set.

### SetOpenNil

`func (o *OverviewSummerTrails) SetOpenNil(b bool)`

 SetOpenNil sets the value for Open to be an explicit nil

### UnsetOpen
`func (o *OverviewSummerTrails) UnsetOpen()`

UnsetOpen ensures that no value is present for Open, not even an explicit nil
### GetTotal

`func (o *OverviewSummerTrails) GetTotal() int64`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OverviewSummerTrails) GetTotalOk() (*int64, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OverviewSummerTrails) SetTotal(v int64)`

SetTotal sets Total field to given value.


### GetUpdatedAt

`func (o *OverviewSummerTrails) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OverviewSummerTrails) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OverviewSummerTrails) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


