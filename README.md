# Prerequisite
- docker
- docker-compose

# Getting started
- for installation 
  - docker-compose up -d
- for grepping container ip use the following
  - docker ps -> for listing docker container
  - docker inspect [container-id] | grep IPAddress
- for grepping the root password
  - docker exec -it gitlab-ce grep 'Password:' /etc/gitlab/initial_root_password

# credentials
- username: root
- password: use step two from getting started
