# PetsPatchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hunts** | **bool** |  | [optional] 
**age** | **int** |  | [optional] 
**bark** | **bool** |  | [optional] 
**breed** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.pets_patch_request import PetsPatchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PetsPatchRequest from a JSON string
pets_patch_request_instance = PetsPatchRequest.from_json(json)
# print the JSON string representation of the object
print(PetsPatchRequest.to_json())

# convert the object into a dict
pets_patch_request_dict = pets_patch_request_instance.to_dict()
# create an instance of PetsPatchRequest from a dict
pets_patch_request_from_dict = PetsPatchRequest.from_dict(pets_patch_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


