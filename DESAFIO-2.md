//CAMBIA EL CONTENIDO DEL H1 CON DOCUMENT Y ASIGNA EL TEXTO: HORA DEL DESAFIO
let titulo = document.querySelector('h1'); 
titulo.innerHTML='HORA DEL DESAFIO';


//CREA LA FUNCION QUE MUESTRE EN LA CONSOLA EL MENSAJE "EL BOTON FUE CLICADO" SIEMPRE QUE SE PRESIONE 
//EL BOTON "CONSOLE"

function mostrarMensajeEnLaConsola() {
    console.log('El boton fue clicado!')
}

//CREA UNA FUNCION QUE SE EJECUTE CUANDO HAGAS CLICK EN EL BOTON PROMPT, PREGUNTANDO EL
//NOMBRE DE UNA CIUDAD DE BRASIL. LUEGO MUESTRA UN ALERT CON EL MENSAJE CONCATENANDO LA RESPUESTA CON 
//EL TEXTO "ESTUVE EN "CIUDAD" Y ME ACORDE DE TI"

function mostrarAlerta() {
let ciudad = prompt("Por favor, ingresa el nombre de una ciudad de Brasil:");
alert("Estuve en "+ ciudad +" y me acorde de ti")
}


//CREA UNA FUNCION QUE MUESTRE UNA ALERTA CON EL MENSAJE "YO AMO JS" SIEMPRE QUE SE PRESIONE EL BOTON 
//ALERTA

function mostrarAlerta() {
    alert("AMO JAVASCRIPT!"); 
}
