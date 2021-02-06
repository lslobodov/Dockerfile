FROM node:lts
# Update
# Install Apps
RUN npm install -g @angular/cli
# Erstellen des Benutzers
RUN useradd -ms /bin/bash entwickler
# Arbeiitsverzeichnis
USER entwickler
WORKDIR /home/entwickler
CMD [ "/bin/bash" ]
 
