From editor:basev1

COPY . /app
WORKDIR /app
EXPOSE 4500
RUN yarn build:browser
RUN ["chmod", "+x", "command.sh"]
 
RUN yarn -v

ENTRYPOINT ["/app/command.sh"]
