# Arrays

- Un array es una zona de almacenamiento continuo, donde se pueden introducir varios valores, cada un de ellos ubicados por la posicion que ocupa en el array.
- Tambien son denominados como arreglos o vectores, y cuando son de dos dimensiones son llamados matrices.
- Los arrays nos brindan la capacidad de almacenar una coleccion de elementos y acceder a ellos de manera individual.
- Cada elemento se identifica mediante su posicion en array denominada **indice**y estos indices son siempre secuenciales.
- En javascript son altamentes flexibles en terminos de los diferentes tipos de datos que podemos almacenar en cada posicion del array.



## Crear un array

1. Declarar un array con elementos en linea

     ```Javascript
     let miArray = [1,2,3];
        console.log(miArray);
      ``` 
2. Declaando un array con la sintaxis **new Array(**)

    ```Javascript
     let miArray = new Array(1,2,3);
        console.log(miArray);
      ``` 
3. Declarando un array con un tamaño especifico utilizando la sintaxis **new Array** y asignano valores despues:
     ```Javascript
     let miArray = new Array(3);
     miArray [0] =1;
     miArray [1] =2;
     miArray [2] =3;
        console.log(miArray);
      ``` 
4. Declaranddo un array con diferentes tipos dee datos
    ```Javascript
     let miArray4 = [1,"dos",true, {nombre:"juan", edad :30}];
     
        console.log(miArray);
      ``` 
