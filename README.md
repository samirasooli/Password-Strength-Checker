# 🔐 Password Strength Checker

A modern, interactive web-based password strength checker that helps users create secure passwords.

![Password Strength Checker](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- **Real-time password analysis** - See strength updates as you type
- **Visual progress indicator** - Color-coded strength meter
- **Common password detection** - Warns against frequently used passwords
- **Character type validation** - Checks for uppercase, lowercase, numbers, and special characters
- **Length-based scoring** - Rewards longer passwords
- **Password visibility toggle** - Show/hide password option
- **Responsive design** - Works on desktop and mobile devices
- **No data storage** - All processing happens locally in your browser

## 🚀 Demo

[View Live Demo](#) *(Add your GitHub Pages link here)*

## 📸 Screenshot

The password checker features:
- Clean, modern interface
- Real-time strength visualization
- Detailed requirements checklist
- Score from 0-7 based on multiple factors

## 🎯 Scoring System

The password is scored out of **7 points** based on:

### Length (4 points possible)
- +1 point for > 8 characters
- +1 point for > 12 characters
- +1 point for > 16 characters
- +1 point for > 20 characters

### Character Diversity (3 points possible)
- +1 point for 2+ character types
- +1 point for 3+ character types
- +1 point for all 4 character types

**Character types checked:**
- Uppercase letters (A-Z)
- Lowercase letters (a-z)
- Numbers (0-9)
- Special characters (!@#$%^&* etc.)

### Strength Categories
- **0-3 points**: Weak 🔴
- **4 points**: Okay 🟠
- **5 points**: Good 🟢
- **6-7 points**: Strong 🔵

## 🛠️ Installation

### Option 1: Direct Download
1. Download `password-checker.html`
2. Open it in any modern web browser
3. No installation or dependencies required!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/password-strength-checker.git
cd password-strength-checker
# Open password-checker.html in your browser
```

### Option 3: GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/password-strength-checker/`

## 💻 Usage

Simply open the HTML file in any modern browser:
- Chrome, Firefox, Safari, Edge all supported
- No server required
- No external dependencies
- Works completely offline

## 🔒 Privacy & Security

- **100% client-side** - All processing happens in your browser
- **No data transmission** - Passwords never leave your device
- **No tracking** - No analytics or external scripts
- **Open source** - Verify the code yourself

## 🎨 Customization

The entire app is in a single HTML file for easy customization:

### Change Colors
Edit the CSS gradient in the `<style>` section:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Modify Scoring
Adjust the scoring logic in the `checkPasswordStrength()` function:
```javascript
if (length > 8) score += 1;  // Change thresholds here
```

### Add More Common Passwords
Expand the `commonPasswords` array:
```javascript
const commonPasswords = [
    'password', '123456', // Add more here
];
```

## 📋 Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks needed
- **Responsive Design** - Mobile-friendly interface
- **Modern ES6+** - Clean, maintainable code
- **Single File** - Easy to deploy and share

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report bugs** - Open an issue
2. **Suggest features** - Share your ideas
3. **Submit pull requests** - Improve the code
4. **Expand common passwords list** - Add more patterns
5. **Improve UI/UX** - Design enhancements

## 📝 License

MIT License - feel free to use this in your own projects!

## 🙏 Acknowledgments

- Original Python implementation
- Inspired by password security best practices
- Built for educational purposes

## 📧 Contact

Questions or suggestions? Open an issue or reach out!

---

**⭐ If you find this useful, please star the repository!**
