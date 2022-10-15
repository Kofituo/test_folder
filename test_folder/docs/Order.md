# Order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** | The order ID. | 
**adopter** | **i64** | An adopter's user id. | 
**pet** | **i64** | A pet's pet id. | 
**date** | **String** | The date the order was placed. | 
**status** | [**crate::models::OrderStatus**](OrderStatus.md) |  | 
**complete** | Option<[**serde_json::Value**](.md)> | Whether or not the order is considered complete, regardless of status. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


