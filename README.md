# nginx-for-kafka
Install Nginx using `sudo yum -y install nginx` and `sudo yum install nginx-mod-stream.x86_64`.
The `nginx.conf` is located under `/etc/nginx`. Use `sudo systemctl restart nginx` to start Nginx and `sudo systemctl status nginx.service` to check the status of the service. You can tail the Nginx service log via `sudo journalctl -f -u nginx.service`
