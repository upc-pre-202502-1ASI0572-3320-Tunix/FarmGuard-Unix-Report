
### 6.2.2 Sprint 2

#### 6.2.2.1 Sprint Planning 2

A continuación se presenta la planificación del Sprint 2, enfocado en ampliar las capacidades del MVP de FarmGuard mediante la integración de módulos IoT, el desarrollo de la app móvil en Dart (Flutter) y la mejora del diseño de la interfaz web.
En esta iteración se trabajará en la conexión con dispositivos de monitoreo en campo, la implementación de funcionalidades clave en la aplicación móvil y la optimización de la experiencia de usuario en la Landing Page y la WebApp, manteniendo la integración con el backend basado en .NET 8.

| Sprint #                             | Sprint 2                                                                                                                                                                                                                                                                                                                                                              |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint planning <br> background**  |                                                                                                                                                                                                                                                                                                                                                                       |
| **Date**                             | 2025/11/10                                                                                                                                                                                                                                                                                                                                                            |
| **Time**                             | 5:00 PM                                                                                                                                                                                                                                                                                                                                                               |
| **Location**                         | Llamada grupal en la plataforma Discord                                                                                                                                                                                                                                                                                                                               |
| **Prepared By**                      | Brayan Smith Morales Quispe                                                                                                                                                                                                                                                                                                                                           |
| **Attendees <br> (to planning meeting)** | José Daniel Zárate Castro, Brayan Smith Morales Quispe, Oscar Nathaniel Garayar Mori, Quique Vladimir Jara Benites y Carlos Alberto Ochoa Colonio                                                                                                                                                                                                                    |
| **Sprint Goal & User Stories**       |                                                                                                                                                                                                                                                                                                                                                                       |
| **Sprint 2 Goal**                    | Ampliar las capacidades del MVP de **FarmGuard** mediante: <br> - La integración de un módulo **IoT** para el monitoreo en tiempo real de la ubicación y el estado del ganado. <br> - El desarrollo de una **app móvil** en **Dart (Flutter)** que permita el registro y la consulta rápida de información sanitaria y productiva en campo. <br> - La mejora del **diseño y la experiencia de usuario** de la Landing Page y la WebApp. <br> Este sprint busca fortalecer la solución actual, facilitando el uso de la plataforma desde dispositivos móviles y aprovechando datos de IoT para una gestión más ágil y confiable. |
| **Sprint 2 Velocity**                | 24                                                                                                                                                                                                                                                                                                                                                                    |
| **Sum of story points**              | 24                                                                                                                                                                                                                                                                                                                                                                    |


#### 6.2.2.2 Aspect Leaders and Collaborators

El siguiente LACX (Leadership-and-Collaboration Matrix) identifica a los líderes y colaboradores en los principales aspectos abordados durante el Sprint 1, considerando los componentes clave del producto: Landing Page, WebApp y Backend.

<div style="font-size:70%;">

| **Team Member** <br> Last Name, First Name | **GitHub Username** | **Landing Page** <br> L/C | **WebApp (Frontend)** <br> L/C | **Backend (.NET 8)** <br> L/C | **Database / ORM** <br> L/C | **Deployment & DevOps** <br> L/C | **Documentation / Report** <br> L/C |
|:------------------------------------------:|:-------------------:|:--------------------------:|:-------------------------------:|:-----------------------------:|:----------------------------:|:---------------------------------:|:----------------------------------:|
| **Zárate Castro, José Daniel**             | danielzarate20      | C                         | L                              | C                            | C                           | C                                | C                                 |
| **Morales Quispe, Brayan Smith**           | brayan-smithmq      | L                         | C                              | C                            | L                           | C                                | L                                 |
| **Garayar Mori, Oscar Nathaniel**          | oscargarayar        | C                         | C                              | L                            | C                           | C                                | C                                 |
| **Jara Benites, Quique Vladimir**          | quiquevladimir      | C                         | C                              | C                            | C                           | L                                | C                                 |
| **Ochoa Colonio, Carlos Alberto**          | carlosochoac        | C                         | L                              | C                            | C                           | C                                | C                                 |

</div>

<div style="text-align: center; font-size:85%; margin-top: 0.5rem;">

**Nota.** L = *Leader* (responsable principal del aspecto).  
C = *Collaborator* (apoya el desarrollo del aspecto).

</div>


#### 6.2.2.3 Sprint Backlog 2

El Sprint Backlog 1 fue construido a partir del Product Backlog priorizado, incluyendo las historias de usuario correspondientes a las funcionalidades principales de gestión y visualización. 
Cada historia contiene sus tareas (work-items), descripciones, estimaciones y responsables designados.

<table>
    <tr>
        <td><b>Sprint #</b></td>
        <td colspan="7"><b>Sprint 2</b></td>
    </tr>
    <tr>
        <td colspan="2"><b>User Story</b></td>
        <td colspan="2"><b>Work-Item / Task</b></td>
        <td><b>Description</b></td>
        <td><b>Estimation (Hours)</b></td>
        <td><b>Assigned To</b></td>
        <td><b>Status</b></td>
    </tr>
    <tr>
        <td><b>Id</b></td>
        <td><b>Title</b></td>
        <td><b>Id</b></td>
        <td><b>Title</b></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> <!-- Mobile - listado y detalle -->
    <tr>
        <td>US11</td>
        <td>Consultar animales desde la app móvil</td>
        <td>T13</td>
        <td>Implementar vistas principales en Flutter</td>
        <td>Desarrollar en Dart las pantallas de login, listado y detalle de animales consumiendo el backend existente.
        </td>
        <td>8</td>
        <td>Brayan / José</td>
        <td>In-Process</td>
    </tr> <!-- Mobile - historial sanitario -->
    <tr>
        <td>US12</td>
        <td>Visualizar historial sanitario en móvil</td>
        <td>T14</td>
        <td>Diseñar módulo de historial médico en app</td>
        <td>Crear vistas en Flutter para mostrar diagnósticos, vacunas y tratamientos de cada animal, con navegación
            intuitiva.</td>
        <td>7</td>
        <td>Brayan / Carlos</td>
        <td>To-do</td>
    </tr> <!-- IoT - prototipo en Wokwi -->
    <tr>
        <td>US13</td>
        <td>Simular dispositivo IoT de rastreo</td>
        <td>T15</td>
        <td>Configurar prototipo en Wokwi</td>
        <td>Crear un prototipo en Wokwi (p. ej. ESP32) que envíe datos de ubicación simulada al backend de FarmGuard.
        </td>
        <td>6</td>
        <td>Oscar / Quique</td>
        <td>In-Process</td>
    </tr> <!-- IoT - visualización en mapa web -->
    <tr>
        <td>US14</td>
        <td>Visualizar posiciones IoT en la WebApp</td>
        <td>T16</td>
        <td>Integrar datos IoT en el mapa web</td>
        <td>Consumir los datos del prototipo IoT y mostrarlos en el mapa web con indicadores de ubicación y estado
            básico del animal.</td>
        <td>6</td>
        <td>José / Oscar</td>
        <td>To-do</td>
    </tr> <!-- Mejora de vistas web -->
    <tr>
        <td>US15</td>
        <td>Mejorar diseño de vistas web</td>
        <td>T17</td>
        <td>Refactorizar UI de dashboard y landing</td>
        <td>Actualizar estilos, jerarquía visual y diseño responsive de la Landing Page y el dashboard de la WebApp para
            mejorar la experiencia de usuario.</td>
        <td>7</td>
        <td>Carlos / Quique</td>
        <td>In-Process</td>
    </tr>
</table>


#### 6.2.2.4 Development Evidence

A continuación se presenta un resumen de los commits realizados durante el Sprint 2, evidenciando el progreso en las diferentes áreas del proyecto FarmGuard.
| Repository | Commit | Author | Date | Message |
| :--- | :--- | :--- | :--- | :--- |
| repository | `128691b` | Brayan Smith | 2025-11-15 | fix: fixed screen mobile |
| repository | `7d9e9de` | Brayan Smith | 2025-11-14 | fix: change url image view |
| repository | `24d7114` | Brayan Smith | 2025-11-14 | fix: fixed upload image |
| repository | `8d74014` | Brayan Smith | 2025-11-14 | Merge origin/feature/animals-crud: resolve import conflicts |
| repository | `105b000` | QuiqueVladimir | 2025-11-14 | merge: integrate disease\_diagnosis, treatments, vaccines from main |
| repository | `c4994a9` | Brayan Smith | 2025-11-14 | Merge remote-tracking branch 'origin/feature/settings-page' into feature/mobile |
| repository | `f3f2690` | QuiqueVladimir | 2025-11-14 | feat: redirect home |
| repository | `39dd10d` | QuiqueVladimir | 2025-11-14 | feat: add dialog animal |
| repository | `2662c96` | QuiqueVladimir | 2025-11-14 | feat: add url iot |
| repository | `1e894a5` | Brayan Smith | 2025-11-14 | fix: fixed dependencies and remove html |
| repository | `3b7083b` | Brayan Smith | 2025-11-14 | fix: fixed send of data system |
| repository | `0a868c2` | Brayan Smith | 2025-11-14 | feat: initial commit |
| repository | `5f15d87` | QuiqueVladimir | 2025-10-30 | feat: add deprecated code corrected |
| repository | `c5782f2` | QuiqueVladimir | 2025-10-30 | feat: add clinical history |
| repository | `fa01122` | QuiqueVladimir | 2025-10-29 | feat: add animals components |
| repository | `45b23f8` | Oscar Garayar | 2025-10-18 | profile y settings |
| repository | `085b4bf` | Vladimir Jara Benites | 2025-10-18 | Remove README content and add edit note |
| repository | `b147ad5` | QuiqueVladimir | 2025-10-18 | initial commit |

| Repository   | Commit   | Author       | Date       | Message                        |
|--------------|----------|--------------|------------|--------------------------------|
| repository   | 3b7083b  | Brayan Smith | 2025-11-14 | fix: fixed send of data system |
|              | 0a868c2  | Brayan Smith | 2025-11-14 | feat: initial commit           |

#### 6.2.2.5 Testing Suite Evidence

Se realizaron las siguientes pruebas unitarias para validar las funcionalidades implementadas durante el Sprint 2.

**Pruebas unitarias**
<img alt="Image" src="https://github.com/user-attachments/assets/a3be5446-7afa-4f11-9aac-792c2040eae2" />

<img alt="Image" src="https://github.com/user-attachments/assets/61a4bbc0-5289-4d74-9e4a-19dd237d0655" />

<img alt="Image" src="https://github.com/user-attachments/assets/d75c488a-3537-467e-83fd-69230f50b18d" />

**Resultado**
<img alt="Image" src="https://github.com/user-attachments/assets/b14c8ebb-d470-4ffa-904d-036e17b5ba1e" />

#### 6.2.2.6 Execution Evidence

# Web
Evidencia de la ejecución del sistema en los entornos configurados (capturas de pantalla, logs, URLs).
<img alt="Image" src="Assets/img/ChapterVI/AZ1.jpeg">
<img alt="Image" src="Assets/img/ChapterVI/GIT2.jpeg">

# Mobile
Evidencia de la ejecución del sistema en los entornos configurados

<img alt="Image" src="Assets/img/ChapterVI/mob3.jpeg">
<img alt="Image" src="Assets/img/ChapterVI/mobile2.jpeg">

# Iot

<img alt="Image" src="Assets/img/ChapterVI/wok1.jpeg">

# Landing Page

Link de página desplegada: [https://upc-pre-202502-1asi0572-3320-tunix.github.io/FarmGuard-LandingPage/](https://upc-pre-202502-1asi0572-3320-tunix.github.io/FarmGuard-LandingPage/)

#### 6.2.2.7 Services Documentation Evidence

<img alt="Image" src="https://github.com/user-attachments/assets/2ed6dd38-dbd5-463b-896a-ef7143aa0485" />

<img alt="Image" src="https://github.com/user-attachments/assets/5242d684-de2b-4255-8027-bff94ff6ad8b" />

<img alt="Image" src="https://github.com/user-attachments/assets/bf0608cb-b28c-4a20-b521-b23220e24bb2" />

#### 6.2.2.8 Software Deployment Evidence

<img alt="Image" src="Assets/img/ChapterVI/AZ2.jpeg">
<img alt="Image" src="Assets/img/ChapterVI/GIT1.jpeg">

URL de la Landing Page desplegada: [https://ambitious-dune-0b50cbb10.1.azurestaticapps.net/auth/sign-in](https://ambitious-dune-0b50cbb10.1.azurestaticapps.net/auth/sign-in)

URL de la Mobile desplegada: [https://calm-forest-08b0d0210.3.azurestaticapps.net/](https://calm-forest-08b0d0210.3.azurestaticapps.net/)

URL de la Swagger desplegada: [https://www.ibrayan.dev/swagger/index.html](https://www.ibrayan.dev/swagger/index.html)

#### 6.2.2.9 Team Collaboration Insights

<img alt="Image" src="https://github.com/user-attachments/assets/f2ce903e-d1cc-4902-8393-aaad8d408d15" />

---