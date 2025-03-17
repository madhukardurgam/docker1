FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/madhukardurgam/shell-script/refs/heads/main/00-shebang.sh /usr/share/nginx/html/index.html
RUN chmod +R /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]