
# iOS version 13.3.1 artifact and forensic image file directory

| File | Path |
|------|------|
| Discord | `/iOS_13.3.1_Extraction/Extraction/Volumes/JOSH/NoTar-13-3-1/private/var/mobile/Containers/Data/Application/237E0C71-5961-459B-B8AC-831364AB4679/Library/Caches/com.hammerandchisel.discord/fsCachedData/` |
| Instagram | `/iOS_13.3.1_Extraction/Extraction/Volumes/JOSH/NoTar-13-3-1/private/var/mobile/Containers/Data/Application/71B2EBD8-B6DF-4118-908C-7B2976A3019E/Library/Application\ Support/DirectSQLiteDatabase/9368974384.db` |
| Forensic Image | `/iOS_13.3.1_Extraction/` |


## iOS version 13.4.1 artifact and forensic image file directory

| File | Path |
|------|------|
| Discord | `/iOS_13.4.1_Extraction/Extraction/Volumes/JOSH/NoTar-13-4-1/private/var/mobile/Containers/Data/Application/237E0C71-5961-459B-B8AC-831364AB4679/Library/Caches/com.hammerandchisel.discord/fsCachedData/` |
| Instagram | `/iOS_13.4.1_Extraction/Extraction/Volumes/JOSH/NoTar-13-4-1/private/var/mobile/Containers/Data/Application/71B2EBD8-B6DF-4118-908C-7B2976A3019E/Library/Application\ Support/DirectSQLiteDatabase/9368974384.db` |
| Forensic Image | `/iOS_13.4.1_Extraction/` |


## Forensic timeline snapshot of iOS 13.3.1 forensic image

| Datetime | Source | Message | Parser |
|----------|--------|---------|--------|
| ... | ... | ... | ... |
| 2020-03-22T06:06:41.720000+00:00 | Discord iOS | User Id: 579257851646574644 Username: josh_hickman1 Message: Good morning! Channel Id: 622810296226152474 | discord_ios |
| 2020-03-22T06:06:46.000000+00:00 | LOG | MacKeeper Entry : [ URL: https://discordapp.com/api/v6/channels/622810296226152474/messages/691271635344293899/ack ] | sqlite/mackeeper_cache |
| 2020-03-22T06:07:53.780000+00:00 | Discord iOS | User Id: 672145484864815124 Username: ThisIsDFIR Message: Good morning. How are you? The pollen is in full force so my allergies are kicking! Channel Id: 622810296226152474 | discord_ios |
| 2020-03-22T06:07:56.000000+00:00 | LOG | MacKeeper Entry : [ URL: https://discordapp.com/api/v6/channels/622810296226152474/messages ] | sqlite/mackeeper_cache |
| 2020-03-22T06:09:18.000000+00:00 | LOG | Originating call: data_analytics_init_block_invoke Body: data analytics activity | text/ios_sysdiag_log |
| ... | ... | ... | ... |
| 2020-03-22T11:44:48.000000+00:00 | Instagram iOS | Sender ID: 9368974384 Username: ThisIsDFIR Message: Hey what's up. | sqlite/instagram_ios |
| 2020-03-22T11:45:39.000000+00:00 | Instagram iOS | Sender ID: 9368974384 Username: ThisIsDFIR Message: ? | sqlite/instagram_ios |
| 2020-03-22T11:46:08.000000+00:00 | Instagram iOS | Sender ID: 22824420 Username: josh_hickman Message: Not much. Creating data and watching Netflix. | sqlite/instagram_ios |
| 2020-03-22T11:46:09.827397+00:00 | LOG | Subsystem: com.apple.ManagedConfiguration Thread Identifier: 0x2cc0f Process Identifier: 118 Boot Identifier: 4787AD12-20DA-4037-A837-C83BB6EEC4A5 Time To Live: 21 Process image identifier: D94FDF08-B28C-3270-A582-3BEE002358D8 Process image path: /usr/libexec/symptomsd Sender image identifier: A59E2266-CA78-3660-85D9-7A2D12E88F89 Sender image path: /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration Activity identifier: 449609 Category: MC Event type: logEvent Event message: Got system group container path from MCM for systemgroup.com.apple.configurationprofiles: /private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles | unified_logging |
| 2020-03-22T11:46:10.000000+00:00 | HISTORY | Bundle Identifier: com.burbn.instagram Process Name: InstagramNotific/com.burbn.instagram Wifi In: 0 Wifi Out: 0 Wireless Wan In: 28270 Wireless Wan Out: 20203 | sqlite/ios_datausage |
| ... | ... | ... | ... |
