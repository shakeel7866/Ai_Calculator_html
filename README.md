# 🧮 AI Calculator Pro v2.0

A feature-rich, dark-themed calculator web app with AI assistance, graphing, finance tools, and smart notes — all in one sleek inter

## ✨ Features
<img width="209" height="293" alt="Screenshot 2026-06-24 024638" src="https://github.com/user-attachments/assets/9f0027a6-6179-4ea8-b973-1f40242d04c8" />


### 🔢 Calculator Tab
- Standard arithmetic with live preview display
- **Scientific mode** — sin, cos, tan, log, ln, √, π, e
- **Trigonometry mode** — all trig functions + degree converter
- **Constants mode** — π, e, φ (golden ratio), speed of light, gravity, Planck's constant, electron charge
- **History mode** — tap any past result to reload it
- Quick-access chips for %, x², √x, ×π, ×1K

### 📈 Graph Tab
- Plot any mathematical function (sin, cos, x², etc.)
- Real-time canvas rendering with grid lines
- **Linear Equation Solver** — e.g. `2x + 5 = 15`

### 💰 Finance Tab
- **Loan Calculator** — monthly payment, total payment, total interest
- **Investment Calculator** — future value with compound interest + monthly contributions
- **Rate Finder** — find the annual/monthly rate needed to reach a financial goal

### 📝 Notes Tab
- Write freeform notes or math expressions
- **⚡ Calc** — evaluates math expressions inline
- Copy, rename, clear, and skip-line shortcuts

### 🤖 AI Tab (Powered by Claude)
- Ask any math or finance question in plain English
- Conversational memory (up to 20 messages)
- Quick-access suggestion chips
- Powered by `claude-sonnet-4-6` via Anthropic API

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/ai-calculator-pro.git
cd ai-calculator-pro
```

### 2. Open the App
This is a single-file HTML app — no build step required.

```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Serve with a local server (recommended)
npx serve .
# or
python -m http.server 8000
```

### 3. Enable AI Features (Optional)
The AI tab requires an [Anthropic API key](https://console.anthropic.com/).

The app already calls the Anthropic API — just make sure your deployment environment has access or use a proxy.

> ⚠️ **Security Note:** Do not hardcode your API key in public repositories. Use environment variables or a backend proxy in production.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom dark theme, CSS variables) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | [Tabler Icons](https://tabler.io/icons) |
| AI | [Anthropic Claude API](https://docs.anthropic.com/) (`claude-sonnet-4-6`) |
| Graphing | HTML5 Canvas API |


## 📐 Supported Math Functions

| Function | Input Example | Description |
|----------|--------------|-------------|
| `sin(x)` | `sin(30)` | Sine |
| `cos(x)` | `cos(60)` | Cosine |
| `tan(x)` | `tan(45)` | Tangent |
| `sqrt(x)` | `sqrt(144)` | Square root |
| `log(x)` | `log(100)` | Base-10 logarithm |
| `ln(x)` | `ln(2.718)` | Natural logarithm |
| `x**2` | `5**2` | Power/exponent |
| `Math.PI` | `2*Math.PI` | Pi constant |
| `Math.E` | `Math.E**2` | Euler's number |

## 💡 Usage Examples

**Calculator:**
```
3 * (4 + sqrt(16)) = 24
sin(Math.PI / 2) = 1
```

**Equation Solver:**
```
3x + 6 = 21  →  x = 5
```

**Graph:**
```
sin(x)
x**2 - 4
cos(x) * 2
```

**AI Assistant:**
```
"Solve 3x² - 5 = 22"
"What is compound interest?"
"15% tip on $47.50"
"Explain the derivative of sin(x)"

## 🤝 Contributing

Pull requests are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Shakeel**  
CS Student — Shaheed Benazir Bhutto University (SBBU)  
📍 Sindh, Pakistan
> Built with ❤️ using HTML, CSS, Vanilla JS, and Claude AI
