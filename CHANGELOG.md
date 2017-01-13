# Changelog
- Dernière version stable : 1.1.033 (54)
- Dernière version beta : 1.1.034 (55)

##LaMaille-Free [v1.1.033] 29.12.2016 - stable
- Added : Private metrics on picture display, ie time to display in ms
- Added : Privacy management and bandwith used/management - User may join to volontair and send anonymous data for added metrics - Data are collected through PIWIK - https://neptune.opalesurfcasting.net - Volontair user may check which datas are send on previous URL frontpage. 
- Improved : Setting interface : Optin, join volontair to help to improved picture display features.

##LaMaille-Free [v1.1.034] 05.01.2017 - beta
- Added : Private metrics : send data only when device is connected to WIFI - LRU logic : Data timestamp must be less than 24h00 and/or be less than 4 Mo - about 2 Mo JSON compressed POST - Bulktracking. Datas are send to HTTP2 SSL ALPN server. 

##LaMaille-Free [v1.1.03n] not released yet - in progress - beta
- Improved : Private metrics : let user choice on how to send data : None (not optin), WIFI only or no matter (use available connection). https://github.com/piwik/piwik-sdk-android/pull/136
