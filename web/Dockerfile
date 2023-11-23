FROM nginx:latest
RUN rm -rf /usr/share/nginx/html/
COPY webfiles/ /usr/share/nginx/html/
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
#COPY roboshop.conf /etc/nginx/nginx.conf  this step is moved to the manifest files , to get the benifit of not building the image if config file is changed as building the image is a costly operation.
