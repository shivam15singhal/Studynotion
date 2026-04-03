📚 StudyNotion – EdTech Platform (MERN Stack)

StudyNotion is a full-stack EdTech platform where instructors can create and manage courses, and students can explore, purchase, and learn from them. It replicates real-world learning platforms with authentication, payments, and dashboards.

🚀 Features

👨‍🎓 Authentication
User registration & login system
Role-based access (Student / Instructor)
Secure authentication using JWT

📚 Course Management
Instructors can:
Create courses
Edit & delete courses
Upload course content

🛒 Course Purchase
Students can:
Browse available courses
Purchase courses securely
Access enrolled courses

💳 Payment Integration
Integrated Razorpay Payment Gateway
Secure checkout system

📊 Dashboard
Student Dashboard:
Enrolled courses
Instructor Dashboard:
Manage courses
View created content

🛠️ Tech Stack
Frontend:
React.js
Tailwind CSS
Axios
Backend:
Node.js
Express.js
Database:
MongoDB
Other Tools:
Razorpay API
JWT Authentication
Cloudinary (for media uploads, if used)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/studynotion.git
cd studynotion
2️⃣ Setup Backend
cd backend
npm install

Create a .env file:

PORT=5000
MONGODB_URL=your_mongodb_connection
JWT_SECRET=your_secret_key
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret

Run backend:
npm run dev

3️⃣ Setup Frontend
cd frontend
npm install
npm start

🌐 API Endpoints (Sample)
Method	Endpoint	Description
POST	/api/auth/register	Register user
POST	/api/auth/login	Login user
GET	/api/courses	Get all courses
POST	/api/courses	Create course
POST	/api/payment	Handle payment


🎯 Learning Outcomes
Built a complete MERN stack application
Implemented authentication & authorization
Integrated real payment system (Razorpay)
Learned REST API design & architecture
Improved frontend-backend integration skills
