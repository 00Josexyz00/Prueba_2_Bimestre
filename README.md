# Prueba_2_Bimestre
Creación de contenedor Docker con PostgreSQL
•	Lo primero es ejecutar el comando docker pull postgres para que haga una descarga desde el repositorio donde se encuentra postgres
•	Para verificar que se haya descargado se usa docker image ls
•	Aquí usamos docker run --name some-postgres -e POSTGRES_PASSWORD=postgres -d postgres para ejecutar la imagen de postgres y que se cree el contedor en docker.
•	Para ingresar y utilizar postgres desde la consola se puede usar docker run -it --rm --link some-postgres:postgres postgres psql -h postgres -U postgres.
•	Para hacer la prueba conectamos con PgAdmin y utilizamos las siguientes credenciales:

