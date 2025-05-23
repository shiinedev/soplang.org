# Soplang | The First Somali Programming Language

<div align="center">
  <img src="public/images/logo/logo-dark.png" alt="Soplang Logo" width="200"/>
  <p><em>Dhis Software Adigoo Adeegsanaya Afkaaga Hooyo!</em></p>
  <p><em>(Build software using your mother tongue!)</em></p>
</div>

## 🌟 About Soplang

Soplang is the first Somali programming language, designed to make programming accessible to Somali speakers worldwide. By using Somali keywords and syntax, Soplang breaks down language barriers that have traditionally made programming difficult for non-English speakers.

### 🎯 Our Mission

To democratize programming education by providing a structured, intuitive programming language that makes coding accessible to Somali speakers, while maintaining the power and flexibility needed for real-world applications.

## 🚀 Features

- **Somali Keywords & Syntax**: Program using familiar Somali words like "door" (function), "qor" (print), and "haddii" (if)
- **Bilingual Documentation**: Comprehensive documentation available in both Somali and English
- **Cross-Platform**: Runs on Windows, macOS, Linux, and more with consistent behavior
- **Cultural Integration**: Examples and tutorials incorporate Somali cultural contexts
- **Modern Language Features**: Includes pattern matching, async/await, and other modern programming paradigms
- **Performance Optimized**: Includes a just-in-time compiler for significant performance improvements
- **Comprehensive Standard Library**: Rich set of modules and functions for common tasks

## 🌐 Website Structure

This repository contains the source code for the Soplang programming language's official website (soplang.org). The website is built using Next.js and TailwindCSS.

### 📂 Project Structure

```
/soplang.org
├── public/               # Static assets (images, fonts, etc.)
├── src/                  # Source directory
│   ├── app/              # Next.js App Router
│   │   ├── about/        # About pages (team, quotes, help, applications)
│   │   ├── blog/         # Blog and news articles
│   │   ├── community/    # Community pages (forums, contribute, events)
│   │   ├── docs/         # Documentation pages
│   │   │   ├── getting-started/ # Getting started guides
│   │   │   ├── faq/      # Frequently asked questions
│   │   │   └── ...       # Other documentation sections
│   │   ├── downloads/    # Download pages for different platforms
│   │   ├── privacy/      # Privacy policy
│   │   ├── terms/        # Terms of use
│   │   ├── trademarks/   # Trademark information
│   │   ├── sitemap/      # Site map
│   │   ├── success-stories/ # Success stories and testimonials
│   │   ├── write/        # Contribution writing page
│   │   ├── layout.tsx    # Root layout component
│   │   └── page.tsx      # Homepage
│   ├── components/       # Reusable components
│   │   ├── CodeWindow.tsx # Code display component
│   │   ├── Footer.tsx    # Footer component
│   │   ├── Navbar.tsx    # Navigation bar component
│   │   ├── SoplangHighlighter.tsx # Syntax highlighting component
│   │   ├── ThemeProvider.tsx # Dark/light theme provider
│   │   └── ThemeToggle.tsx # Theme toggle component
│   ├── styles/           # Global styles
│   │   ├── globals.css   # Global CSS with Tailwind imports
│   │   └── soplang-syntax.css # Syntax highlighting styles
│   └── utils/            # Utility functions
│       └── formatDate.ts # Date formatting utilities
├── scripts/              # Helper scripts
├── .gitignore            # Git ignore file
├── LICENSE               # License information
├── next.config.js        # Next.js configuration
├── package.json          # Project dependencies and scripts
├── postcss.config.js     # PostCSS configuration
├── tailwind.config.js    # Tailwind CSS configuration
└── tsconfig.json         # TypeScript configuration
```

## 🛠️ Development Setup

### Prerequisites

- Node.js 18.x or later
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/soplang/soplang.org.git
cd soplang.org
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or use the provided script for colored output
./start-dev-with-colors.sh
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## 🤝 Contributing

We welcome contributions from everyone! Here's how you can help:

### Types of Contributions

1. **Code Contributions**: Improve the website, fix bugs, or add new features
2. **Documentation**: Enhance or translate documentation
3. **Design**: Improve UI/UX or create visual assets
4. **Content**: Write blog posts, tutorials, or examples
5. **Testing**: Test the website on different devices and browsers

### Contribution Process

1. **Fork the Repository**: Create your own fork of the project
2. **Create a Branch**: Make your changes in a new branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Implement your changes following our coding standards
4. **Test Your Changes**: Ensure your changes work as expected
5. **Commit Your Changes**: Use clear commit messages
   ```bash
   git commit -m "Add feature: your feature description"
   ```
6. **Push to Your Fork**: Upload your changes
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Create a Pull Request**: Submit a PR to the main repository

### Coding Standards

- Follow the existing code style and structure
- Use TailwindCSS for styling (avoid inline styles)
- Write clean, readable, and well-documented code
- Ensure your code is responsive and accessible
- Test your changes on different browsers and devices

## 🎨 Design Guidelines

### Colors

We use CSS variables for colors to maintain consistency and enable theming:

```css
:root {
  --primary-color: #3F72AF; /* Soft blue */
  --secondary-color: #5E9A78; /* Soft green */
  --background-color: #F9F7F7; /* Light gray with slight warmth */
  --text-color: #333333; /* Dark gray */
  --link-color: #3F72AF; /* Matching primary */
}

.dark {
  --primary-color: #5085C1; /* Lighter blue for dark mode */
  --secondary-color: #6BAA88; /* Lighter green for dark mode */
  --background-color: #1A202C; /* Dark blue-gray */
  --text-color: #E2E8F0; /* Off-white */
  --link-color: #5085C1; /* Matching dark mode primary */
}
```

### Typography

- Use the Roboto font family for consistent typography
- Follow a clear hierarchy with appropriate heading sizes
- Ensure sufficient contrast for readability

### Components

Use our predefined component classes for consistency:

```css
.container-custom /* Main container */
.btn-primary /* Primary buttons */
.btn-secondary /* Secondary buttons */
.nav-link /* Navigation links */
.soplang-box /* Content boxes */
.soplang-header /* Section headers */
.soplang-link /* Text links */
```

## 📚 Soplang Language Syntax

Soplang uses Somali keywords to make programming more intuitive for Somali speakers:

| Keyword | English Equivalent | Description |
|---------|-------------------|-------------|
| `door` | function | Defines a function |
| `howl` | return | Returns a value from a function |
| `soo_celi` | import | Imports modules or functions |
| `qor` | print | Outputs text to the console |
| `akhri` | input | Reads user input |
| `haddii` | if | Conditional statement |
| `haddii_kale` | else | Alternative conditional branch |
| `haddii_kalena` | elif | Additional conditional branch |
| `ku_celi` | for | Loop iteration |
| `inta_ay` | while | Conditional loop |
| `jooji` | break | Exits a loop |
| `sii_wad` | continue | Skips to next iteration |
| `isku_day` | try | Exception handling block |
| `qabo` | catch | Catches exceptions |
| `ka_keen` | from | Imports from modules |
| `fasalka` | class | Defines a class |
| `ka_dhaxal` | extends | Inherits from a class |
| `cusub` | new | Creates a new instance |
| `nafta` | self | References the current instance |
| `liis` | list | Array data structure |
| `shey` | object | Object data structure |
| `waxba` | null | Null value |
| `run` | true | Boolean true value |
| `been` | false | Boolean false value |

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- Website: [https://soplang.org](https://soplang.org)
- GitHub: [https://github.com/soplang](https://github.com/soplang)
- Discord: [https://discord.gg/soplang](https://discord.gg/soplang)
- Email: info@soplang.org

## 🙏 Acknowledgements

- All contributors who have helped build and improve Soplang
- The Somali tech community for their support and feedback
- Open source projects that have inspired and enabled this work
