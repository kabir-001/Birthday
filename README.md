
# For My Queen | Happy Birthday Website

This is a **premium single-page birthday website** designed as a gift. It includes cinematic sections, animations, a premium gallery, floating petals, music, and a heartfelt message section. The design is **fully responsive**, optimized for desktop and mobile devices.

---

## Features

1. **Hero Section**
   - Full-screen background image.
   - Animated heading with gold gradient text.
   - Cinematic typography and spacing.

2. **Countdown Timer**
   - Displays days, hours, and minutes until the birthday.
   - Dynamic and automatically updates.

3. **Premium Bento Gallery**
   - Grid-based layout with responsive columns.
   - Hover captions on desktop.
   - **Lightbox effect**: click/tap to zoom images with gold overlay.
   - Mobile-friendly touch tap to view images.

4. **Floating Rose Petals**
   - Animated particles falling gently.
   - Reduced particle count on smaller devices for performance.

5. **Music Player**
   - Plays background music automatically.
   - Play/Pause toggle button.
   - Custom gold pulse indicator.

6. **Message Section**
   - Centered framed quote with gold border.
   - Rounded corners and elegant typography.

7. **Custom Cursor**
   - Gold circle following the mouse on desktop.

8. **Mobile Responsiveness**
   - Adjusts font sizes, grid layout, countdown stacking, and music player for all screen sizes.
   - Ensures smooth animations on mobile.

---

## How to Use

1. **Download the project** or copy the HTML file.
2. **Add your images**:
   - Replace `image1.jpg`, `image2.jpg`, … with your personal photos in the `gallery-grid`.
3. **Add your music**:
   - Replace `your_song.mp3` with your preferred audio file.
4. **Set the birthday date**:
   - Open the `<script>` section.
   - Update the line:  
     ```javascript
     const birthday = new Date("Jan 19, 2026 00:00:00").getTime();
     ```
     Replace with the correct date and time.
5. **Open in browser**:
   - Simply open the HTML file in any modern browser (Chrome, Firefox, Safari, Edge).

---

## Customization Tips

- **Gallery captions**: update `data-caption` attribute in each `.bento-item`.
- **Hero text**: change the text inside the `#hero` section.
- **Colors**: modify CSS variables in `:root`:
  ```css
  --gold: #c5a059;
  --dark-gold: #8e6d2f;
  --black: #050505;

Particle count: adjust in JS for performance:

let petalCount = window.innerWidth < 768 ? 20 : 40;



---

Dependencies

GSAP (GreenSock Animation Platform) for animations:

<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>

No other libraries needed. Fully self-contained.



---

License

This project is for personal use only. Do not redistribute without permission.


---

Author

Created by Kabir Singh as a personalized premium birthday website.

