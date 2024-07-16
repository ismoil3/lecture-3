##### lecture 3
# string
# number

## what is method in javascript
ya blok kodi tayor function tayor  

# 3 namudi string sozi 
  - double quotes
  - single quotes
  - Bacrticrs
# JAVASCRIPT STRING METHODS

charAt()
```javascript
let a="string"
console.log(a.charAt(0)) // output s
```

at()

mo indexsa metem modA elementsha meburora
```javascript
let a="string"
console.log(a.charAt(-1)) // output g
```

concat()

yajoya mekna

```javascript
let a="string"
let b="hello"

console.log(a.concat(b)) // output stringhello
```

replace()

alish mekna 
yagonjira ba yagonji diga
```javascript
let b="hello  salom "

console.log(a.replace("salom", "hi")) // output  hello hi
```

replaceall( )

jantahe rangi guftagimon  bosha  bosha alish mekna


split( )

ba znajeniyai dodagimon elementa judo mekna
```javascript
let b="hello"

console.log(a.split("")) // output [h , e ,l ,l ,o]
```


substring ( )

start va end dora start ay chandm index to chandm index elementosha brora
```javascript
let b="hello"

console.log(a.substring(0,4)) // output ello
```

slice ( )

 bamondi substring nekem i minusa kabul mekna


toLowerCase ( )

hamai hjarfora mayda  mekna
```javascript
let b="Hello"

console.log(a.tolowerCase()) // output hello
```



toUpperCase ( )

hamoi hjarfora kalon mekna

```javascript
let b="hello"

console.log(a.tolowerCase()) // output HELLO
```


trim ( )

prabelloi ziyotira nest mekna ay baro

```javascript
let b="    hello     "

console.log(a.trim()) // output hello
```


includes ( )

mesancha hamu elemen ta daruni elememti mo hastay yo ne

```javascript
let b="hello hi"

console.log(a.includes("hi")) // output true
```


toString ( )

hamaichira ba string megardona


indexof ( )

mesanja hamu elemen chandm indexsay

```js
let b="hello"

console.log(a.indexOf("h")) // output 0
```

repeat ( )

takror mekna

```js
let b="hello"

console.log(a.repeat(3)) // output hellohellohello
```


# JAVASCRIPT NUMBERS METHODS


math.floor( )

agar 11.1 bosha moda 11 meta azdara da adadi poyongi meta

```js
let b=11.77

console.log(math.floor(a)) // output 11
```


Math.ceil( )

agar 11.1 bosha moda 12 meta azdara da adadi bologi meta

```js
let b=11.7

console.log(math.ceil(a)) // output 12
```


Math.round( )

agar az azdar 5 bollo bosha da bvologi mebahsha   aksihol da poyongi



max( )

adadi kalona meyoba


min ( )

adadi hurda

pow ( )

ba daraja megardona

sgrt( )

ba kub megardona 

abs ( )

minusara polysa makna

random ( )

trandomni rakam meta




