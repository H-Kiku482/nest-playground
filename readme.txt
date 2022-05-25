# first step
docker-compose run --rm backend bash -c 'npm i -g @nestjs/cli && nest new .'
docker-compose run --rm frontend bash -c 'yarn create next-app . --typescript'
docker-compose up