# TrailMapStaticElementOneOf2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Uuid** | **string** |  | 
**Points** | **[]float64** |  | 
**Tension** | Pointer to **NullableFloat64** |  | [optional] 
**Geometry** | Pointer to [**NullableGeometryMode**](GeometryMode.md) |  | [optional] 
**LabelOffset** | Pointer to [**NullableLabelOffset**](LabelOffset.md) |  | [optional] 
**TerrainParkUuid** | **string** |  | 

## Methods

### NewTrailMapStaticElementOneOf2

`func NewTrailMapStaticElementOneOf2(type_ string, uuid string, points []float64, terrainParkUuid string, ) *TrailMapStaticElementOneOf2`

NewTrailMapStaticElementOneOf2 instantiates a new TrailMapStaticElementOneOf2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapStaticElementOneOf2WithDefaults

`func NewTrailMapStaticElementOneOf2WithDefaults() *TrailMapStaticElementOneOf2`

NewTrailMapStaticElementOneOf2WithDefaults instantiates a new TrailMapStaticElementOneOf2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrailMapStaticElementOneOf2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrailMapStaticElementOneOf2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrailMapStaticElementOneOf2) SetType(v string)`

SetType sets Type field to given value.


### GetUuid

`func (o *TrailMapStaticElementOneOf2) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapStaticElementOneOf2) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapStaticElementOneOf2) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetPoints

`func (o *TrailMapStaticElementOneOf2) GetPoints() []float64`

GetPoints returns the Points field if non-nil, zero value otherwise.

### GetPointsOk

`func (o *TrailMapStaticElementOneOf2) GetPointsOk() (*[]float64, bool)`

GetPointsOk returns a tuple with the Points field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoints

`func (o *TrailMapStaticElementOneOf2) SetPoints(v []float64)`

SetPoints sets Points field to given value.


### GetTension

`func (o *TrailMapStaticElementOneOf2) GetTension() float64`

GetTension returns the Tension field if non-nil, zero value otherwise.

### GetTensionOk

`func (o *TrailMapStaticElementOneOf2) GetTensionOk() (*float64, bool)`

GetTensionOk returns a tuple with the Tension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTension

`func (o *TrailMapStaticElementOneOf2) SetTension(v float64)`

SetTension sets Tension field to given value.

### HasTension

`func (o *TrailMapStaticElementOneOf2) HasTension() bool`

HasTension returns a boolean if a field has been set.

### SetTensionNil

`func (o *TrailMapStaticElementOneOf2) SetTensionNil(b bool)`

 SetTensionNil sets the value for Tension to be an explicit nil

### UnsetTension
`func (o *TrailMapStaticElementOneOf2) UnsetTension()`

UnsetTension ensures that no value is present for Tension, not even an explicit nil
### GetGeometry

`func (o *TrailMapStaticElementOneOf2) GetGeometry() GeometryMode`

GetGeometry returns the Geometry field if non-nil, zero value otherwise.

### GetGeometryOk

`func (o *TrailMapStaticElementOneOf2) GetGeometryOk() (*GeometryMode, bool)`

GetGeometryOk returns a tuple with the Geometry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeometry

`func (o *TrailMapStaticElementOneOf2) SetGeometry(v GeometryMode)`

SetGeometry sets Geometry field to given value.

### HasGeometry

`func (o *TrailMapStaticElementOneOf2) HasGeometry() bool`

HasGeometry returns a boolean if a field has been set.

### SetGeometryNil

`func (o *TrailMapStaticElementOneOf2) SetGeometryNil(b bool)`

 SetGeometryNil sets the value for Geometry to be an explicit nil

### UnsetGeometry
`func (o *TrailMapStaticElementOneOf2) UnsetGeometry()`

UnsetGeometry ensures that no value is present for Geometry, not even an explicit nil
### GetLabelOffset

`func (o *TrailMapStaticElementOneOf2) GetLabelOffset() LabelOffset`

GetLabelOffset returns the LabelOffset field if non-nil, zero value otherwise.

### GetLabelOffsetOk

`func (o *TrailMapStaticElementOneOf2) GetLabelOffsetOk() (*LabelOffset, bool)`

GetLabelOffsetOk returns a tuple with the LabelOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelOffset

`func (o *TrailMapStaticElementOneOf2) SetLabelOffset(v LabelOffset)`

SetLabelOffset sets LabelOffset field to given value.

### HasLabelOffset

`func (o *TrailMapStaticElementOneOf2) HasLabelOffset() bool`

HasLabelOffset returns a boolean if a field has been set.

### SetLabelOffsetNil

`func (o *TrailMapStaticElementOneOf2) SetLabelOffsetNil(b bool)`

 SetLabelOffsetNil sets the value for LabelOffset to be an explicit nil

### UnsetLabelOffset
`func (o *TrailMapStaticElementOneOf2) UnsetLabelOffset()`

UnsetLabelOffset ensures that no value is present for LabelOffset, not even an explicit nil
### GetTerrainParkUuid

`func (o *TrailMapStaticElementOneOf2) GetTerrainParkUuid() string`

GetTerrainParkUuid returns the TerrainParkUuid field if non-nil, zero value otherwise.

### GetTerrainParkUuidOk

`func (o *TrailMapStaticElementOneOf2) GetTerrainParkUuidOk() (*string, bool)`

GetTerrainParkUuidOk returns a tuple with the TerrainParkUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerrainParkUuid

`func (o *TrailMapStaticElementOneOf2) SetTerrainParkUuid(v string)`

SetTerrainParkUuid sets TerrainParkUuid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


