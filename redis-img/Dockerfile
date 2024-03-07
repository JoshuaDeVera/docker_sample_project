# Use an existing docker image as base
FROM alpine

# Install dependency
RUN apk add --update redis

# What image does when it starts as a container
CMD ["redis-server"]
