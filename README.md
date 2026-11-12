# REPO projecte-smx2c-2026-2027

Llista de projectes d'SMX2C del curs 2026-2027.

  - [FerroNetwork](#FerroNetwork), [ferronetwork.cat](https://ferronetwork.cat)
  - [GymZero](#GymZero), [gymzero.cat](https://gymzero.cat)
  - [RetroArcade](#RetroArcade), [retroarcade.cat](https://retroarcade.cat)
  - [Ro-Chess](#Ro-Chess), [ro-chess.cat](https://ro-chess.cat)
  - [Katal](#Katal), [katal.cat](https://katal.cat)

### [FerroNetwork](https://github.com/LGZV1/projecte-smx2c-2026-2027/tree/Lucas-Y-Santi)

Santi Osella y Lucas Gagliano · SMX2 · INS Palamós
![Ferronetwork](image.png) 

#### 1. De què va el projecte
FerroNetwork es una compañia a gran escala que que se encarga de el servicios de seguridad y ciberseguridad centrado en el ambito tecnologico y fisico de la seguridad, para demostarr como funciona la compañia les mostarremos como funciona internamente FerroNetwork

El sistema que implementamos se llama "eye hunter" es un conjunto de normas junto a medidas de seguridad para evitar muchos problemas de brechas de seguridad (fisicas/digitale) o filtraciones de informacion relevante aparte de garantizar algunas medidas de defensa fisicas tecnologicas avanzadas conectadas con la red. Este sistema cumple los requisitos necesarios para dar una mayor seguridad a tus distritos y a tu red empresarial. 

Por el lado digital lo principal que tenemos para la empresa es una Intraned que da a servidores la posibilidad de que puedan compartir informacion entre ellos y que solo se puedan conectar usuarios especificos desde un sitio permitido por su empresa ya sea: paises, pueblos ciudades o zonas más concretamente distritos o edificios.

Cosas que no incluye el proyecto, la forma de trabajo de los trabajadores no es parte de nuestra responsabilidad como empresa ya que nosotros nos encargamos de proteger y asegurar la informacacion aparte brindando algunas herramientas pero no optimizamos la forma de trabajar de la gente ni el orden de los trabajadores o en cambio si la empresa necesita ayuda por cualquier tema de seguridad o que necesiten una explicacion para los trabajadores podremos ofrecer un pequeño curso y aparte os pdf de instrucciones

en principio lo no habria nada posteriro y en otras empresas depende de la forma de trabajar ya podriamos adaptar el "eye hunter"

### 2.Cosas que abarca el proyecto de forma seccionada:

1 Una Intraned entre servidores que contiene:

## Componentes individuales del sistema

Componentes:
1A.Servidor de intranet	
2B.Base de datos	
3C.Servidor web	
4D.VPN Proton	
5E.Sistema de seguridad Huntress	
6F.Sistema de autenticación	
7G.Sistema de cifrado y hashing con SALT	
8H.Equipos informáticos	
9I.Router y firewall	
10J.Plataforma Atlassian

Tipo:
1A.Software/servidor	
2B.Software
3C.Software/servidor
4D.Software/servicio	
5E.Software/servicio	
6F.Software
7G.Software
8H.Hardware
9I.Hardware/software	
10J.Servicio cloud

Función:
1A.Permite compartir información interna.
2B.Almacena usuarios e información empresarial.
3C.Aloja la página web de FerroNetwork.
4D.Permite conexiones remotas seguras.
E5.Detecta y ayuda a responder ante amenazas en los equipos.
6F.Comprueba la identidad de los usuarios.
7G.Protege la información y las contraseñas.
8H.Ordenadores y dispositivos utilizados por los trabajadores.
9I.Gestionan y controlan las conexiones de red.
10J.Facilita la colaboración y organización del trabajo.

Componentes internos:
- Servidor de intranet.
- Base de datos empresarial.
- Sistema de autenticación.
- Equipos informáticos.
- Firewall de la red.
Componentes externos:
- Proton VPN como proveedor de servicio.
- Huntress como plataforma de seguridad.
- Atlassian como plataforma de colaboración.
- Clientes que acceden a la página web.

### DE AQUI--------------------






### LA DIAPOSITIVA 5 DEL POWERPOINT 6 COMO SE RELACIONAN QUE ES, NO ENTIENDO A QUE SE REFIERE








### HASTA AQUI-----------------------
### Quien utiliza el sistema 
Actor
1A.Administrador de sistemas	
2B.Técnico de ciberseguridad
3C.Trabajador de FerroNetwork
4D.Director de la empresa	
5E.Cliente	
6F.Proveedores externos	

Función
1A.Gestiona servidores, usuarios y permisos.
2B.Supervisa amenazas y protege la infraestructura.
3C.Utiliza la intranet y las herramientas colaborativas.
4D.Consulta información y supervisa el funcionamiento.
5E.Accede a la web para realizar solicitudes o compras.
6F.Proporcionan servicios como VPN, seguridad y almacenamiento cloud.

### Gymzero

Jan Palahí · SMX2 · INS Palamós

#### 1. De què va el projecte

GYM-ZERO és un gimnàs tradicional (fictici) que no té gairebé res de tecnologia: les reserves es fan en paper o per telèfon, els cobraments a mà i no hi ha cap sistema per guardar dades dels clients. El projecte consisteix a informatitzar-lo.

El gimnàs és inventat, però tot el que és programari sí que és real: la web, el PHP, la base de dades i el repositori de GitHub.

#### 2. On estava el projecte l'any passat

L'any passat vaig presentar el projecte i no el vaig aprovar. Els problemes principals van ser:

- Hi havia un mòdul, el LAB, que només era una idea i no estava fet. **L'he tret del projecte.**
- Les reserves es guardaven sense controlar les places, i dues persones podien reservar l'última plaça alhora.
- Els casos d'ús i la planificació estaven mal plantejats.
- La infraestructura era massa general i no hi havia topologia de xarxa.
- La memòria explicava més coses de les que estaven fetes.

Aquest curs mantinc la mateixa idea, però em centro en serveis que pugui demostrar que funcionen. Cada part del projecte la marcaré com a **implementada**, **simulada** o **dissenyada**, per deixar clar què està fet de veritat i què no.

#### 3. Què hi ha fet ara mateix

| Part | Estat | Comentari |
|---|---|---|
| Web pública (gym-zero.cat) | Implementada | HTML, CSS i JavaScript, allotjada a Dinahosting |
| Calculadores (1RM, IMC, TDEE, RPE) | Implementades | En JavaScript, dins la web |
| Formulari de reserves | Implementat (versió antiga) | PHP + MariaDB. Guarda la reserva però no controla places ni duplicats |
| Base de dades nova | Dissenyada i provada en local | 9 taules, provada a XAMPP. Encara no és a Dinahosting |
| Control de places a les reserves | Provat en local | Transacció amb `SELECT ... FOR UPDATE` |
| Registre i login d'usuaris | En curs | PHP amb sessions i contrasenyes xifrades amb `password_hash` |

#### 4. Què vull implementar aquest curs

L'esquema que vaig ensenyar al professor té dues parts: la web pública i l'àrea privada. Totes dues passen pel PHP, que és el que parla amb la base de dades.

##### 4.1 Web pública

Es manté la web que ja tinc, amb informació del gimnàs, les calculadores i les activitats. Des de les activitats es podrà anar a reservar.

##### 4.2 Usuaris

- Registre i inici de sessió.
- Dos rols: **client** i **administrador**. Cada un només pot entrar a la seva part.
- Les contrasenyes no es guarden mai en text pla.

##### 4.3 Àrea del client

- Veure les classes que té reservades i cancel·lar-les.
- Reservar una classe.
- Veure els seus avisos (reserva confirmada, classe cancel·lada...).
- Veure l'historial dels seus entrenaments a les màquines.

##### 4.4 Reserves amb control de places

Ara el client no reserva una hora qualsevol, sinó una **classe** que existeix (una activitat en un dia i una hora, amb un nombre de places).

- Un usuari no pot reservar dues vegades la mateixa classe.
- No es poden fer més reserves que places.
- Si dues persones reserven l'última plaça al mateix moment, només n'entra una. Això ho faig amb una transacció que bloqueja la classe mentre es fa la reserva.

Ja ho he provat en local amb tres usuaris reservant alhora una classe de 2 places on ja n'hi havia una d'ocupada. Sense el bloqueig, la classe acabava amb 4 reserves. Amb el bloqueig, en té 2.

##### 4.5 Panell d'administració

L'administrador podrà gestionar usuaris, activitats, classes, reserves i màquines.

##### 4.6 Màquines intel·ligents

És la part nova del projecte. La idea és que una màquina del gimnàs (per exemple, un press de banca) identifiqui el client amb una targeta RFID i reculli dades de cada sèrie: càrrega, repeticions, velocitat, recorregut i durada. Aquestes dades s'envien al servidor i el client les pot consultar.

- **La màquina física no la construiré.** La deixaré dissenyada: lector RFID, sensors, una placa ESP32 i connexió wifi.
- El que sí faré és un **simulador**, un programa que envia les mateixes dades que enviaria la màquina real.
- Les dades arriben a una **API en PHP**, que comprova que són correctes i les guarda a la base de dades.
- Amb aquestes dades, l'historial del client mostrarà coses senzilles: la velocitat mitjana de cada sèrie, quant baixa la velocitat dins la sèrie i com evoluciona d'una sessió a una altra. No faré cap conclusió mèdica.

##### 4.7 Còpies de seguretat i notificacions

- Còpies de seguretat de la base de dades amb `mysqldump`.
- Notificacions dins de l'àrea del client quan es fa o es cancel·la una reserva.

#### 5. Base de dades

Ja tinc dissenyada la base de dades nova. Les taules són:

| Taula | Què guarda |
|---|---|
| usuaris | Clients i administradors |
| activitats | Tipus d'activitat (Musculació, Cross Training...) |
| classes | Una activitat en un dia i hora, amb places |
| reserves | Qui ha reservat a quina classe |
| maquines | Les màquines intel·ligents |
| entrenaments | El dia que un usuari entrena |
| series | Cada sèrie feta en una màquina |
| repeticions | Les dades de cada repetició que envia la màquina |
| notificacions | Avisos per a l'usuari |

#### 6. Ordre de feina

1. Base de dades nova (fet en local).
2. Registre, login i àrea del client.
3. Reserves noves amb control de places.
4. Panell d'administració.
5. API PHP per a les dades de les màquines.
6. Simulador de les màquines.
7. Historial i anàlisi dels entrenaments.
8. Còpies de seguretat i notificacions.
9. Pujar-ho tot a Dinahosting i fer proves.
10. Refer la memòria, la planificació a GitHub (milestones i issues) i la presentació.

#### 7. Què queda fora

- Construir la màquina, els sensors i el lector RFID de veritat.
- Instal·lar una xarxa real al gimnàs. La xarxa la dissenyaré, amb la topologia, però no la muntaré.

### [RetroArcade](https://github.com/TeteDeiVi/RetroArcade)
#### Projecte Retro Game Club (RetroArcade.cat)
- - -
#### Que volem fer?
Volem crear un club de "Retro Gaming" on poder emular jocs antics, bloquejats i fer un club on la gent pugui pagar una subscripció perque puguin jugar a tots el jocs que estigui disponibles i proximament potser poder fer torneigos contra el usuaris, que els usuaris faguin una promoció del nostre projecte i que tinguin a canvi: (un mes de subscripció gratis...)
---
#### Que necessitem? (Abast)
  * Un software que ens permeteixi fer subscripcions per als clients (**berrly.com**)
  * Un software amb un docker que ens permeteixi pujar el nostres "ROMS" per emular els nostres jocs en una pagina web (**retroassembly.com**)
  * Un software per gestionar el club de "Retro Gaming" on podem veure els usuaris, que jugen més... (**sportmember.es**)
  * Una base de dades
  * Un software on es pugin entrar tots els clients per informar d'incidencies dels jocs... per si hi ha una actualització on afageixen un joc nou i un altre joc que ja i era peta que es pugui avisar (un tipus de discord on estigui tots els clients i els desarrolladors i pugin parlar entre ells per intentar arreglar els problemes) (**SLACK**,**berrly.com**)
---
#### Context
Volíem jugar un joc pero estava bloquejat, per això hem decidit fer aquesta pàgina web perque tot el món que no pugui jugar a aquests jocs que no estan disponibles, puguin disfrutar com nosaltres aquesta diversió de jugar als seus jocs.
###### Disseny Projecte
  ![Disseny Projecte](DissenyGraficProjecte.excalidraw.png)
 Fet per: David i Neal

### Ro-Chess https://github.com/trec24/Ro-chess


####Avasto del projecto

Context

1)

a)Alguna vegada volies jugar als escacs i aquells microsegons no tan contat per el rendiment? docs el projecte es sobre el sistema d'escacs per web

b)El projecte serveix per aconseguir una millor experiencia per als escacs
Aquest projecte


c)millora l'interfaz

2)

a) les millores son d'interfaz grafica i dona serveis com donarse de baixa


b) El sistema funciona amb un software, dockers

c) Cualsevol persona que sapiga entrar al lloc, per la rao de entreteniment o deport o per comparativa dels serveis e interficie grafica.

3)

a)

(Organizacion) 
Software para controlar a los usuarios comparado con la partida, elimina o añade los usuarios, el ajedrez sera controlado por Lichess que gestionara las reglas, el comportamiento de las piesas

El software sera para dar de baja a los clientes o insertar usuarios
El docker representara el usuario para la provacion de insercion e inicio de sesion










Contexto
Tenemos un ajedrez un club de ajedrez online, pero tenia una cierta cantidad de lag que me hacia perder 0,3 segundos por jugada haciendolo mas impresiso de lo normal

### [KATAL](https://github.com/ikeerrivass/KATAL)

![Brand LOGO](KATAL.png)
---
Katal és una marca de roba catalana que s’ha actualitzat a la moda actual.
Mostra una estètica futurista fosca però dirigida al públic català principalment, amb símbols com el llaç groc o la falç lligada amb l’himne català
---

##### COM ERA PRÈVIAMENT

La botiga era vella i no estava adaptada a l’actualitat, venia roba de llana ja que no constaba ni amb electricitat ni amb la maquinària adequada, no hi havia seguretat per això mateix, era fàcil robar les prendes…

##### QUE VOLEM IMPLEMENTAR PER MODERNITZAR LA MARCA

  * Noves instal·lacions
  * Nova pàgina web
  * Nou logo
  * Roba de diferents textures
  * Nova maquinària avançada
  * Càmeres de seguretat, alarmes a les prendes i detector d’alarmes a entrades i sortides de la botiga
  * Electricitat
  * BBDD
  * Xarxa
  * Enviament a domicili
  * Serveis de enviament de material a l’empresa
  * Unificar-ho en un ERP…
  
