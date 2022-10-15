# \OrderApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**inventory**](OrderApi.md#inventory) | **GET** /v1/orders/orders | Query the current inventory of pets.
[**order**](OrderApi.md#order) | **POST** /v1/orders/orders | Order a new pet. (unary operation)
[**order_status**](OrderApi.md#order_status) | **GET** /v1/orders/orders/{id} | Check the status of your order.



## inventory

> crate::models::Inventory inventory()
Query the current inventory of pets.

Query the current inventory of pets.

### Parameters

This endpoint does not need any parameter.

### Return type

[**crate::models::Inventory**](Inventory.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## order

> crate::models::Order order(order_request)
Order a new pet. (unary operation)

Order a new pet. (unary operation)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**order_request** | [**OrderRequest**](OrderRequest.md) |  | [required] |

### Return type

[**crate::models::Order**](Order.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## order_status

> crate::models::Order order_status(id)
Check the status of your order.

Check the status of your order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**crate::models::Order**](Order.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

