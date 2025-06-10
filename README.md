# Sudoku Solver 

A beautiful, responsive web-based Sudoku puzzle solver with an authentic Indian design theme. This application allows users to fetch new puzzles and automatically solve them using advanced algorithms.

## ✨ Features

- **Fetch New Puzzles**: Get fresh Sudoku puzzles with varying difficulty levels (easy, medium, hard, random)
- **Auto-Solve**: Intelligent backtracking algorithm to solve any valid Sudoku puzzle
- **Indian Theme**: Beautiful design inspired by Indian traditions, colors, and motifs
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive UI**: Clean, modern interface with helpful side panels
- **Rules & Hints**: Built-in guide with rules, strategies, and playing tips

## 🎨 Design Highlights

- **Authentic Indian Colors**: Saffron, green, peacock blue, maroon, and gold palette
- **Traditional Motifs**: Mandala patterns, peacock feathers, and diya icons
- **Sanskrit Quotes**: Inspirational messages in Devanagari script
- **Cultural Elements**: Design elements that celebrate Indian heritage

## 🚀 Technologies Used

- **HTML5**: Semantic structure and accessibility
- **CSS3**: Advanced styling with gradients, shadows, and responsive design
- **JavaScript**: Puzzle fetching, solving algorithms, and DOM manipulation
- **External API**: Sudoku puzzle generation via sugoku.onrender.com

## 📁 File Structure

```
sudoku-solver/
├── index.html          # Main HTML file with Indian-themed layout
├── style.css           # CSS file with Indian design theme
├── Script.js           # JavaScript for puzzle logic and solving
├── logo.png           # Project logo (add your own)
└── README.md          # This file
```

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pre-18/Sudoku-solver.git
   cd sudoku-solver
   ```

2. **Add your logo**
   - Place your logo image as `logo.png` in the root directory
   - Recommended size: 100x100 pixels

3. **Open in browser**
   - Simply open `index.html` in any modern web browser
   - No server setup required - it's a client-side application

## 🎮 How to Use

1. **Get a New Puzzle**
   - Click the "Get Puzzle" button to fetch a new Sudoku puzzle
   - The difficulty is set to "easy" by default (can be modified in code)

2. **Solve the Puzzle**
   - Click "Solve Puzzle" to automatically solve the current puzzle
   - The solution will be displayed on the grid

3. **Understanding the Grid**
   - **Orange cells (box1)**: First 3x3 sections
   - **Green cells (box2)**: Middle 3x3 sections  
   - **Blue cells (box3)**: Last 3x3 sections

## 🧠 Algorithm Details

The solver uses a **backtracking algorithm** with the following approach:

- **Constraint Checking**: Validates row, column, and 3x3 box rules
- **Recursive Solving**: Tries numbers 1-9 in each empty cell
- **Backtracking**: Undoes moves when no valid solution is found
- **Optimization**: Skips pre-filled cells for efficiency

## 🌐 API Information

- **Puzzle Source**: [Sugoku API](https://sugoku.onrender.com/)
- **Endpoint**: `https://sugoku.onrender.com/board?difficulty=easy`
- **Difficulty Levels**: `easy`, `medium`, `hard`, `random`

## 🎯 Side Panel Guide

### Left Panel - Rules & How to Play
- Complete rules of Sudoku
- Step-by-step playing instructions
- Cultural quote: "सत्यमेव जयते" (Truth Alone Triumphs)

### Right Panel - Hints & Strategy
- Solving techniques and tips
- Strategic approaches for beginners
- Cultural quote: "धैर्यं सर्वत्र साधनम्" (Patience accomplishes everything)

## 📱 Responsive Features

- **Desktop**: Full three-panel layout with side guides
- **Tablet**: Adjusted grid size and stacked panels
- **Mobile**: Compact single-column layout
- **Touch-Friendly**: Optimized for touch interactions

## 🛠️ Customization

### Changing Difficulty
In `Script.js`, modify the API call:
```javascript
xhrRequest.open('get', 'https://sugoku.onrender.com/board?difficulty=medium')
```

### Color Themes
The CSS uses CSS custom properties. You can easily modify colors by updating the color values in `style.css`.

### Adding Features
- Input validation for manual number entry
- Timer functionality
- Hint system
- Multiple puzzle storage

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 🙏 Acknowledgments

- **Sugoku API** for providing free Sudoku puzzles
- **Indian Cultural Heritage** for design inspiration
- **Open Source Community** for tools and resources

## 📞 Contact

Your Name - emailtanjiro7@gmail.com

Project Link: [https://github.com/Pre-18/Sudoku-solver.git]
---

**It was my first project**
