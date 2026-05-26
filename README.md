# puede visualizarse en ejecución en

<a href="https://go.drvelasquezq.dev" target="_blank">https://go.drvelasquezq.dev</a>
<br>

## Descripción

Ejemplo mínimo de un servidor HTTP con web framework Echo en su versión 5 para Go [https://echo.labstack.com/docs/quick-start](https://echo.labstack.com/docs/quick-start). Responde con `Hello, World!` en la ruta raíz.

# Uso


### 1. Clonar el repositorio

```bash
git clone https://github.com/drvelasquezq/golang1.26-echo5-hello-world.git
cd golang1.26-echo5-hello-world.git
```

### 2. Instalar dependencias

Este repositorio no incluye la carpeta `vendor/`. Ejecuta el siguiente comando **una sola vez** para descargar e instalar las dependencias dentro del proyecto:

```bash
go mod vendor
```

### 3. Ejecutar el servidor

```bash
go run main.go
```

El servidor quedará escuchando en el puerto `1323`.

### 4. Probar

Abre en el navegador o ejecuta:

```bash
curl http://localhost:1323
# Hello, World!
```

Tener en cuenta que también es posible compilar el programa y luego ejecutarlo:

```bash
# -o especifica el nombre del ejecutable
go build -o hello-world
./hello-world
```

# Entorno de ejecución 

## docker

<a href="https://github.com/drvelasquezq/docker-golang1.26-trixie" target="_blank">https://github.com/drvelasquezq/docker-golang1.26-trixie</a> 