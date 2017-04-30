FROM nginx:latest

MAINTAINER Liam Hockley (contact@liamhockley.me)

RUN apt-get update && apt-get install -y curl gnupg

# NODE
RUN cd ~/
RUN curl -sL https://deb.nodesource.com/setup_7.x | bash -
RUN apt-get install -y nodejs

CMD ["nginx", "-g", "daemon off;"]