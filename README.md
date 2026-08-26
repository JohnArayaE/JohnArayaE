<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:7C3AED&height=220&section=header&text=John%20Araya&fontSize=55&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=Full%20Stack%20Developer%20%7C%20Cloud&descSize=20&descAlignY=55"/>

<a href="https://www.linkedin.com/in/johnaraya/">
  <img src="https://img.shields.io/badge/LinkedIn-John%20Araya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:johnae1205@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Contactame-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/JohnArayaE">
  <img src="https://img.shields.io/badge/GitHub-JohnArayaE-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=JohnArayaE&style=flat-square&label=Profile+Views"/>

</div>

---

## 👨‍💻 Sobre mí

Soy **Full Stack Developer** con interés en el desarrollo de aplicaciones web, APIs, bases de datos, arquitectura de software y tecnologías **Cloud**.

Me gusta trabajar en proyectos completos, conectando diferentes capas de una aplicación: desde la interfaz y la experiencia del usuario hasta el backend, la persistencia de datos y la automatización mediante servicios en la nube.

```javascript
const john = {
  role: "Full Stack Developer",
  interests: ["Backend", "Frontend", "Databases", "Cloud"],
  currentlyWorkingWith: [
    "Vue.js",
    "Nuxt",
    "Node.js",
    "Express",
    "MongoDB",
    "AWS"
  ],
  goal: "Build useful, scalable and well-structured software"
};
```

---

# 🚀 Proyecto destacado

<div align="center">

## CommunityHub

### Plataforma Full Stack para gestión y participación en actividades y eventos

</div>

**CommunityHub** es una aplicación web completa que integra frontend, API REST, base de datos y servicios cloud.

El sistema permite administrar usuarios y actividades, manejar diferentes roles, realizar inscripciones, guardar favoritos y generar notificaciones automáticas para eventos próximos.

### ⚡ Arquitectura del sistema

```mermaid
flowchart LR
    A["💻 Nuxt + Vue<br/>Frontend"] <-->|REST API| B["⚙️ Node.js + Express<br/>Backend"]
    B <-->|Mongoose| C[("🍃 MongoDB Atlas")]

    D["☁️ Amazon<br/>EventBridge"] --> E["λ AWS Lambda"]
    E -->|Consulta eventos e inscripciones| C
    E -->|Genera recordatorios| C
```

### 🧩 Componentes

|    | Componente           | Tecnologías                                     | Repositorio                                                        |
| -- | -------------------- | ----------------------------------------------- | ------------------------------------------------------------------ |
| 💻 | **Frontend**         | Nuxt 4 · Vue 3 · TypeScript · Pinia · PWA       | [Ver Frontend](https://github.com/JohnArayaE/ProyectoWeb2_Fronted) |
| ⚙️ | **Backend API**      | Node.js · Express 5 · MongoDB · Mongoose · JWT  | [Ver Backend](https://github.com/RNVG/ProyectoWeb2_Back)           |
| ☁️ | **Cloud Automation** | AWS Lambda · Amazon EventBridge · MongoDB Atlas | [Ver Lambda](https://github.com/JohnArayaE/ProyectoWeb2_Lambda)    |

### ✨ Funcionalidades principales

* 🔐 Autenticación mediante **JSON Web Tokens**
* 👥 Roles de **usuario, organizador y administrador**
* 📅 Creación y administración de actividades
* 🎟️ Inscripción de usuarios en eventos
* ❤️ Sistema de favoritos
* 🔎 Búsqueda y filtrado de actividades
* 📊 Dashboards adaptados según el rol
* 🗃️ Persistencia mediante **MongoDB Atlas**
* 🔌 Comunicación Frontend–Backend mediante **REST API**
* 📱 Soporte **Progressive Web App**
* ☁️ Integración con **AWS**
* ⚡ Procesamiento serverless mediante **AWS Lambda**
* ⏰ Ejecuciones programadas con **Amazon EventBridge**
* 🔔 Generación automática de recordatorios para actividades próximas

---

# 🛠️ Tech Stack

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=vue,nuxt,ts,js,html,css&theme=dark"/>

### Backend & Databases

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb&theme=dark"/>

### Cloud & Tools

<img src="https://skillicons.dev/icons?i=aws,git,github,postman,vscode&theme=dark"/>

<br/>

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge\&logo=awslambda\&logoColor=white)
![Amazon EventBridge](https://img.shields.io/badge/Amazon_EventBridge-8C4FFF?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge\&logo=fastapi\&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge\&logo=jsonwebtokens\&logoColor=white)

</div>

---

# ☁️ Cloud & Backend

Una de las áreas que más me interesa es la integración entre aplicaciones tradicionales y servicios cloud.

En **CommunityHub**, Amazon EventBridge ejecuta periódicamente una función AWS Lambda que consulta MongoDB Atlas, identifica actividades que comienzan dentro de las próximas 24 horas, encuentra los usuarios inscritos y genera sus notificaciones automáticamente.

Esto permite ejecutar procesos independientemente del frontend y del backend principal.

```text
Amazon EventBridge
        │
        ▼
    AWS Lambda
        │
        ▼
  MongoDB Atlas
        │
        ├── Busca actividades próximas
        ├── Consulta usuarios inscritos
        └── Genera recordatorios
```

---

# 📊 GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=JohnArayaE&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JohnArayaE&layout=compact&theme=tokyonight&hide_border=true"/>

<br/>

<img src="https://streak-stats.demolab.com?user=JohnArayaE&theme=tokyonight&hide_border=true"/>

</div>

---

# 🌱 Actualmente

Estoy fortaleciendo mis conocimientos en:

`Full Stack Development` · `Backend Development` · `REST APIs` · `Databases` · `Cloud Computing` · `AWS` · `Software Architecture`

---

# 📫 Contacto

<div align="center">

### ¿Quieres contactarme?

📧 **[johnae1205@gmail.com](mailto:johnae1205@gmail.com)**

<br/>

<a href="mailto:johnae1205@gmail.com">
  <img src="https://img.shields.io/badge/Enviar%20correo-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/johnaraya/">
  <img src="https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/JohnArayaE">
  <img src="https://img.shields.io/badge/GitHub-Seguir-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<br/>

<div align="center">

### 💻 Building • Learning • Improving

<i>Transformando ideas en aplicaciones, una línea de código a la vez.</i>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:2563EB,100:0F172A&height=120&section=footer"/>
