FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY expense.conf /etc/nginx/nginx.conf
COPY asset-manifest.json /usr/share/nginx/html/
COPY index.html /usr/share/nginx/html/
#CMD ["sleep","500"]