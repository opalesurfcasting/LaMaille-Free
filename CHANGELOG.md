# Changelog
- Dernière version stable : 1.1.033 (54)
- Use it : https://play.google.com/store/apps/details?id=net.opalesurfcasting.lamaille
- Dernière version beta : 1.1.034 (55)
- Try in dev new features : https://play.google.com/apps/testing/net.opalesurfcasting.lamaille 

##LaMaille-Free [v1.1.033] 29.12.2016 - stable
- Added : Private metrics on picture display, ie time to display in ms
- Added : Privacy management and bandwith used/management - User may join to volonteers and send anonymous data for added metrics - Data are collected through PIWIK - https://neptune.opalesurfcasting.net - Volonteers may check which datas are sent on previous URL frontpage. 
- Improved : Setting interface : Optin, join volonteers to help to improve picture display features.

##LaMaille-Free [v1.1.034] 05.01.2017 - beta
- Added : Private metrics : send data only when device is connected to WIFI - LRU logic : Data timestamp must be less than 24h00 and/or be less than 4 Mo - about 2 Mo JSON compressed POST - Bulktracking. Datas are sent to HTTP2 SSL ALPN server. 

##LaMaille-Free [v1.1.03n] not released yet - in progress - beta
- Improved : Private metrics : let user choose how to send datas : None (not optin), WIFI only or no matter (use available connection). https://github.com/piwik/piwik-sdk-android/pull/136

#On the road - prospection - sandbox
- Identification keys for species
- Apply legislation to territory - local laws - geographical data - point in polygon - with respect on privacy - in use web implementation : http://www.opalesurfcasting.net/tableaux_de_bord/rubrique190.html
