# POST CoreGame_DisassociatePlayer

Leave an in-progress game  


Method: `POST`  
URL: `https://glz-{region}-1.{region}.a.pvp.net/core-game/v1/players/{puuid}/disassociate/{in-progress match id}`  
Headers:
 - `X-Riot-Entitlements-JWT`: `{Riot entitlement}`
 - `Authorization`: `Bearer {base64 encoded Riot token}`

Variables:
 - `{Riot entitlement}`: Read [Common Components - Riot Entitlement](../common-components.md#riot-entitlement)
 - `{base64 encoded Riot token}`: Read [Common Components - Riot Token](../common-components.md#riot-token)
 - `{region}`: Read [Common Components - Region](../common-components.md#region)
 - `{puuid}`: Read [Common Components - PUUID](../common-components.md#puuid)
 - `{in-progress match id}`: Read [Common Components - Coregame Match ID](../common-components.md#coregame-match-id)

