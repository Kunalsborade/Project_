FROM node:14
# USER node

# RUN mkdir /home/node/.npm-global
# ENV PATH=/home/node/.npm-global/bin:$PATH
# ENV NPM_CONFIG_PREFIX=/home/node/.npm-global
# Install Truffle
RUN npm install -g ganache@7.0.0 --unsafe
EXPOSE 8545
# CMD [ "" ]