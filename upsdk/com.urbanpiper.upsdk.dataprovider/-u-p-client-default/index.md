[upsdk](../../index.md) / [com.urbanpiper.upsdk.dataprovider](../index.md) / [UPClientDefault](./index.md)

# UPClientDefault

`class UPClientDefault : `[`UPClient`](../-u-p-client/index.md)

All methods for the UPSDK are available through
this class.

This class is a facade

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UPClientDefault(bizId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, apiUsername: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, apiKey: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, language: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserBizInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-biz-info-response/index.md)`>)`<br>All methods for the UPSDK are available through this class. |

### Functions

| Name | Summary |
|---|---|
| [addAddress](add-address.md) | `fun addAddress(userAddress: `[`UserAddress`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address/index.md)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun addAddress(userAddress: `[`UserAddress`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address/index.md)`): Observable<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>`<br>This method adds a new address for the user |
| [changeLanguage](change-language.md) | `fun changeLanguage(language: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>This method is used to change the language of the response being passed to the SDK |
| [changePassword](change-password.md) | `fun changePassword(oldPassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, newPassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, confirmPassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`GenericResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-generic-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun changePassword(oldPassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, newPassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, confirmPassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`GenericResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-generic-response/index.md)`>`<br>Change the password for a user, The new password has to be passed in twice so the server can verify it |
| [checkAppVersion](check-app-version.md) | `fun checkAppVersion(username: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`VersionCheckResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-version-check-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun checkAppVersion(username: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`VersionCheckResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-version-check-response/index.md)`>`<br>returns the latest version of the android app as configured on the server |
| [deleteAddress](delete-address.md) | `fun deleteAddress(addressId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun deleteAddress(addressId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>`<br>This method deletes an existing address for a user |
| [getAPIKey](get-a-p-i-key.md) | `fun getAPIKey(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns api key |
| [getAllStores](get-all-stores.md) | `fun getAllStores(callback: `[`Callback`](../-callback/index.md)`<`[`StoreListResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-store-list-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getAllStores(): Observable<`[`StoreListResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-store-list-response/index.md)`>`<br>Returns all the stores for the business |
| [getApiUserName](get-api-user-name.md) | `fun getApiUserName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns api username |
| [getBanners](get-banners.md) | `fun getBanners(callback: `[`Callback`](../-callback/index.md)`<`[`BannerResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-banner-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getBanners(): Observable<`[`BannerResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-banner-response/index.md)`>`<br>The Gallery method returns the list of images that have been uploaded through the configuration portal. |
| [getBizId](get-biz-id.md) | `fun getBizId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns biz id |
| [getBizLanguage](get-biz-language.md) | `fun getBizLanguage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns current language being passed to the SDK |
| [getCart](get-cart.md) | `fun getCart(locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Cart`](../-cart/index.md)<br>This method returns a reference to a singleton instance of a cart |
| [getCartRelatedItems](get-cart-related-items.md) | `fun getCartRelatedItems(itemIds: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`RecommendedItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-recommended-item-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getCartRelatedItems(itemIds: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`RecommendedItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-recommended-item-response/index.md)`>`<br>returns a list of items which are sent based on the location id and other items Multiple item id's can be passed as comma separated values Eg( id1,id2,id3 ) |
| [getCategories](get-categories.md) | `fun getCategories(locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`CategoriesResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-categories-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getCategories(locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`CategoriesResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-categories-response/index.md)`>`<br>returns a list of active categories of items from which an order can be placed |
| [getCategoryItems](get-category-items.md) | `fun getCategoryItems(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`CategoryItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-item-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getCategoryItems(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`CategoryItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-item-response/index.md)`>`<br>returns a list of active items for a category from which an order can be placed |
| [getCheckOutBuilder](get-check-out-builder.md) | `fun getCheckOutBuilder(): `[`CheckoutBuilder`](../-checkout-builder/index.md)<br>This method returns an instance of the Checkout Builder |
| [getCoupons](get-coupons.md) | `fun getCoupons(callback: `[`Callback`](../-callback/index.md)`<`[`OffersResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-offers-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getCoupons(): Observable<`[`OffersResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-offers-response/index.md)`>`<br>This method returns a list of offers that can be applied to an order |
| [getDeliverableAddresses](get-deliverable-addresses.md) | `fun getDeliverableAddresses(locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`DeliverableAddressResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-deliverable-address-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>This method returns a list of addresses for a given location idm with a field deliverable(true or false) indicating if delivery is possible for that location or not`fun getDeliverableAddresses(locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`DeliverableAddressResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-deliverable-address-response/index.md)`>`<br>This method returns a list of addresses for a given location id with a field deliverable(true or false) indicating if delivery is possible for that location or not |
| [getFilterAndSortOptions](get-filter-and-sort-options.md) | `fun getFilterAndSortOptions(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`FilterAndSortOptionsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-filter-and-sort-options-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getFilterAndSortOptions(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`FilterAndSortOptionsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-filter-and-sort-options-response/index.md)`>`<br>This endpoint handles requests to get available filter and sort options for a category. |
| [getFilteredItems](get-filtered-items.md) | `fun getFilteredItems(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, filterBy: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`CategoryItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-item-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getFilteredItems(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, filterBy: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`CategoryItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-item-response/index.md)`>`<br>returns a list of active items filtered based on the filters passed |
| [getItemDetails](get-item-details.md) | `fun getItemDetails(itemId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`ItemDetailsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-item-details-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getItemDetails(itemId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`ItemDetailsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-item-details-response/index.md)`>`<br>This method returns detailed information for a particular ordering item |
| [getItemOptionBuilder](get-item-option-builder.md) | `fun getItemOptionBuilder(): `[`ItemOptionBuilder`](../-item-option-builder/index.md)<br>This method returns an instance of the item option builder |
| [getNearestStore](get-nearest-store.md) | `fun getNearestStore(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`StoreResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-store-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getNearestStore(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): Observable<`[`StoreResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-store-response/index.md)`>`<br>Returns the nearest store based on lat/ lng |
| [getNotifications](get-notifications.md) | `fun getNotifications(callback: `[`Callback`](../-callback/index.md)`<`[`UserBizNotificationsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-biz-notifications-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getNotifications(): Observable<`[`UserBizNotificationsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-biz-notifications-response/index.md)`>`<br>This method returns a list of all the notifications that was sent to that user |
| [getPastOrderDetails](get-past-order-details.md) | `fun getPastOrderDetails(orderId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`OrderDetailResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-order-detail-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getPastOrderDetails(orderId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`OrderDetailResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-order-detail-response/index.md)`>`<br>Returns details information about an order |
| [getPastOrders](get-past-orders.md) | `fun getPastOrders(callback: `[`Callback`](../-callback/index.md)`<`[`OrderHistoryResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-order-history-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getPastOrders(): Observable<`[`OrderHistoryResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-order-history-response/index.md)`>`<br>This endpoint returns the list of orders placed by a user in the past. Only the summary data for each order is returned. This should be used when a client needs to display the past orders placed by a user. |
| [getRecommendedItems](get-recommended-items.md) | `fun getRecommendedItems(locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`RecommendedItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-recommended-item-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getRecommendedItems(locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`RecommendedItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-recommended-item-response/index.md)`>`<br>returns a list of active recommended items which are sent based on the location id (based on the store) |
| [getRegistrationBuilder](get-registration-builder.md) | `fun getRegistrationBuilder(): `[`RegistrationBuilder`](../-registration-builder/index.md)<br>This method returns an instance of the Registration Builder |
| [getRelatedItems](get-related-items.md) | `fun getRelatedItems(itemId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`RecommendedItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-recommended-item-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getRelatedItems(itemId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`RecommendedItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-recommended-item-response/index.md)`>`<br>returns a list of items which are sent based on the location id and other items Multiple item id's can be passed as comma separated values Eg( id1,id2,id3 ) |
| [getResetPasswordBuilder](get-reset-password-builder.md) | `fun getResetPasswordBuilder(): `[`ResetPasswordBuilder`](../-reset-password-builder/index.md)<br>This method returns an instance of the reset password builder |
| [getRewards](get-rewards.md) | `fun getRewards(callback: `[`Callback`](../-callback/index.md)`<`[`RewardsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-rewards-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getRewards(): Observable<`[`RewardsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-rewards-response/index.md)`>`<br>This endpoint returns the list of rewards that are configured in the system. Rewards might be in one of the following states for a user |
| [getSocialRegBuilder](get-social-reg-builder.md) | `fun getSocialRegBuilder(): `[`SocialRegBuilder`](../-social-reg-builder/index.md)<br>This method returns an instance of the social reg builder |
| [getSortedItems](get-sorted-items.md) | `fun getSortedItems(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, sortBy: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`CategoryItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-item-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getSortedItems(categoryId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, sortBy: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`CategoryItemResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-item-response/index.md)`>`<br>returns a list of active items sorted based on the sort option passed |
| [getUser](get-user.md) | `fun getUser(): `[`User`](../../com.urbanpiper.upsdk.model/-user/index.md)`?`<br>This method returns an instance of the user object, it can be null if user is not signed in |
| [getUserLikes](get-user-likes.md) | `fun getUserLikes(ids: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserLikesResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-likes-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getUserLikes(ids: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`UserLikesResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-likes-response/index.md)`>`<br>Returns a list of likes for item id's passed as (eg - id1,id2,id3) |
| [getWalletTransactions](get-wallet-transactions.md) | `fun getWalletTransactions(limit: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`TransactionsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-transactions-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun getWalletTransactions(limit: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, offset: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`TransactionsResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-transactions-response/index.md)`>`<br>This endpoint returns a list of prepaid transactions associated with the user. Each of the transactions contains some basic information about the context of the transaction. Since the white-label prepaid wallet instrument is available to the user to perform some other transaction - like paying for an online order or an in-store purchase - each prepaid transaction can be thought of as an enabler for an associated transaction. |
| [initWalletReload](init-wallet-reload.md) | `fun initWalletReload(storeId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, amount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, redirectUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paytm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, simpl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, callback: `[`Callback`](../-callback/index.md)`<`[`PaymentInitResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-payment-init-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun initWalletReload(storeId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, amount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, redirectUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paytm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, simpl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Observable<`[`PaymentInitResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-payment-init-response/index.md)`>`<br>Initiates wallet reload |
| [likeItem](like-item.md) | `fun likeItem(itemId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`Like`](../../com.urbanpiper.upsdk.model.networkresponse/-like/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun likeItem(itemId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`Like`](../../com.urbanpiper.upsdk.model.networkresponse/-like/index.md)`>`<br>This method likes an item based on the item id |
| [login](login.md) | `fun login(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`AuthSuccessResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-auth-success-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun login(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`AuthSuccessResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-auth-success-response/index.md)`>`<br>For login the user needs to provide his/her phone number, along with the password that they had set for their account. |
| [reOrder](re-order.md) | `fun reOrder(orderId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lat: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lng: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`ReOrderResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-re-order-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun reOrder(orderId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lat: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lng: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`ReOrderResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-re-order-response/index.md)`>`<br>This endpoint validates whether a previously placed order can be re-ordered. The response indicates which items can be re-ordered and which can’t be. |
| [redeemReward](redeem-reward.md) | `fun redeemReward(rewardId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`RedeemRewardResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-redeem-reward-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun redeemReward(rewardId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`RedeemRewardResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-redeem-reward-response/index.md)`>`<br>This method redeems a reward for a user |
| [refreshToken](refresh-token.md) | `fun refreshToken(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`AuthSuccessResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-auth-success-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun refreshToken(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`AuthSuccessResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-auth-success-response/index.md)`>`<br>We use JWT tokens for authentication, we need to use this method to get a new token if the current token has completed 80% of it's lifetime |
| [refreshUserBizInfo](refresh-user-biz-info.md) | `fun refreshUserBizInfo(callback: `[`Callback`](../-callback/index.md)`<`[`UserBizInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-biz-info-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun refreshUserBizInfo(): Observable<`[`UserBizInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-biz-info-response/index.md)`>`<br>Returns the profile data associated with a particular user identified by his/her phone number. |
| [refreshUserInfo](refresh-user-info.md) | `fun refreshUserInfo(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-info-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun refreshUserInfo(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`UserInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-info-response/index.md)`>`<br>Returns the profile data associated with a particular user identified by his/her phone number. |
| [registerFCMToken](register-f-c-m-token.md) | `fun registerFCMToken(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, deviceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`Void`](https://developer.android.com/reference/java/lang/Void.html)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun registerFCMToken(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, deviceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`Void`](https://developer.android.com/reference/java/lang/Void.html)`>`<br>Register the device for FCM |
| [searchItems](search-items.md) | `fun searchItems(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`CategorySearchResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-search-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun searchItems(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, locationId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`CategorySearchResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-category-search-response/index.md)`>`<br>This endpoint handles requests made for searching items in the current inventory. |
| [socialLogin](social-login.md) | `fun socialLogin(email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, provider: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, accessToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`SocialAuthResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-social-auth-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun socialLogin(email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, provider: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, accessToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`SocialAuthResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-social-auth-response/index.md)`>`<br>Login using social auth providers (eg. google, facebook) |
| [submitFeedback](submit-feedback.md) | `fun submitFeedback(feedback: `[`UserFeedback`](../../com.urbanpiper.upsdk.model.networkresponse/-user-feedback/index.md)`, callback: `[`Callback`](../-callback/index.md)`<`[`SimpleResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-simple-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun submitFeedback(feedback: `[`UserFeedback`](../../com.urbanpiper.upsdk.model.networkresponse/-user-feedback/index.md)`): Observable<`[`SimpleResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-simple-response/index.md)`>`<br>Submit feedback for the order |
| [unLikeItem](un-like-item.md) | `fun unLikeItem(itemId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`Like`](../../com.urbanpiper.upsdk.model.networkresponse/-like/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun unLikeItem(itemId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`Like`](../../com.urbanpiper.upsdk.model.networkresponse/-like/index.md)`>`<br>This method un likes an item based on the item id |
| [updateAddress](update-address.md) | `fun updateAddress(userAddress: `[`UserAddress`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address/index.md)`, callback: `[`Callback`](../-callback/index.md)`<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun updateAddress(userAddress: `[`UserAddress`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address/index.md)`): Observable<`[`UserAddressSaveResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-user-address-save-response/index.md)`>`<br>This method adds a updates an existing address for the user |
| [updateUserInfo](update-user-info.md) | `fun updateUserInfo(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, body: `[`UpdateUserInfoBody`](../../com.urbanpiper.upsdk.model/-update-user-info-body/index.md)`, callback: `[`Callback`](../-callback/index.md)`<`[`UpdateUserInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-update-user-info-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun updateUserInfo(phone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, body: `[`UpdateUserInfoBody`](../../com.urbanpiper.upsdk.model/-update-user-info-body/index.md)`): Observable<`[`UpdateUserInfoResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-update-user-info-response/index.md)`>`<br>Updates the profile data associated with a particular user identified by the phone number. |
| [verifyWalletPayment](verify-wallet-payment.md) | `fun verifyWalletPayment(transactionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, gwTxnId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, transactionStatus: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, callback: `[`Callback`](../-callback/index.md)`<`[`PaymentCallbackResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-payment-callback-response/index.md)`>): `[`CancellableTask`](../-cancellable-task/index.md)<br>`fun verifyWalletPayment(transactionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, gwTxnId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, transactionStatus: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`PaymentCallbackResponse`](../../com.urbanpiper.upsdk.model.networkresponse/-payment-callback-response/index.md)`>`<br>This step is only required if the payment did not happen through a redirection flow (i.e - through a webview with a redirection url from the payment init response) This Marks the completion of a transaction. |