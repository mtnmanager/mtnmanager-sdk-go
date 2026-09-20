# AppConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HostedBaseUrl** | **string** | The resort&#39;s hosted base URL — scheme + host with no path, e.g.  &#x60;https://powder-mountain.mtnmanager.net&#x60;, or the resort&#39;s own custom  domain when one is configured. | 
**TrailMapAssetsUpdatedAt** | **string** | Last time the static trail-map assets were re-published, ISO 8601 UTC.  Bumped when those assets change so clients can cache-bust. | 

## Methods

### NewAppConfig

`func NewAppConfig(hostedBaseUrl string, trailMapAssetsUpdatedAt string, ) *AppConfig`

NewAppConfig instantiates a new AppConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppConfigWithDefaults

`func NewAppConfigWithDefaults() *AppConfig`

NewAppConfigWithDefaults instantiates a new AppConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHostedBaseUrl

`func (o *AppConfig) GetHostedBaseUrl() string`

GetHostedBaseUrl returns the HostedBaseUrl field if non-nil, zero value otherwise.

### GetHostedBaseUrlOk

`func (o *AppConfig) GetHostedBaseUrlOk() (*string, bool)`

GetHostedBaseUrlOk returns a tuple with the HostedBaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostedBaseUrl

`func (o *AppConfig) SetHostedBaseUrl(v string)`

SetHostedBaseUrl sets HostedBaseUrl field to given value.


### GetTrailMapAssetsUpdatedAt

`func (o *AppConfig) GetTrailMapAssetsUpdatedAt() string`

GetTrailMapAssetsUpdatedAt returns the TrailMapAssetsUpdatedAt field if non-nil, zero value otherwise.

### GetTrailMapAssetsUpdatedAtOk

`func (o *AppConfig) GetTrailMapAssetsUpdatedAtOk() (*string, bool)`

GetTrailMapAssetsUpdatedAtOk returns a tuple with the TrailMapAssetsUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailMapAssetsUpdatedAt

`func (o *AppConfig) SetTrailMapAssetsUpdatedAt(v string)`

SetTrailMapAssetsUpdatedAt sets TrailMapAssetsUpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


