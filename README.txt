
#creacion imagen
docker build -t dashbi:v12 .

#Ejecucion de la imagen
docker run -p 8050:8050 dashbi:v12


