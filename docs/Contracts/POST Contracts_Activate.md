# POST Contracts_Activate

Activate a particular contract  


Method: `POST`  
URL: `https://pd.{region}.a.pvp.net/contracts/v1/contracts/{puuid}/special/{contract id}`  
Headers:
 - `X-Riot-Entitlements-JWT`: `{Riot entitlement}`
 - `Authorization`: `Bearer {base64 encoded Riot token}`
 - `X-Riot-ClientVersion`: `{client version}`

Variables:
 - `{Riot entitlement}`: Read [Common Components - Riot Entitlement](../common-components.md#riot-entitlement)
 - `{base64 encoded Riot token}`: Read [Common Components - Riot Token](../common-components.md#riot-token)
 - `{client version}`: Read [Common Components - Client Version](../common-components.md#client-version)
 - `{region}`: Read [Common Components - Region](../common-components.md#region)
 - `{puuid}`: Read [Common Components - PUUID](../common-components.md#puuid)
 - `{contract id}`: The ID of the contract to activate. Can be found from the [ContractDefinitions_Fetch](GET%20ContractDefinitions_Fetch.md) endpoint.

