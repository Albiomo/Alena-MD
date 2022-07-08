FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Afx-Abu/Alena-MD /jsl/Alena
WORKDIR /jsl/Alena
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]