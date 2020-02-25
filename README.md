<p class="changelog-title"><span><strong>PageSize limitation to 5000</strong></span><span class="pull-right">25 February 2020</span></p>

To improve the speed and efficiency of our APIs, the maximum value of pageSize has been limited to 4800. 
* [More details here.](https://apiv2.arcadier.com/?version=latest#pagination)
* It is advised to use extra filters when doing searches.
* If the intention is to get 100% of Records, where the number of Records exceed 4800, combine `pageSize` with `pageNumber` and do a couple of API calls.

---

<p class="changelog-title"><span><strong>Item Creation API</strong></span><span class="pull-right">25 February 2020</span></p>

Both Admin and Merchant can use this API:
* [Item Create](https://apiv2.arcadier.com/?version=latest#03d18078-0f46-4c84-b9ff-c464c7853580)
* The Admin can create items on behalf of other merchants.

---

<p class="changelog-title"><span><strong>Transaction History APIs</strong></span><span class="pull-right">7 February 2020</span></p>

Added time filtering query parameters to:
* [Get Transactions History of the marketplace](https://apiv2.arcadier.com/?version=latest#fd876791-d71f-43bd-be02-bfe6bf17747a)

---

<p class="changelog-title"><span><strong>Item Search APIs</strong></span><span class="pull-right">6 February 2020</span></p>

Added sorting query parameters to:
* [Get All Items](https://apiv2.arcadier.com/?version=latest#c06e85df-93f9-446c-a9b2-426296185d0d)
* [Search for items - Params in URL](https://apiv2.arcadier.com/?version=latest#c6d3c581-2556-4cb0-a7f1-daed8733f9fd)
* [Search for items - Params in JSON body](https://apiv2.arcadier.com/?version=latest#61b718db-2d07-4af1-992d-520c0fe259c0)

---
