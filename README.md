# Comandos básicos de Terminal

- Listar archivos y carpetas dentro del directorio en el que nos encontramos en la terminal

```bash
ls
```

- Navegar hacia una de las carpetas (también se puede autocompletar con TAB)

```bash
cd nombreDirectorio
```

- Retroceder una carpeta hacia atrás

```bash
cd ..
```

- Conocer en qué directorio estás

```bash
pwd
```

- Crear directorio

```bash
mkdir nombreDirectorio
```

- Crear archivo

```bash
touch nombreArchivo.extensión

```

- Abrir directorio actual en Visual Studio Code

```bash
code .
```

- En caso de permisos denegados, habilitar todos los permisos para nuestro usuario en el directorio actual

```bash
chmod 777
```

- Eliminar archivo

```bash
rm nombreArchivo.extensión
```

- Eliminar directorio

```bash
rm -d directorio
```

# Comandos básicos de Git

- Inicializar un directorio como repositorio local

```bash
git init
```

- Enlazar repositorio local al repositorio remoto en Github

```bash
git remote add origin URL
```

- Agregar un archivo pendiente al stage

```bash
git add nombreArchivo
```

- Agregar todos los archivos pendientes al stage

```bash
git add .
```

- Agregar un commit

```bash
git commit -m "Mensaje de commit"
```

- Enviar cambios a branch principal (main o master)

```bash
git push -u origin main

git push -u origin master
```

# Otros comandos de Git

- Visualizar estado de los archivos

```bash
git status
```

- Ver el log

```bash
git log
```