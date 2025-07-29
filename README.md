# Drive Landing Page

A beautiful, animated landing page inspired by the movie "Drive" featuring neon aesthetics, smooth animations, and a cinematic experience.

## 🎬 Features

### ✨ Animations & Interactions
- **Framer Motion Integration**: Smooth fade-in, slide-up, and stagger animations
- **Hover Effects**: Interactive buttons with scale and glow effects
- **Scroll-triggered Animations**: Elements animate as they come into view
- **Floating Background Elements**: Subtle animated circles for atmosphere

### 🎨 Design Elements
- **Neon Aesthetics**: Pink and blue color scheme inspired by the movie
- **Typography**: Orbitron font for headings (sci-fi feel) and Inter for body text
- **Gradient Backgrounds**: Dynamic color transitions
- **Glow Effects**: CSS animations for neon-like text and borders

### 📱 Responsive Design
- **Mobile-first Approach**: Optimized for all screen sizes
- **Flexible Grid System**: Adapts from 1 column (mobile) to 3 columns (desktop)
- **Touch-friendly Interactions**: Proper spacing and sizing for mobile devices

## 🚀 Sections

### 1. **Animated Navbar**
- Fixed position with backdrop blur
- Smooth entrance animations
- Responsive mobile menu button

### 2. **Hero Section**
- Full-screen gradient background
- Animated floating elements
- Large typography with glow effects
- Call-to-action button with hover animations

### 3. **Features Section**
- Three key features with icons
- Staggered entrance animations
- Hover lift effects on cards

### 4. **Characters Section**
- Character introductions with icons
- Alternating layout (left/right)
- Smooth scroll-triggered animations

### 5. **Call-to-Action Section**
- Dual button design
- Hover effects with glow
- Clear conversion focus

### 6. **Footer**
- Brand elements
- Links with hover states
- Fade-in animation

## 🛠️ Technologies Used

- **HTML5**: Semantic structure
- **Tailwind CSS**: Utility-first styling
- **Framer Motion**: JavaScript animation library
- **Google Fonts**: Orbitron and Inter typefaces

## 📁 File Structure

```
drive-landing-page/
├── index.html          # Main landing page
└── README.md          # Project documentation
```

## 🎯 Key Animation Features

### Framer Motion Components
- `motion.div`: Container animations
- `initial`: Starting state
- `animate`: Target state
- `transition`: Animation timing and easing
- `whileHover`: Interactive hover states
- `whileInView`: Scroll-triggered animations

### CSS Animations
- `@keyframes glow`: Text glow effect
- `@keyframes float`: Floating animation
- `animate-glow`: Tailwind animation class
- `animate-float`: Tailwind animation class

## 🎨 Color Palette

- **Primary Pink**: `#ff6b9d` (Drive pink)
- **Primary Blue**: `#1e3a8a` (Drive blue)
- **Dark Background**: `#0f172a` (Deep space)
- **Gray Text**: `#334155` (Subtle contrast)

## 📱 Responsive Breakpoints

- **Mobile**: `< 768px` (1 column layouts)
- **Tablet**: `768px - 1024px` (2 column layouts)
- **Desktop**: `> 1024px` (3 column layouts)

## 🚀 How to Use

1. **Open the file**: Simply open `index.html` in any modern web browser
2. **No build process required**: All dependencies are loaded via CDN
3. **Customize**: Modify colors, text, or animations in the HTML file
4. **Deploy**: Upload to any web hosting service

## 🎬 Movie Inspiration

This landing page captures the essence of "Drive" through:
- **Neon aesthetics** reminiscent of LA nightlife
- **Minimalist design** reflecting the Driver's character
- **Pink/blue color scheme** from the movie's iconic poster
- **Cinematic typography** with sci-fi elements
- **Smooth animations** that feel premium and polished

## 🔧 Customization

### Changing Colors
Modify the Tailwind config in the `<script>` tag:
```javascript
colors: {
    'drive-pink': '#your-pink-color',
    'drive-blue': '#your-blue-color',
    // ... other colors
}
```

### Adding Sections
Use the existing motion.div pattern:
```html
<motion.div 
    initial={{ opacity: 0, y: 50 }}
    whileInView={{ opacity: 1, y: 0 }}
    transition={{ duration: 0.8 }}
    viewport={{ once: true }}
>
    <!-- Your content here -->
</motion.div>
```

### Modifying Animations
Adjust Framer Motion props:
- `duration`: Animation length (seconds)
- `delay`: Wait time before animation starts
- `ease`: Animation curve ("easeOut", "easeIn", etc.)

## 🌟 Performance Notes

- **CDN Dependencies**: Fast loading via CDN
- **Optimized Animations**: Hardware-accelerated transforms
- **Lazy Loading**: Animations only trigger when elements are visible
- **Minimal JavaScript**: Lightweight and efficient

## 📄 License

This project is open source and available under the MIT License.

---

*"I drive." - The Driver* 