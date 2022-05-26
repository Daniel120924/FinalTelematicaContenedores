# FinalTelematicaContenedores
En primer lugar para clonar este repositorio debemos emplear el siguiente comando:
git clone https://github.com/Daniel120924/FinalTelematicaContenedores.git 

  1. Para iniciar el contenedor se ejecuta el siguiente comando: sudo docker build -t proyectofinal:01 .

  2. Para ejecutar el servicio se usa el siguiente comando: sudo docker run -it -p 80:80 proyectofinal:01 python3 app.py
