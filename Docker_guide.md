***Build new image from docker file.***\
$docker build -t image:ver -f Dockerfile .

***Start a container from image using docker file.***\
$docker run --mount source=local_volume_name,target=/vol1 -rm -it image:version bash






***Create docker local volume:***\
$docker volume create my-vol\
$docker volume ls\
$docker volume inspect my-vol\


