# angular-docker-01
npm install -g @angular/cli
ng version

# Crear proyecto 
ng new angular-docker
cd angular-docker
ng serve:  Local:   http://localhost:4200/


# Creamos la imagen
docker build -t angular-dockerizado:v1 .

# Vamos a correr el contenedor creado
docker run angular-dockerizado:v1