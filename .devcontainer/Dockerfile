FROM ruby:3.2

# Install dependencies
RUN apt-get update -qq && apt-get install -y nodejs postgresql-client

# Set working directory
WORKDIR /workspace

# Install Rails
RUN gem install rails

# Expose port 3000
EXPOSE 3000
