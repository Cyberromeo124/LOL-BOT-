FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Cyberromeo124/LOL-BOT- /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
