FROM fusuf/whatsasena:latest

RUN git clone https://Lilyflower2004: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@github.com/Lilyflower2004/WhatsAsenaDuplicated /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
