# Sligo Plant Hire — Admin Backend Demo

Interactive back-office dashboard for **McMunn Sligo Plant Hire & Haulage Ltd.**, matching the existing AdminLTE-style admin, with two new modules added:

- **Machine Service Log** — mechanic job cards: machine/fault, work carried out, parts used, labour, sign-off & status.
- **Tyre Fitter Job Sheets** — vehicle reg, wheel-position picker, tyre brand/size/tread/pressure, fitter sign-off.

Both pages include searchable/filterable data tables, add-record modals, and read-only detail views.

## Run locally

```bash
npm start
```

Then open http://localhost:3000

## Deployment (Railway)

Railway auto-detects the Node app and runs `npm start`. The static `index.html` is served on the port provided by `process.env.PORT`. No build step or environment variables required.
