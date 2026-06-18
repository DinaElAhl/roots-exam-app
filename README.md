# The Roots — Arabic & Quran Proficiency Assessment

A Duolingo-inspired, single-file web app for assessing Arabic Language and Quran (Tajweed) proficiency. Built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

🔗 **Live app:** [dinaelahl.github.io/roots-exam-app](https://dinaelahl.github.io/roots-exam-app/)

## Features

- 🎯 **Two tracks** — Arabic Language (6 levels) and Quran & Tajweed (4 levels)
- - 📚 **Prep phase** — Duolingo-style flashcards with key vocabulary and grammar tips before the exam
  - - ❤️ **Hearts system** — 5 lives per exam; lose a heart on each wrong answer
    - - ⚡ **Auto-advance** — pass a level and move up automatically; fail and stay to retry
      - - 🏆 **XP & streaks** — earn points and maintain daily streaks
        - - 📜 **Certificate** — awarded at your highest passing level
          - - 📱 **Responsive** — works on mobile, tablet, and desktop
            - - 🌙 **Dark/light theme** — respects `prefers-color-scheme` with a manual toggle
             
              - ## Tech Stack
             
              - | Layer | Technology |
              - |-------|------------|
              - | Frontend | Plain HTML5 + CSS3 + Vanilla JS |
              - | Hosting | GitHub Pages (auto-deploy on push to `main`) |
              - | Build | None — zero dependencies |
             
              - ## Project Structure
             
              - ```
                roots-exam-app/
                ├── index.html       # Entire app (HTML + CSS + JS, single file)
                └── README.md
                ```

                ## Running Locally

                Just open `index.html` in any browser — no server or build step needed.

                ```bash
                git clone https://github.com/DinaElAhl/roots-exam-app.git
                cd roots-exam-app
                open index.html
                ```

                ## Contributing

                Pull requests welcome. The app is intentionally a single-file architecture for simplicity and zero-dependency deployment.

                ## License

                MIT © Dina El Ahl
