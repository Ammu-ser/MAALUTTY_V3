FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Ammu-ser/AMMUSER_V3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ammu-ser/media

CMD ["node", "bot.js"]
