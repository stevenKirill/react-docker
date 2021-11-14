practising docker (run react app in docker)

docker run -e CHOKIDAR_USEPOLLING=true -v ${pwd\src:/app/src} -d -p 3000:3000 --name react-app react-image