# Changelog
- Dernière version stable : 1.1.036 (57)
- Use it : https://play.google.com/store/apps/details?id=net.opalesurfcasting.lamaille
- Dernière version beta : none released for the moment
- Try in dev new features : https://play.google.com/apps/testing/net.opalesurfcasting.lamaille 

##LaMaille-Free [v1.1.036] 06.02.2017 - stable
- Modified : apply new legal statement in seabass *Dicentrarchus labrax* french leasure sea fishing.
- Improved : display for species with bag limit (PMA).
- Improved : display for species with limited fishing dates.
- Added : Private metrics on picture display, ie time to display in ms
- Added : Private metrics : privacy management and bandwith used/management - User may join to volonteers and send anonymous data for added metrics
  - Data are collected through PIWIK.
  - LRU logic : Data timestamp must be less than 24h00 and/or be less than 4 Mo - about 2 Mo JSON compressed POST - Bulktracking.
- Added : Private metrics : setting interface : Optout (default). Optin, join volonteers to help to improve picture display features + send data when WIFI. Optin + always send data. Choice is made in one list and in one click.
- Modified : handle devices from API 10 to API 25
- Modified : switch from Fresco 1.0.0 to 1.0.1
- Modified : switch from OkHttp 3.0.1 to 3.6.0 https://github.com/facebook/fresco/issues/1648
- Modified : switch pictures download to HTTP2 when device API handle it

##LaMaille-Free [v1.1.03n] not released yet - in progress - beta
 - Planned : use of piwik-android-sdk 2.0 https://github.com/piwik/piwik-sdk-android/pull/148
 - Planned : improved UI to download/cache pictures
 - Planned : improved general UI to display legal datas
 
#On the road - prospection - sandbox
- Identification keys for species
- Apply legislation to territory - local laws - geographical data - point in polygon - with respect on privacy - in use web implementation : http://www.opalesurfcasting.net/tableaux_de_bord/rubrique190.html
