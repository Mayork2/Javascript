# Solucion del Desafio 3

1. Crea una función que calcule el índice de masa corporal (IMC) de una persona a partir de su altura en metros y peso en kilogramos, que se recibirán como parámetros.
```
function calcularIMC(masa, altura){
    let imc = masa / (altura * altura);
    return imc;
}
```

2. Crea una función que calcule el valor del factorial de un número pasado como parámetro.
```
function calcularFactorial(number){
    if (number === 0 || number === 1){
        return 1;
    } else {
        return number * calcularFactorial(number - 1);
    }
}

let number = 4;
let resultados = calcularFactorial(number);

console.log(`El factorial de ${number} es ${resultados}`);
```

3. Crea una función que convierta un valor en dólares, pasado como parámetro, y devuelva el valor equivalente en reales(moneda brasileña,si deseas puedes hacerlo con el valor del dólar en tu país). Para esto, considera la cotización del dólar igual a R$4,80.
```
function convertirDolares(reales,dolar){
    return dolar * reales;
}
let dolar = 4.8;
let reales = 9;
let resultado = convertirDolares(reales,dolar);

console.log(`La conversion de ${reales} soles a dolares, seria ${resultado} dolares`);
```

4. Crea una función que muestre en pantalla el área y el perímetro de una sala rectangular, utilizando la altura y la anchura que se proporcionarán como parámetros.
```
function salaRectangularAreayPerimetro(altura,base){
    let area = base * altura;
    let perímetro = 2 * (base + altura);
    console.log('El area es: ' + area);
    console.log('El perimetro es: '+ perímetro);
}
let altura = 4;
let base = 3;
salaRectangularAreayPerimetro(altura,base);
```

5. Crea una función que muestre en pantalla el área y el perímetro de una sala circular, utilizando su radio que se proporcionará como parámetro. Considera Pi = 3,14.*/
```
function salaCircular(pi,radio){
    let area = pi * (radio * radio);
    let perimetro = 2 * pi * radio;

    console.log('El area es: '+ area);
    console.log('El perimetro es: '+ perimetro);
}

let radio = 3;
let pi = 3.14;
salaCircular(pi,radio);
```

6. Crea una función que muestre en pantalla la tabla de multiplicar de un número dado como parámetro.
```
function tablaMultiplicar(numero){
    while(i <= 12){
        let producto = numero * i;
        console.log(producto+' = '+numero+' x '+i)
        i++;
    }
}
let numero = 5;
let i = 1
tablaMultiplicar(numero);
```


