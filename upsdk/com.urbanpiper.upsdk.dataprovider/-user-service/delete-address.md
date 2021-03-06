[upsdk](../../index.md) / [com.urbanpiper.upsdk.dataprovider](../index.md) / [UserService](index.md) / [deleteAddress](./delete-address.md)

# deleteAddress

`abstract fun deleteAddress(addressId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)

This method deletes an existing address for a user

### Parameters

`addressId` -
* Address id

`callback` -
* Callback

**Return**
CancellableTask - the request can be cancelled by calling .cancel() on the CancellableTask

`abstract fun deleteAddress(addressId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>`

This method deletes an existing address for a user

### Parameters

`addressId` -
* Address id

**Return**
Observable - the result of the network request is returned as an Observable

