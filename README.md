# Data-Dog-Test
Data-Dog-Test

Date


Service


Host


Nov 25 19:31:11.275
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexController:53 - searchingest - deltaRefresh - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - Request receive for deltaRequest with parameters env: staging, notifyType: automatic, sentToTopic: true, startTimeUTC: null

Nov 25 19:31:11.441
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:397 - searchingest - handleDeltaRefresh - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - litWidenDelta: 7cd63dc5-f3da-440c-a4ba-71ea7f1324e8 | request: | WidenDeltaIndexRequest(env=staging, notifyType=automatic, requestId=7cd63dc5-f3da-440c-a4ba-71ea7f1324e8, startTime=null, sentToTopic=true) |  litWidenDelta request receive at: 2026-11-25T14:01:11.151001027

Nov 25 19:31:11.623
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:402 - searchingest - handleDeltaRefresh - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - litWidenDelta: 7cd63dc5-f3da-440c-a4ba-71ea7f1324e8 | request: | 2026-11-25T13:45:00Z |  last Delta Success Time : 2026-11-25T14:01:11.283530402

Nov 25 19:31:11.777
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:580 - searchingest - fetchAndProcess - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - fetchAndProcess:WidenDeltaIndexRequest(env=staging, notifyType=automatic, requestId=7cd63dc5-f3da-440c-a4ba-71ea7f1324e8, startTime=2026-11-25T13:45:00Z, sentToTopic=true) | request: | start

Nov 25 19:31:11.777
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:601 - searchingest - fetchAndProcess - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - getWidenDeltaData: GsuhXrAk | request: | param: targetURL http://api.widencollective.com/v2/, query TargetAppID:-(IsEmpty) CountryCode:-(IsEmpty) Language:-(IsEmpty) contentID:-(IsEmpty) lhd:[2026-11-25T13:45:00Z to 2026-11-25T14:01:11Z], expand metadata,file_properties,thumbnails,embeds,security,asset_properties calling widen service

Nov 25 19:31:12.888
searchresponse
2026-11-25 14:01:12 INFO  ConfigHelper:156 - searchingest - siteConfigFromFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - siteConfigFromFile:| request: | Success | File found

Nov 25 19:31:13.025
searchresponse
2026-11-25 14:01:12 INFO  NotifyParser:439 - searchingest - parseWidenResItem2Data - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - parseWidenResItem2Data: null | request | suppressedforitems & audiences is zero, so not adding Suppressedfor

Nov 25 19:31:13.177
searchresponse
2026-11-25 14:01:12 INFO  ConfigHelper:156 - searchingest - siteConfigFromFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - siteConfigFromFile:| request: | Success | File found

Nov 25 19:31:13.340
searchresponse
2026-11-25 14:01:13 INFO  NotifyParser:420 - searchingest - parseWidenResItem2Data - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - createDataListWiden: null | request | Indexing skip as onetis number 'COIPFUSEIBDP' is not part of allowed fund for WidenId: fe06911b-7a43-4c4c-bea0-165343df2176

Nov 25 19:31:13.501
searchresponse
2026-11-25 14:01:13 INFO  ConfigHelper:156 - searchingest - siteConfigFromFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - siteConfigFromFile:| request: | Success | File found

Nov 25 19:31:13.671
searchresponse
2026-11-25 14:01:13 INFO  NotifyParser:439 - searchingest - parseWidenResItem2Data - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - parseWidenResItem2Data: null | request | suppressedforitems & audiences is zero, so not adding Suppressedfor

Nov 25 19:31:14.011
searchresponse
2026-11-25 14:01:13 INFO  FileUtil:66 - searchingest - saveJsonDataToFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - saveJsonDataToFile: | param: filename index_delta_lit_en-usa_GsuhXrAk__e8ce1efd-a70d-4772-9f81-ee5e6f904adc.json, directory /home/indexQueue saving file

Nov 25 19:31:14.367
searchresponse
2026-11-25 14:01:13 INFO  FileUtil:66 - searchingest - saveJsonDataToFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - saveJsonDataToFile: | param: filename index_delta_lit_en-in_GsuhXrAk__fb3418e3-c565-4379-9311-123642b6ffb4.json, directory /home/indexQueue saving file

Nov 25 19:31:14.367
searchresponse
2026-11-25 14:01:14 INFO  LiteratureIndexServiceImpl:640 - searchingest - fetchAndProcess - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - fetchAndProcess: null| request: | type: GsuhXrAk | start

Nov 25 19:31:14.574
searchresponse
2026-11-25 14:01:14 INFO  LiteratureIndexServiceImpl:576 - searchingest - indexWidenDelta - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - indexWidenDelta: WidenDeltaIndexRequest(env=staging, notifyType=automatic, requestId=7cd63dc5-f3da-440c-a4ba-71ea7f1324e8, startTime=2026-11-25T13:45:00Z, sentToTopic=true) | request | complete




Date


Service


Host


Nov 25 19:31:14.574
searchresponse
2026-11-25 14:01:14 INFO  LiteratureIndexServiceImpl:576 - searchingest - indexWidenDelta - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - indexWidenDelta: WidenDeltaIndexRequest(env=staging, notifyType=automatic, requestId=7cd63dc5-f3da-440c-a4ba-71ea7f1324e8, startTime=2026-11-25T13:45:00Z, sentToTopic=true) | request | complete

Nov 25 19:31:14.367
searchresponse
2026-11-25 14:01:14 INFO  LiteratureIndexServiceImpl:640 - searchingest - fetchAndProcess - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - fetchAndProcess: null| request: | type: GsuhXrAk | start

Nov 25 19:31:14.367
searchresponse
2026-11-25 14:01:13 INFO  FileUtil:66 - searchingest - saveJsonDataToFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - saveJsonDataToFile: | param: filename index_delta_lit_en-in_GsuhXrAk__fb3418e3-c565-4379-9311-123642b6ffb4.json, directory /home/indexQueue saving file

Nov 25 19:31:14.011
searchresponse
2026-11-25 14:01:13 INFO  FileUtil:66 - searchingest - saveJsonDataToFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - saveJsonDataToFile: | param: filename index_delta_lit_en-usa_GsuhXrAk__e8ce1efd-a70d-4772-9f81-ee5e6f904adc.json, directory /home/indexQueue saving file

Nov 25 19:31:13.671
searchresponse
2026-11-25 14:01:13 INFO  NotifyParser:439 - searchingest - parseWidenResItem2Data - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - parseWidenResItem2Data: null | request | suppressedforitems & audiences is zero, so not adding Suppressedfor

Nov 25 19:31:13.501
searchresponse
2026-11-25 14:01:13 INFO  ConfigHelper:156 - searchingest - siteConfigFromFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - siteConfigFromFile:| request: | Success | File found

Nov 25 19:31:13.340
searchresponse
2026-11-25 14:01:13 INFO  NotifyParser:420 - searchingest - parseWidenResItem2Data - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - createDataListWiden: null | request | Indexing skip as onetis number 'COIPFUSEIBDP' is not part of allowed fund for WidenId: fe06911b-7a43-4c4c-bea0-165343df2176

Nov 25 19:31:13.177
searchresponse
2026-11-25 14:01:12 INFO  ConfigHelper:156 - searchingest - siteConfigFromFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - siteConfigFromFile:| request: | Success | File found

Nov 25 19:31:13.025
searchresponse
2026-11-25 14:01:12 INFO  NotifyParser:439 - searchingest - parseWidenResItem2Data - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - parseWidenResItem2Data: null | request | suppressedforitems & audiences is zero, so not adding Suppressedfor

Nov 25 19:31:12.888
searchresponse
2026-11-25 14:01:12 INFO  ConfigHelper:156 - searchingest - siteConfigFromFile - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - siteConfigFromFile:| request: | Success | File found

Nov 25 19:31:11.777
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:601 - searchingest - fetchAndProcess - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - getWidenDeltaData: GsuhXrAk | request: | param: targetURL http://api.widencollective.com/v2/, query TargetAppID:-(IsEmpty) CountryCode:-(IsEmpty) Language:-(IsEmpty) contentID:-(IsEmpty) lhd:[2026-11-25T13:45:00Z to 2026-11-25T14:01:11Z], expand metadata,file_properties,thumbnails,embeds,security,asset_properties calling widen service

Nov 25 19:31:11.777
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:580 - searchingest - fetchAndProcess - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - fetchAndProcess:WidenDeltaIndexRequest(env=staging, notifyType=automatic, requestId=7cd63dc5-f3da-440c-a4ba-71ea7f1324e8, startTime=2026-11-25T13:45:00Z, sentToTopic=true) | request: | start

Nov 25 19:31:11.623
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:402 - searchingest - handleDeltaRefresh - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - litWidenDelta: 7cd63dc5-f3da-440c-a4ba-71ea7f1324e8 | request: | 2026-11-25T13:45:00Z |  last Delta Success Time : 2026-11-25T14:01:11.283530402

Nov 25 19:31:11.441
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexServiceImpl:397 - searchingest - handleDeltaRefresh - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - litWidenDelta: 7cd63dc5-f3da-440c-a4ba-71ea7f1324e8 | request: | WidenDeltaIndexRequest(env=staging, notifyType=automatic, requestId=7cd63dc5-f3da-440c-a4ba-71ea7f1324e8, startTime=null, sentToTopic=true) |  litWidenDelta request receive at: 2026-11-25T14:01:11.151001027

Nov 25 19:31:11.275
searchresponse
2026-11-25 14:01:11 INFO  LiteratureIndexController:53 - searchingest - deltaRefresh - b820f4b15dda7e0450029b4a6ca0ae43 4958406710547078759 - Request receive for deltaRequest with parameters env: staging, notifyType: automatic, sentToTopic: true, startTimeUTC: null

