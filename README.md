# docker-lemp
Before use:
1. Deploy a virtual machine (Optional)
2. Install git, docker, docker-compose
3. Create network "front" from docker($docker network create front)
4. Project build($docker-compose build)
5. Project start($docker-compose up -d)
6. Add 2 redirect lines to the host machine. For example in debian location - /etc/hosts/
127.0.0.1 site1.docker.ru
127.0.0.1 site.docker.ru
127.0.0.1 pma.docker.ru

#Magic
