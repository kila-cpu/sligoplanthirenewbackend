# Sligo Plant Hire — Workshop Job Cards (Backend Demo)

Interactive back-office **Workshop Job Cards** page for **McMunn Sligo Plant Hire & Haulage Ltd.**

The former separate *Machine Service Log* and *Tyre Fitter* modules are combined into one
job-cards table. Tyre work is a **work type** inside a job sheet, so jobs are categorised as:

- **Plant** / **Vehicle** — mechanical service, repair, breakdown or inspection.
- **Tyre Plant** / **Tyre Vehicle** — tyre fit, repair, rotation or inspection.

Features: searchable table, **Add Plant Job Sheet** / **Add Vehicle Job Sheet** forms with a
smart mechanical/tyre section toggle, view detail, delete confirmation, and PDF/edit hooks.

## Run locally

```bash
npm start
```

Then open http://localhost:3000

## Deployment (Railway)

Railway auto-detects the Node app and runs `npm start`. The static `index.html` is served on the
port provided by `process.env.PORT`. No build step or environment variables required.
