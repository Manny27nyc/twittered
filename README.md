This project is a JAVA library which allows you to consume the Twitter API.

## /!\ Development in progress... /!\ 

### Configuration
The file `src/main/resources/twitter-credentials.json` should contain your twitter credentials like this :
```
{
  "consumerKey": "xxx",
  "consumerSecret": "xxx",
  "accessToken": "xxx",
  "secretToken": "xxx"
}
```
It can be found in [your app page](https://developer.twitter.com/en/apps) in the _Key and tokens_
tab.

### How to use it
1) Clone this repository
2) Run `mvn clean install`
3) Add a dependency on your project with the generated `.jar` file from `target` folder
4) Start using `TwitterClient` class

### Available methods
See : [ITwitterClient.java](https://github.com/redouane59/twitter-client/blob/master/src/main/java/com/socialmediaraiser/twitter/ITwitterClient.java)
### External Resources
[Twitter Developers docs](https://developer.twitter.com/en/docs)

### Special thanks
[@hypr2771](https://github.com/hypr2771)
[@andypiper](https://github.com/andypiper)
[@igorbrigadir](https://github.com/igorbrigadir)

