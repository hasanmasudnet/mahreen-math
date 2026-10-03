# Mahreen's Math Sheet

Big-number math practice for Class 1: addition, subtraction, multiplication and division.

- Easy / Medium / Hard / Custom difficulty
- Up-and-down (column) or side-by-side question layout
- Start, Pause and Finish timer (stopwatch or 2/5/10 minute countdown)
- Automatic results with stars, time taken and answer review
- Progress page: every finished test is saved in the browser, with a score chart,
  accuracy per topic and a full history. Use **Save backup (JSON)** to download it
  and **Load backup** to restore it or move it to another device.

It is a single static `index.html` with no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5178
```

## Deploy on Vercel

Import this repository in Vercel, choose the **Other** framework preset, and leave the
build command and output directory empty. Vercel serves `index.html` as is.
