# Mentors - AI Subject Mentors Platform

A platform enabling teachers to create customized AI mentors for educational support, serving as both teaching assistants and student mentors.

## 🎯 Features

### For Teachers (Admin Portal)
- Create and customize subject-specific AI mentors
- Upload course materials and curriculum
- Configure mentor's knowledge base and teaching style
- Grade assignments with AI assistance
- Generate assessments and practice materials
- Track student progress and engagement
- Research assistance and literature review
- Manage student access and permissions

### For Students (Client Portal)
- Access subject-specific AI mentors 24/7
- Get personalized learning assistance
- Practice with auto-generated questions
- Receive immediate feedback on assignments
- Get help with exam preparation
- Create customized study schedules
- Track learning progress
- Access course materials and resources

## 🛠️ Tech Stack
- Frontend: React with TypeScript
- Backend: Node.js & Express
- Database: MongoDB
- AI Integration: OpenAI/Anthropic API
- Authentication: JWT
- File Storage: AWS S3
- Real-time Updates: Socket.io

## 📁 Project Structure
```
mentors/
├── client/                 # React frontend
├── admin/                  # Admin portal frontend
├── server/                 # Express backend
├── shared/                 # Shared utilities
└── docs/                   # Documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js >= 18
- MongoDB
- npm or yarn
- OpenAI/Anthropic API key

### Installation

1. Clone the repository
```bash
git clone https://github.com/lemma-ai/mentors.git
cd mentors
```

2. Install dependencies
```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Install admin portal dependencies
cd ../admin
npm install
```

3. Configure environment variables
```bash
# Server
cp .env.example .env
# Add your configuration values
```

4. Start development servers
```bash
# Start backend
cd server
npm run dev

# Start client
cd client
npm start

# Start admin portal
cd admin
npm start
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Planned Features
- [ ] Real-time chat with AI mentors
- [ ] Assignment grading automation
- [ ] Progress tracking dashboard
- [ ] Custom assessment generation
- [ ] Research paper assistance
- [ ] Study schedule optimization
- [ ] Integration with popular LMS platforms
- [ ] Mobile application
- [ ] API for third-party integrations

## 🔐 Security

- JWT-based authentication
- Role-based access control
- Rate limiting
- Input validation
- Data encryption
- Regular security audits

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🌟 Acknowledgments
- OpenAI/Anthropic for AI capabilities
- Educational institutions for feedback and testing
- Contributors and testers

---
Made with ❤️ for educators and learners
