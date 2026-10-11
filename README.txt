VAYA JAVA LAB — QUICK START

Included files
- index.html: the complete interactive learning site. CSS and JavaScript are included in this file; the custom robot GLB is embedded inside it.
- VAYA-Java-Robot.glb: standalone copy of the custom 3D robot model, with arm nodes for waving.
- manifest.webmanifest, sw.js, vaya-icon.svg, vaya-icon-192.png, vaya-icon-512.png: Progressive Web App icon/install/offline-shell assets.
- VAYA-Spoken-Content-and-Code.txt: the Java teaching topics and code examples separated from UI/design requirements.

Run locally
- Open index.html in a modern browser. Lesson content, navigation, code highlighting, simulated output, and the CSS robot fallback work locally.
- The enhanced GLB/Three.js renderer loads Three.js modules from jsDelivr; internet access is needed for that enhanced renderer. If the CDN cannot load, a CSS animated robot fallback remains visible.
- Browser speech synthesis uses voices installed/provided by the device/browser. Bengali voice availability and quality differ by device; the page does not call a paid Google API.

Install as an app
- Deploy all files to an HTTPS site (for example, the root of GitHub Pages), then open it in a supported browser and choose Install/Add to Home Screen. Service workers do not run from file://.

Honest Run-demo behaviour
- “Run demo” displays the expected output for the lesson. This page does not include an actual Java compiler and does not compile arbitrary Java code entered by a visitor.

Content/image note
- The conversation message refers to three screenshots/images, but no images were attached in the current chat. Therefore the example code was not image-matched. The Java examples were normalized into valid Java syntax and technically clarified where needed.
