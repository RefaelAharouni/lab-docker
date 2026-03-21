FROM nginx:alpine
RUN apk add --no-cache bash
WORKDIR /usr/share/nginx/html
COPY . .
RUN chmod +x entrypoint.sh
ENTRYPOINT [ "./entrypoint" ]
EXPOSE 80