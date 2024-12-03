/education-platform-frontend
│
├── package.json
├── tsconfig.json
├── next.config.js
│
├── src/
│   ├── components/
│   │   ├── common/
│   │   │   ├── Button.tsx
│   │   │   ├── Input.tsx
│   │   │   └── Layout.tsx
│   │   ├── auth/
│   │   │   ├── LoginForm.tsx
│   │   │   └── RegisterForm.tsx
│   │   └── courses/
│   │       ├── CourseCard.tsx
│   │       └── CourseList.tsx
│   │
│   ├── pages/
│   │   ├── _app.tsx
│   │   ├── index.tsx
│   │   ├── login.tsx
│   │   ├── register.tsx
│   │   ├── dashboard.tsx
│   │   └── courses/
│   │       ├── index.tsx
│   │       └── [courseId].tsx
│   │
│   ├── styles/
│   │   ├── globals.css
│   │   └── theme.ts
│   │
│   ├── store/
│   │   ├── index.ts
│   │   ├── rootReducer.ts
│   │   └── slices/
│   │       ├── authSlice.ts
│   │       └── courseSlice.ts
│   │
│   ├── services/
│   │   ├── api.ts
│   │   ├── authService.ts
│   │   └── courseService.ts
│   │
│   └── types/
│       ├── User.ts
│       └── Course.ts
│
├── public/
│   ├── favicon.ico
│   └── logo.svg
│
└── README_FRONTEND.md
