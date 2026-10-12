# Minor_Project
An Full stack P2P Learning Application .
Structure of P2P Learning 


p2p-learning-platform/
│
├── client/                        
│   ├── public/
│   │
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── common/
│   │   │   │   ├── Navbar.jsx
│   │   │   │   ├── Footer.jsx
│   │   │   │   ├── Loader.jsx
│   │   │   │   └── ProtectedRoute.jsx
│   │   │   ├── dashboard/
│   │   │   ├── peers/
│   │   │   ├── chat/
│   │   │   └── partnerships/
│   │   │
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── Onboarding.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   ├── MyProfile.jsx
│   │   │   ├── EditProfile.jsx
│   │   │   ├── PeerDiscovery.jsx
│   │   │   ├── PeerDetails.jsx
│   │   │   ├── Connections.jsx
│   │   │   ├── Chat.jsx
│   │   │   ├── Partnerships.jsx
│   │   │   ├── LearningPlan.jsx
│   │   │   ├── Sessions.jsx
│   │   │   ├── Assessments.jsx
│   │   │   ├── Progress.jsx
│   │   │   ├── Ratings.jsx
│   │   │   ├── Notifications.jsx
│   │   │   └── Settings.jsx
│   │   │
│   │   ├── context/
│   │   │   ├── AuthContext.jsx
│   │   │   └── SocketContext.jsx
│   │   │
│   │   ├── hooks/
│   │   │   ├── useAuth.js
│   │   │   └── useSocket.js
│   │   │
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   ├── authService.js
│   │   │   ├── peerService.js
│   │   │   ├── partnershipService.js
│   │   │   ├── chatService.js
│   │   │   └── assessmentService.js
│   │   │
│   │   ├── layouts/
│   │   │   ├── MainLayout.jsx
│   │   │   └── DashboardLayout.jsx
│   │   │
│   │   ├── utils/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── .env.example
│   ├── package.json
│   └── vite.config.js
│
├── server/                         # Node.js backend
│   ├── prisma/
│   │   ├── schema.prisma
│   │   ├── migrations/
│   │   └── seed.js
│   │
│   ├── src/
│   │   ├── config/
│   │   │   ├── database.js
│   │   │   ├── env.js
│   │   │   └── google.js
│   │   │
│   │   ├── middleware/
│   │   │   ├── authenticate.js
│   │   │   ├── authorize.js
│   │   │   ├── validate.js
│   │   │   ├── errorHandler.js
│   │   │   └── rateLimiter.js
│   │   │
│   │   ├── modules/
│   │   │   ├── auth/
│   │   │   │   ├── auth.routes.js
│   │   │   │   ├── auth.controller.js
│   │   │   │   └── auth.service.js
│   │   │   │
│   │   │   ├── users/
│   │   │   │   ├── user.routes.js
│   │   │   │   ├── user.controller.js
│   │   │   │   └── user.service.js
│   │   │   │
│   │   │   ├── profiles/
│   │   │   ├── fields/
│   │   │   ├── skills/
│   │   │   ├── matching/
│   │   │   ├── connections/
│   │   │   ├── introSessions/
│   │   │   ├── partnerships/
│   │   │   ├── learningPlans/
│   │   │   ├── sessions/
│   │   │   ├── chat/
│   │   │   ├── resources/
│   │   │   ├── assessments/
│   │   │   ├── ratings/
│   │   │   ├── badges/
│   │   │   ├── notifications/
│   │   │   └── integrations/
│   │   │
│   │   ├── ai/
│   │   │   ├── geminiClient.js
│   │   │   ├── matchingAI.js
│   │   │   ├── questionGenerator.js
│   │   │   ├── answerEvaluator.js
│   │   │   └── learningRecommendations.js
│   │   │
│   │   ├── integrations/
│   │   │   ├── google/
│   │   │   │   ├── googleAuth.js
│   │   │   │   ├── calendarService.js
│   │   │   │   ├── meetService.js
│   │   │   │   └── classroomService.js
│   │   │   ├── email/
│   │   │   │   └── emailService.js
│   │   │   └── externalProfiles/
│   │   │
│   │   ├── sockets/
│   │   │   ├── socketServer.js
│   │   │   ├── chatSocket.js
│   │   │   └── notificationSocket.js
│   │   │
│   │   ├── utils/
│   │   │   ├── ApiError.js
│   │   │   ├── ApiResponse.js
│   │   │   └── dateUtils.js
│   │   │
│   │   ├── app.js
│   │   └── server.js
│   │
│   ├── tests/
│   ├── .env.example
│   └── package.json
│
├── database/
│   ├── seed-data/
│   └── database-design.md
│
├── docs/
│   ├── PRD.md
│   ├── SRS.md
│   ├── architecture.md
│   ├── database-schema.md
│   ├── api-documentation.md
│   ├── test-cases.md
│   └── user-guide.md
│
├── .gitignore
├── README.md
└── package.json                  # Optional root scripts
