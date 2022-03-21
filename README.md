# Prerequisite
- docker
- docker-compose

# Getting started
- for installation 
  - mkdir gitlab 
  - cd gitlab
  - vim docker-compose.yaml
  - past file configs here and exit
  - export GITLAB_HOME=$(pwd)/gitlab
  - docker-compose up -d
- for grepping container ip use the following
  - docker ps -> for listing docker container
  - docker inspect [container-id] | grep IPAddress
- for grepping the root password
  - docker exec -it gitlab-ce grep 'Password:' /etc/gitlab/initial_root_password

# credentials
- username: root
- password: use step two from getting started
