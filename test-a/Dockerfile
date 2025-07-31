FROM nginx:stable-alpine3.21

RUN echo "<p>Hello from test-a" > /usr/share/nginx/html/index.html

RUN echo '{"greeting":"Hello from Docker test-a"}' > /usr/share/nginx/html/greeting.json

COPY Dockerfile-nginx.config /etc/nginx/nginx.conf

EXPOSE 80