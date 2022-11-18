# examenDAM

Para utilizarlo en el examen

---

![imagen](https://cibertest.com/public/img/main/categorias/thumbs/13-examen-test-lenguaje-de-programacion-python-thumb-592w.jpg)

### - Primera modificación

---

## Para clonar el repositorio usé el comando:

````
-git clone url
````
"url" es sustituído por la url del repositorio que queremos clonar.

Una vez clonado el repositorio desde el entorno gráfico añadí una modificacion al readme e hice un commit usando estos comandos:
````
git add Readme.md     --->     Añadí el Readme

git commit -m "Primera modificación"	--->	Hice el commit con los ficheros añadidos	

git remote set-url origin https://github.com.....	--->	Cambié la url asociada a origin

git push -u origin main	--->	Hice un push de la rama main en el remote origin 

````

---

## Añadir el programa:

Escogí uno de los extras de Nina y añadi el src del programa con :

````
git add src
````

#### Cambiar username de los commit:

Para cambiar el username/autor de los commit hay que usar el comando:

````
git config user.name "ExamenLorenzo"    -->     ExamenLorenzo es el nombre de usuario que usé yo
````

---

## Diagrama de flujo.

````mermaid
graph TD;

INICIO-->id1[Mostrar menu]
id1-->id2[/Opciones/]
id2-->sw{1,2 o 3}
sw-->|Opcion 1|1[/Pedir filas/]
sw-->|Opcion 2|2[/Pedir filas/]
sw-->|Opcion 3|3[/Pedir filas/]
sw-->|Default|4[Mostrar error]
1-->1.1[Dibujar TrianguloA]
2-->2.1[Dibujar TrianguloB]
3-->3.1[Dibujar TrianguloC]
4-->sw
1.1-->FINAL
2.1-->FINAL
3.1-->FINAL











