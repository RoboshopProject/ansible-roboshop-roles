create ansible-roboshop-roles directory
roboshop. yaml
inventory. ini
ansible. cfg
roles/


1. load cayalogue role
2. ansible finds meta dir and main. yaml
3. it depends on common role
4. ansible exetue main. yam in task folder
5. now ansible stsrt executingbcatalogue task and main. yaml
6. we extracted common code into coommon? app. setup. yaml
7. ansible import this into catalogu/task/main
