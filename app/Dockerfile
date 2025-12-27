FROM nginx:1.25-alpine

# Remove default config
RUN rm /etc/nginx/conf.d/default.conf

# Fix cache permissions (still needed)
RUN mkdir -p /var/cache/nginx \
    && chown -R nginx:nginx /var/cache/nginx

# Copy config and content
COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html/index.html

USER nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]