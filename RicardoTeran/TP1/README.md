# **TRABAJOS PRACTICA 1**

# Índice

- [Hola Mundo con C++](#Hola-Mundo-con-C)
- [Pasos para realizar un Pull request](#Pasos-para-realizar-un-Pull-request)
- [Tabla de comandos mas usados en git](#Tabla-de-comandos-mas-usados-en-git)

## Hola Mundo con C++

En C++ todo el código se ejecuta en la función `main()`

```C++
#include <iostream>
using namespace std;

int main(){
    cout<<"Hola Mundo"<<endl;

    return 0;
}
```

por lo general se usa `return 0` para que el programa retorne el valor de `0` este nos sirve para comprobar que no haya errores.

## Pasos para realizar un Pull request

1) Lo primero a realizar, es hacer un `git push` desde nuestra maquina local.
Una vez realizado lo anterior nos saldrá un mensaje en GitHub. 
    
![Ejemplo 1](https://imgur.com/ogbg8A0.png)

2) Damos clic en el botón `Compare & pull request` y seguimos los pasos a continuación.

![Ejemplo 2](https://imgur.com/cWJmncQ.png)
![Ejemplo 3](https://imgur.com/HdHOd4L.png)

**!Listo!** ahora solo falta que el dueño del repositorio revise los cambios.

## Tabla de comandos mas usados en git

| Comando | Descripción |
| :--- | :--- |
| git add | Este comando nos permite agregar archivos al index|
| git merge | Este comando se usa para fusionar una rama con otra |
| git clone | Nos ayuda a taer los repositorios remotos a nuestra PC |
| git branch | Este comando se una para listar, crear o borrar ramas |
| git config | Nos ayuda a acceder a las configuraciones del usuario|
| git init | Este comando se usa para crear un nuevo repertorio GIT|
| git commit | Se usa principalmente para mandar los cambios a la cabecera |
| git status | Nos muestra el estado de nuestro proyecto |
| git checkout | El comando checkout se puede usar para crear ramas o cambiar entre ellas |
| git diff | Este comando nos sirve para comparar diferencias |
|git rm | Este comando se usa para remover archivos del index y del directorio en que se esta trabajando |





