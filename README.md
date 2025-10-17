# 🍞 Toasty Meals

A fun, interactive meal decision app that uses a toaster metaphor to help you decide what to cook today!

## ✨ Features

- 🎰 **Random Meal Selection** - Pull the lever or click the button to get a random meal suggestion
- 🌓 **Light & Dark Mode** - Gorgeous themes with custom backgrounds for each
- 💾 **Persistent Storage** - Your meals are saved locally
- ⌨️ **Keyboard Support** - Press Space to toast!
- 🎯 **Simple & Fun** - No decision fatigue, just pull and go!

## 🚀 Live Demo

[View Live Demo](https://newnadik.github.io/ToastyMeals/) <!-- Update with your GitHub Pages URL -->

## 🎮 How to Use

1. **Add Your Meals**: Click the menu icon (☰) to add your favorite meals to the list
2. **Pull the Lever**: Drag the lever down or click the "What to cook today?" button
3. **Watch the Magic**: The bread lowers into the toaster, the timer ticks, and your meal pops up!
4. **Get Cooking**: Follow the toaster's suggestion and enjoy your meal! 🍽️

## 🛠️ Tech Stack

- **React** - UI framework
- **Tailwind CSS** - Styling
- **LocalStorage** - Data persistence
- **Vanilla HTML/CSS/JS** - No build process needed!

## 📦 Installation

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to Settings → Pages
3. Select "main" branch as source
4. Your app will be live at `https://your-username.github.io/toasty-meals`

### Option 2: Local Development

1. Clone the repository:
```bash
git clone https://github.com/your-username/toasty-meals.git
cd toasty-meals
```

2. Open `index.html` in your browser:
```bash
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

That's it! No build process or dependencies needed.

## 📁 Project Structure

```
toasty-meals/
├── index.html              # Main HTML file (contains all code)
└── images/
    ├── background.png      # Light mode background
    ├── background_dark.png # Dark mode background
    ├── toaster_body.png    # Toaster illustration
    ├── toaster_knob.png    # Timer dial
    ├── toaster_leverage.png # Lever handle
    └── toast.png           # Bread/toast illustration
```

## 🎨 Customization

### Change Default Meals

Edit the `DEFAULT_MEALS` array in `index.html`:

```javascript
const DEFAULT_MEALS = ['Pizza', 'Pasta', 'Sandwich'];
```

### Change Colors

Modify the background colors in the main div style:

```javascript
backgroundColor: theme === 'light' ? '#fef1d6' : '#1a1a1a'
```

### Replace Images

Simply replace the images in the `/images/` folder with your own. Keep the same filenames and dimensions for best results.


## 🙏 Acknowledgments

- Inspired by the daily struggle of "What should I eat?"
- Built with love and a bit of hunger 🍕


Made with 🍞 and ❤️

**Bon Appétit!** 👨‍🍳