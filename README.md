# Amoria - Micro-Social Platform

## 📖 Descriere
**Amoria** este o platformă de tip **micro-rețea socială**, dezvoltată în **C# și ASP.NET Core**, care oferă utilizatorilor posibilitatea de a interacționa, crea conexiuni și distribui conținut, într-un mediu intuitiv și sigur. Inspirată de platforme precum Facebook și Instagram, **Amoria** pune accent pe **gestionarea vizibilității profilului, interacțiunea prin postări, comentarii, grupuri private și relații de prietenie**.

Acest proiect a fost realizat în cadrul materiei **Dezvoltarea Aplicațiilor Web**, respectând cerințele impuse și implementând toate funcționalitățile esențiale. **Echipa noastră a lucrat colaborativ, utilizând Trello pentru gestionarea task-urilor și Google Meet, Discord și WhatsApp pentru comunicare eficientă.**

---

## 🚀 **Funcționalități implementate**
### 👤 **Gestionarea utilizatorilor**
 **Trei tipuri de utilizatori:**
   -  Vizitator neînregistrat
   -  Utilizator înregistrat
   -  Administrator (control total asupra conținutului platformei)
       - **Creare și editare profil personal** *(nume, descriere, poza de profil, vizibilitate public/privat)*
       - **Căutare utilizatori după nume complet sau părți din nume**
       - **Vizualizarea profilurilor private doar cu informații de bază (nume, descriere, imagine profil)**
       - **Sistem de cereri de prietenie (follow), în funcție de vizibilitatea profilului**

### 📢 **Postări și interacțiuni**
- **Creare, editare și ștergere postări** *(text, imagini, video embedded)*
- **Comentarii la postări, editabile și șterse doar de proprietar**
- **Administratorul poate șterge conținut inadecvat**

### 👥 **Grupuri și comunicare**
- **Crearea și administrarea grupurilor** *(denumire, descriere, moderator)*
- **Alăturarea la grupuri doar cu cont activ și aprobat de moderator**
- **Mesaje private în grupuri, editabile doar de autor**
- **Posibilitatea de a părăsi grupurile sau a fi eliminat de moderator**

---

## 🛠 **Tehnologii utilizate**
- **C# & ASP.NET Core** - Backend robust și scalabil
- **Entity Framework Core** - Gestionarea bazei de date
- **SQL Server** - Stocarea datelor utilizatorilor
- **Bootstrap & CSS** - Interfață modernă și responsive
- **JavaScript & jQuery** - Funcționalități dinamice pe frontend

---

## 🎯 **Metodologie & Organizare**
 **Planificare prin sprinturi** – Fiecare etapă a fost organizată în sprinturi săptămânale, cu scopuri clar definite:
- **Săptămâna 1** – Diagrama ER, clarificarea cerințelor, setarea mediului
- **Săptămâna 2-3** – Dezvoltarea modelelor și controllerelor
- **Săptămâna 4-5** – Implementarea interfeței și testare

📌 **Utilizarea Trello pentru organizare** – Am urmărit progresul și ne-am distribuit task-urile echitabil.

🗣️ **Comunicare eficientă** prin **Google Meet, Discord, WhatsApp** – Am lucrat sincronizat, discutând dificultățile și soluțiile în timp real.

🎨 **Branding & Identitate** – Am realizat un **logo personalizat** pentru Amoria, adăugând un plus de profesionalism proiectului.

---

## 📌 **Provocări și soluții**
 **Inițial, am încercat să folosim Docker**, însă am întâmpinat dificultăți tehnice care ne-au făcut să revenim la o abordare clasică pentru a ne eficientiza munca.

 **Implementarea grupurilor și gestionarea relațiilor între utilizatori** – A necesitat o abordare iterativă, ajustând codul în funcție de testări și feedback.

 **Optimizarea bazei de date și gestionarea relațiilor între modele** – Am folosit tehnici eficiente de indexare și relaționare pentru a optimiza performanța.

---

## 🔧 **Cum se rulează proiectul**
1. **Clonează repository-ul:**
   ```sh
   git clone https://github.com/utilizatorul-tau/Amoria.git
   ```
2. **Navighează în folderul proiectului:**
   ```sh
   cd Amoria
   ```
3. **Instalează dependențele și rulează serverul:**
   ```sh
   dotnet restore
   dotnet run
   ```
4. **Accesează aplicația în browser:**
   ```
   http://localhost:5000
   ```

---

## 🎓 **Experiență de învățare și concluzii**
 Acest proiect a fost mai mult decât o cerință academică – ne-a oferit **oportunitatea de a lucra în echipă, de a ne organiza eficient și de a implementa o aplicație complexă, similară cu rețelele sociale moderne.**

💡 **Ne-am dezvoltat abilități esențiale precum:**
- Lucru colaborativ într-un mediu structurat
- Utilizarea unui framework backend performant (**ASP.NET Core**)
- Gestionarea bazelor de date relaționale cu **Entity Framework Core**
- Implementarea principiilor **MVC (Model-View-Controller)**

📌 **Toate funcționalitățile cerute au fost implementate cu succes și am învățat cum să abordăm provocările tehnice în mod profesionist.**

🔹 **Acesta este doar începutul – Amoria reprezintă o platformă în continuă dezvoltare, iar posibilitățile de extindere sunt nelimitate!** 🚀



