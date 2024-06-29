# Solucionario del Desafio 2

1. Crear una función que muestre "¡Hola, mundo!" en la consola.
```
function saludo(){
    console.log('¡Hola, mundo!');
}
saludo();
```

2. Crear una función que reciba un nombre como parámetro y muestre "¡Hola, [nombre]!" en la consola.
```
function mostrarNombre(nombre){
    console.log(`Hola, ${nombre}`);
}
mostrarNombre('Luis');
```

3. Crear una función que reciba un número como parámetro y devuelva el doble de ese número.
```
function buscarNumero(numero){
    let doble = numero * 2;
    console.log(doble);
}
buscarNumero(7);
```

5. Crear una función que reciba tres números como parámetros y devuelva su promedio.
```
function numerosPromedio(a, b, c){
    let resultado = (a + b + c)/3;
    console.log(resultado);
}
numerosPromedio(4,6,2);
```

6. Crear una función que reciba dos números como parámetros y devuelva el mayor de ellos.
```
function numeroMayor(a,b){
    if (a > b){
        console.log(a + ' es mayor');
    } else {
        console.log(b + ' es mayor');
    }
}
numeroMayor(5,8);
```

7. Crear una función que reciba un número como parámetro y devuelva el resultado de multiplicar ese número por sí mismo.
```
function recibirNumero(numero){
    let multiplicar = numero * numero;
    console.log(multiplicar);
}
recibirNumero(7);
```
