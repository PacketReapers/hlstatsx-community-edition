1. if we use in localhost (home computer) in main directory - cd hlstatsx-community-edition,
we need to run this after git clone:
find . -type f -exec sed -i 's/localhost/192.168.1.19/g' {} +

2. after that we can build completely the whole project with:
docker-compose -f docker-compose.yml up -d