Jeremy's Line (portfolio)

A train-journey portfolio: transit-map navigation, a different landscape at every station,
a lo-fi soundtrack with synthesized train sounds, a passport stamp collection and three mini games.
Plain HTML, CSS and JavaScript. No build step, no libraries.

Files
| File | What it holds |
|------|---------------|
| `index.html` | The page structure (title screen, nav, hero, map container). |
| `style.css`  | All the design: colors (`:root` variables at the top), layout, fonts, animations. |
| `script.js`  | Everything that moves: navigation, train travel, map, background landscapes, games, audio. |

Keep the three files in the same folder.


The fonts come from Google Fonts, so you need an internet connection to see them.
Without it the page still works and falls back to system fonts.

Make it yours
Open `script.js` and edit the **`CFG`** block near the top:
- `name`, `status`, `email`, `github`, `linkedin`, `resume` (a link to your resume; `'#'` shows a reminder)
- `roles`, the lines that get typed on the home screen
- `bio` and `about2`, your story
- `skills`, a list of `[name, percent]`
- `projects`, each with title, tagline, year, role, problem, approach, result, numbers and tech

All the names, projects and numbers included are placeholders.

Other things you may want to change:
- **Colors:** the `:root { ... }` block at the top of `style.css`.
- **Station names and times:** the `ST` object in `script.js`.
- **Map shape:** the `route` path in the "Transit map" section of `script.js`.
- **Landscapes:** the `SC` object in the "Landscape background" section (sky colors, sun, hills, scenery type).
- **Music and sound levels:** the "Audio" and "Train audio" sections.


Notes
- Sound starts after you press "All aboard", because browsers block audio until you interact with the page.
- If your device is set to "reduce motion", the big train effects are replaced by quick fades.
- Your passport stamps are saved in the browser (localStorage).
- The contact form opens your email app (a `mailto:` link). It has no server behind it.
