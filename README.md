# To build redis image

docker build -t redis:3.2.7 -f .docker/redis.dockerfile .

# To run redis container in background

docker run -p 6379:6379 -d -t redis:3.2.7
