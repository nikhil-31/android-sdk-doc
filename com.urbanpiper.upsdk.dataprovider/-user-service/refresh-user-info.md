[upsdk](../../index.md) / [com.urbanpiper.upsdk.dataprovider](../index.md) / [UserService](index.md) / [refreshUserInfo](./refresh-user-info.md)

# refreshUserInfo

`abstract fun refreshUserInfo(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-info-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)

Returns the profile data associated with a particular user identified by his/her phone number.

### Parameters

`phone` -
* Phone number

`callback` -
* The result is returned as a callback

**Return**
CancellableTask - the request can be cancelled by calling .cancel() on the CancellableTask

`abstract fun refreshUserInfo(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`UserInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-info-response/index.md)`>`

Returns the profile data associated with a particular user identified by his/her phone number.

### Parameters

`phone` -
* Phone number

**Return**
Observable - the result of the network request is returned as an Observable

