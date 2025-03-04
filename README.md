# Amoria - Micro-Social Platform  

## 📖 Description  
**Amoria** is a **micro-social network** platform, developed using **C# and ASP.NET Core**, allowing users to interact, create connections, and share content in an intuitive and secure environment. Inspired by platforms like Facebook and Instagram, **Amoria** focuses on **profile visibility management, interactions through posts, comments, private groups, and friendship relations**.  

This project was developed as part of the **Web Application Development** course, adhering to all requirements and implementing essential functionalities. **Our team worked collaboratively, using Trello for task management and Google Meet, Discord, and WhatsApp for effective communication.**  

---  

## 🚀 **Implemented Features**  
### 👤 **User Management**  
**Three types of users:**  
- Unregistered visitor  
- Registered user  
- Administrator (full control over platform content)  

**Key functionalities:**  
- **Create and edit personal profile** *(name, description, profile picture, public/private visibility)*  
- **Search users by full name or partial name**  
- **View private profiles with basic information only (name, description, profile picture)**  
- **Friend request system (follow), depending on profile visibility**  

### 📢 **Posts and Interactions**  
- **Create, edit, and delete posts** *(text, images, embedded videos)*  
- **Comment on posts, with editing and deletion allowed only for the owner**  
- **Administrator can remove inappropriate content**  

### 👥 **Groups and Communication**  
- **Create and manage groups** *(name, description, moderator)*  
- **Join groups only with an active account and moderator approval**  
- **Private group messaging, with messages editable only by the author**  
- **Ability to leave groups or be removed by a moderator**  

---  

## 🛠 **Technologies Used**  
- **C# & ASP.NET Core** - Robust and scalable backend  
- **Entity Framework Core** - Database management  
- **SQL Server** - User data storage  
- **Bootstrap & CSS** - Modern and responsive UI  
- **JavaScript & jQuery** - Dynamic frontend functionalities  

---  

## 🎯 **Methodology & Organization**  
**Sprint-based planning** – Each stage was organized into weekly sprints with clearly defined goals:  
- **Week 1** – ER diagram, requirement clarification, environment setup  
- **Weeks 2-3** – Development of models and controllers  
- **Weeks 4-5** – UI implementation and testing  

📌 **Trello for task tracking** – We monitored progress and distributed tasks fairly.  

🗣️ **Efficient communication** via **Google Meet, Discord, WhatsApp** – We worked in sync, discussing challenges and solutions in real time.  

🎨 **Branding & Identity** – We designed a **custom logo** for Amoria, adding professionalism to the project.  

---  

## 📌 **Challenges and Solutions**  
- **Initially, we tried using Docker**, but faced technical difficulties, leading us to switch to a traditional setup for better efficiency.  
- **Implementing groups and managing user relationships** required an iterative approach, refining the code based on testing and feedback.  
- **Optimizing the database and managing model relationships** – We used efficient indexing and relationship techniques to enhance performance.  

---  

## 🔧 **How to Run the Project**  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/your-username/Amoria.git
   ```
2. **Navigate to the project folder:**  
   ```sh
   cd Amoria
   ```
3. **Install dependencies and run the server:**  
   ```sh
   dotnet restore
   dotnet run
   ```
4. **Access the application in your browser:**  
   ```
   http://localhost:5000
   ```  

---  

## 🎓 **Learning Experience and Conclusions**  
This project was more than just an academic requirement – it provided **an opportunity to work as a team, organize efficiently, and develop a complex application similar to modern social networks.**  

💡 **Key takeaways:**  
- Collaborative work in a structured environment  
- Using a powerful backend framework (**ASP.NET Core**)  
- Managing relational databases with **Entity Framework Core**  
- Implementing **MVC (Model-View-Controller) principles**  

📌 **All required functionalities were successfully implemented, and we learned how to tackle technical challenges professionally.**  

🔹 **This is just the beginning – Amoria is a continuously evolving platform with limitless expansion possibilities!** 🚀
