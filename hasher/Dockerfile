FROM ruby:3-alpine
RUN apk add --update build-base curl
RUN gem install sinatra
RUN gem install thin
COPY hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 8080
