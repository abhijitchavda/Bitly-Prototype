# bitly-Prototype
### node.js|express|handlebars|redis|mongodb
1)UI accepts long url and provides a unique short link by requesting service from Control Panel Service </br>
2)Control Panel Service generates the unique link and send it as a response to the UI </br>
3)Redirecting server is used to redirect user to the original link by using cache from redis, when user pings using the short link </br>
4)Trending server is used to show the top three trending urls in the UI and also store the top three to redis cache </br>
