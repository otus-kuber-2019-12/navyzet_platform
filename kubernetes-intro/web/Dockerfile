FROM nginx:latest

RUN useradd -u 1001 user

WORKDIR /app

RUN chown -R user:user /app/

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 8000
