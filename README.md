<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=6,11,20&amp;height=200&amp;text=HTML%20Experiments&amp;fontSize=48&amp;fontColor=fff&amp;animation=twinkling&amp;fontAlignY=38&amp;desc=Vanilla%20HTML%20%7C%20CSS%20%7C%20JavaScript%20Playground&amp;descAlignY=58&amp;descSize=16&amp;descColor=fff"/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black"/>
<img src="https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&amp;logo=github&amp;logoColor=white"/>

**[🚀 Live Demo →](https://evans-0.github.io/HTML-Experiments/)**

</div>

---

A collection of small, focused HTML/CSS/JS experiments — each file is self-contained, zero-dependency, and runs directly in the browser. Built to explore what's possible with just the fundamentals.

---

## 🧪 Experiments

### 🎨 Background Color Changer — [`bgcolor.html`](./bgcolor.html)
A 6-line HTML experiment that demonstrates how minimal code can produce interactive behaviour. Type a CSS color name (e.g. `red`, `cornflowerblue`) or a hex code (e.g. `#ff5733`) and the page background updates **in real time** on every keystroke.

**How it works:**
```html
<body onkeyup="document.bgColor=document.f.a.value">
  <form name="f">
    <input type="text" name="a">
  </form>
</body>
```
A single `onkeyup` attribute wires the input directly to `document.bgColor` — no JavaScript file, no framework, no build step.

---

### 🎆 Fireworks Generator — [`fireworks.html`](./fireworks.html)
A full canvas-based fireworks animation built with vanilla JavaScript. Click anywhere to launch fireworks at that exact position, or let the auto-launcher do it for you.

**Features:**
- 🖱️ **Click-to-fire** — launch fireworks at any point on screen
- 🤖 **Auto-launch mode** — continuously fires at random positions
- 🎛️ **Particle count slider** — control explosion density (50–500 particles)
- 🔄 **Reset button** — clear the canvas instantly
- 🌈 **Colour cycling** — HSL hue shifts on every launch for rainbow fireworks
- 🌙 **Trailing effect** — `destination-out` composite operation creates the fade

**Under the hood:**
- `Firework` class — rocket that accelerates toward a target using trigonometry
- `Particle` class — explosion sparks with friction, gravity, and fade
- `requestAnimationFrame` loop — smooth 60fps rendering
- Glassmorphism control panel — `backdrop-filter: blur(10px)`

---

## 🚀 Running Locally

No setup needed. Just clone and open in a browser:

```bash
git clone https://github.com/evans-0/HTML-Experiments.git
cd HTML-Experiments
open index.html          # macOS
# or
xdg-open index.html     # Linux
```

Or visit the live site: **[evans-0.github.io/HTML-Experiments](https://evans-0.github.io/HTML-Experiments/)**

---

## 📁 Structure

```
HTML-Experiments/
├── index.html       # Landing page (GitHub Pages entry point)
├── bgcolor.html     # Background color changer
├── fireworks.html   # Canvas fireworks animation
└── README.md
```

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=6,11,20&amp;height=100&amp;section=footer"/>
</div>
