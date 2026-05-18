# \MtnManagerAPI

All URIs are relative to *https://your-resort.mtnmanager.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAmenities**](MtnManagerAPI.md#GetAmenities) | **Get** /api/v1/report/amenities | Get amenities
[**GetFullReport**](MtnManagerAPI.md#GetFullReport) | **Get** /api/v1/report | Get full report
[**GetHours**](MtnManagerAPI.md#GetHours) | **Get** /api/v1/report/hours | Get operating hours
[**GetLifts**](MtnManagerAPI.md#GetLifts) | **Get** /api/v1/report/lifts | Get lifts
[**GetOverview**](MtnManagerAPI.md#GetOverview) | **Get** /api/v1/report/overview | Get overview
[**GetParkingLots**](MtnManagerAPI.md#GetParkingLots) | **Get** /api/v1/report/parking-lots | Get parking lots
[**GetRuns**](MtnManagerAPI.md#GetRuns) | **Get** /api/v1/report/runs | Get runs
[**GetSnow**](MtnManagerAPI.md#GetSnow) | **Get** /api/v1/report/snow | Get snow conditions
[**GetSummerTrails**](MtnManagerAPI.md#GetSummerTrails) | **Get** /api/v1/report/summer-trails | Get summer trails
[**GetTerrainParks**](MtnManagerAPI.md#GetTerrainParks) | **Get** /api/v1/report/terrain-parks | Get terrain parks
[**GetTrailMap**](MtnManagerAPI.md#GetTrailMap) | **Get** /api/v1/report/trail-map/{uuid} | Get trail map
[**GetTrailMaps**](MtnManagerAPI.md#GetTrailMaps) | **Get** /api/v1/report/trail-maps | Get trail maps
[**GetWeather**](MtnManagerAPI.md#GetWeather) | **Get** /api/v1/report/weather | Get weather



## GetAmenities

> []Amenity GetAmenities(ctx).AcceptLanguage(acceptLanguage).Execute()

Get amenities

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetAmenities(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetAmenities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAmenities`: []Amenity
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetAmenities`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAmenitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]Amenity**](Amenity.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFullReport

> FullReport GetFullReport(ctx).AcceptLanguage(acceptLanguage).Execute()

Get full report

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetFullReport(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetFullReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFullReport`: FullReport
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetFullReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFullReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**FullReport**](FullReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetHours

> OperatingHours GetHours(ctx).AcceptLanguage(acceptLanguage).Execute()

Get operating hours

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetHours(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetHours``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHours`: OperatingHours
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetHours`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetHoursRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**OperatingHours**](OperatingHours.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLifts

> []Lift GetLifts(ctx).AcceptLanguage(acceptLanguage).Execute()

Get lifts

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetLifts(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetLifts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLifts`: []Lift
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetLifts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLiftsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]Lift**](Lift.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOverview

> Overview GetOverview(ctx).AcceptLanguage(acceptLanguage).Execute()

Get overview

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetOverview(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetOverview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOverview`: Overview
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetOverview`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetOverviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**Overview**](Overview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetParkingLots

> []ParkingLot GetParkingLots(ctx).AcceptLanguage(acceptLanguage).Execute()

Get parking lots

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetParkingLots(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetParkingLots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetParkingLots`: []ParkingLot
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetParkingLots`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetParkingLotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]ParkingLot**](ParkingLot.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRuns

> []Run GetRuns(ctx).AcceptLanguage(acceptLanguage).Execute()

Get runs

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetRuns(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRuns`: []Run
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetRuns`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRunsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]Run**](Run.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSnow

> []SnowReport GetSnow(ctx).AcceptLanguage(acceptLanguage).Execute()

Get snow conditions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetSnow(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetSnow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSnow`: []SnowReport
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetSnow`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSnowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]SnowReport**](SnowReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSummerTrails

> []SummerTrail GetSummerTrails(ctx).AcceptLanguage(acceptLanguage).Execute()

Get summer trails

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetSummerTrails(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetSummerTrails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSummerTrails`: []SummerTrail
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetSummerTrails`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSummerTrailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]SummerTrail**](SummerTrail.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTerrainParks

> []TerrainPark GetTerrainParks(ctx).AcceptLanguage(acceptLanguage).Execute()

Get terrain parks

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetTerrainParks(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetTerrainParks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTerrainParks`: []TerrainPark
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetTerrainParks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTerrainParksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]TerrainPark**](TerrainPark.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrailMap

> TrailMap GetTrailMap(ctx, uuid).AcceptLanguage(acceptLanguage).Execute()

Get trail map

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	uuid := "uuid_example" // string | Resource UUID
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetTrailMap(context.Background(), uuid).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetTrailMap``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrailMap`: TrailMap
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetTrailMap`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Resource UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTrailMapRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**TrailMap**](TrailMap.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrailMaps

> []TrailMapSummary GetTrailMaps(ctx).AcceptLanguage(acceptLanguage).Execute()

Get trail maps

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetTrailMaps(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetTrailMaps``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrailMaps`: []TrailMapSummary
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetTrailMaps`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTrailMapsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**[]TrailMapSummary**](TrailMapSummary.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWeather

> Weather GetWeather(ctx).AcceptLanguage(acceptLanguage).Execute()

Get weather

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {
	acceptLanguage := "fr-CA" // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetWeather(context.Background()).AcceptLanguage(acceptLanguage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetWeather``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWeather`: Weather
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetWeather`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWeatherRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | 

### Return type

[**Weather**](Weather.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

