web: erb nginx/conf/nginx.conf.erb > nginx/conf/nginx.conf && touch nginx/logs/access.log nginx/logs/error.log && (tail -f -n 0 logs/*.log &) && nginx/objs/nginx -p .
