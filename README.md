# 5iveLevels Cohesion Assessment

A facilitated leadership assessment from 5iveDays Strategy. A VP or director answers first, then their directors, managers and team members answer the same 14 questions blind. The readout shows where leadership and the organization agree, where they don't, and what to do next.

## Files

| File | What it holds |
|---|---|
| `index.html` | Page shell: header, step rail and the main area the app draws into |
| `assets/styles.css` | Colors, type and layout for light and dark mode |
| `assets/framework.js` | All assessment wording: levels, layers, the 14 questions, answer descriptions, evidence, root causes, next steps, the AI adviser brief and the sample company |
| `assets/app.js` | The engine: interview flow, scoring rules, flags, readout, Markdown report and saved sessions |
| `assets/config.js` | Site settings, such as the address for the live AI conversation |
| `netlify.toml` | Netlify settings: no build step, publish the root folder |

## Deploying

Netlify imports this repository with no build command. Every commit to the main branch redeploys the site.

## Data

Answers are saved in the browser of whoever runs the session, separately for each site address. Nothing is sent to a server unless the Enhanced Report is turned on and the facilitator chooses to start it.
