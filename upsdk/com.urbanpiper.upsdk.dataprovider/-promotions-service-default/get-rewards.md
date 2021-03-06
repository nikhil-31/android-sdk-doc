[upsdk](../../index.md) / [com.urbanpiper.upsdk.dataprovider](../index.md) / [PromotionsServiceDefault](index.md) / [getRewards](./get-rewards.md)

# getRewards

`fun getRewards(callback: `[`Callback`](../-callback/index.md)`<`[`RewardsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-rewards-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)

Overrides [PromotionsService.getRewards](../-promotions-service/get-rewards.md)

This endpoint returns the list of rewards that are configured in the system.
Rewards might be in one of the following states for a user

### Parameters

`callback` -
* Callback to return the result

**Return**
CancellableTask - the request can be cancelled by calling .cancel() on the CancellableTask

`fun getRewards(): Observable<`[`RewardsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-rewards-response/index.md)`>`

Overrides [PromotionsService.getRewards](../-promotions-service/get-rewards.md)

This endpoint returns the list of rewards that are configured in the system.
Rewards might be in one of the following states for a user

**Return**
Observable - the result of the network request is returned as an Observable

