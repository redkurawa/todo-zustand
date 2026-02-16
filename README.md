# 🚀 Supercharged Todo App - Next.js 15 + Zustand

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=todo-zustand&repo=todo-zustand&color=46f018&style=flat-square&label=Views" alt="Profile views" />
  <img src="https://img.shields.io/github/stars/redkurawa/todo-zustand?style=flat-square" alt="GitHub stars" />
  <img src="https://img.shields.io/github/forks/redkurawa/todo-zustand?style=flat-square" alt="GitHub forks" />
  <img src="https://img.shields.io/github/issues/redkurawa/todo-zustand?style=flat-square" alt="GitHub issues" />
  <img src="https://img.shields.io/github/license/redkurawa/todo-zustand?style=flat-square" alt="License" />
</p>

<p align="center">
  <a href="https://nextjs.org">
    <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js" alt="Next.js" />
  </a>
  <a href="https://react.dev">
    <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react" alt="React" />
  </a>
  <a href="https://www.typescriptlang.org">
    <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript" />
  </a>
  <a href="https://tailwindcss.com">
    <img src="https://img.shields.io/badge/Tailwind%20CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS" />
  </a>
</p>

---

## 🌟 The Most EPIC Todo App You've Ever Seen!

Welcome to the **most powerful, most beautiful, most adrenaline-pumping** Todo application ever built! 🚀

This isn't just another todo app. This is a **BEAST** 🦍 built with cutting-edge technology that will make your task management experience feel like you're riding a rocket through space! 🌌

### 🎯 What Makes This App SO SPECIAL?

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  ✨ PURE MAGIC ✨                                                           │
│  ─────────────────────────────────────────────────────────────────────────  │
│  🗓️  Smart Date Filtering  →  Today | Upcoming | Completed                │
│  🎯  Priority System       →  Low | Medium | High | Critical              │
│  🌙  Dark/Light Mode       →  Auto-detect + Manual toggle                 │
│  📱  100% Responsive       →  Mobile-first design                          │
│  ⚡  Lightning Fast         →  Next.js Turbopack powered                   │
│  🔄  Real-time Sync        →  TanStack Query with smart caching            │
│  🎨  Beautiful UI          →  shadcn/ui components galore!                │
│  🔔  Toast Notifications   →  Never miss an action with Sonner            │
│  📝  Form Handling         →  React Hook Form with validation              │
│  🛡️  Type Safety          →  Full TypeScript from head to toe             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack - The Arsenal of a Warrior

| Category | Technology | Description |
|----------|------------|-------------|
| ⚛️ **Framework** | [Next.js 15](https://nextjs.org/) | The most powerful React framework with App Router |
| 🦸 **Language** | [TypeScript 5](https://www.typescriptlang.org/) | Type-safe from start to finish |
| 🎨 **Styling** | [Tailwind CSS v4](https://tailwindcss.com/) | The latest and greatest CSS framework |
| 🎯 **UI Components** | [shadcn/ui](https://ui.shadcn.com/) | Beautiful, accessible, customizable components |
| ✨ **Icons** | [Lucide React](https://lucide.dev/) | Clean and consistent icon set |
| 🔄 **State/Fetching** | [TanStack Query](https://tanstack.com/query/latest) | Powerful asynchronous state management |
| 🌐 **HTTP Client** | [Axios](https://axios-http.com/) | Promise-based HTTP client |
| 📅 **Date Handling** | [Day.js](https://dayjs.org/) | Moment.js alternative - tiny and fast |
| 📝 **Forms** | [React Hook Form](https://react-hook-form.com/) | Performant and easy form handling |
| 🔔 **Notifications** | [Sonner](https://sonner.emilkowal.ski/) | Beautiful toast notifications |
| 🎭 **Animations** | [tw-animate-css](https://github.com/cmd强行列/tw-animate-css) | Smooth CSS animations |
| 📦 **Package Manager** | npm | Node package manager |

---

## 🎬 Getting Started - Let's Rock!

### Prerequisites

Before you begin, make sure you have:

- 🟢 **Node.js** 18.17 or later (recommended: 20.x LTS)
- 🟢 **npm** or yarn or pnpm
- 🟢 **Git** installed
- 🧠 A brain ready to be blown away! 🧠

### Installation Steps

```bash
# 1. Clone the repository - Get the code!
git clone git@github.com:redkurawa/todo-zustand.git
cd todo-zustand

# 2. Install dependencies - Grab all the goodies!
npm install
# OR if you're fancy
yarn install
# OR if you're FAST
pnpm install

# 3. Set up environment variables - Configure your backend!
# Create a .env.local file in the root directory:

cat > .env.local << 'EOF'
NEXT_PUBLIC_LOCAL_API_URL=http://localhost:8080
EOF

# 4. Fire up the development server - LET'S GO!
npm run dev

# 5. Open your browser and witness the MAGIC!
# Navigate to: http://localhost:3000
```

---

## 📜 Available Scripts

| Command | Description | What it does |
|---------|-------------|--------------|
| `npm run dev` | 🚀 Development Mode | Start dev server with Turbopack (blazing fast!) |
| `npm run build` | 🏗️ Production Build | Build for production with optimizations |
| `npm run start` | 🎯 Production Server | Start the production server |
| `npm run lint` | 🔍 Code Quality | Run ESLint to check for issues |

---

## 🏗️ Project Structure - Your Map to Treasure!

```
🎯 todo-zustand/
│
├── 📁 src/
│   ├── 📁 app/                          # Next.js App Router - The heart of the app!
│   │   ├── 📄 page.tsx                 # Main landing page
│   │   ├── 📄 layout.tsx               # Root layout with providers
│   │   ├── 📄 globals.css              # Global styles & Tailwind config
│   │   ├── 📄 provider.tsx             # App providers wrapper (QueryClient, Theme, etc.)
│   │   ├── 📄 top-menu.tsx             # Top navigation menu
│   │   ├── 📄 footer.tsx               # Footer component
│   │   ├── 📄 check.tsx                # Check/verification page
│   │   ├── 📄 list-today.tsx           # 📅 Today's tasks - What needs to be done NOW!
│   │   ├── 📄 list-completed.tsx       # ✅ Completed tasks - Look at your achievements!
│   │   ├── 📄 list-upcoming.tsx        # 🔮 Upcoming tasks - Plan for the future!
│   │   └── 📁 api/                     # (Future API routes)
│   │
│   ├── 📁 components/                  # React Components - Building blocks!
│   │   ├── 📁 ui/                      # shadcn/ui components
│   │   │   ├── 📄 button.tsx           # Clickable buttons
│   │   │   ├── 📄 checkbox.tsx         # Checkbox input
│   │   │   ├── 📄 dialog.tsx           # Modal dialogs
│   │   │   ├── 📄 command.tsx           # Command palette
│   │   │   ├── 📄 calendar.tsx         # Date calendar
│   │   │   ├── 📄 popover.tsx          # Popover component
│   │   │   ├── 📄 tabs.tsx             # Tab navigation
│   │   │   ├── 📄 label.tsx            # Form labels
│   │   │   ├── 📄 input.tsx           # Text input
│   │   │   ├── 📄 sonner.tsx           # Toast notifications
│   │   │   └── 📄 *more*              # Even more components!
│   │   │
│   │   ├── 📄 list-page.tsx           # 📋 Main list page with tabs
│   │   ├── 📄 todo-card.tsx           # 🎯 Individual todo card
│   │   ├── 📄 todo-checkbox.tsx       # ☑️ Todo checkbox
│   │   ├── 📄 task-priority.tsx       # 🎯 Priority selector
│   │   ├── 📄 date-picker.tsx         # 📅 Date picker
│   │   ├── 📄 edit-delete-dialog.tsx  # ✏️ Edit/Delete modal
│   │   ├── 📄 selected-button.tsx     # 🔘 Selection button
│   │   ├── 📄 theme-provider.tsx      # 🌙 Theme provider
│   │   └── 📄 *more*                  # Even more awesome components!
│   │
│   ├── 📁 constants/                   # Constants - The unchanging truths!
│   │   └── 📄 todo-type.ts            # Todo TypeScript interfaces/types
│   │
│   ├── 📁 lib/                         # Utilities - Helper functions!
│   │   ├── 📄 utils.ts                # General utilities (cn, date helpers, etc.)
│   │   └── 📄 useInfiniteScrollQuery.ts  # ♾️ Infinite scroll hook
│   │
│   ├── 📁 services/                    # API Services - Communication with backend!
│   │   ├── 📄 api.ts                  # Axios instance configuration
│   │   └── 📄 service.ts              # API endpoints
│   │
│   └── 📁 *others*                    # More app stuff!
│
├── 📁 public/                          # Static assets (images, fonts, etc.)
├── 📄 .eslintrc.json                   # ESLint configuration
├── 📄 .prettierrc                      # Prettier configuration
├── 📄 next.config.ts                   # Next.js configuration
├── 📄 tailwind.config.ts              # Tailwind CSS configuration
├── 📄 tsconfig.json                    # TypeScript configuration
├── 📄 components.json                  # shadcn/ui configuration
├── 📄 package.json                     # Dependencies
└── 📄 README.md                        # 📖 This file!
```

---

## 🔌 API Integration - Connect to the Backend!

### Environment Variables

Create a `.env.local` file in the root directory:

```env
# Base URL for your API - Where the magic data comes from!
NEXT_PUBLIC_LOCAL_API_URL=http://localhost:8080
```

### API Endpoints

| Method | Endpoint | Description | Response |
|--------|----------|-------------|----------|
| 📥 **GET** | `/todos` | Fetch ALL todos | Array of todo objects |
| 📥 **GET** | `/todos/:param` | Fetch todos with filter | Filtered array |

### Example API Response

```json
{
  "id": "1",
  "title": "Conquer the world! 🌍",
  "description": "Start with small tasks first",
  "completed": false,
  "priority": "high",
  "date": "2024-01-15",
  "createdAt": "2024-01-01T00:00:00Z",
  "updatedAt": "2024-01-01T00:00:00Z"
}
```

---

## 🎨 Customization - Make It YOURS!

### Adding More shadcn/ui Components

```bash
# Add a new component - it's that easy!
npx shadcn@latest add [component-name]

# Examples:
npx shadcn@latest add card        # Add a card component
npx shadcn@latest add dropdown-menu  # Add dropdown menu
npx shadcn@latest add toast       # Add toast notifications
npx shadcn@latest add skeleton     # Add loading skeletons
```

### Theming - Express Yourself!

```css
/* In src/app/globals.css - Edit these variables! */
@theme {
  /* Primary colors */
  --color-primary: 222.2 47.4% 11.2%;
  --color-primary-foreground: 210 40% 98%;
  
  /* Secondary colors */
  --color-secondary: 217.2 32.6% 17.5%;
  --color-secondary-foreground: 210 40% 98%;
  
  /* Add your own brand colors! */
  --color-brand: 250 100% 50%;
}
```

### Tailwind Configuration

Edit `tailwind.config.ts` for custom:
- Breakpoints
- Custom colors
- Animation durations
- And much more!

---

## 🧪 Development - Code Like a Pro!

### Code Quality Tools

| Tool | Purpose |
|------|---------|
| 🧹 **ESLint** | Catches bugs and enforces code style |
| 💅 **Prettier** | Automatic code formatting |
| 🔧 **TypeScript** | Type safety and IntelliSense |

### VS Code Setup

We recommend these extensions:

```json
// Recommended VS Code extensions
{
  "recommendations": [
    "dbaeumer.vscode-eslint",
    "esbenp.prettier-vscode",
    "bradlc.vscode-tailwindcss",
    "ms-vscode.vscode-typescript-next"
  ]
}
```

---

## 🚦 Roadmap - What's Coming Next?

- [ ] 🔐 Authentication - User login/signup
- [ ] ☁️ Cloud Sync - Sync across devices
- [ ] 📊 Analytics - Task completion statistics
- [ ] 🎯 Goals - Set and track goals
- [ ] 👥 Team Collaboration - Share tasks with team
- [ ] 📱 PWA Support - Install as app
- [ ] 🔔 Push Notifications - Real-time alerts
- [ ] 🎨 More Themes - Custom themes
- [ ] 📤 Export/Import - Backup your data
- [ ] ⌨️ Keyboard Shortcuts - Power user features

---

## 🤝 Contributing - Join the Revolution!

We welcome contributions! Here's how you can help:

```bash
# 1. Fork the repository
# Click the "Fork" button on GitHub!

# 2. Clone YOUR fork
git clone https://github.com/YOUR_USERNAME/todo-zustand.git
cd todo-zustand

# 3. Create a new branch
git checkout -b feature/amazing-new-feature

# 4. Make your changes and commit!
git add .
git commit -m "✨ Add some amazing new feature!"

# 5. Push to your fork
git push origin feature/amazing-new-feature

# 6. Create a Pull Request!
# Go to GitHub and click "New Pull Request"
```

### Contributing Guidelines

1. ⭐ Star the repo if you like it!
2. 🐛 Report bugs using GitHub Issues
3. 💡 Suggest features using GitHub Issues
4. 🔧 Submit PRs for bug fixes/features
5. 📖 Improve documentation

---

## 📞 Support - We're Here to Help!

If you need help or have questions:

- 🐛 **Bug Reports**: [Open an Issue](https://github.com/redkurawa/todo-zustand/issues)
- 💡 **Feature Requests**: [Open an Issue](https://github.com/redkurawa/todo-zustand/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/redkurawa/todo-zustand/discussions)
- 📧 **Email**: (Check GitHub profile)

---

## 📄 License - Free to Use!

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 - Present redkurawa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The amazing React framework
- [shadcn/ui](https://ui.shadcn.com/) - The beautiful component library
- [Tailwind CSS](https://tailwindcss.com/) - The utility-first CSS framework
- [TanStack Query](https://tanstack.com/query/) - The powerful data fetching library
- [All Contributors](https://github.com/redkurawa/todo-zustand/graphs/contributors) - The awesome people who help!
- **YOU** - For checking out this project! 🎉

---

## 🌟 Show Your Support!

If you love this project:

- ⭐ Give us a Star on GitHub!
- 🍴 Fork it and make it better!
- 🐛 Report bugs and issues!
- 💡 Share your ideas!
- 📢 Tell your friends!

---

<p align="center">
  <img src="https://img.shields.io/badge/Made_with_❤️_by-redkurawa-red?style=for-the-badge" alt="Made with love" />
  <br />
  <sub>Built with 🚀 and lots of ☕</sub>
</p>

---

<div align="center">

### 🎉 Thanks for checking out this project! Happy coding! 🎉

**Don't forget to ⭐ the repo if you found it useful!**

</div>

<!--
  @TODO: Add screenshots here!
  ![Screenshot 1](screenshots/screenshot-1.png)
  ![Screenshot 2](screenshots/screenshot-2.png)
-->
