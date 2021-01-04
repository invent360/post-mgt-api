# Post

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**UserId** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewPost

`func NewPost(id int64, ) *Post`

NewPost instantiates a new Post object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostWithDefaults

`func NewPostWithDefaults() *Post`

NewPostWithDefaults instantiates a new Post object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Post) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Post) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Post) SetId(v int64)`

SetId sets Id field to given value.


### GetUserId

`func (o *Post) GetUserId() int64`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Post) GetUserIdOk() (*int64, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Post) SetUserId(v int64)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Post) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetName

`func (o *Post) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Post) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Post) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Post) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


