# Language Learning Game

A comprehensive web application for interactive language learning through games, quizzes, and educational modules.

## Features

### Core Features
- **Home Page**: Landing page with introduction and call-to-action
- **Learning Modules**: Interactive learning activities including:
  - Vocabulary Builder (Flashcards)
  - Grammar Quizzes
  - Pronunciation Practice
  - Timed Language Challenges
- **User Authentication**: Sign up and login functionality with form validation
- **About Page**: Information about the platform and team
- **Contact Page**: Contact form with validation

### Additional Features
- **Progress Tracking**: Track your learning progress across modules
- **Responsive Design**: Fully responsive layout for desktop, tablet, and mobile
- **Dynamic Content**: JavaScript-powered interactive learning activities
- **Form Validation**: Comprehensive client-side validation for all forms
- **Level Filtering**: Filter modules by difficulty level (Beginner, Intermediate, Advanced)

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, flexbox, and grid
- **JavaScript (ES6+)**: Dynamic content and interactivity
- **LocalStorage**: Client-side data persistence

## Design

### Color Scheme
- Background: Light blue (#e0f7fa)
- Primary Button: Coral (#ff7043)
- Text: Dark gray (#263238)
- Highlight: Yellow (#fbc02d)
- Error: Red (#f44336)

### Typography
- Headings: Montserrat/Roboto
- Body: Arial/Helvetica

## File Structure

```
Language Learning Game/
├── index.html          # Home page
├── modules.html        # Learning modules page
├── signup.html         # User registration
├── login.html          # User login
├── about.html          # About page
├── contact.html        # Contact page
├── css/
│   └── style.css      # Main stylesheet
├── js/
│   ├── main.js        # General functionality
│   ├── validation.js  # Form validation
│   └── modules.js     # Learning modules logic
└── README.md          # This file
```

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required - works directly in the browser!

### Deployment

#### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and folder (usually `main` and `/root`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

#### Netlify
1. Sign up/login to Netlify
2. Drag and drop your project folder, or
3. Connect your GitHub repository
4. Deploy automatically

#### Vercel
1. Sign up/login to Vercel
2. Import your GitHub repository
3. Deploy with default settings

## Usage

### For Users

1. **Sign Up**: Create an account to track your progress
2. **Login**: Access your learning history
3. **Explore Modules**: Browse available learning modules
4. **Start Learning**: Click "Start Learning" on any module
5. **Track Progress**: Your scores and progress are saved automatically

### Learning Modules

- **Vocabulary Builder**: Flip flashcards to learn new words
- **Grammar Quizzes**: Answer multiple-choice grammar questions
- **Pronunciation Practice**: Listen and repeat words (uses Web Speech API)
- **Timed Challenges**: Test your speed with time-limited quizzes

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

Note: Pronunciation Practice uses the Web Speech API, which may not be available in all browsers.

## Data Storage

All user data (accounts, progress) is stored in the browser's LocalStorage. This means:
- Data persists between sessions
- Data is specific to each browser/device
- No server or database required

## Future Enhancements

- Backend integration for persistent data storage
- More language options
- Advanced progress analytics
- Social features and leaderboards
- Mobile app version

## License

This project is open source and available for educational purposes.

## Credits

Developed as a comprehensive web application project demonstrating modern HTML, CSS, and JavaScript practices.

---

**Note**: This is a frontend-only application. For production use, consider adding backend authentication and data storage.
