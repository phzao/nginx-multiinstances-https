FROM nginx:alpine
RUN apk add python3 python3-dev py3-pip build-base libressl-dev musl-dev libffi-dev rust cargo
RUN pip3 install pip --upgrade
RUN pip3 install certbot-nginx

#enter on container and run
#certbot --nginx -d yourdomain.com -d www.yourdomain.com
#
