# AWS-Despliegue
Despliegue semi-automático aplicación EC2 instancia ubuntu con main.yml

#Pasos manuales de instalacion npm
#1- curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
#2- . ~/.nvm/nvm.sh
#3- nvm install --lts
#4- mkdir logs
#5- curl -sL https://github.com/DavidHormigoRamirez/aws-helloworld-node/archive/master.zip --output master.zip
#6- apt install unzip
#7- unzip master
#8- mv aws-helloworld-node-master/ app
#9- cd app
#10- npm install
#11- npm start
#12 -curl localhost:8080

#Pasos Semi-Automaticos de instalacion npm en archivo main.yml
#echo "Instalando dependencias Node.JS"
            #curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
            #. ~/.nvm/nvm.sh
            #. ~/.bashrc
            #node -v
            #npm -v
            #nvm install --lts
            #curl -sL https://github.com/DavidHormigoRamirez/aws-helloworld-node/archive/master.zip --output master.zip
            #mkdir -p ~/logs
            #unzip master.zip
            #mv aws-helloworld-node-master/ app 
            #cd app
            #npm install
            #npm start
