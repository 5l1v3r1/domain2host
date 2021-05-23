# domain2host
Behind every domain, there is an hosting. To find vuln in hosting, we do check hosting history and get information about provider.
So today we will check hosting by its domain.
Example domains: `google.com`,`discord.com`,`microsoft.com`...

## Practical
### Example#1:
- Visit `http://ip-api.com/line/google.com` (Replace `google.com` with domain you wanna get hosting provider)
```
success
South Korea
KR
11
Seoul
Seoul
03153
37.5665
126.978
Asia/Seoul
Google LLC
Google LLC
AS15169 Google LLC
74.125.24.106
```
- If you notice, it clearly include some words like `Google LLC` etc. So they are their hosting provider. 
- If didn't understood, please view more examples.
### Example#2:
- Visit `http://ip-api.com/line/slimbrowser.net` (Replace `slimbrowser.net` with domain you wanna get hosting provider)
```
success
United States
US
IL
Illinois
Chicago
60666
41.8781
-87.6298
America/Chicago
Cloudflare, Inc.
Cloudflare, Inc.
AS13335 Cloudflare, Inc.
172.67.151.231
```
- If you notice, it clearly include some words like `Cloudflare ,Inc.` etc. So they are their hosting provider.
### Example#3:
- Visit `http://ip-api.com/line/discord.com` (Replace `discord.com` with domain you wanna get hosting provider)
```
success
United States
US
VA
Virginia
Ashburn
20149
39.0438
-77.4874
America/New_York
Cloudflare, Inc.
Cloudflare, Inc.
AS13335 Cloudflare, Inc.
162.159.135.232
```
- If you notice, it clearly include some words like `Cloudflare ,Inc.` etc. So they are their hosting provider.  

### Example#4:
- Visit `http://ip-api.com/line/libretranslate.com` (Replace `libretranslate.com` with domain you wanna get hosting provider)
```
success
United States
US
IL
Illinois
Chicago
60666
41.8781
-87.6298
America/Chicago
Cloudflare, Inc.
Cloudflare, Inc.
AS13335 Cloudflare, Inc.
172.67.213.179
```
- If you notice, it clearly include some words like `Cloudflare ,Inc.` etc. So they are their hosting provider.  

### Example#5:
- Visit `http://ip-api.com/line/visualstudio.com` (Replace `visualstudio.com` with domain you wanna get hosting provider)
```
success
United States
US
NY
New York
New York
10123
40.7128
-74.006
America/New_York
Microsoft Corporation
Microsoft Corporation
AS8068 Microsoft Corporation
13.107.42.18
```
- If you notice, it clearly include some words like `Microsoft Corporation`, obviously visual studio is part of microsoft.  
