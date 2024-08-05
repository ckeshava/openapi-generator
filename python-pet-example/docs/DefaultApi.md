# openapi_client.DefaultApi

All URIs are relative to *https://petstore3.swagger.io/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**pets_patch**](DefaultApi.md#pets_patch) | **PATCH** /pets | 


# **pets_patch**
> pets_patch(pets_patch_request=pets_patch_request)



### Example


```python
import openapi_client
from openapi_client.models.pets_patch_request import PetsPatchRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://petstore3.swagger.io/api/v3
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://petstore3.swagger.io/api/v3"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    pets_patch_request = openapi_client.PetsPatchRequest() # PetsPatchRequest |  (optional)

    try:
        api_instance.pets_patch(pets_patch_request=pets_patch_request)
    except Exception as e:
        print("Exception when calling DefaultApi->pets_patch: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pets_patch_request** | [**PetsPatchRequest**](PetsPatchRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Updated |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

