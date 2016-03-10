### Angular Js runtime based alpine

####The Document Root:
> /home


#### We set the rewrite in nginx, and you should do:
>1. Add  $locationProvider.html5Mode(true);  to your app config
2. Add <base href="/"> to your index.html (<head></head>)

####Then the # is hidden ~ enjoy it;