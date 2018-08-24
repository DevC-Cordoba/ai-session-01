# ai-session-01
Repositorio del material utilizado en el evento AI Session 01: Machine Learning

## Lista TODO 

Aceptamos colaboraciones! o denme más tiempo. Cualquier comentario es bienvenido.
- [ ] Instructivo para windows
- [ ] Explicar sobre Anaconda
- [ ] Explicar sobre environments en python
- [ ] Explicar sobre Jupyter Notebooks

## Comenzando...

Las siguientes instrucciones son para que puedan correr el proyecto en sus computadoras tanto para desarrollo, prueba y modificaciones del contenido presentado durante la charla. 

### Prerrequisitos

Antes de comenzar es necesario tener instalado Miniconda con Python 3.6. Miniconda (Anaconda) es un gestor de paquetes y environments de Python. Se puede descargar desde el siguiente link https://conda.io/miniconda.html

### Instalación

Paso a paso el proceso de instalación una vez cumplidos los prerrequisitos. Durante el siguiente instructivo vamos a suponer que nos encontramos parados en la carpeta del sistema "~/Documents"

``` sh
$ cd ~/Documents
# clonamos el repo
$ git clone https://github.com/DevC-Cordoba/ai-session-01
$ cd ai-session-01/setup
# corremos el script con el cual se descargan las dependencias necesarias 
# y crea el environment ai-session-01
# PUEDE TARDAR VARIOS MINUTOS, SEAN PACIENTES
$ sh setup.sh
```
Si todo termina con éxito ya estarán listos para trabajar con las jupyter notebooks. Para chequear la correcta instalación ejecuten el siguiente comando para activar el environment ai-session-01
```sh
$ source activate ai-session-01
```
Deberían ver en los comandos delante de todo lo siguiente -> (ai-session-01) 

## Ejecutando la presentación

Teniendo en cuenta que están en la carpeta "~/Documents/ai-session-01" ejecuten el siguiente comando
```sh
$ jupyter notebook
```
Esto les abrirá un browser con la siguiente url http://localhost:8888/tree

## Built With

* [Jupyter Notebook](http://jupyter.org/) - Presentación
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

