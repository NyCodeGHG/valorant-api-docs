# GET RSO_RNet_FetchClientAuthorizations

Gets tokens in use by the client  


Method: `GET`  
URL: `https://127.0.0.1:{lockfile port}/rso-auth/v2/authorizations/valorant-client`  
Headers:
 - `Authorization`: `Basic {base64 encoded "riot:{lockfile password}"}`

Variables:
 - `{lockfile password}` and `{lockfile port}`: Read [Common Components - Lockfile Data](../common-components.md#lockfile-data)

