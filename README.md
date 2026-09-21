# tejal — portfolio

Personal portfolio site (single-file, static HTML). No build step.

## Run locally
Just open `index.html` in a browser, or serve it:
```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy
Hosted on Vercel as a static site (root `index.html`). Pushing to the
`main` branch auto-deploys.

## Analytics
Vercel Web Analytics + Speed Insights are enabled in the Vercel dashboard.
The `/_vercel/insights` and `/_vercel/speed-insights` script tags in
`index.html` start reporting once Analytics is turned on for the project.
