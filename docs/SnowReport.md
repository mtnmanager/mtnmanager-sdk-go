# SnowReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for this snow report. | 
**AreaUuid** | Pointer to **NullableString** | UUID of the area this report covers, if area-specific.  &#x60;null&#x60; for resort-wide reports. | [optional] 
**AreaName** | Pointer to **NullableString** | Name of the area this report covers, if area-specific. | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** | Display order of the area this report covers, if area-specific, for sorting purposes. | [optional] 
**BaseDepthCm** | Pointer to **NullableInt32** | Current base depth in centimeters.  Not included if the base depth feature is disabled. | [optional] 
**BaseDepthIn** | Pointer to **NullableInt32** | Current base depth in inches.  Not included if the base depth feature is disabled. | [optional] 
**SurfaceCondition** | Pointer to [**NullableSurfaceCondition**](SurfaceCondition.md) |  | [optional] 
**SecondarySurfaceCondition** | Pointer to [**NullableSurfaceCondition**](SurfaceCondition.md) |  | [optional] 
**ConditionNotes** | **string** | Additional notes about current snow conditions, e.g. groomer&#39;s notes | 
**SnowfallCm** | [**SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in centimeters. | 
**SnowfallIn** | [**SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in inches. | 
**ReportedAt** | **time.Time** | When this snow report was last updated. | 

## Methods

### NewSnowReport

`func NewSnowReport(uuid string, conditionNotes string, snowfallCm SnowMetrics, snowfallIn SnowMetrics, reportedAt time.Time, ) *SnowReport`

NewSnowReport instantiates a new SnowReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnowReportWithDefaults

`func NewSnowReportWithDefaults() *SnowReport`

NewSnowReportWithDefaults instantiates a new SnowReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *SnowReport) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *SnowReport) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *SnowReport) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetAreaUuid

`func (o *SnowReport) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *SnowReport) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *SnowReport) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *SnowReport) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *SnowReport) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *SnowReport) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *SnowReport) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *SnowReport) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *SnowReport) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *SnowReport) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *SnowReport) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *SnowReport) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *SnowReport) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *SnowReport) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *SnowReport) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *SnowReport) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *SnowReport) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *SnowReport) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetBaseDepthCm

`func (o *SnowReport) GetBaseDepthCm() int32`

GetBaseDepthCm returns the BaseDepthCm field if non-nil, zero value otherwise.

### GetBaseDepthCmOk

`func (o *SnowReport) GetBaseDepthCmOk() (*int32, bool)`

GetBaseDepthCmOk returns a tuple with the BaseDepthCm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseDepthCm

`func (o *SnowReport) SetBaseDepthCm(v int32)`

SetBaseDepthCm sets BaseDepthCm field to given value.

### HasBaseDepthCm

`func (o *SnowReport) HasBaseDepthCm() bool`

HasBaseDepthCm returns a boolean if a field has been set.

### SetBaseDepthCmNil

`func (o *SnowReport) SetBaseDepthCmNil(b bool)`

 SetBaseDepthCmNil sets the value for BaseDepthCm to be an explicit nil

### UnsetBaseDepthCm
`func (o *SnowReport) UnsetBaseDepthCm()`

UnsetBaseDepthCm ensures that no value is present for BaseDepthCm, not even an explicit nil
### GetBaseDepthIn

`func (o *SnowReport) GetBaseDepthIn() int32`

GetBaseDepthIn returns the BaseDepthIn field if non-nil, zero value otherwise.

### GetBaseDepthInOk

`func (o *SnowReport) GetBaseDepthInOk() (*int32, bool)`

GetBaseDepthInOk returns a tuple with the BaseDepthIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseDepthIn

`func (o *SnowReport) SetBaseDepthIn(v int32)`

SetBaseDepthIn sets BaseDepthIn field to given value.

### HasBaseDepthIn

`func (o *SnowReport) HasBaseDepthIn() bool`

HasBaseDepthIn returns a boolean if a field has been set.

### SetBaseDepthInNil

`func (o *SnowReport) SetBaseDepthInNil(b bool)`

 SetBaseDepthInNil sets the value for BaseDepthIn to be an explicit nil

### UnsetBaseDepthIn
`func (o *SnowReport) UnsetBaseDepthIn()`

UnsetBaseDepthIn ensures that no value is present for BaseDepthIn, not even an explicit nil
### GetSurfaceCondition

`func (o *SnowReport) GetSurfaceCondition() SurfaceCondition`

GetSurfaceCondition returns the SurfaceCondition field if non-nil, zero value otherwise.

### GetSurfaceConditionOk

`func (o *SnowReport) GetSurfaceConditionOk() (*SurfaceCondition, bool)`

GetSurfaceConditionOk returns a tuple with the SurfaceCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSurfaceCondition

`func (o *SnowReport) SetSurfaceCondition(v SurfaceCondition)`

SetSurfaceCondition sets SurfaceCondition field to given value.

### HasSurfaceCondition

`func (o *SnowReport) HasSurfaceCondition() bool`

HasSurfaceCondition returns a boolean if a field has been set.

### SetSurfaceConditionNil

`func (o *SnowReport) SetSurfaceConditionNil(b bool)`

 SetSurfaceConditionNil sets the value for SurfaceCondition to be an explicit nil

### UnsetSurfaceCondition
`func (o *SnowReport) UnsetSurfaceCondition()`

UnsetSurfaceCondition ensures that no value is present for SurfaceCondition, not even an explicit nil
### GetSecondarySurfaceCondition

`func (o *SnowReport) GetSecondarySurfaceCondition() SurfaceCondition`

GetSecondarySurfaceCondition returns the SecondarySurfaceCondition field if non-nil, zero value otherwise.

### GetSecondarySurfaceConditionOk

`func (o *SnowReport) GetSecondarySurfaceConditionOk() (*SurfaceCondition, bool)`

GetSecondarySurfaceConditionOk returns a tuple with the SecondarySurfaceCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondarySurfaceCondition

`func (o *SnowReport) SetSecondarySurfaceCondition(v SurfaceCondition)`

SetSecondarySurfaceCondition sets SecondarySurfaceCondition field to given value.

### HasSecondarySurfaceCondition

`func (o *SnowReport) HasSecondarySurfaceCondition() bool`

HasSecondarySurfaceCondition returns a boolean if a field has been set.

### SetSecondarySurfaceConditionNil

`func (o *SnowReport) SetSecondarySurfaceConditionNil(b bool)`

 SetSecondarySurfaceConditionNil sets the value for SecondarySurfaceCondition to be an explicit nil

### UnsetSecondarySurfaceCondition
`func (o *SnowReport) UnsetSecondarySurfaceCondition()`

UnsetSecondarySurfaceCondition ensures that no value is present for SecondarySurfaceCondition, not even an explicit nil
### GetConditionNotes

`func (o *SnowReport) GetConditionNotes() string`

GetConditionNotes returns the ConditionNotes field if non-nil, zero value otherwise.

### GetConditionNotesOk

`func (o *SnowReport) GetConditionNotesOk() (*string, bool)`

GetConditionNotesOk returns a tuple with the ConditionNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionNotes

`func (o *SnowReport) SetConditionNotes(v string)`

SetConditionNotes sets ConditionNotes field to given value.


### GetSnowfallCm

`func (o *SnowReport) GetSnowfallCm() SnowMetrics`

GetSnowfallCm returns the SnowfallCm field if non-nil, zero value otherwise.

### GetSnowfallCmOk

`func (o *SnowReport) GetSnowfallCmOk() (*SnowMetrics, bool)`

GetSnowfallCmOk returns a tuple with the SnowfallCm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfallCm

`func (o *SnowReport) SetSnowfallCm(v SnowMetrics)`

SetSnowfallCm sets SnowfallCm field to given value.


### GetSnowfallIn

`func (o *SnowReport) GetSnowfallIn() SnowMetrics`

GetSnowfallIn returns the SnowfallIn field if non-nil, zero value otherwise.

### GetSnowfallInOk

`func (o *SnowReport) GetSnowfallInOk() (*SnowMetrics, bool)`

GetSnowfallInOk returns a tuple with the SnowfallIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfallIn

`func (o *SnowReport) SetSnowfallIn(v SnowMetrics)`

SetSnowfallIn sets SnowfallIn field to given value.


### GetReportedAt

`func (o *SnowReport) GetReportedAt() time.Time`

GetReportedAt returns the ReportedAt field if non-nil, zero value otherwise.

### GetReportedAtOk

`func (o *SnowReport) GetReportedAtOk() (*time.Time, bool)`

GetReportedAtOk returns a tuple with the ReportedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportedAt

`func (o *SnowReport) SetReportedAt(v time.Time)`

SetReportedAt sets ReportedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


