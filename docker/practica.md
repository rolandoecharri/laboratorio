# 1. Whalesay - Inicio divertido
docker run docker/whalesay cowsay "¡Bienvenidos a Docker!"

# 2. Nginx - Servidor web instantáneo
docker run -d -p 8080:80 --name mi-nginx nginx

# 3. Juego 2048
docker run -d -p 8080:80 --name juego-2048 alexwhen/docker-2048

# 4. DOOM - ¡El clásico! 🎮
docker run -p 8080:8080 mattipaksula/http-doom

# Whiteboard (pizarra online)
docker run -d -p 8080:8080 --name whiteboard rofl256/whiteboard

# Excalidraw (pizarra colaborativa)
docker run -d -p 8080:80 --name excalidraw excalidraw/excalidraw

# Actual Budget (presupuestos)
docker run -d -p 8080:5006 --name actual actualbudget/actual-server

# VS Code en navegador
docker run -d -p 8080:8080 --name vscode codercom/code-server