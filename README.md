# Fun-Game

1)Install nginx server

2)Set the index.html path on the nginx config at /usr/local/etc/nginx/nginx.config

example inside the nginx.config

 server {
        listen       8081;
        server_name  localhost;

        location / {
            root /Users/ugaddta/git/GameQuin;
            index  AllThree.html index.html index.htm;
        }

3)open browser for localhost:8081
4) Press start Game :)