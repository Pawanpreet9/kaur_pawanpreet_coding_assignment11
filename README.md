# To create react image for docker.
docker build -t kaur_pawanpreet_coding_assignment11.dev .

# To run the container.
docker run --name=kaur_pawanpreet_coding_assignment11.dev -it -v %cd%:/app -v /app/node_modules -p 7775:3000 -e CHOKIDAR_USEPOLLING=true kaur_pawanpreet_coding_assignment11.dev