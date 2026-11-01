AU MATHEMATICS FRESHERS PARTY — AR INVITATION

WHAT THIS DEMO DOES
When the camera recognizes your invitation card, small 3D flowers grow out from it and pink petals float around it. It uses MindAR image tracking and A-Frame. The flowers are made from simple 3D shapes, so you do not need to buy or download a 3D model.

IMPORTANT: ONE REQUIRED SETUP STEP
MindAR needs a tracking file called targets.mind. I cannot generate that file inside this package because the MindAR compiler runs in your browser.

1. Open this compiler page:
   https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2. Upload freshers-invitation.png (the exact card image included here).
3. Press Start and wait for compilation to finish.
4. Download targets.mind.
5. Put targets.mind in this same folder, beside index.html.

HOW TO TEST / PUBLISH
- Camera access requires HTTPS (or localhost).
- Easiest publishing: create a free GitHub repository, upload index.html, freshers-invitation.png and targets.mind, then enable GitHub Pages in Settings > Pages.
- Open the GitHub Pages HTTPS link on your phone, tap Start AR experience, allow camera access, and point the camera at the printed card.
- Print the same image used for compilation. Use a matte print, good lighting, and keep the whole card in view.

CUSTOMIZATION
The flowers and floating petals are procedural 3D shapes in index.html. Colors, positions and animation timings can be adjusted there. This is a starter demo, not a finished hosted website; you must compile targets.mind and publish the folder before scanning it with your phone.

LIBRARIES LOADED FROM CDN
A-Frame 1.6.0 and MindAR 1.2.5. Internet is required when the AR page loads.
