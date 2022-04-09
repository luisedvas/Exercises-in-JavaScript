# JAvaScript
Team Nieva
// VARIABLES - DEFINICIÓN

// Contenededores de datos

// let - Voy a crear una variable
// bonafont - Nombre de la variable
// =  - Operador de asignación
// "Agua" - Texto plano (String) (tipo de dato)

// ES5 - Estándares tradicionales de JS
let bonafont = "Agua"

let edad = 28 // Podrá hacer operaciones aritméticas
let edadDos = "28" // Texto plano que no podrá hacer operaciones aritméticas

console.log(bonafont)
console.log(edad)

// 1. EJERCICIO
// A. DOS VARIABLES DE TEXTO PLANO
// B. DOS VARIABLES DE NÚMEROS


// BOOLEANS - BOOLEANOS
// true 
// false

// Convención CAMEL CASE
// Están nombrando una variable, comienzan la palabra en minuscula, y cuando añadan la segunda palabra, su primera letra en mayúscula y de resto en minúscula.
let estaLloviendo = true
let diaCalurosoEnAbril = false


// ARREGLOS
// Conjunto de datos. Puede ser cada elemento un tipo de dato diferente

let sistemasOperativos = [
  "Windows", 
  "MacOS", 
  "Linux"
]

let usuario = ["Mike", 34, true]

// EJERCICIO 2. 
// A) Crear dos arreglos
// B) Crear dos booleanos

// EJERCICIO 2 SOLUCION

let hayElectricidad = true
let estaDisponibleElInternet = false 

let comidaRapida = ["Hamburguesa", "Hotdog", "Pizza"]
let comidaCasera = ["Arroz", "Horneado", "Pasteles"]

// OBJETOS
// TIPO DE DATOS QUE AGRUPA DATOS, LE DAMOS CONTEXTO A TRAVÉS DE UN CONCEPTO PROPIEDADES

let yo = {
  nombre: "Mike",
  apellido: "Nieva",
  edad: edadDos,
  dondeViveHaceFrio: false
}

console.log(yo)
console.log("yo")

console.log(yo.nombre) // DOT NOTATION - NOTACIÓN DE PUNTO
console.log(yo.edad)
console.log(yo.dondeViveHaceFrio)

// EJERCICIO 3
// A) CREACIÓN DE UN OBJETO. 6 PROPIEDADES.
// EJERCICIO 3 SOLUCION

let hermana = {
  nombre: "Maria", 
  segundoNombre: "Jose",
  apellido: "Castillo",
  edad: 14,
  pasatiempoFavorito: "Roblox",
  comidaFavorita : "Pastelitos",
  peliculaFavorita: "Encanto",
  despiertaTemprano: False
}

let celular = {
  marca: "Apple",
  colores: {
    rojo: true,
    azul: false,
    verde: true
  },
  modelos: ["iPhone X", "iPhone 13", "iPhone 13 Pro"],
  paisesEnDistribucion: {
    mx: {
      ciudades: ["Ciudad de México", "Puebla", "Veracruz"]
    },
    col: {
      // ZERO-INDEX  0          1           2            3        4      
      ciudades: ["Bogotá", "Medellín", "Barranquilla", "Cali", "Cucuta"]
    },
    arg: {
      ciudades: ["Buenos Aires", "Cordoba", "Mendoza"]
    }
  }
}

// DOT NOTATION - NOTACIÓN DE PUNTO - ACCEDER A PROPS EN OBJETOS
// BRACKET NOTATION - NOTACIÓN DE CORCHETES - ACCEDER A ELEM DE ARR
console.log(celular.paisesEnDistribucion.col.ciudades[2])

// FUNCIONES
// FÁBRICAS DE CÓDIGO

// INPUTS - DATOS INTRODUCIDOS
// fx() - FÁBRICA DE PROCESOS DE CÓDIGO
// OUTPUTS - RESULTADO QUE SALIÓ DESPUÉS DEL PROCESO DE LA FÁBRICA

// INPUTS -> fx() -> OUTPUTS

// ETAPAS DE LAS FUNCIONES
// 1. DECLARACIÓN - DECLARATION
// ESCRIBIR UNA SOLA VEZ
// AL DECLARAR, EL VALOR DE LOS PARÉNTESIS SE LES CONOCE COMO PARÁMETROS
function saludar(nombre){
  // TÉCNICA DE CONCATENACIÓN
  return "Hola " + nombre
}

// 2. INVOCACIÓN - CALLING - "call a function"
// EJECUTAR LAS VECES QUE YO CONSIDERE NECESARIOS
// AL INVOCAR, EL VALOR DE LOS PARÉNTESIS SE LES CONOCE COMO ARGUMENTOS
let kath = saludar("Kath")
console.log(kath)

let joseDaniel = saludar("JoseDaniel")
console.log(joseDaniel)

saludar("Adrian")
saludar("Nat")
saludar("Jorge")
saludar("Andrea")
