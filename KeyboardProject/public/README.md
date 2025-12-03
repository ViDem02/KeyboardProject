# ⌨️ Typing Trainer — US International Keyboard (French)

A sleek, customizable typing practice web app built for mastering the **US International keyboard** while typing **French text**.

This project helps users type accented characters correctly (like `é`, `è`, `à`, `ç`, etc.) and measure their **speed**, **accuracy**, and **progress over time**.  
Perfect for students, language learners, or anyone improving bilingual typing proficiency.

---

## 🌟 Features

### 🧠 Smart Typing Practice
- Type any **French text** (default example: *Le matin, Théo se lève à six heures*).
- Automatically converts accents (e.g., `è` → `` `e``) for validation against the US International keyboard layout.
- Visual feedback:
  - ✅ Correct characters are shown in **green**.
  - ❌ Mistakes appear in **red**.
  - Accent dead keys (`'`, `"`, `~`, `` ` ``, `,`) don’t trigger false errors.

### ⏱️ Real-Time Stats
- **Live WPM counter** (Words Per Minute) updates dynamically.
- **Timer** tracks total typing duration.
- **Color-changing WPM**: transitions from 🔴 red (slow) to 🟢 green (fast).
  - Thresholds (default 40–90) can be customized in the UI.

### ⚙️ Practice Options
- **Restart button** to retry the same exercise.
- **Disable Backspace** mode for strict practice sessions.
- **Error logging**: view which characters were mistyped, and where.

### 💾 Data Management
- **Export** typing history as a JSON file.
- **Import** previous stats back into the app.
- Each session stores:
  - WPM
  - Mistake count
  - List of individual errors
  - Whether Backspace was disabled
  - Date & time

### 🎨 Modern UI
- Styled with **Bootstrap 5** and **custom CSS gradients**.
- Responsive design:
  - Margins adapt automatically (20% on large screens, none below 500 px).
- Light, elegant color palette for readability and focus.

---

## 🧩 Technologies Used

| Component | Technology |
|------------|-------------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| UI Framework | Bootstrap 5 |
| Typography | System fonts (clean, legible sans-serif) |
| File Handling | JSON import/export |
| Animations | CSS transitions and dynamic color gradients |

---

