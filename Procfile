nginx: nginx
confgen: docker-gen -watch -only-exposed -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
sslgen: docker-gen -watch -only-exposed -notify "/createSSL.sh" /app/ssl.tmpl /createSSL.sh