[upsdk](../../index.md) / [com.urbanpiper.upsdk.dataprovider](../index.md) / [UserService](index.md) / [submitFeedback](./submit-feedback.md)

# submitFeedback

`abstract fun submitFeedback(feedback: `[`UserFeedback`](../../com.urbanpiper.upsdk.model.networkresponse/-user-feedback/index.md)`, callback: `[`Callback`](../-callback/index.md)`<`[`SimpleResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-simple-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)

Submit feedback

### Parameters

`feedback` -

`callback` -

**Return**
CancellableTask - the request can be cancelled by calling .cancel() on the CancellableTask

`abstract fun submitFeedback(feedback: `[`UserFeedback`](../../com.urbanpiper.upsdk.model.networkresponse/-user-feedback/index.md)`): Observable<`[`SimpleResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-simple-response/index.md)`>`

Submit feedback

### Parameters

`feedback` -

**Return**
Observable - the result of the network request is returned as an Observable

