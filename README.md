# 3D Flip Card | HTML & CSS ✨

Daily CSS/HTML code from [@b.bty.coder](https://facebook.com/bbtycoder.dev) Facebook reels 💚

## 🚀 Live Demo
**[View Live Demo](https://b-bty-coder.github.io/3d-flip-card/)**

## 📸 Preview
![3D Flip Card Demo](demo2.gif)  
*Hover effect: Card flips 180° on mouse hover*

## 🛠️ Built With
- HTML5
- CSS3
- CSS Transforms & Transitions
- Perspective & 3D Effects

## ✨ Features
- ✅ Pure HTML/CSS - No JS
- ✅ Smooth 3D flip animation on hover
- ✅ Front & back face design
- ✅ Responsive design
- ✅ `backface-visibility` + `transform-style: preserve-3d`

## 📂 Reel #2 - 3D Flip Card
**HTML | CSS** files included

Hover over the card to see the 3D flip effect. Built with pure CSS transforms.

## 🎯 How It Works
1. **Front face** - Visible by default
2. **Hover** - Card rotates 180° on Y-axis 
3. **Back face** - Shows hidden content
4. **`perspective`** - Adds 3D depth to animation

## 💻 Code Highlights
```css
.main-container:hover .thecard {
  transform: rotateY(180deg);
}
.theback {
  transform: rotateY(180deg);
  backface-visibility: hidden;
}
