# TAREA N°6

## Participantes:

- Alejandro Serna Loaiza 
- Maria Camila Rueda Cano

### Ejercicio N°1

```javascript
var nombre = prompt("Ingresa nombre");
console.log("Ahora estas en la matrix" + " " + nombre);
```

![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejericioUno.png)

### Ejercicio N°2

```javascript
var numero;
var numeroEnt;
var suma = parseFloat(numero) + parseInt(numeroEnt);
numero = prompt("Ingresa numero con decimales");
numeroEnt = prompt("Ingresa numero entero");
console.log("Primer numero:" + " " + numero);
console.log("Segundo numero:" + " " + numeroEnt);
console.log("El resultado de la suma es:" + " " + suma);
```

![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejercioDos.png)

### Ejercicio N°3

```javascript
var numeroUno;
var numeroDos;
var numeroTres;
var suma = parseInt(numeroUno) + parseInt(numeroDos);
var x = suma * parseInt(numeroTres);
numeroUno = prompt("Ingresa un numero");
numeroDos = prompt("Ingresa otro numero");
numeroTres = prompt("Ingresa un nuevo numero");
console.log("Ingresa un numero:" + " " + numeroUno);
console.log("Ingresa otro numero:" + " " + numeroDos);
console.log("Suman:" + " " + suma);
console.log("Multiplicacion de la suma por el ultimo numero:" + x);
```

![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejercioTres.png)

### Ejercicio N°4

```javascript
var km;
var ltr;
var y = parseInt(km)/parseFloat(ltr);
km= prompt("Kilometros recorridos");
ltr= prompt("Litros de combustible gastados");
console.log("Ingresa los kilometros recorridos"+ " " + km);
console.log("Ingresa los litros de combustible gastados"+ " " + ltr);
console.log("EL consumo por kilometro es de"+y);
```

![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejercicioCuatro.png)
### Ejercicio N°5

```javascript
var x=5;
var m=9;
var n=32;
var f;
f= prompt("Ingresa la tempratura expresada en Farenheit");
var c=(x/m)*(f-n);
console.log("Ingresa la tempratura expresada en Farenheit"+" "+f);
console.log(c)

```
![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejericioCinco.png)


### Ejercicio N°6

```javascript
var c=3;
var numeroUno;
var numeroDos;
var numeroTres;
var numeroUno= prompt("Ingresa primer numero");
var numeroDos= prompt("Ingrese segundo numero");
var numeroTres= prompt("Ingrese tercer numero");
var p= (parseInt(numeroUno)+ parseInt(numeroDos)+ parseInt(numeroTres))/c;
console.log("Primer numero"+" "+ numeroUno);
console.log("Segundo numero"+" "+numeroDos);
console.log("Tercer numero"+" "+numeroTres);
console.log("EL promedio de los tres es"+p);

```
![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejercicioSeis.png)

### Ejercicio N°7

```javascript
var numero=prompt("Ingresa numero");
var b= (parseInt(numero)*85)/100;
console.log("ingresa un numero:"+" "+numero);
console.log("Descontando el 15% queda:"+" "+ b);
```
![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejercicioSiete.png)

### Ejercicio N°8

```javascript
var palabraUno =prompt("Ingrese la primera palabra");
var palabraDos =prompt("Ingrese la segunda palabra");
console.log("Primera palabra:"+" "+palabraUno);
console.log("Primera palabra"+" "+palabraDos);
console.log(palabraUno +" "+ palabraDos);
```
![ll](https://github.com/camilaru15/javascript/blob/master/imagenes/ejericioOcho.png)

### Ejercicio N°9

```javascript
var cadena=prompt("Ingrese una palabra o un texto");
console.log("El caracter en primer lugar es:", cadena[0]);
console.log("Ingrese un numero positivo menor a", (cadena).length);
var indice=parseInt(prompt());
console.log("EL caracter en esa posicion es:", cadena[indice]);
```
![ll]()

### Ejercicio N°10

```javascript
var shows=parseInt(prompt("Shows vistos en el ultimo año:"));
console.log("Shows vistos en el ultimo año:"+" "+shows)
console.log(shows>3)

```
![ll]()

### Ejercicio N°11

```javascript
var fecha=prompt("Fecha en formato DD/MM/AAAA:");
var año=fecha0000;
var dia=fecha\\1000000;
var mes=(fecha\\10000)/100;
console.log(dia+"/"+mes+"/"+año);
```
![ll]()

### Ejercicio N°12

```javascript
var numero=parseInt(prompt("Número entero:"));
console.log("Numero entero:" + " "+numero);
console.log((numero/2) == 0);

```
![ll]()

### Ejercicio N°13

```javascript
var edad=parseInt(prompt("Tu edad:"));
var articulos=parseInt(prompt("Artículos comprados:"));
console.log("Tu edad:" + " "+edad);
console.log("Articulos comparados":+" "+ articulos);
console.log((edad>18) and (articulos>1));

```
![ll]()

### Ejercicio N°14

```javascript

var cadena=prompt("Ingresá una frase:");
var longitud= (cadena).length;
console.log("Ingresa una frase:"+" "+ cadena);
console.log(longitud/2 == 0);


```
![ll]()

### Ejercicio N°15

```javascript
var palabra1=prompt("Una palabra:");
var palabra2=prompt("Otra palabra:");
console.log("Una palabra:"+" "+ palabra1);
console.log("Otra palabra:"+" "+ palabra2);
console.log(palabra1<palabra2);

```
![ll]()

### Ejercicio N°16

```javascript
var nombre1=prompt("Tu nombre:");
var nombre2=prompt("Otro nombre:");
var posicion_final_nombre1=(nombre1).length-1;
var posicion_final_nombre2=len(nombre2).length-1;
console.log("Tu nombre:" + " "+nombre1);
console.log("Otro nombre:" + " "+ nombre2);
console.log((nombre1[0] == nombre2[0]) or (nombre1[posicion_final_nombre1] == nombre2[posicion_final_nombre2]));

```
![ll]()

### Ejercicio N°17

```javascript
var numero=parseInt(prompt("Número:"))
if (numero<0){
    numero=numero*-1
console.log("Numero:"+ " "+numero)
console.log("Valor absoluto:", numero)}

```
![ll]()

### Ejercicio N°18

```javascript
var numero1=parseInt(prompt("Un número:"))
var numero2=parseInt(prompt("Un numero:"))
if (numero1>numero2){
    console.log(numero1, "es mayor")
}
else{
console.log(numero2, "es mayor")
}

```
![ll]()

### Ejercicio N°19

```javascript
letra=window.prompt("Letra:")
if (letra.leght!=2){
    console.log("Debe ser sólo una letra")
}
else{
 if (letra=="a" || letra=="e" || letra=="i" || letra=="o" || letra=="u")
 console.log("Es vocal")}

```
![ll]()

### Ejercicio N°20

```javascript
num1=parseInt(prompt("Primer número:"))
num2=parseInt(prompt("Segundo número:"))
num3=parseInt(prompt("Tercer número:"))
if (num1<num2){
    if (num1<num3){
        console.log("Menor:", num1)
    }else{
        console.log("Menor:", num3)
    }
}else{
    if (n2<n3){
        console.log("Menor:", num2)
    }else{
        console.log("Menor:", num3)
    }
}

```
![ll]()