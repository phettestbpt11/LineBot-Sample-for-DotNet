## Deploy LineSearchDotNetCoreFxRepoBot to Azure WebJobs

Publish this project as WebJob to your WebApps

Edit your WebApp App settings like a following

![App settings](https://raw.githubusercontent.com/kiyoaki/LineBotNet/master/Images/LineSearchDotNetCoreFxRepoBot.PNG "App settings")

[How to generate GitHub API access token](https://github.com/blog/1509-personal-api-tokens "How to generate GitHub API access token")

Add your WebJob global IP address to yout LINE Channels Server IP Whitelist

If LINE Channels Server IP Whitelist has setting error, LINE Sending messages API response status code is 403 and content is like a following.

```javascript
{"statusCode":"427","statusMessage":"Your ip address [XXX.XXX.XXX.XXX] is not allowed to access this API."}