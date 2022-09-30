# dockerized-webwok
installation steps on webwork docker
### Download webwork from official github page <code>git clone https://github.com/openwebwork/webwork2.git</code> 
### Copy docker-config/docker-compose.yml.dist and docker-config/env.dist to parent folder as docker-compose.yml and .env under webwokr2
## <code>cd webwork2</code> 
## <code>cp docker-config/docker-compose.yml.dist ./docker-compose.yml</code> 
## <code>cp docker-config/env.dist ./.env</code>
## You can change the set values in the .env file if you want.
### webwork setup as follows 
## <code>docker build --tag webwork-base:forWW217 -f DockerfileStage1 .</code>
## <code>docker-compose build</code>
## <code>docker-compose up app -d --build</code>
