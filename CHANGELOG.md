# Changelog
- Dernière version stable : 1.1.038 (59)
- Use it : https://play.google.com/store/apps/details?id=net.opalesurfcasting.lamaille
- Dernière version beta : 1.1.041 (62)
- Try in dev new features : https://play.google.com/apps/testing/net.opalesurfcasting.lamaille 

## LaMaille-Free [v1.1.038] 17.02.2017 - stable
- Modified : apply new legal statement in seabass *Dicentrarchus labrax* french leasure sea fishing.
- Improved : display for species with bag limit (PMA).
- Improved : display for species with limited fishing dates.
- Added : Private metrics on picture display, ie time to display in ms
- Added : Private metrics : privacy management and bandwith used/management - User may join to volonteers and send anonymous data for added metrics
  - Data are collected through PIWIK.
  - LRU logic : Data timestamp must be less than 24h00 and/or be less than 4 Mo - about 2 Mo JSON compressed POST - Bulktracking.
- Added : Private metrics : setting interface : Optout (default). Optin, join volonteers to help to improve picture display features + send data when WIFI. Optin + always send data. Choice is made in one list and in one click.
- Modified : handle devices from API 10 to API 25
- Modified : switch from Fresco 1.0.1 to 1.1.0
- Modified : switch from OkHttp 3.0.1 to 3.6.0 https://github.com/facebook/fresco/issues/1648
- Modified : switch pictures download to HTTP2 when device API handle it
- Modified : removed Google Play Services depencies to keep API 10 devices not deprecated with next releases. In app textual suggestions when search with Google on device will not work anymore.
- Removed : setting interface : checkbox to enable Google textual suggestions on in app searches. Not in use anymore.

## LaMaille-Free [v1.1.041] 26.08.2017 - beta
- improved : app package size
- Modified : switch from Fresco 1.1.0 to 1.5.0
- Modified : switch from OkHttp 3.6.0 to 3.8.0 https://github.com/facebook/fresco/pull/1874
- Modified : use HSTS (https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security ) for picture download and stats : https://neptune.opalesurfcasting.net
- Add one species and picture : Callianasse - *Pestarella tyrrhena*
- Begin Android O - Api 26 - support

## LaMaille-Free [v1.1.04n] not released yet - in progress - beta
 - Planned : use of piwik-android-sdk 2.0 https://github.com/piwik/piwik-sdk-android/pull/148
 - In progress : improved UI to download/cache pictures
 - In tests : improved general UI to display legal datas https://github.com/facebook/litho https://code.facebook.com/posts/531104390396423/components-for-android-a-declarative-framework-for-efficient-uis/ https://code.facebook.com/posts/1187475984695956/open-sourcing-litho-a-declarative-ui-framework-for-android/
 - In tests : apply local legislation : add open source and private geolocation - don't use Google Play Services - https://mapzen.com/blog/lets-get-lost/
 - In tests : apply local legislation : add Geoserver layers - https://github.com/eldk/osmdroid/commit/db57d6b641daf22caf7c8180d79b6cb84e866b43
 
## On the road - prospection - sandbox
- Identification keys for species
- Apply legislation to territory - local laws - geographical data - point in polygon - with respect on privacy - in use web implementation : http://www.opalesurfcasting.net/tableaux_de_bord/rubrique190.html
