# HooksVideo - Video Transitions Platform

HooksVideo is a modern web platform that provides professional video transitions and hooks to help content creators make viral videos. Built with React, TypeScript, and Tailwind CSS.

## 🌟 Features

- **Video Gallery**: Browse and preview video transitions
- **Download System**: Easy-to-use video download functionality
- **Responsive Design**: Works seamlessly across all devices
- **Modern UI/UX**: Professional and intuitive interface
- **Contact Form**: Built-in communication channel
- **Pricing Plans**: Flexible subscription options

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Amarnath-WebDev/HooksVideo-AI.git
cd hooksvideo
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🛠 Tech Stack

- **Frontend Framework**: React
- **Type System**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Shadcn/ui
- **Icons**: Lucide Icons
- **State Management**: React Hooks
- **Build Tool**: Vite

## 📁 Project Structure

```
hooksvideo/
├── src/
│   ├── components/
│   │   ├── ui/
│   │   │   ├── button.tsx
│   │   │   ├── card.tsx
│   │   │   ├── input.tsx
│   │   │   └── textarea.tsx
│   │   └── ...
│   ├── App.tsx
│   └── main.tsx
├── public/
├── package.json
└── README.md
```

## 📋 Key Components

### VideoCard

- Displays video previews
- Handles video playback
- Manages download functionality
- Supports multiple video formats

### Navbar

- Responsive navigation
- Smooth scrolling
- Dynamic styling based on scroll position

### Pricing Section

- Three-tier pricing structure
- Highlighted popular plan
- Clear feature comparison

### Contact Form

- User-friendly input fields
- Form validation
- Contact information display

## 🎨 Styling

The project uses Tailwind CSS for styling with a custom color scheme:

```javascript
// tailwind.config.js
{
  theme: {
    extend: {
      colors: {
        primary: '#your-primary-color',
        secondary: '#your-secondary-color',
        accent: '#your-accent-color'
      }
    }
  }
}
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=your_api_url
VITE_CONTACT_EMAIL=your_email
```

## 📱 Responsive Design

The application is fully responsive with breakpoints:

- Mobile: 0-640px
- Tablet: 641-1024px
- Desktop: 1025px+

## 🔒 Security

- Input sanitization for contact form
- Protected API endpoints
- Secure video download system

## 🚀 Deployment

1. Build the project:

```bash
npm run build
# or
yarn build
```

2. Deploy the `dist` folder to your hosting service

## 📈 Performance Optimization

- Lazy loading for videos
- Optimized image assets
- Efficient component rendering
- Minimized bundle size

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 📞 Support

For support, email support@hooksvideo.com or visit our website.

## ✨ Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Shadcn/ui](https://ui.shadcn.com/)
