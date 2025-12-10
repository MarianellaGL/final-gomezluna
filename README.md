# Examen Final - Ingenieria de Software

## Informacion

- **Nombre:** Marianella Gomez Luna
- **DNI:** 35326129
- **Materia:** Ingenieria de Software

## Como ejecutar

1. Abrir el archivo `index.html` en cualquier navegador web
2. Tambien puede usar un servidor local:

   ```bash
   # Con Python
   python -m http.server 8000

   # Con Node.js (npx)
   npx serve
   ```

3. Navegar a `http://localhost:8000`

## Docker

### Comandos utilizados

```bash
# Construir la imagen
docker build -t examen-final .

# Ejecutar el contenedor
docker run -d -p 8080:80 --name examen-final-container examen-final

# Ver contenedores activos
docker ps

# Detener el contenedor
docker stop examen-final-container

# Eliminar el contenedor
docker rm examen-final-container
```

### Acceso

Una vez ejecutado el contenedor, acceder a: `http://localhost:8080`

### Imagenes de docker
[DockerContainer.png](https://github.com/MarianellaGL/final-gomezluna/blob/686612d86487bfe213bb100337948fb6239fc143/DockerContainer.png)
[DockerImage.png](https://github.com/MarianellaGL/final-gomezluna/blob/686612d86487bfe213bb100337948fb6239fc143/DockerImage.png)

