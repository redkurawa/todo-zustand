# Todo App with Next.js & Zustand

A modern, responsive Todo application built with Next.js 15, React 19, TypeScript, and Tailwind CSS v4. Features a clean UI powered by shadcn/ui components, dark/light mode support, and seamless API integration with TanStack Query.

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat&logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-v4-38B2AC?style=flat&logo=tailwind-css)

## ✨ Features

- 📋 **Task Management**: Create, read, update, and delete todo items
- 📅 **Date-based Filtering**: Organize tasks by Today, Upcoming, and Completed
- 🎯 **Priority Levels**: Assign priority to tasks for better organization
- 🌓 **Dark/Light Mode**: Automatic theme switching with next-themes
- 📱 **Responsive Design**: Fully responsive layout for all devices
- ⚡ **Fast Performance**: Powered by Next.js Turbopack for lightning-fast development
- 🔄 **Real-time Updates**: TanStack Query for efficient data fetching and caching
- 🎨 **Modern UI**: Beautiful components from shadcn/ui library

## 🚀 Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Data Fetching**: [TanStack Query](https://tanstack.com/query/latest)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Date Handling**: [Day.js](https://day.js.org/)
- **Forms**: [React Hook Form](https://react-hook-form.com/)
- **Notifications**: [Sonner](https://sonner.emilkowal.ski/)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone git@github.com:redkurawa/todo-zustand.git
   cd todo-zustand
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_LOCAL_API_URL=http://localhost:8080
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with Turbopack |
| `npm run build` | Build the application for production |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint to check code quality |

## 🏗️ Project Structure

```
todo-zustand/
├── src/
│   ├── app/                    # Next.js App Router
│   │   ├── page.tsx           # Main page component
│   │   ├── layout.tsx         # Root layout with providers
│   │   ├── globals.css        # Global styles
│   │   ├── top-menu.tsx       # Top navigation menu
│   │   ├── footer.tsx         # Footer component
│   │   ├── list-today.tsx     # Today's tasks list
│   │   ├── list-completed.tsx # Completed tasks list
│   │   ├── list-upcoming.tsx  # Upcoming tasks list
│   │   └── provider.tsx       # App providers wrapper
│   ├── components/            # React components
│   │   ├── ui/               # shadcn/ui components
│   │   ├── list-page.tsx     # Main list page with tabs
│   │   ├── todo-card.tsx     # Individual todo card
│   │   ├── todo-checkbox.tsx # Todo checkbox component
│   │   ├── task-priority.tsx # Priority selector
│   │   ├── date-picker.tsx   # Date picker component
│   │   ├── edit-delete-dialog.tsx # Edit/delete modal
│   │   ├── selected-button.tsx    # Selection button
│   │   └── theme-provider.tsx     # Theme provider
│   ├── constants/            # Constants and types
│   │   └── todo-type.ts     # Todo TypeScript interfaces
│   ├── lib/                  # Utility functions
│   │   ├── utils.ts         # General utilities
│   │   └── useInfiniteScrollQuery.ts # Infinite scroll hook
│   └── services/             # API services
│       ├── api.ts           # Axios instance configuration
│       └── service.ts       # API endpoints
├── public/                   # Static assets
├── components.json           # shadcn/ui configuration
├── next.config.ts           # Next.js configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
├── eslint.config.mjs        # ESLint configuration
└── package.json             # Dependencies
```

## 🔧 Configuration

### Tailwind CSS v4

This project uses Tailwind CSS v4 with the new CSS-based configuration approach. The styling is configured in `globals.css` using the `@import` and `@theme` directives.

### shadcn/ui Components

Components are installed using the shadcn/ui CLI and located in `src/components/ui/`. Currently used components:
- Button
- Checkbox
- Dialog
- Command
- Calendar
- Popover
- Tabs
- Label
- Sonner (toast notifications)

## 🌐 API Integration

The app connects to a REST API for todo operations. Configure the API base URL in your `.env.local`:

```env
NEXT_PUBLIC_LOCAL_API_URL=http://your-api-url
```

### API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/todos` | GET | Fetch all todos |
| `/todos/:param` | GET | Fetch todos with filter |

## 🎨 Customization

### Adding New shadcn/ui Components

```bash
npx shadcn@latest add [component-name]
```

### Theme Configuration

Edit `src/app/globals.css` to customize the theme colors and variables.

### Tailwind Configuration

Modify `tailwind.config.ts` for custom breakpoints, colors, and other Tailwind settings.

## 🧪 Development

### Code Quality

- **ESLint**: Configured with Next.js and Prettier integration
- **Prettier**: Formats code on save with Tailwind CSS plugin

### VS Code Settings

Recommended settings are included in `.vscode/settings.json` for consistent formatting.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or issues, please open an issue on GitHub.

---

Made with ❤️ by [redkurawa](https://github.com/redkurawa)
