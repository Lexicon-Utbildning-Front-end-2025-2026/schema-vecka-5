# 📅 Schema vecka 5

**Next.js, vecka 1 av ?**

Intro till next.js/react med grunderna från installation av Next.js till reacts komponent-tänk

---

## 📅 Måndag
Vi bygger början på en liten app. Med huvudmeny och en om-oss-sida.

### Mål för dagen
* Förstår grundstrukturen i ett Next.js App router projekt, dvs filer (pages, layout, tsx, route), mappar och sånt
* Kunna installera och köra projektet
* Förstå vad komponenter är i react
* Grundläggande routing i Next.js
* Kort om tailwind vs css modules

### E-learning
* Se del 1-4 - https://app.pluralsight.com/ilx/video-courses/nextjs-13-fundamentals/course-overview (En äldre version av Nextjs används, så det är lite skillnader mot vad vi går igenom på föreläsningarna).
* Tailwind (Frivilligt) - https://app.pluralsight.com/library/courses/tailwind-css-foundations/table-of-contents

### Läsning
* Läs fram till och med "Displaying Data" - https://react.dev/learn
* Dokumentation om Next.js installation - https://nextjs.org/docs/app/getting-started/installation
* Docs om första stegen med page.tsx och layout.tsx - https://nextjs.org/docs/app/getting-started/layouts-and-pages#creating-a-page

### Frivilligt
* Extra om man är nyfiken react docs - https://react.dev/
* Historik/bakgrund react/next.js - https://nextjs.org/learn/react-foundations/what-is-react-and-nextjs
* Struktur på Next.js projekt - https://nextjs.org/docs/app/getting-started/project-structure
* Om ni vill använda CSS Modules istället för Tailwind - https://nextjs.org/docs/app/getting-started/css


---

## 📅 Tisdag
Vi bygger en Hero-komponent för vår app.

### Mål för dagen
* Inbyggda komponenter i next.js som Image, externa bilder och next.config.ts.
* Mer om komponenter, skillnaden mellan funktioner/metoder och komponenter
* Namnkonventioner i Next.js
* Ev children/React.ReactNode

### Läsning
* Läs "Conditional Rendering" - https://react.dev/learn
* Docs om inbyggda komponenten Image - https://nextjs.org/docs/app/getting-started/images

### Övningar
Skapa er egen Hero i appen.

---

## 📅 Onsdag
Vi hämtar data från json och bygger en grid med kort från denna och props. 

### Mål för dagen
* Arbeta med interfaces i komponenter
* Förstå props i komponenter
* Parameter destructuring i komponenter

### Läsning
* Läs "Rendering lists" - https://react.dev/learn

### Övningar
Skapa komponenter för att rendera ut en grid med saker och deras detaljer

---

## 📅 Torsdag
Vi bygger sidor för varje enskilt kort med dynamic routes och params samt skapar en not found-sida

### Mål för dagen
* Förstå vad dynamic routes är och hur de fungerar
* Kunna använda params i komponenter
* Async i komponenter
* Använda notFound()

### Läsning
https://nextjs.org/docs/app/getting-started/layouts-and-pages#creating-a-dynamic-segment
https://nextjs.org/docs/app/api-reference/functions/not-found
https://nextjs.org/docs/app/api-reference/file-conventions/not-found

### Övningar
Skapa dynamisk route och en sida med detaljer för korten samt en 404-sida.

---

## 📅 Fredag

### Mål för dagen
Fördjupa förståelsen genom att granska och diskutera kod. 

**Frågor för Code Review:**

* **I grupp:**

* **Gemensamt:**


### Övningar
* **Code Review:** Gå igenom era projekt i basgrupperna.
* **Final Polish:** Använd feedbacken för att göra de sista justeringarna på ert projekt innan helgen.

---

#### Extra material för hela kursen i next.js
Allt här är bara extra och sånt vi kommer gå igenom senare i kursen. 
Det är om ni vill köra lite snabbare takt eller se hur någon annan förklarar vissa bitar. 
Obs - En del av det de visar kommer vi troligen inte ta upp alls under kursen som prisma t ex. 
* https://www.youtube.com/watch?v=PqxHnMfyCUY
* https://www.youtube.com/watch?v=KAQCHfu_3jw

### Övningar
* Skapa ett projekt och en grundläggande struktur med huvudmeny och några länkar till andra sidor/routes.

frivilliga än så länge
* finns lite olika övningar här ev. https://app.pluralsight.com/paths/skills/nextjs typ CODE LAB Guided: Foundations of Next.js 14 och CODE LAB Guided: Creating Pages, Layouts, & Routes in a Next.js Finance Application
* om man vill köra next.js dashboard (innehåller dock en del komplext) https://nextjs.org/learn/dashboard-app
