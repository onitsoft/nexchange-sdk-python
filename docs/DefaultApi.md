# nexchange.DefaultApi

All URIs are relative to *https://nexchange.co.uk*

Method | HTTP request | Description
------------- | ------------- | -------------
[**en_api_v1_currency_get**](DefaultApi.md#en_api_v1_currency_get) | **GET** /en/api/v1/currency/ | Get Currencies
[**en_api_v1_orders_get**](DefaultApi.md#en_api_v1_orders_get) | **GET** /en/api/v1/orders/ | Get Orders
[**en_api_v1_orders_post**](DefaultApi.md#en_api_v1_orders_post) | **POST** /en/api/v1/orders/ | Create Anonymous Order
[**en_api_v1_orders_unique_reference_get**](DefaultApi.md#en_api_v1_orders_unique_reference_get) | **GET** /en/api/v1/orders/{unique_reference}/ | Get Order
[**en_api_v1_pair_get**](DefaultApi.md#en_api_v1_pair_get) | **GET** /en/api/v1/pair/ | Get Pairs
[**en_api_v1_price_pair_name_history_get**](DefaultApi.md#en_api_v1_price_pair_name_history_get) | **GET** /en/api/v1/price/{pair_name}/history/ | Get Ticker History
[**en_api_v1_price_pair_name_latest_get**](DefaultApi.md#en_api_v1_price_pair_name_latest_get) | **GET** /en/api/v1/price/{pair_name}/latest/ | Get Latest Ticker
[**en_api_v1_users_me_orders_get**](DefaultApi.md#en_api_v1_users_me_orders_get) | **GET** /en/api/v1/users/me/orders/ | Get User Orders
[**en_api_v1_users_me_orders_post**](DefaultApi.md#en_api_v1_users_me_orders_post) | **POST** /en/api/v1/users/me/orders/ | Create User Order
[**en_api_v1_users_me_orders_unique_reference_get**](DefaultApi.md#en_api_v1_users_me_orders_unique_reference_get) | **GET** /en/api/v1/users/me/orders/{unique_reference}/ | Get User Order


# **en_api_v1_currency_get**
> en_api_v1_currency_get()

Get Currencies

Get pairs.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()

try: 
    # Get Currencies
    api_instance.en_api_v1_currency_get()
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_currency_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_orders_get**
> en_api_v1_orders_get(page, page_size)

Get Orders

Gets list of orders.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()
page = 'page_example' # str | 
page_size = 'page_size_example' # str | 

try: 
    # Get Orders
    api_instance.en_api_v1_orders_get(page, page_size)
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_orders_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **str**|  | 
 **page_size** | **str**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_orders_post**
> en_api_v1_orders_post()

Create Anonymous Order

Create order.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()

try: 
    # Create Anonymous Order
    api_instance.en_api_v1_orders_post()
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_orders_post: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_orders_unique_reference_get**
> en_api_v1_orders_unique_reference_get(unique_reference)

Get Order

Get order data.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()
unique_reference = 'unique_reference_example' # str | 

try: 
    # Get Order
    api_instance.en_api_v1_orders_unique_reference_get(unique_reference)
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_orders_unique_reference_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **unique_reference** | **str**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_pair_get**
> en_api_v1_pair_get()

Get Pairs

Get pairs.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()

try: 
    # Get Pairs
    api_instance.en_api_v1_pair_get()
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_pair_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_price_pair_name_history_get**
> en_api_v1_price_pair_name_history_get(pair_name, hours, data_points)

Get Ticker History

Gets latests price of selected pair.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()
pair_name = 'pair_name_example' # str | 
hours = 'hours_example' # str | 
data_points = 'data_points_example' # str | 

try: 
    # Get Ticker History
    api_instance.en_api_v1_price_pair_name_history_get(pair_name, hours, data_points)
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_price_pair_name_history_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pair_name** | **str**|  | 
 **hours** | **str**|  | 
 **data_points** | **str**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_price_pair_name_latest_get**
> en_api_v1_price_pair_name_latest_get(pair_name)

Get Latest Ticker

Gets latests price of selected pair.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()
pair_name = 'pair_name_example' # str | 

try: 
    # Get Latest Ticker
    api_instance.en_api_v1_price_pair_name_latest_get(pair_name)
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_price_pair_name_latest_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pair_name** | **str**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_users_me_orders_get**
> en_api_v1_users_me_orders_get(page, page_size)

Get User Orders

Get user orders.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()
page = 'page_example' # str | 
page_size = 'page_size_example' # str | 

try: 
    # Get User Orders
    api_instance.en_api_v1_users_me_orders_get(page, page_size)
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_users_me_orders_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **str**|  | 
 **page_size** | **str**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_users_me_orders_post**
> en_api_v1_users_me_orders_post()

Create User Order

Create order.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()

try: 
    # Create User Order
    api_instance.en_api_v1_users_me_orders_post()
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_users_me_orders_post: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **en_api_v1_users_me_orders_unique_reference_get**
> en_api_v1_users_me_orders_unique_reference_get(unique_reference)

Get User Order

Get user order.

### Example 
```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = nexchange.DefaultApi()
unique_reference = 'unique_reference_example' # str | 

try: 
    # Get User Order
    api_instance.en_api_v1_users_me_orders_unique_reference_get(unique_reference)
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_users_me_orders_unique_reference_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **unique_reference** | **str**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

