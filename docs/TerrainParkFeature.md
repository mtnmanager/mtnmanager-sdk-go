# TerrainParkFeature

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the feature. | 
**Name** | **string** | Display name of the feature. | 
**Slug** | **string** | URL-friendly name of the run. | 
**Number** | Pointer to **NullableInt32** | Optional feature number. | [optional] 
**FeatureType** | [**FeatureType**](FeatureType.md) | Type of feature (jump, box, rail, other). | 
**Size** | Pointer to [**NullableFeatureSize**](FeatureSize.md) |  | [optional] 
**Status** | [**TerrainParkFeatureStatus**](TerrainParkFeatureStatus.md) | Current operational status (open, closed, or unknown).  &#x60;unknown&#x60; unless the terrain park feature status is enabled. | 

## Methods

### NewTerrainParkFeature

`func NewTerrainParkFeature(uuid string, name string, slug string, featureType FeatureType, status TerrainParkFeatureStatus, ) *TerrainParkFeature`

NewTerrainParkFeature instantiates a new TerrainParkFeature object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerrainParkFeatureWithDefaults

`func NewTerrainParkFeatureWithDefaults() *TerrainParkFeature`

NewTerrainParkFeatureWithDefaults instantiates a new TerrainParkFeature object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *TerrainParkFeature) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TerrainParkFeature) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TerrainParkFeature) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *TerrainParkFeature) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TerrainParkFeature) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TerrainParkFeature) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *TerrainParkFeature) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *TerrainParkFeature) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *TerrainParkFeature) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetNumber

`func (o *TerrainParkFeature) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *TerrainParkFeature) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *TerrainParkFeature) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *TerrainParkFeature) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *TerrainParkFeature) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *TerrainParkFeature) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetFeatureType

`func (o *TerrainParkFeature) GetFeatureType() FeatureType`

GetFeatureType returns the FeatureType field if non-nil, zero value otherwise.

### GetFeatureTypeOk

`func (o *TerrainParkFeature) GetFeatureTypeOk() (*FeatureType, bool)`

GetFeatureTypeOk returns a tuple with the FeatureType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureType

`func (o *TerrainParkFeature) SetFeatureType(v FeatureType)`

SetFeatureType sets FeatureType field to given value.


### GetSize

`func (o *TerrainParkFeature) GetSize() FeatureSize`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *TerrainParkFeature) GetSizeOk() (*FeatureSize, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *TerrainParkFeature) SetSize(v FeatureSize)`

SetSize sets Size field to given value.

### HasSize

`func (o *TerrainParkFeature) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *TerrainParkFeature) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *TerrainParkFeature) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetStatus

`func (o *TerrainParkFeature) GetStatus() TerrainParkFeatureStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TerrainParkFeature) GetStatusOk() (*TerrainParkFeatureStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TerrainParkFeature) SetStatus(v TerrainParkFeatureStatus)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


