# OverviewNews

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Raw** | **string** | Raw Markdown source. | 
**Html** | **string** | Rendered HTML (from Markdown). | 
**UpdatedAt** | **time.Time** | When the news was last updated. | 

## Methods

### NewOverviewNews

`func NewOverviewNews(raw string, html string, updatedAt time.Time, ) *OverviewNews`

NewOverviewNews instantiates a new OverviewNews object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewNewsWithDefaults

`func NewOverviewNewsWithDefaults() *OverviewNews`

NewOverviewNewsWithDefaults instantiates a new OverviewNews object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRaw

`func (o *OverviewNews) GetRaw() string`

GetRaw returns the Raw field if non-nil, zero value otherwise.

### GetRawOk

`func (o *OverviewNews) GetRawOk() (*string, bool)`

GetRawOk returns a tuple with the Raw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaw

`func (o *OverviewNews) SetRaw(v string)`

SetRaw sets Raw field to given value.


### GetHtml

`func (o *OverviewNews) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *OverviewNews) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *OverviewNews) SetHtml(v string)`

SetHtml sets Html field to given value.


### GetUpdatedAt

`func (o *OverviewNews) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OverviewNews) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OverviewNews) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


