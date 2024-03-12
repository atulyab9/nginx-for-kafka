# nginx-for-kafka

The `nginx.conf` is located under `/etc/nginx`. Use `sudo systemctl restart nginx` to start Nginx and `sudo systemctl status nginx.service` to check the status of the service. You can tail the Nginx service log via `sudo journalctl -f -u nginx.service`
