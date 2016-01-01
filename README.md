# _Murder She Generated_ Frontend

A hastly hacked together frontend to Sam Corcoran's [MurderSheGenerated Python scripts](https://github.com/samcorcoran/MurderSheGenerated), produced as part of a Secret Santa present in 2015. Happy Christmas, Sam!

To deploy this project:

1. Edit `js/app.js`:

    1. Change the value of baseServerURL to wherever is serving your Murder
      She Generated JSON. e.g. if you could get game JSON from ```http://murdershegenerated.com/players/8``` you should set the value to
      ```http://murdershegenerated.com/```
      (including trailing slash).
      
    2. If you are hosting the frontend on a different domain to the backend,
      uncomment the statement
      ```// $httpProvider.defaults.useXDomain = true;```
      to enable CORS.
      
2. Host the files somewhere

