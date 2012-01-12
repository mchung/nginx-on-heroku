web: erb nginx/conf/nginx.conf.erb > nginx/conf/nginx.conf && touch logs/access.log logs/error.log && (tail -f -n 0 logs/*.log &) && nginx/objs/nginx -p ./nginx
