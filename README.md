# Personal Portfolio Website

A modern, responsive portfolio website built with Next.js, TypeScript, and Tailwind CSS. Showcase your skills, projects, and experience with a beautiful, animated interface.

## ✨ Features

- 🖼️ **Hero Section**: Prominent display of your picture and bio at the very top
- 🛠️ **Tools & Technologies**: Moving logos showcase of technologies and companies you work with
- 🚀 **Projects Showcase**: Display your work with featured projects and full portfolio
- 📧 **Contact Form**: Interactive form for visitors to reach out to you
- 📱 **Responsive Design**: Mobile-first design that works seamlessly on all devices
- ✨ **Smooth Animations**: Beautiful animations using Framer Motion
- 🎨 **Modern UI**: Clean, professional design with Tailwind CSS

## 🚀 Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Deployment**: Vercel (recommended)

## 📋 Prerequisites

- Node.js 18+ 
- npm or yarn

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd portfolio-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎯 Customization

### Personal Information
Update the following files with your information:

- **`components/Hero.tsx`**: Your name, title, and profile picture
- **`components/Projects.tsx`**: Add your actual projects and work
- **`components/Contact.tsx`**: Update contact information and availability

### Profile Picture
1. Add your profile picture to the `public/` folder
2. Update the image path in `components/Hero.tsx`
3. Recommended size: 400x400 pixels or larger

### Projects
1. Update the `projects` array in `components/Projects.tsx`
2. Add your project images to the `public/` folder
3. Include live demo links and GitHub repositories
4. Categorize projects by type (Web App, Mobile App, Website, etc.)

### Technologies & Companies
1. Update the `technologies` array in `components/Tools.tsx`
2. Modify the `companies` array with companies you've worked with
3. Customize the technology categories to match your expertise

### Contact Information
1. Update email, phone, and location in `components/Contact.tsx`
2. Modify the "Available For" section based on your preferences
3. Customize the contact form validation if needed

## 🏗️ Project Structure

```
portfolio-website/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Main page
├── components/             # React components
│   ├── Portfolio.tsx      # Main portfolio component
│   ├── Navigation.tsx     # Navigation bar
│   ├── Hero.tsx           # Hero section with picture and bio
│   ├── Tools.tsx          # Tools and technologies showcase
│   ├── Projects.tsx       # Projects showcase
│   └── Contact.tsx        # Contact form and information
├── lib/                    # Utility functions
│   └── utils.ts           # Helper functions
├── public/                 # Static assets
├── tailwind.config.js     # Tailwind CSS configuration
├── postcss.config.js      # PostCSS configuration
├── tsconfig.json          # TypeScript configuration
└── package.json           # Dependencies and scripts
```

## 🎨 Styling & Theming

### Colors
The portfolio uses a blue-based color scheme that can be customized in `tailwind.config.js`:

```javascript
colors: {
  primary: {
    50: '#eff6ff',
    100: '#dbeafe',
    // ... customize these colors
  }
}
```

### Animations
- **Framer Motion**: Smooth scroll animations and transitions
- **Tailwind CSS**: Custom animations and keyframes
- **Intersection Observer**: Trigger animations when elements come into view

### Responsive Design
- **Mobile-first**: Designed for mobile devices first
- **Breakpoints**: Responsive grid layouts for different screen sizes
- **Navigation**: Collapsible mobile navigation menu

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically with zero configuration

### Other Platforms
The portfolio can be deployed to any platform that supports Next.js:
- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## 🔧 Configuration

### Environment Variables
No environment variables are required for basic functionality.

### Build Optimization
- **Static Generation**: Pages are statically generated for optimal performance
- **Image Optimization**: Next.js Image component for optimized images
- **Code Splitting**: Automatic code splitting for better performance

## 📱 Mobile Experience

- **Touch-friendly**: Large touch targets for mobile devices
- **Smooth scrolling**: Native-like scrolling experience
- **Responsive images**: Images that adapt to screen size
- **Mobile navigation**: Collapsible navigation menu

## 🎭 Animation Features

- **Scroll-triggered**: Animations that start when scrolling into view
- **Staggered**: Sequential animations for lists and grids
- **Smooth transitions**: CSS transitions for hover effects
- **Loading states**: Animated loading indicators

## 🐛 Troubleshooting

### Common Issues

**Build Errors**
- Clear `.next` folder and node_modules
- Reinstall dependencies
- Check TypeScript configuration

**Animation Issues**
- Ensure Framer Motion is properly installed
- Check browser compatibility
- Verify animation props are correct

**Styling Issues**
- Clear browser cache
- Check Tailwind CSS configuration
- Verify CSS imports are correct

### Debug Mode
Enable debug logging by setting:
```env
DEBUG=true
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the framework
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Framer Motion](https://www.framer.com/motion/) for animations
- [Lucide React](https://lucide.dev/) for icons

## 📞 Support

If you encounter any issues or have questions:
1. Check the troubleshooting section
2. Search existing issues
3. Create a new issue with detailed information

---

**Happy building your portfolio! 🎉✨**
