# Spylt-awward-clone

Recreating a website frontend that has won an Awwwards Site of the Day, using GSAP, ReactJS, and Tailwind CSS.

## 🎨 Description

This project is a recreation of an Awwwards-awarded website (Site of the Day). It showcases smooth and modern animations with a clean and responsive user interface. The site features multiple dynamic sections including product benefits, a flavor gallery, and customer testimonials.

## 🚀 Features

- **Advanced GSAP Animations** : Smooth and performant animations for an exceptional user experience
- **Responsive Design** : Interface adapted to all devices (mobile, tablet, desktop)
- **Dynamic Sections** : Hero, Benefits, Flavors, Nutrition, Testimonials, Messages
- **Smooth Navigation** : Interactive navigation bar
- **Multimedia Gallery** : Integrated images and videos
- **Interactive Slider** : Flavor selection with intuitive navigation

## 🛠️ Technologies Used

- **React 19** : JavaScript library for building user interfaces
- **Vite** : Ultra-fast build tool for development
- **Tailwind CSS 4** : Utility-first CSS framework for styling
- **GSAP 3** : Professional animation library
- **React Responsive** : Media queries management in React
- **ES Modules** : Modern JavaScript syntax

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Prince-Elie/Spylt-awward-clone.git
   cd Spylt-awward-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

## 📝 Available Scripts

```bash
# Start the development server
npm run dev

# Build for production
npm run build

# Check code linting
npm run lint

# Preview the production build
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # Reusable components
│   ├── ClipPathTitle.jsx
│   ├── FlavorSlider.jsx
│   ├── FlavorTitle.jsx
│   ├── NavBar.jsx
│   └── VideoPinSection.jsx
├── sections/           # Main page sections
│   ├── HeroSection.jsx
│   ├── BenefitSection.jsx
│   ├── FlavorSection.jsx
│   ├── NutritionSection.jsx
│   ├── TestimonialSection.jsx
│   ├── MessageSection.jsx
│   └── FooterSection.jsx
├── constants/          # Constants and data
├── App.jsx            # Main component
├── main.jsx           # Entry point
└── index.css          # Global styles
```

## 🎯 Main Sections

- **HeroSection** : Landing section with introduction animation
- **BenefitSection** : Product benefits presentation
- **FlavorSection** : Interactive flavor gallery with slider
- **NutritionSection** : Nutritional information
- **TestimonialSection** : Customer testimonials
- **MessageSection** : Call-to-action or promotional message
- **FooterSection** : Footer with links and information

## 🌐 Deployment

To deploy the production version:

```bash
npm run build
```

Compiled files will be available in the `dist/` folder.

## 📱 Responsiveness

The project uses Tailwind CSS and React Responsive to ensure an optimal experience on:
- Mobile devices (320px and above)
- Tablets (768px and above)
- Desktops (1024px and above)

## 💡 Development Notes

- GSAP animations are integrated via `@gsap/react` for better React integration
- Images and videos are stored in the `public/` folder
- Custom fonts are imported from Google Fonts
<!-- Development commit 1 -->
<!-- Development commit 2 -->
