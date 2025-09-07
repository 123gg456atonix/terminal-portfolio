# Terminal Portfolio

A modern, interactive terminal-based portfolio website built with Next.js, React, and TypeScript. Experience a unique blend of command-line interface and modern web design, featuring a simulated Kali Linux environment with full portfolio functionality.

![Terminal Portfolio Preview](/Live-preview.png)

## 🌟 Features

- **Interactive Terminal Interface**: Authentic Kali Linux simulation with commands like `ls`, `cd`, `cat`, `nano`, `neofetch`, and more
- **Portfolio GUI**: Modern, responsive portfolio interface with animated transitions
- **Multiple Themes**: Cyber Green, Hacker Blue, Matrix Red, and Amber Haze themes
- **Responsive Design**: Optimized for desktop and mobile devices
- **Real-time Animations**: Smooth transitions and hover effects throughout
- **File System Simulation**: Navigate through a virtual file system with realistic directory structure
- **Command History**: Full command history with arrow key navigation
- **Tab Completion**: Intelligent tab completion for commands and file paths
- **Statistics Dashboard**: Animated counters for projects, vulnerabilities, clients, and coffee consumption
- **Project Showcase**: Featured projects with GitHub links and live demos
- **Skills & Expertise**: Categorized skills in frontend, backend, cybersecurity, and DevOps
- **Achievements**: Professional certifications and milestones
- **Contact Integration**: Direct links to email, GitHub, LinkedIn, and Discord

## 🛠️ Tech Stack

### Frontend
- **Next.js 14.2.16** - React framework for production
- **React 18** - UI library
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS 4.1.9** - Utility-first CSS framework
- **Radix UI** - Accessible UI components
- **Lucide React** - Beautiful icons
- **Framer Motion** - Animation library

### Development Tools
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing
- **Vercel Analytics** - Web analytics

### Key Dependencies
- `@radix-ui/*` - UI component primitives
- `class-variance-authority` - Component variant utilities
- `clsx` - Conditional CSS classes
- `tailwind-merge` - Tailwind class merging
- `date-fns` - Date utilities
- `react-hook-form` - Form handling
- `zod` - Schema validation

## 🚀 Where to buy?

**Built By Bit**
   Go to https://builtbybit.com/resources/terminal-portfolio-nextjs.76628 and Buy the thing.

## ⏬ Installation and Development

1. **Install dependencies**
   ```bash
   # change this to the path to your files
   cd /path/to/files
   npm install 
   # use npm install --force if needed or
   yarn install
   # or
   pnpm install
   ```

2. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

3. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
terminal-portfolio/
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── terminal.tsx       # Terminal interface
│   ├── portfolio.tsx      # Portfolio GUI
│   ├── expandable-button.tsx
│   ├── theme-provider.tsx
│   └── ui/                # UI components
├── config/                # Configuration files
│   └── portfolio-config.ts # Portfolio data and settings
├── lib/                   # Utility libraries
│   └── utils.ts           # Helper functions
├── public/                # Static assets
│   ├── favicon.png
│   ├── logo.png
│   └── fonts/
└── styles/                # Additional styles
    └── globals.css
```

## 🎮 Usage

### Terminal Commands

The terminal interface supports various commands:

- `help` - Display available commands
- `ls` - List directory contents
- `cd <directory>` - Change directory
- `cat <file>` - Display file contents
- `nano <file>` - Edit files
- `pwd` - Show current directory
- `clear` - Clear terminal
- `theme` - Cycle through themes
- `history` - Show command history
- `neofetch` - Display system information
- `npm run start` - Launch portfolio GUI (from /var/www/html)

### Navigation

1. **Terminal Mode**: Start in the terminal interface
2. **Portfolio GUI**: Use `npm run start` from `/var/www/html` or click the launch button
3. **Theme Switching**: Use the theme button or `theme` command
4. **Back to Terminal**: Use the "Back to Terminal" button

## 🎨 Customization

### Adding New Themes

Edit `config/portfolio-config.ts` to add new themes:

```typescript
{
  name: "New Theme",
  primary: "from-color1 to-color2",
  accent: "color1",
  bg: "from-color1/10 to-color2/10",
  hover: "hover:bg-color1/20",
  colors: {
    primary: "#hex1",
    secondary: "#hex2",
    accent: "#hex3",
  },
}
```

### Updating Portfolio Content

Modify `config/portfolio-config.ts` to update:
- Personal information
- Projects
- Skills
- Achievements
- Navigation links

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- Desktop (1920px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Code Quality

- TypeScript for type safety
- ESLint for code linting
- Prettier for code formatting
- Tailwind CSS for consistent styling

## 🌐 Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect Next.js and deploy
3. Configure environment variables if needed

### Other Platforms

The app can be deployed to any platform supporting Node.js:
- Netlify
- Railway
- Render
- DigitalOcean App Platform

## 🤝 Contributing

1. If you find any bugs or issues and you have a solution or want a solution. Contact me thru https://123gg456.com/contact .

## 🙏 Acknowledgments

- **Geist Font** - Modern typography
- **Radix UI** - Accessible component library
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide** - Beautiful icon set
- **Vercel** - Hosting platform

## 📞 Contact

**123gg456**
- Email: admin@123gg456.com
- Website: https://123gg456.com
- GitHub: [@123gg456atonix](https://github.com/123gg456atonix)
- LinkedIn: [123gg456](https://linkedin.com/in/123gg456)
- Discord: @123gg456_

## 🔗 Links

- **Live Demo**: [https://terminal.123gg456.com](https://terminal.123gg456.com)
- **GitHub Repository**: [https://github.com/123gg456atonix/terminal-portfolio](https://github.com/123gg456atonix/terminal-portfolio)
- **My Website**: [https://123gg456.com](https://123gg456.com)

---

Built with ❤️ by 123gg456 using Next.js, TypeScript, and Tailwind CSS
