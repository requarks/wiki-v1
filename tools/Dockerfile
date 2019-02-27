FROM requarks/wiki:latest

# Replace with your email address:
ENV WIKI_ADMIN_EMAIL admin@example.com

# Replace with the path to your config file
ENV CONFIG_PATH /var/wiki

# Replace your-config.yml with the path to your config file:
ADD your-config.yml ${CONFIG_PATH}/config.yml

WORKDIR /var/wiki

EXPOSE 3000
ENTRYPOINT [ "node", "server" ]
