# WCodingTest HackerNews Api
This is an API to get best 20 posts with details from Hacker News API.
First, the API makes one call to get Top 20 Posts IDs from Hacker News.
Then, for each Id returned, the API makes one call to get post details.
There is a cache with determinated time set in 30 minutes to store the results. 
This way, the Hacker News API only will be called each 30 minutes.

# Prerequisites
.Net Core 2.2 framework
Visual Studio or VS Code

# Built With
Visual Studio 2017 - IDE
.Net Core 2.2 - Language 
XUnit - Tests
Swashbuckle - Swagger documentation
Caching Memory - Cache

# Getting Started
First of all, you need to unzip file on the computer's hard disk.
Second, open solution file "WCodingTest.HackerNews.Api.sln".
Third, build solution and run with F5 key.
You can test the application using Postman or Swagger.

# Backlog
Implement log to store call's information, like number of calls, number of errors, response time, etc.

# Authors
Ricardo Corrêa Gonçalves
