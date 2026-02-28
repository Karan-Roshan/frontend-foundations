# CSS City Skyline
A responsive **city skyline** built entirely with **HTML5 + CSS3**, featuring layered buildings, window patterns using gradients, and a dynamic day/night theme that adapts based on screen size.


## Preview
- Day Skyline
<p align="center">
  <img src="https://github.com/Karan-Roshan/City-Skyline/blob/974aef7f55ebc5a16e762f293f60f6b0a40c4ef8/Photos/Day%20Skyline.png" 
       alt="Day Skyline" 
       width="300">
</p>

- Night Skyline
<p align="center">
  <img src="https://github.com/Karan-Roshan/City-Skyline/blob/af37b45d97ab79945c85f4c29e32f453fe3bab04/Photos/Night%20Skyline.png" 
       alt="Night Skyline" 
       width="300">
</p>

## Features
- **Customizable Colors** – Uses CSS variables (`:root`) for easy theming of buildings and windows.  
- **Layered Depth** – Background and foreground building groups create a skyline effect.  
- **Realistic Windows** – Achieved with **repeating-linear-gradient** for horizontal + vertical criss-cross windows.  
- **Responsive Theme** –  
  - Large screens → colorful daytime skyline with sun + sky gradient.  
  - Small screens (`< 1000px`) → dark silhouette with grey windows (night mode).  
- **Responsive Design** – Works across different screen sizes.


## Project Structure
- index.html       # Main HTML file
- styles.css       # CSS for layout, buildings, and sky
- README.md        # Project documentation

### **HTML Overview (`index.html`)**
- **`.background-buildings.sky`** → Holds background buildings (`bb1–bb4`) with gradients and simple window patterns.  
- **`.foreground-buildings`** → Contains foreground buildings (`fb1–fb6`) with more detailed window grids and rooftop styles.  
- **`.building-wrap`** → Groups building sections vertically.  
- **`.window-wrap`** → Wraps rows of windows for alignment.

### **CSS Overview (`styles.css`)**
- **CSS Variables (`:root`)** → Define building and window colors.  
- **Sky Gradient** → Radial gradient for sun + sky.  
- **Building Classes (`bb*`, `fb*`)** →  
  - Use **linear gradients**, **repeating-linear-gradients**, and **border tricks** to create rooftops, windows, and structures.  
- **Media Query (`@media max-width: 1000px`)** → Switches to dark/night theme.  


## Technologies Used
- **HTML5** – Page structure.  
- **CSS3** – Layout, gradients, shapes, responsiveness.  
- **Flexbox** – Aligns and spaces buildings evenly.  
- **CSS Gradients** – Simulates windows, sky, and building textures.


# Connect with Me
- LinkedIn: www.linkedin.com/in/karanroshan
- Email: karanroshan91@gmail.com
