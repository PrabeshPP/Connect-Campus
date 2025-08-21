# ConnectCampus

> A localized student-to-student support platform.  
> Post tasks, find help, and make college life easier.  

[View on Devpost →](https://devpost.com/software/connectcampus)

---

## 🌟 Inspiration
College students often juggle overwhelming academic and daily responsibilities. Inspired by this challenge, we created **ConnectCampus**—a platform like TaskRabbit, but tailored for the unique needs of students in college communities.  

---

## 💡 What It Does
- Students can **post tasks** they need help with (academic or daily chores).  
- Other students can **offer services** and connect instantly.  
- Focused on **local and efficient collaboration** within the college ecosystem.  

---

## 🛠 How We Built It
- **Frontend:** React.js + Ant Design (AntD) for a clean and intuitive UI.  
- **Backend:** Express.js with a REST API.  
- **Database:** PostgreSQL with Prisma ORM for streamlined queries.  
- **Auth:** Secure login and user management using Auth0.  

---

## 🚧 Challenges We Faced
- Learning and implementing a new tech stack during a **36-hour hackathon**.  
- Building a functional, integrated platform under strict time constraints.  

---

## 🎉 Accomplishments
- Delivered a **working platform** within the hackathon timeline.  
- Successfully connected two sides of the platform: task posters and helpers.  
- Gained hands-on experience in **rapid prototyping** with modern tools.  

---

## 📚 What We Learned
- The importance of **adaptability** and quick learning under pressure.  
- How to **design for niche audiences** by focusing on student-specific needs.  
- Value of **collaborative problem-solving** in high-stakes environments.  

---

## 🚀 What’s Next
- Expand to **colleges nationwide**.  
- Diversify service categories (academic, errands, creative projects, etc.).  
- Partner with **universities and student organizations**.  
- Build a **mobile app** for better accessibility and engagement.  

---

## 🏁 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) installed.  
- [PostgreSQL](https://www.postgresql.org/) running locally or via a service like [Render](https://render.com).  

### Installation
```bash
# Clone the repo
git clone https://github.com/yourusername/connectcampus.git
cd connectcampus

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Run the backend
npm run server

# Run the frontend
npm start
