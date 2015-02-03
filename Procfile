nginx: nginx
dockergen: docker-gen -watch -only-exposed -notify "sed -i '/^\s*$/d' /etc/nginx/conf.d/default.conf | nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
