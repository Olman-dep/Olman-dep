<div align="center">

<img src="./banner.svg" width="100%" alt="Olman Zapata - banner pixel art"/>

<a href="https://github.com/Olman-dep">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=900&color=A78BFA&center=true&vCenter=true&width=700&lines=Desarrollador+Backend+%26+Full+Stack;Java+%7C+Spring+Boot+%7C+Python+%7C+TypeScript+%7C+React;An%C3%A1lisis+de+datos+descriptivo%2C+predictivo+y+prescriptivo" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/olman-alejandro-zapata-florez-863123353/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/Olman-dep">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>

<br/>

## 👋 Sobre mí

Soy **Olman Zapata**, de **Medellín, Antioquia, Colombia** 🇨🇴. Desarrollador de Software **Backend & Full Stack** con experiencia en desarrollo de **APIs**, **aplicaciones web** y **automatización de procesos**. Trabajo con **Java, Spring Boot, Python, TypeScript y React**, y me enfoco en crear soluciones eficientes, mantenibles y orientadas a resultados.

Además del desarrollo, tengo una base sólida en **análisis de datos**: manejo grandes volúmenes de información y trabajo con **análisis descriptivo, predictivo y prescriptivo**, para pasar de "qué pasó" a "qué va a pasar" y "qué deberíamos hacer".

- 🔭 Construyo APIs REST, motores de predicción y pipelines de datos
- 📊 Limpio, transformo y analizo datos con Python, SQL y Power BI
- 🌱 Sigo profundizando en TypeScript, arquitectura de software y buenas prácticas
- 💬 Pregúntame sobre programación, lógica, datos y proyectos
- 📫 Contáctame por [LinkedIn](https://www.linkedin.com/in/olman-alejandro-zapata-florez-863123353/)

<br/>

## 🧠 Análisis de datos

| Enfoque | Qué hago |
| --- | --- |
| **Descriptivo** | Limpieza, exploración y dashboards para entender qué está pasando (Python, SQL, Power BI) |
| **Predictivo** | Modelos probabilísticos y estadísticos para estimar lo que puede ocurrir (Poisson, simulación Monte Carlo) |
| **Prescriptivo** | Convertir los hallazgos en acciones concretas: qué cambiar, dónde y cuándo |
| **Grandes volúmenes** | Procesamiento con pandas/NumPy, consultas optimizadas (CTEs, Window Functions), pre-cálculo de agregados e índices |

<br/>

## 🛠️ Tecnologías

<div align="center">

**Backend y Full Stack**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Datos y bases de datos**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Herramientas**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

</div>

<br/>

## 🚀 Proyectos destacados

### ⚽ [ApiFootbalEDZAP](https://github.com/Olman-dep/ApiFootbalEDZAP): Backend de pronósticos deportivos

Backend en **NestJS (TypeScript) + MongoDB** para una plataforma de analítica deportiva. Expone una API REST que genera pronósticos probabilísticos (goles, córners, tiros, props de jugadores) con un motor **Poisson + Monte Carlo** y los compara contra cuotas de mercado para calcular el **Expected Value (EV)**.

- Ingesta de datos por **scraping** (cheerio / Playwright) o por **APIs de fútbol**, intercambiables mediante *providers* de Nest
- Ingesta desacoplada del request con jobs periódicos (`@nestjs/schedule` / BullMQ + Redis): los endpoints siempre leen de Mongo
- Autenticación **JWT**, planes Free/Premium, documentación **Swagger** y tests con Jest + Supertest

`NestJS` `TypeScript` `MongoDB` `Poisson` `Monte Carlo` `JWT` `Swagger`

### 📊 [prueba-técnica-LikeU](https://github.com/Olman-dep/prueba-t-cnica-LikeU): Análisis de datos de una campaña de WhatsApp

Caso técnico de analista de datos para un BPO: procesar datos transaccionales crudos de una campaña de WhatsApp para encontrar por qué fallaban las entregas y por qué los asesores estaban saturados.

- **Python (pandas):** limpieza estructural, parsing de JSON (errores y plantillas), clasificación de mensajes en *Soporte / Queja / Pedido* y carga a **MySQL** con SQLAlchemy
- **SQL:** funnel de entrega, SLA de respuesta y curva de calor horaria usando **CTEs y Window Functions**
- **Power BI:** dashboard interactivo con filtros por fecha y estado, con diseño previo en Figma
- **Visión de negocio:** diagnóstico con acciones sugeridas y propuesta de escalabilidad de bajo costo (data marts, modo Import, indexación)

`Python` `pandas` `SQL` `MySQL` `Power BI` `Jupyter`

### 🧩 Otros

<div align="center">

<a href="https://github.com/Olman-dep/AngularInventory">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Olman-dep&repo=AngularInventory&theme=tokyonight&hide_border=true&bg_color=0b0d2a" alt="AngularInventory"/>
</a>

</div>

<br/>

## 📈 Estadísticas

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Olman-dep&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b0d2a" alt="stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Olman-dep&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b0d2a" alt="top langs"/>

</div>

<br/>

<div align="center">

✨ *"El espacio es grande, pero el código nos permite explorarlo."* ✨

</div>

<img src="./footer.svg" width="100%" alt="footer pixel art"/>
