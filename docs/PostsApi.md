# \PostsApi

All URIs are relative to *http://jsonplaceholder.typicode.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPosts**](PostsApi.md#GetPosts) | **Get** /posts | Get all posts



## GetPosts

> Post GetPosts(ctx).Execute()

Get all posts



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewAPIClient(configuration)
    resp, r, err := api_client.PostsApi.GetPosts(context.Background()).Execute()
    if err.Error() != "" {
        fmt.Fprintf(os.Stderr, "Error when calling `PostsApi.GetPosts``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `GetPosts`: Post
    fmt.Fprintf(os.Stdout, "Response from `PostsApi.GetPosts`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPostsRequest struct via the builder pattern


### Return type

[**Post**](Post.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

