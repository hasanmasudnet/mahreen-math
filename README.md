# Mahreen's Math Sheet

Big-number math practice for Class 1: addition, subtraction, multiplication and division.
Also a Class 1 English test: letters, spelling, words and sentences, with pictures and
tap-to-choose answers (Easy, Medium, Hard, and Harder for Class 2).

- Easy / Medium / Hard / Harder (Class 2: 3-digit carrying and borrowing, tables to ×12) / Custom difficulty
- Up-and-down (column) or side-by-side question layout
- Worlds: 👑 Princess castle, 🚀 Space adventure (astronauts and robots) or ✏️ Classic.
  An animated friend walks to her kingdom (or a planet) as questions are answered, cheers
  during the test and celebrates on the results screen. Stars earned unlock more friends
  (at 3, 6, 10 and 15 stars).
- Princesses: Sofia, Elsa, Rapunzel, Snow White and Cinderella, each with her own kingdom
  (castle, ice palace, tower, cottage, pumpkin carriage), colours, background and rewards.
  The drawings are simple home-made fan art for family use.
- Princess ranking: every test is scored to the princess (or space friend) chosen when it
  was taken. The progress page ranks them by stars earned, with tests, best and average
  scores, and the results screen shows where the chosen friend now stands.
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
