# -Portainer_Traefik
Instalação do Portainer e Traefik

:::::::  Instalação docker  ::::::

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

#####Comando Para Criar o acme.json:

touch acme.json

#####Trocando as Permissoes do Arquivo:

sudo chmod 600 acme.json

#####Instalando Utilitario do Apache:

sudo apt-get install apache2-utils -y

#####Criando Senha Traefik:

htpasswd -nbB USUARIO SENHA

###### Se a senha gerada tiver $ vc deve duplicar o $

nexabot:$2y$05$GGI.VUVMR0ljrynX.C0g5.UmqjaHd4M.0QGAQ3BZKWIisaGG5qBJC


sudo docker compose up -d

####################################

sudo docker compose down

sudo docker compose pull

sudo docker compose up -d


![image](https://github.com/CursoAnalistaVoip/-Portainer_Traefik/assets/102430464/1f919ff4-9fb0-4f99-a03e-bcbda7931884)

