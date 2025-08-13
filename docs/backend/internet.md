# ¿Qué es Internet?
Aquí tengo suerte porque esto lo dimos en el grado medio con un profesor buenísimo, y como yo ya desarrollaba pues le vi utilidad a todo. En fin. A lo que vamos

Internet es una red... de redes. Sin más

## ¿Cómo funciona?
Para empezar puede ser bastante útil recordar cómo empezó. De memoria me acuerdo de que el primer hito en cuanto a comunicación de ordenadores a distancia fue entre 2 universidades, no me acuerdo ni del año ni de las unis, pero es suficiente. No es una wiki esto

Y como todas las tecnologías esto fue volviéndose más accesible, y a día de hoy tú no necesitas tener, o estar, en una universidad de prestigio con un super ordenador para comunicarte con otra. Pero supongamos que estamos a 1 continente de distancia... ¿realmente crees que hay algún cable que nos conecte directamente? ¿A tu país y al mío? ¿A tu casa y a la mía?

Ahí está la magia de Internet. En el mundo hay diferentes tipos de redes, más grandes o más pequeñas, de hecho tenemos una lista de tipos y su alcance:

- LAN: Local Access Network. Alcance local. Puede ser una casa o apartamento
- MAN:
- WAN: Wide / World-wide Access Network. Alcance amplio, o directamente del mundo entero, como puede ser Internet

Y es gracias a la colaboración de todas las redes juntas que hemos llegado a algo como Internet. No existen conexiones directas para todos los puntos, pero sí existen redes suficientes para poder llegar de A a B dando más saltos o menos, pasando por más redes diferentes o menos, pero se llega

## ¿Qué es HTTP?
HyperText Transfer Protocol. Protocolo de transferencia de hipertexto. El hipertexto es básicamente un contenido escrito que incluye enlaces a otros contenidos

## ¿Qué es un "nombre de dominio"?
Es una dirección en un formato que es más fácilmente legible para un ser humano

En realidad, en la red, se identifican unos dispositivos de otros gracias a las direcciones IP. El problema es que estas direcciones suelen ser una secuencia de números, o números con letras, y son difíciles de memorizar para un ser humano. Compruébalo tú mismo si no; ¿de qué te acuerdas más? ¿De 142.250.201.78, o de google.com?

## ¿Qué es el "hosting"?
Es el servicio que consiste en proveer servidores, de forma que personas de a pie no tengan que montarse un datacenter para poner su web o software de forma pública

Si tú puedes entrar a una web, es porque detrás hay un ordenador (o varios) configurado/s para _servirte_ dicha web, con sus archivos y todo lo necesario. Justamente por eso se llaman _servidores_. Cuando te paras expresamente a ver el vocabulario de casi cualquier sector TI ves que suele tener mucho sentido

Entonces, el hosting lo que te permite es tener precisamente ese servidor, o servidores, para tu web, sin necesariamente comprarlos físicamente, instalarles el sistema operativo, configurarlos... Si te va ese rollo, hay gente que lo hace, justamente se llama "self-hosting". Aprenderías bastante en el proceso. Pero aprende también a usar Vercel, Netlify y otros servicios también. Después de que ya hayas sido capaz de desarrollar algo claro, todo a su tiempo

## ¿Qué es un DNS y cómo funciona?
Un DNS es un registro que mapea nombres de dominio a IPs. Antes te había dicho que los equipos se identifican por IPs. ¿Entonces por qué yo puedo poner google.com en mi navegador en vez de 142.250.201.78? Porque por debajo ocurre lo siguiente:

1. El navegador agarra el nombre que le has indicado
2. Consulta con un DNS a qué IP corresponde dicho nombre
3. Una vez se la da, ya hace la petición a la IP, pues era lo que necesitaba en primer lugar

Algo curioso con los DNS es que en realidad no existe un sólo DNS todo poderoso que te ubica cualquier dominio, si no que hay varios de ellos, y muchas veces pasa que tu navegador le consulta a un DNS que no conoce el dominio, pero sabe qué DNS _podría saberlo_, y te redirige a él. Esto puede ocurrir varias veces en una sola consulta

## ¿Qué es un navegador y cómo funciona?
Es un programa que te ayuda a navegar por Internet. Entiende el código del que están hechas las webs y lo renderiza, de forma que te enseña una foto en vez de una etiqueta `<img>`, y así con todo lo demás

Esa es su cualidad básica digamos, pero los navegadores modernos tienen más features para facilitar la vida del usuario, como los marcadores, las pestañas, las extensiones...
