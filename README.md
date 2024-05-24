# Desarrollo con Python

El proposito de este repositorio, es de uso personal & guia, para quien este interesado en aprender este lenguaje. 

Nota : *Algunas librerias y versiones de python pueden variar dada la fecha de la creacion de este repositorio, se tratara de mantenerlo actualizado, asi como sus librerias utilizadas.* 
## Antes de empezar
***Lee los pasos de los numeros, si ya tienes todo puedes saltarlo**

## 1- Instalar Python

Tener instalada una version de [Python](https://www.python.org/downloads/) version realizada de proyecto (3.12.3) 

Como recomendación marcar la opcion Add Python "version" to PATH, una ves concluida la instalación validamos que este instalado Python, en nuestro PC 

Abrimos Terminal/CMD(En caso de Windows) y ejecutamos

Windows
```bash
 python --version
```

Linux
```bash
 python -v
```

Nota : *Si ya manejas una version, verifica que las librerias funcionen para dicha version*

## 2 - Instalar IDE 

IDE = Entorno de Desarrollo Integrado

El IDE utilizado para esta version es [Visual Studio Code](https://code.visualstudio.com/download) , instalar la version basada en tu SO

## 3 - Activacion Entornos Virtuales Windows

Habilitar la funcionalidad de maquinas Virtuales (Windows)

Abrir PowerShell (Administrador)

Ejecutar

```bash
Get-ExecutionPolicy -List
```

```bash
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

En el texto despues de los : , escribir :

```bash
S
```

Validamos Ejecutando :

```bash
Get-ExecutionPolicy -List
```

validando que la opcion CurrenUser, sea "RemoteSigned"


## 4 - Instalación pip Windows

Ejecutamos los Scripts

```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```

```bash
python get-pip.py
```

Validamos instalacion

```bash
pip --version
```

## 5 - Instalacion virtualenv

Ejecucion

```bash
pip install virtualenv
```

## 6 - Creacion entorno y Activacion env

Antes que nada, ¿Que son los [Entornos Virtuales ](https://docs.python.org/es/3/tutorial/venv.html#creating-virtual-environments)?
En resumen son espacios aislados donde seremos capaces de gestionar cada una de las dependencias necesarias para cada proyecto.

Nos ubicamos en nuestro proyecto y en la terminal de Visual Studio, ejecutamos los siguientes comandos. "name" es el nombre de tu entorno, recomendacion, llamarlo venv

```bash
virtualenv "name"
```

Activacion

```bash
"name"\Scripts\activate
```
Si todo salio correctamente, visualizaremos un ejemplo como el siguiente :

*(venv) PS L:\Repo_Publico\Desarrollo_Python>*

Para desactivar el entorno, ejecutamos el siguiente comando :

```bash
deactivate
```
## Authors

- [@d3m0n](https://github.com/luiszjimenez)