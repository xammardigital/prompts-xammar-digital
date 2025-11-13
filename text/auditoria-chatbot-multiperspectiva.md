```
<context>
Projecte: Xatbot a WhatsApp per a app de gestió de fisioterapeutes.
Funció actual: Agendament de cites, consultes.
Objectiu: Optimitzar el flux conversacional actual per a una màxima intuïció i un mínim esforç de l'usuari.
</context>

<input_data>
## Transcripció de la Conversa (Usuari/Agent)
Usuario: "Hola"
Agente: "👋 ¡Hola! Estamos encantados de ayudarte. Para comenzar, por favor elige el idioma en el que quieres que te hablemos. Solo tienes que seleccionar el número correspondiente:
1 Català
2 Castellano
3 English
4 Euskera"

Usuario: "2"
Agente: "¡Perfecto! Hemos configurado el idioma en Español. ¿En qué estás interesad@ o qué te gustaría hacer ahora?"

Usuario: "Quiero pedir cita para un fisioterapeuta"
Agente: "¿Necesitas una ecografía con tu fisioterapia?"

Usuario: "No"
Agente: "Aquí tienes algunos terapeutas que podrían acompañarte en tu proceso: 🧘‍♀🧘‍♂

G. López

J. Urrutia

L. Russano

S. Sanchez

Elige el terapeuta con quien te sientas más cómodo o di 'indiferente' si no tienes preferencia."

Usuario: "Indiferente"
Agente: "Para el servicio seleccionado (FISIOTERAPIA), le mostramos fechas disponibles para su reserva:

Miércoles 12/11/2025

Jueves 13/11/2025
Si prefiere una fecha diferente o tiene alguna restricción, no dude en indicárnoslo para ajustar las opciones."

Usuario: "1"
Agente: "Las horas libres que he encontrado para el servicio FISIOTERAPIA son:

20:00 con L. Russano
¿Quieres alguna de estas horas o prefieres cambiar de día?"

Usuario: "1"
Agente: "Perfecto, para confirmar tu sesión de FISIOTERAPIA con INDIFERENTE el 12/11/2025 a las 20:00, por favor indícanos tu nombre y apellidos para finalizar la reserva."

Usuario: "Fernando Alonso"
Agente: "🎉 ¡Listo! Tu reserva se ha realizado correctamente. Gracias por confiar en nosotros, Fernando Alonso. Nos vemos muy pronto para tu sesión."

Usuario: "Adeu"
Agente: "¡Hola! Bienvenido a Fisioterapia Deportiva. ¿En qué podemos ayudarte? ¿Te gustaría reservar una cita o saber más sobre nuestro centro?"

Usuario: "Quiero saber mas"
Agente: "¡Hola! En Fisioterapia Deportiva estamos aquí para ayudarte. ¿En qué podemos asistirte? ¿Te gustaría reservar una cita o saber más sobre nuestro centro?"

Usuario: "Quiero saber más sobre el centro"
Agente: "El centro Fisioterapia Deportiva es un centro de fisioterapia moderno en Mataró especializado en rehabilitación deportiva y tratamiento de lesiones para todas las edades, utilizando tecnología de vanguardia a precios asequibles. Nos encontramos en Baixada de les Espenyes 6, 1a Planta, 08301 Mataró, España. Nuestro horario de atención es de lunes a viernes de 9:00 a 21:00, y estamos cerrados los sábados, domingos y festivos. Para más información, puedes contactarnos al teléfono 666 66 66 66 o enviar un correo electrónico a info@fisioterapiadeportiva.cat"

Usuario: "Perfecto, gracias"
Agente: "¡De nada! Si tienes más preguntas sobre el centro, no dudes en preguntar."
</input_data>

<role>
Ets un comitè d'experts multidisciplinari fusionat en una única entitat. Els teus components són:
- Alex, Desenvolupador de Xatbot: Enfocat en la lògica, l'eficiència del flux i la gestió d'estats.
- Ben, Especialista en Integració d'API: Avalua des de les limitacions i capacitats de l'API de WhatsApp i la sincronització de dades.
- Clara, Dissenyadora d'UX Conversacional: Centrada en el viatge de l'usuari, la fricció, la claredat i les heurístiques d'usabilitat.
- Diana, Experta en IA/PLN: Analitza el reconeixement d'intencions, l'extracció d'entitats i els errors de comprensió.
El teu estil és analític, col·laboratiu i orientat a solucions accionables.
</role>

<task>
1.  **Anàlisi Individual:** Revisa la transcripció proporcionada a `<input_data>` des de la perspectiva única de cada rol (Alex, Ben, Clara, Diana).
2.  **Simulació de Crítica:** Condueix una "reunió" interna on sintetitzis les troballes de cada expert. Identifica punts de fricció, bucles lògics, errors de comprensió i barreres tècniques observades a la transcripció.
3.  **Consolidació:** Estructura els resultats de la crítica en un informe unificat de millores. Prioritza les accions segons el seu impacte en l'experiència d'usuari i la seva viabilitat tècnica.
</task>

<output_format>
Informe en Markdown amb la següent estructura exacta:

# Informe d'Optimització del Flux Conversacional

## 1. Resum Executiu
Síntesi dels problemes crítics i 3 recomanacions principals.

## 2. Anàlisi Multidisciplinària
### 2.1. Lògica i Flux (Alex)
- Punts de trencament en la conversa.
- Ineficiències en la recopilació de dades.

### 2.2. Integració i Sincronia (Ben)
- Collarets d'ampolla o avantatges per l'API.
- Errors en la consistència de les dades (ex. disponibilitat).

### 2.3. Experiència d'Usuari (Clara)
- Punts d'alta fricció per a l'usuari.
- Ambigüitat en els missatges del bot.

### 2.4. Comprensió Lingüística (Diana)
- Errors recurrents d'interpretació d'intencions.
- Errors en l'extracció d'entitats (dates, noms).

## 3. Pla d'Acció Prioritzat
Llista numerada de millores concretes i accionables, ordenades per impacte.
1. [Millora 1: Descripció]
2. [Millora 2: Descripció]
...
</output_format>

<constraints>
- Omet formalitats i salutacions. Ves directe a l'anàlisi.
- Les recomanacions han de ser directives i específiques, no abstractes.
- Basa tota l'anàlisi estrictament en la transcripció proporcionada a `<input_data>`.
- Mantingues la veu i la perspectiva de cada rol a la secció 2.
</constraints>
```
