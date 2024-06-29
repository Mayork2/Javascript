# Solucion del Desafio 4

1. Crea una lista vacía llamada "listaGenerica".
```
let listaGenerica = [];
```

2. Crea una lista de lenguajes de programación llamada "lenguagesDeProgramacion con los siguientes elementos: 'JavaScript', 'C', 'C++', 'Kotlin' y 'Python'.
```
let lenguagesDeProgramacion = ['JavaScript','C','C++','Kotlin','Python'];
```

3. Agrega a la lista "lenguagesDeProgramacion los siguientes elementos: 'Java', 'Ruby' y 'GoLang'.
```
lenguagesDeProgramacion.push('Java','Ruby','GoLang');
```

4. Crea una función que muestre en la consola todos los elementos de la lista "lenguagesDeProgramacion.
```
function lenguajesProgramacion(){
    for(let i = 0; i < lenguagesDeProgramacion.length; i++){
        console.log(lenguagesDeProgramacion[i]);
    }
}
lenguajesProgramacion();
```

5. Crea una función que muestre en la consola todos los elementos de la lista "lenguagesDeProgramacion en orden inverso.
```
function lenguagesProgramacion(){
    for(let i = (lenguagesDeProgramacion.length-1); i >= 0 ; i--){
        console.log(lenguagesDeProgramacion[i]);
    }
}
lenguagesProgramacion();
```

6. Crea una función que calcule el promedio de los elementos en una lista de números.
```
function calcularPromedio(numeros){
    let suma = 0;
    for(let i = 0; i < numeros.length; i++){
        suma += numeros[i];
        
    }
    return suma / numeros.length;
}

let numeros = [10,30,50,70,90];
let media = calcularPromedio(numeros);
console.log(`El promedio es: ${media}`);
```

7. Crea una función que muestre en la consola el número más grande y el número más pequeño en una lista.
```
function numeroMayoryMenor(numeros){
    let mayor = numeros[0];
    let menor = numeros[0];

    for(let i = 0; i < numeros.length; i++){
        if(numeros[i]<mayor){
            mayor = numeros[i];
        }
        if(numeros[i]>menor){
            menor = numeros[i];
        }
    }
    console.log(`el menor es: ${menor}`);
    console.log(`el mayor es: ${mayor}`);
}

let numeros = [10,20,30,40,50];
numeroMayoryMenor(numeros);
```

8. Crea una función que devuelva la suma de todos los elementos en una lista.
```
function sumaLista(numeros){
    let suma = 0;
    for(let i = 0; i < numeros.length; i++){
        suma += numeros[i];
    }
    return suma;
}
let numeros = [10,20,30,40];
let suma = sumaLista(numeros);
console.log(`la suma es: ${suma}`);
```

9. Crea una función que devuelva la posición en la lista donde se encuentra un elemento pasado como parámetro, o -1 si no existe en la lista.
```
function elementoPasado(lista){
    for(let i = 0; i < lista.length; i++){
        if(lista[i] == numero){
            console.log(`Esta en la posicion ${i}`);
        }
    }
    return -1;
}

let numeros = [10,20,40,50,60,70];
let numero = 10;
let elementos = elementoPasado(numeros);
console.log(elementos);
```

10. Crea una función que reciba dos listas de números del mismo tamaño y devuelva una nueva lista con la suma de los elementos uno a uno.
```
function cantidadListas(a,b){
    if(a.length != b.length){
        console.log('Error las listas deberian ser del mismo tamaño')
    }

    let resultado = [];
    for(let i = 0; i < a.length; i++){
        resultado.push(a[i]+b[i]);  
    }
    return resultado;  
}

let lista1 = [1,2,3,4];
let lista2 = [5,6,7,8];
let solucionSuma = cantidadListas(lista1,lista2);
console.log(solucionSuma);
```

11. Crea una función que reciba una lista de números y devuelva una nueva lista con el cuadrado de cada número.
```
function listaNumeros(numeros){
    let resultado = [];
    for(let i = 0; i < numeros.length; i++){
        resultado.push(numeros[i]**potencia);
    }
    return resultado;
}
let lista = [1,2,3,4,5,6];
let potencia = 2;
let listaPotencia = listaNumeros(lista);
console.log(listaPotencia)
```
