# 🏆 Seller Awards Announcement — LIVE SHOP Vonder

A web application developed for the **Grupo OVD LIVE SHOP Vonder** to showcase previously selected award winners through a cinematic presentation with animated reveals, visual effects, and background music.

**This application does not perform random draws.** All winners and prizes are predefined.

## ✨ Features

- Team-based winner organization (Manager, Coordinator, and Salesperson).
- Cinematic winner and prize reveals.
- Animated cards, lighting effects, and confetti.
- Background music and synthesized sound effects.
- CSV file import and spreadsheet data paste.
- Data review, editing, and deletion before confirmation.
- Final summary of all winners and prizes.
- Responsive layout and full-screen presentation.
- Local data persistence using `localStorage`.
- Keyboard shortcuts for presentation control.

## 📊 Data Format

Each row represents one team and must contain six columns:

| **Manager** | **Prize** | **Coordinator** | **Prize** | **Salesperson** | **Prize** |
| ----------- | --------- | --------------- | --------- | --------------- | --------- |
|             |           |                 |           |                 |           |
|             |           |                 |           |                 |           |

Supports CSV files (`;` or `,`) and tab-separated spreadsheet data.

## 🎬 Presentation Flow

1. Welcome screen.
2. Team introduction.
3. Winner name reveal.
4. Prize reveal with cinematic effects.
5. Team winners summary.
6. Final awards overview.

The presenter manually controls the presentation. Winners are never randomly selected or modified by the application.

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Web Audio API
- LocalStorage

## 🚀 How to Run

1. Download `index_60_com_musica.html`.
2. Open it in Chrome, Edge, or Firefox.
3. Import a CSV file or paste spreadsheet data.
4. Review and confirm the winners.
5. Start the presentation.

**No installation, backend, or external audio files required.**

## ⚠️ Limitations

- No random winner selection.
- No database or cloud synchronization.
- No direct `.xlsx` import.
- No results export.
- Background music volume is fixed at 22%.
- Data is stored locally in the browser.

## 📁 Project Structure

The application is delivered as a single standalone HTML file, including embedded images, background music, styles, and scripts.
