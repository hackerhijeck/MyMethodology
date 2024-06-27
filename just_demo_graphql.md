```
query{
  __schema{
    types{
      name,
      fields{
        name
}}}}
```

New
```
POST /graphql HTTP/2
Host: hackerone.com
Cookie: h1_device_id=98956a6b-b1b5-4adb-b570-c7da97bde4d9; AMP_b7cba2c14c=JTdCJTIyZGV2aWNlSWQlMjIlM0ElMjIzNTMzNWM1Zi0xN2UwLTRhMzAtYjIyYy0zYWE4ZGRlZjhhNmIlMjIlMkMlMjJzZXNzaW9uSWQlMjIlM0ExNzE5NTE0Njc5MTM4JTJDJTIyb3B0T3V0JTIyJTNBZmFsc2UlMkMlMjJsYXN0RXZlbnRUaW1lJTIyJTNBMTcxOTUxNDY4MTUxMCUyQyUyMmxhc3RFdmVudElkJTIyJTNBMzElN0Q=; AMP_MKTG_b7cba2c14c=JTdCJTIycmVmZXJyZXIlMjIlM0ElMjJodHRwcyUzQSUyRiUyRnd3dy5oYWNrZXJvbmUuY29tJTJGJTIyJTJDJTIycmVmZXJyaW5nX2RvbWFpbiUyMiUzQSUyMnd3dy5oYWNrZXJvbmUuY29tJTIyJTdE; optimizelyEndUserId=oeu1699179537884r0.04971664092517214; _ga_BM4MFJMH6W=GS1.1.1719514671.3.0.1719514677.54.0.0; _ga=GA1.2.1125500036.1699179540; _clck=hwcfrc%7C2%7Cfmz%7C0%7C1404; rm_sLqSAErKFkmmugkG9Fxg={%22$uid%22:%2218b9efe3213-8758ea92-3356-4897-b7df-b506f61420bc%22}; lo-uid=9145dfbd-1699179540759-d219af3f3b385d3e; lo-visits=1; notice_preferences=2:; notice_gdpr_prefs=0,1,2:; cmapi_gtm_bl=; cmapi_cookie_privacy=permit 1,2,3; _mkto_trk=id:168-NAU-732&token:_mch-hackerone.com-1705730857240-28473; _cfuvid=aU.4jgoo50awMO70PLJSQkA7r4gdZBti8eMfBalB7Gs-1719514671261-0.0.1.1-604800000; pjs_hackc55_6sense_audience=false; _gcl_au=1.1.1313301054.1719514671; TAsessionID=94dca8d6-4bac-4144-ba71-0558603d901e|EXISTING; _gid=GA1.2.116674858.1719514672; _uetsid=27ddc34034b711ef964fcfe7f49d2ad4; _uetvid=bcabc3507bc411eeb99729a2aa83ae49; _gat_UA-49905813-1=1; _gat_cro_metrics_tracker=1; _clsk=1qqozl8%7C1719514676458%7C1%7C1%7Cw.clarity.ms%2Fcollect; __Host-session=Zys0K00vVHArZTQrQ3p3YTJROEtiNEhYV0I3dzliQStCaXZINjFOSmxJa3V5NWRGQU9hbVlNUU9WcDd5RnZGejJGem9vdDdYbE1ZdXFIclplVTd2RVpEMTh3ZHFHS3JYTko3Y250Z21kTUt6RDZKRVhHQ2lWclRUSTNoUktweFAyRmEzcHREMDZZaVZUeEhoNXo4OVVIbk1xRjZINENtTG5vNnMxMy9oZVBYWDFZTGVCWk1GTWFYUlhrVkFUazhzRzlGZUxqOGd6ait3WExSWW1SYlFoNldkUGJBNjBHSTNtQVhvL2FTeFEzQ3hlNi9GQkxPcVJ5TGdHS0hZVEpZMVBVM1hQU3BvS09tNk1xOFdqdFhaRFVrWEJEZTBPZU9YQ0Z2TzNMSW9pbTlaTlpBQjB6UDRhei9TMzNPamswYW0yZSs3V29tUVEzYkhEaVk5SmJYV0lnPT0tLUlvS0dzREQ2Zlp4dUFrNXNyKytkVWc9PQ%3D%3D--5732c182c3ee0b9112f03f6be3fd7e0b3c2df4d6; _dd_s=rum=2&id=8cca4871-763e-4afa-9e5c-682da634b198&created=1719514681514&expire=1719515581514
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:127.0) Gecko/20100101 Firefox/127.0
Accept: */*
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Referer: https://hackerone.com/hacktivity/overview
Content-Type: application/json
X-Csrf-Token: WUIYggb8A9FJBba6ywuaht2+ya2WDokvOimikP5rJ5g0fWzLSQRm8az6pnhRpD0Znj7O74e3gqKeK5rAGb/zsQ==
X-Product-Area: hacktivity
X-Product-Feature: overview
X-Datadog-Origin: rum
X-Datadog-Parent-Id: 7294859249387883909
X-Datadog-Sampling-Priority: 1
X-Datadog-Trace-Id: 4639943795420597037
Content-Length: 160
Origin: https://hackerone.com
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin
Priority: u=4
Te: trailers

{"operationName":"FeatureToggles","variables":{"product_area":"hacktivity","product_feature":"overview"},"query":"{clientMutationId { description enumValues}}"}
```
New
```
POST /graphql HTTP/2
Host: hackerone.com
Cookie: h1_device_id=98956a6b-b1b5-4adb-b570-c7da97bde4d9; AMP_b7cba2c14c=JTdCJTIyZGV2aWNlSWQlMjIlM0ElMjIzNTMzNWM1Zi0xN2UwLTRhMzAtYjIyYy0zYWE4ZGRlZjhhNmIlMjIlMkMlMjJzZXNzaW9uSWQlMjIlM0ExNzE5NTE0Njc5MTM4JTJDJTIyb3B0T3V0JTIyJTNBZmFsc2UlMkMlMjJsYXN0RXZlbnRUaW1lJTIyJTNBMTcxOTUxNDY4MTUxMCUyQyUyMmxhc3RFdmVudElkJTIyJTNBMzElN0Q=; AMP_MKTG_b7cba2c14c=JTdCJTIycmVmZXJyZXIlMjIlM0ElMjJodHRwcyUzQSUyRiUyRnd3dy5oYWNrZXJvbmUuY29tJTJGJTIyJTJDJTIycmVmZXJyaW5nX2RvbWFpbiUyMiUzQSUyMnd3dy5oYWNrZXJvbmUuY29tJTIyJTdE; optimizelyEndUserId=oeu1699179537884r0.04971664092517214; _ga_BM4MFJMH6W=GS1.1.1719514671.3.0.1719514677.54.0.0; _ga=GA1.2.1125500036.1699179540; _clck=hwcfrc%7C2%7Cfmz%7C0%7C1404; rm_sLqSAErKFkmmugkG9Fxg={%22$uid%22:%2218b9efe3213-8758ea92-3356-4897-b7df-b506f61420bc%22}; lo-uid=9145dfbd-1699179540759-d219af3f3b385d3e; lo-visits=1; notice_preferences=2:; notice_gdpr_prefs=0,1,2:; cmapi_gtm_bl=; cmapi_cookie_privacy=permit 1,2,3; _mkto_trk=id:168-NAU-732&token:_mch-hackerone.com-1705730857240-28473; _cfuvid=aU.4jgoo50awMO70PLJSQkA7r4gdZBti8eMfBalB7Gs-1719514671261-0.0.1.1-604800000; pjs_hackc55_6sense_audience=false; _gcl_au=1.1.1313301054.1719514671; TAsessionID=94dca8d6-4bac-4144-ba71-0558603d901e|EXISTING; _gid=GA1.2.116674858.1719514672; _uetsid=27ddc34034b711ef964fcfe7f49d2ad4; _uetvid=bcabc3507bc411eeb99729a2aa83ae49; _gat_UA-49905813-1=1; _gat_cro_metrics_tracker=1; _clsk=1qqozl8%7C1719514676458%7C1%7C1%7Cw.clarity.ms%2Fcollect; __Host-session=Zys0K00vVHArZTQrQ3p3YTJROEtiNEhYV0I3dzliQStCaXZINjFOSmxJa3V5NWRGQU9hbVlNUU9WcDd5RnZGejJGem9vdDdYbE1ZdXFIclplVTd2RVpEMTh3ZHFHS3JYTko3Y250Z21kTUt6RDZKRVhHQ2lWclRUSTNoUktweFAyRmEzcHREMDZZaVZUeEhoNXo4OVVIbk1xRjZINENtTG5vNnMxMy9oZVBYWDFZTGVCWk1GTWFYUlhrVkFUazhzRzlGZUxqOGd6ait3WExSWW1SYlFoNldkUGJBNjBHSTNtQVhvL2FTeFEzQ3hlNi9GQkxPcVJ5TGdHS0hZVEpZMVBVM1hQU3BvS09tNk1xOFdqdFhaRFVrWEJEZTBPZU9YQ0Z2TzNMSW9pbTlaTlpBQjB6UDRhei9TMzNPamswYW0yZSs3V29tUVEzYkhEaVk5SmJYV0lnPT0tLUlvS0dzREQ2Zlp4dUFrNXNyKytkVWc9PQ%3D%3D--5732c182c3ee0b9112f03f6be3fd7e0b3c2df4d6; _dd_s=rum=2&id=8cca4871-763e-4afa-9e5c-682da634b198&created=1719514681514&expire=1719515581514
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:127.0) Gecko/20100101 Firefox/127.0
Accept: */*
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Referer: https://hackerone.com/hacktivity/overview
Content-Type: application/json
X-Csrf-Token: WUIYggb8A9FJBba6ywuaht2+ya2WDokvOimikP5rJ5g0fWzLSQRm8az6pnhRpD0Znj7O74e3gqKeK5rAGb/zsQ==
X-Product-Area: hacktivity
X-Product-Feature: overview
X-Datadog-Origin: rum
X-Datadog-Parent-Id: 7294859249387883909
X-Datadog-Sampling-Priority: 1
X-Datadog-Trace-Id: 4639943795420597037
Content-Length: 182
Origin: https://hackerone.com
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin
Priority: u=4
Te: trailers

{"operationName":"FeatureToggles","variables":{"product_area":"hacktivity","product_feature":"overview"},"query":"query{ AcceptInvitationPayload{  fields{  name, fields{  name }}}}"}
```
New
```
POST /graphql HTTP/2
Host: hackerone.com
Cookie: h1_device_id=98956a6b-b1b5-4adb-b570-c7da97bde4d9; AMP_b7cba2c14c=JTdCJTIyZGV2aWNlSWQlMjIlM0ElMjIzNTMzNWM1Zi0xN2UwLTRhMzAtYjIyYy0zYWE4ZGRlZjhhNmIlMjIlMkMlMjJzZXNzaW9uSWQlMjIlM0ExNzE5NTE0Njc5MTM4JTJDJTIyb3B0T3V0JTIyJTNBZmFsc2UlMkMlMjJsYXN0RXZlbnRUaW1lJTIyJTNBMTcxOTUxNDY4MTUxMCUyQyUyMmxhc3RFdmVudElkJTIyJTNBMzElN0Q=; AMP_MKTG_b7cba2c14c=JTdCJTIycmVmZXJyZXIlMjIlM0ElMjJodHRwcyUzQSUyRiUyRnd3dy5oYWNrZXJvbmUuY29tJTJGJTIyJTJDJTIycmVmZXJyaW5nX2RvbWFpbiUyMiUzQSUyMnd3dy5oYWNrZXJvbmUuY29tJTIyJTdE; optimizelyEndUserId=oeu1699179537884r0.04971664092517214; _ga_BM4MFJMH6W=GS1.1.1719514671.3.0.1719514677.54.0.0; _ga=GA1.2.1125500036.1699179540; _clck=hwcfrc%7C2%7Cfmz%7C0%7C1404; rm_sLqSAErKFkmmugkG9Fxg={%22$uid%22:%2218b9efe3213-8758ea92-3356-4897-b7df-b506f61420bc%22}; lo-uid=9145dfbd-1699179540759-d219af3f3b385d3e; lo-visits=1; notice_preferences=2:; notice_gdpr_prefs=0,1,2:; cmapi_gtm_bl=; cmapi_cookie_privacy=permit 1,2,3; _mkto_trk=id:168-NAU-732&token:_mch-hackerone.com-1705730857240-28473; _cfuvid=aU.4jgoo50awMO70PLJSQkA7r4gdZBti8eMfBalB7Gs-1719514671261-0.0.1.1-604800000; pjs_hackc55_6sense_audience=false; _gcl_au=1.1.1313301054.1719514671; TAsessionID=94dca8d6-4bac-4144-ba71-0558603d901e|EXISTING; _gid=GA1.2.116674858.1719514672; _uetsid=27ddc34034b711ef964fcfe7f49d2ad4; _uetvid=bcabc3507bc411eeb99729a2aa83ae49; _gat_UA-49905813-1=1; _gat_cro_metrics_tracker=1; _clsk=1qqozl8%7C1719514676458%7C1%7C1%7Cw.clarity.ms%2Fcollect; __Host-session=Zys0K00vVHArZTQrQ3p3YTJROEtiNEhYV0I3dzliQStCaXZINjFOSmxJa3V5NWRGQU9hbVlNUU9WcDd5RnZGejJGem9vdDdYbE1ZdXFIclplVTd2RVpEMTh3ZHFHS3JYTko3Y250Z21kTUt6RDZKRVhHQ2lWclRUSTNoUktweFAyRmEzcHREMDZZaVZUeEhoNXo4OVVIbk1xRjZINENtTG5vNnMxMy9oZVBYWDFZTGVCWk1GTWFYUlhrVkFUazhzRzlGZUxqOGd6ait3WExSWW1SYlFoNldkUGJBNjBHSTNtQVhvL2FTeFEzQ3hlNi9GQkxPcVJ5TGdHS0hZVEpZMVBVM1hQU3BvS09tNk1xOFdqdFhaRFVrWEJEZTBPZU9YQ0Z2TzNMSW9pbTlaTlpBQjB6UDRhei9TMzNPamswYW0yZSs3V29tUVEzYkhEaVk5SmJYV0lnPT0tLUlvS0dzREQ2Zlp4dUFrNXNyKytkVWc9PQ%3D%3D--5732c182c3ee0b9112f03f6be3fd7e0b3c2df4d6; _dd_s=rum=2&id=8cca4871-763e-4afa-9e5c-682da634b198&created=1719514681514&expire=1719515581514
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:127.0) Gecko/20100101 Firefox/127.0
Accept: */*
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Referer: https://hackerone.com/hacktivity/overview
Content-Type: application/json
X-Csrf-Token: WUIYggb8A9FJBba6ywuaht2+ya2WDokvOimikP5rJ5g0fWzLSQRm8az6pnhRpD0Znj7O74e3gqKeK5rAGb/zsQ==
X-Product-Area: hacktivity
X-Product-Feature: overview
X-Datadog-Origin: rum
X-Datadog-Parent-Id: 7294859249387883909
X-Datadog-Sampling-Priority: 1
X-Datadog-Trace-Id: 4639943795420597037
Content-Length: 62
Origin: https://hackerone.com
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin
Priority: u=4
Te: trailers

{"query":"query{ __schema{  types{  name, fields{  name }}}}"}
```
POST /api/v1/graphql HTTP/2
Host: core.hivelocity.net
Cookie: _ga_1EEEKLRQ8E=GS1.1.1719508962.2.1.1719509200.0.0.0; _ga=GA1.1.333667454.1718654371; _ga_E53KXNCNFS=GS1.1.1719508965.2.1.1719509200.0.0.0; _gac_UA-291922-18=1.1718654374.Cj0KCQjwvb-zBhCmARIsAAfUI2shORorgkhDdPuLB05a1Mo938hyWQVBo5xcLOQc96kBb2Lo298rpy8aAoCDEALw_wcB; __zlcmid=1MJmnmopltqre6J; _gid=GA1.2.1954447509.1719508966; OptanonConsent=isGpcEnabled=0&datestamp=Thu+Jun+27+2024+23%3A05%3A33+GMT%2B0530+(India+Standard+Time)&version=202403.1.0&browserGpcFlag=0&isIABGlobal=false&hosts=&consentId=1893ce6e-b8fe-416a-ae02-f02b9edfbb72&interactionCount=1&isAnonUser=1&landingPath=NotLandingPage&groups=C0001%3A1%2CC0002%3A1%2CC0003%3A1%2CC0004%3A1&geolocation=IN%3BKA&AwaitingReconsent=false; OptanonAlertBoxClosed=2024-06-27T17:23:12.553Z; _hp2_id.1980318981=%7B%22userId%22%3A%227676089069617646%22%2C%22pageviewId%22%3A%224210059383557039%22%2C%22sessionId%22%3A%227326731254978026%22%2C%22identity%22%3Anull%2C%22trackerVersion%22%3A%224.0%22%7D; _gcl_au=1.1.1351380567.1719508996; _ga_532E6HLHK4=GS1.1.1719508996.1.1.1719509732.59.0.0; _hjSessionUser_473797=eyJpZCI6IjZjODM2MDRkLWEwMDUtNTE4Zi1iNGM4LTQzODA0MmU1MWZmYyIsImNyZWF0ZWQiOjE3MTk1MDg5OTcxNDMsImV4aXN0aW5nIjp0cnVlfQ==; _ga_S1VJVJT12E=GS1.2.1719508999.1.1.1719509748.0.0.0; token_expires=Fri%20Jun%2028%202024%2003%3A55%3A52%20GMT%2B0530%20(India%20Standard%20Time)
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:127.0) Gecko/20100101 Firefox/127.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: none
Sec-Fetch-User: ?1
Priority: u=1
Te: trailers
Content-Type: application/x-www-form-urlencoded
Content-Length: 2434

query=query IntrospectionQuery {%0A%20%20%20 __schema {%0A%20%20%20%20%20%20%20 queryType {%0A%20%20%20%20%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 mutationType {%0A%20%20%20%20%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 subscriptionType {%0A%20%20%20%20%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 types {%0A%20%20%20%20%20%20%20%20 ...FullType%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 directives {%0A%20%20%20%20%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20%20%20%20%20 description%0A%20%20%20%20%20%20%20%20%20%20%20 args {%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20 ...InputValue%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 }%0A%20%20%20 }%0A}%0A%0Afragment FullType on __Type {%0A%20%20%20 kind%0A%20%20%20 name%0A%20%20%20 description%0A%20%20%20 fields(includeDeprecated%3A true) {%0A%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20 description%0A%20%20%20%20%20%20%20 args {%0A%20%20%20%20%20%20%20%20%20%20%20 ...InputValue%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 type {%0A%20%20%20%20%20%20%20%20%20%20%20 ...TypeRef%0A%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 isDeprecated%0A%20%20%20%20%20%20%20 deprecationReason%0A%20%20%20 }%0A%20%20%20 inputFields {%0A%20%20%20%20%20%20%20 ...InputValue%0A%20%20%20 }%0A%20%20%20 interfaces {%0A%20%20%20%20%20%20%20 ...TypeRef%0A%20%20%20 }%0A%20%20%20 enumValues(includeDeprecated%3A true) {%0A%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20 description%0A%20%20%20%20%20%20%20 isDeprecated%0A%20%20%20%20%20%20%20 deprecationReason%0A%20%20%20 }%0A%20%20%20 possibleTypes {%0A%20%20%20%20%20%20%20 ...TypeRef%0A%20%20%20 }%0A}%0A%0Afragment InputValue on __InputValue {%0A%20%20%20 name%0A%20%20%20 description%0A%20%20%20 type {%0A%20%20%20%20%20%20%20 ...TypeRef%0A%20%20%20 }%0A%20%20%20 defaultValue%0A}%0A%0Afragment TypeRef on __Type {%0A%20%20%20 kind%0A%20%20%20 name%0A%20%20%20 ofType {%0A%20%20%20%20%20%20%20 kind%0A%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20 ofType {%0A%20%20%20%20%20%20%20%20%20%20%20 kind%0A%20%20%20%20%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20%20%20%20%20 ofType {%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20 kind%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20 name%0A%20%20%20%20%20%20%20%20%20%20%20 }%0A%20%20%20%20%20%20%20 }%0A%20%20%20 }%0A}&operationName=IntrospectionQuery
```
