# OverviewRuns

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Open** | Pointer to **NullableInt64** | Number of runs currently open.  Not included if the runs status feature is disabled. | [optional] 
**Groomed** | Pointer to **NullableInt64** | Number of runs groomed within the last 24 hours.  Not included if the runs grooming feature is disabled. | [optional] 
**Total** | **int64** | Total number of runs at the resort. | 
**OpenAcres** | Pointer to **NullableInt64** | Total acres of open runs.  Not included if acres are not tracked or the runs status feature is disabled. | [optional] 
**TotalAcres** | Pointer to **NullableInt64** | Total acres of all runs.  Not included if acres are not tracked. | [optional] 
**UpdatedAt** | **time.Time** | When the most recent update to run status was made. | 

## Methods

### NewOverviewRuns

`func NewOverviewRuns(total int64, updatedAt time.Time, ) *OverviewRuns`

NewOverviewRuns instantiates a new OverviewRuns object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewRunsWithDefaults

`func NewOverviewRunsWithDefaults() *OverviewRuns`

NewOverviewRunsWithDefaults instantiates a new OverviewRuns object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOpen

`func (o *OverviewRuns) GetOpen() int64`

GetOpen returns the Open field if non-nil, zero value otherwise.

### GetOpenOk

`func (o *OverviewRuns) GetOpenOk() (*int64, bool)`

GetOpenOk returns a tuple with the Open field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpen

`func (o *OverviewRuns) SetOpen(v int64)`

SetOpen sets Open field to given value.

### HasOpen

`func (o *OverviewRuns) HasOpen() bool`

HasOpen returns a boolean if a field has been set.

### SetOpenNil

`func (o *OverviewRuns) SetOpenNil(b bool)`

 SetOpenNil sets the value for Open to be an explicit nil

### UnsetOpen
`func (o *OverviewRuns) UnsetOpen()`

UnsetOpen ensures that no value is present for Open, not even an explicit nil
### GetGroomed

`func (o *OverviewRuns) GetGroomed() int64`

GetGroomed returns the Groomed field if non-nil, zero value otherwise.

### GetGroomedOk

`func (o *OverviewRuns) GetGroomedOk() (*int64, bool)`

GetGroomedOk returns a tuple with the Groomed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroomed

`func (o *OverviewRuns) SetGroomed(v int64)`

SetGroomed sets Groomed field to given value.

### HasGroomed

`func (o *OverviewRuns) HasGroomed() bool`

HasGroomed returns a boolean if a field has been set.

### SetGroomedNil

`func (o *OverviewRuns) SetGroomedNil(b bool)`

 SetGroomedNil sets the value for Groomed to be an explicit nil

### UnsetGroomed
`func (o *OverviewRuns) UnsetGroomed()`

UnsetGroomed ensures that no value is present for Groomed, not even an explicit nil
### GetTotal

`func (o *OverviewRuns) GetTotal() int64`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OverviewRuns) GetTotalOk() (*int64, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OverviewRuns) SetTotal(v int64)`

SetTotal sets Total field to given value.


### GetOpenAcres

`func (o *OverviewRuns) GetOpenAcres() int64`

GetOpenAcres returns the OpenAcres field if non-nil, zero value otherwise.

### GetOpenAcresOk

`func (o *OverviewRuns) GetOpenAcresOk() (*int64, bool)`

GetOpenAcresOk returns a tuple with the OpenAcres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenAcres

`func (o *OverviewRuns) SetOpenAcres(v int64)`

SetOpenAcres sets OpenAcres field to given value.

### HasOpenAcres

`func (o *OverviewRuns) HasOpenAcres() bool`

HasOpenAcres returns a boolean if a field has been set.

### SetOpenAcresNil

`func (o *OverviewRuns) SetOpenAcresNil(b bool)`

 SetOpenAcresNil sets the value for OpenAcres to be an explicit nil

### UnsetOpenAcres
`func (o *OverviewRuns) UnsetOpenAcres()`

UnsetOpenAcres ensures that no value is present for OpenAcres, not even an explicit nil
### GetTotalAcres

`func (o *OverviewRuns) GetTotalAcres() int64`

GetTotalAcres returns the TotalAcres field if non-nil, zero value otherwise.

### GetTotalAcresOk

`func (o *OverviewRuns) GetTotalAcresOk() (*int64, bool)`

GetTotalAcresOk returns a tuple with the TotalAcres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAcres

`func (o *OverviewRuns) SetTotalAcres(v int64)`

SetTotalAcres sets TotalAcres field to given value.

### HasTotalAcres

`func (o *OverviewRuns) HasTotalAcres() bool`

HasTotalAcres returns a boolean if a field has been set.

### SetTotalAcresNil

`func (o *OverviewRuns) SetTotalAcresNil(b bool)`

 SetTotalAcresNil sets the value for TotalAcres to be an explicit nil

### UnsetTotalAcres
`func (o *OverviewRuns) UnsetTotalAcres()`

UnsetTotalAcres ensures that no value is present for TotalAcres, not even an explicit nil
### GetUpdatedAt

`func (o *OverviewRuns) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OverviewRuns) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OverviewRuns) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


