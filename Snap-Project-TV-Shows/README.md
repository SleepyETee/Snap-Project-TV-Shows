# LA TV Shows Catalog

A dynamic, interactive catalog of TV shows set in Los Angeles. Built with vanilla HTML, CSS, and JavaScript, this project demonstrates proficiency in data structures, DOM manipulation, and modern web development practices.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🎬 Demo

[Live Demo](https://sleepyetee.github.io/Snap-Project-TV-Shows)

## ✨ Features

- **Filter by Genre** - Browse shows by Comedy, Drama, Reality, or Documentary
- **Search** - Real-time search across titles, descriptions, networks, and cast
- **Sort** - Order by name (A-Z), release year, or rating
- **Shuffle** - Randomize the catalog display
- **CRUD Operations** - Add, edit, and delete TV shows
- **Responsive Design** - Works on desktop and mobile devices
- **Visual Effects** - Animated starry background with particle effects

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, animations, and responsive design
- **JavaScript (ES6+)** - Array methods, DOM manipulation, event handling

## 📁 Project Structure

```
├── index.html      # Main HTML structure
├── style.css       # Styling and animations
├── scripts.js      # Application logic and data
├── README.md       # Project documentation
└── LICENSE         # MIT License
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Snap-Project-TV-Shows.git
   ```

2. **Open locally**
   ```bash
   cd Snap-Project-TV-Shows
   open index.html
   ```

3. **Or use a local server**
   ```bash
   npx serve .
   ```

## 📊 Data Model

Each TV show is represented as an object with the following properties:

| Property | Description |
|----------|-------------|
| `id` | Unique identifier |
| `name` | Show title |
| `category` | Genre (comedy, drama, reality, documentary) |
| `description` | Brief synopsis |
| `value` | Release year |
| `rarity` | Network/streaming service |
| `rating` | Rating out of 10 |
| `element` | Lead actor/actress or director |
| `bonusEffect` | Tagline or notable feature |
| `imageURL` | Poster image URL |

## 🎯 Key Implementations

- **Fisher-Yates Shuffle** - Efficient randomization algorithm
- **Debounced Search** - Optimized real-time search performance
- **Dynamic Card Rendering** - Template cloning pattern for efficient DOM updates
- **Responsive Grid Layout** - CSS Grid with auto-fill for adaptive layouts

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Built as part of the Snap Engineering Academy program.*

