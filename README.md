# Edi

Developer focused on porting open-source PC and web games to Android.

I adapt desktop-first and browser games for mobile devices—implementing multi-touch controls, resolving display and viewport scaling across modern aspect ratios, and optimizing runtime performance and audio lifecycle handling.

---

### Featured Ports

#### [Mari0 Android](https://github.com/ediussss/mari0-android)
Android port of Stabyourself's *Mari0* (Super Mario Bros. mechanics combined with Portal).
* **Stack:** LÖVE 11.5, LuaJIT, SDL2 Android runtime
* **Key Work:**
  * Implemented an on-screen multi-touch HUD with virtual D-pad, action buttons, and direct touch-to-aim portal firing.
  * Resolved viewport letterbox translation conflicts between `love.graphics.setScissor` and non-standard screen dimensions.
  * Packaged as a standalone APK targeting Android 5.0+ (API 21–34).
* [View Repository](https://github.com/ediussss/mari0-android) · [Download Releases](https://github.com/ediussss/mari0-android/releases)

#### [Phaser 3 Space Shooter](https://github.com/ediussss/phaser-3-space-shooter)
Mobile adaptation of DevShareAcademy's vertical arcade space shooter.
* **Stack:** Phaser 3, Capacitor 6, Android API 34
* **Key Work:**
  * Designed touch drag-to-steer controls with auto-fire toggles for one-handed portrait gameplay.
  * Hooked Android `MainActivity` lifecycle events with Web Audio pause/resume listeners to prevent background battery drain.
  * Added responsive canvas scaling with automatic letterboxing for tall smartphone displays.
* [View Repository](https://github.com/ediussss/phaser-3-space-shooter) · [Download Releases](https://github.com/ediussss/phaser-3-space-shooter/releases)

---

### Technologies

* **Platforms & Runtimes:** Android SDK, Capacitor, LÖVE 2D Android Runtime, Linux
* **Engines:** LÖVE 2D, Phaser 3
* **Languages:** Lua, JavaScript, Java, Bash
* **Tooling:** Git, Gradle, Android NDK/SDK Build Tools

---

### Activity

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=ediussss&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ediussss&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
</p>
