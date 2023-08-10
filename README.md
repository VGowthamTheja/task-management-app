This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

# Task Manager App

Welcome to the Task Manager App! This is a web application built using Next.js 13.4, designed to help you manage your tasks effectively.

![App Screenshot](./screenshot.png)

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create, view, update, and delete tasks.
- Organize tasks with due dates, priorities, and categories.
- Mark tasks as completed.
- User authentication and secure task management.
- Intuitive user interface for easy task management.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) package manager

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/VGowthamTheja/task-management-app.git
   cd task-management-app
   ```

Install dependencies:

```bash
Copy code
npm install
# or
yarn install
```

Set up environment variables:

Copy the .env.example file and rename it to .env.local. Replace the values with your configuration details (e.g., database connection, authentication keys).

Run the development server:

```bash
Copy code
npm run dev
# or
yarn dev
```

The app will be accessible at http://localhost:3000.

## Usage

- Sign Up / Log In: Create an account or log in using your credentials.

- Dashboard: View your tasks, organize them by due date and priority, and mark them as completed.

- Add Task: Create new tasks by providing task details like title, description, due date, and priority.

- Edit Task: Click on a task to edit its details or mark it as completed.

- Delete Task: Remove tasks you no longer need.

- Log Out: Securely log out of your account.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature: git checkout -b feature/my-feature

3. Commit your changes: git commit -m 'Add some feature'

4. Push to the branch: git push origin feature/my-feature

5. Open a pull request, describing the feature and changes.

Feel free to contact the maintainers for any questions or assistance.

# License

This project is licensed under the **MIT License.**
