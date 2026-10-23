# challenge answers 
1.show CPU,RAM,and process details
- command 'sudo apt install -y & 'htop'
2. checkout apache2 version without installing
- command 'apt show apache2'
3.counted installed packages.
- command : 'apt list --installed | wc -l'
4. printed hello from alphine via docker.
- command: 'sudo docker run --rm aphine echo "hello from alphine"'
5.docker key and sources path.
- key '/etc/apt/keyrings/docker.asc'
- source: '/etc/apt/sources.list.d/docker.sources'
6.removes htop and verified. 
- command: 'sudo apt remove -y htop','hash -r','htop'
