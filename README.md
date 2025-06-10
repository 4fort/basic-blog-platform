# Basic Blog Platform

A modern blog platform built with [Next.js](https://nextjs.org) and bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## 👯‍♂️ Members

- **Dexter Fort Silva**
- **Charles Dave Avenido**
- **James Christian Montealto**

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm, yarn, pnpm, or bun package manager

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd basic-blog-platform
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📁 Project Structure

```
basic-blog-platform/
├── app/                             # Next.js app pages/routes
├── components/                      # Reusable global React components
├── app/[page]/components            # Per-page local React components
├── public/                          # Static assets
└── ...
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Git Commit Message Conventions

This project follows strict commit message conventions to maintain a clear and consistent Git history.

#### Commit Message Structure

```
<type>: <short summary> (max 50 characters)
```

#### Example

```
feat: Add user authentication system
```

### Commit Types

| Type       | Description                                                     |
| ---------- | --------------------------------------------------------------- |
| `feat`     | A new feature for the project                                   |
| `fix`      | A bug fix                                                       |
| `docs`     | Documentation-only changes                                      |
| `style`    | Changes that don't affect code meaning (formatting, whitespace) |
| `refactor` | Code changes that neither fix bugs nor add features             |
| `perf`     | Performance improvements                                        |
| `test`     | Adding or correcting tests                                      |
| `chore`    | Build process, package manager, or auxiliary tool changes       |

### Commit Header Guidelines

- **Limit to 50 characters**
- **Capitalize** the first word
- **No period** at the end
- **Use imperative mood** ("Add feature" not "Added feature")
- **Be descriptive** but concise

### Best Practices

- ✅ **One purpose per commit** - Keep commits focused
- ✅ **Consistent tags** - Use the same commit types throughout
- ✅ **Reference issues** - Link commits to project issues when applicable
- ❌ **Avoid mixing** unrelated changes in a single commit

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - Interactive Next.js tutorial
- [Gum Documentation](https://github.com/charmbracelet/gum) - Learn about the Gum CLI tool

## 🚀 Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
