# Kids Practice Hub

Free, MAP-style practice for Grades 2–5. It runs entirely in the browser: no sign-in, no server, and no data collected.

**Live site:** `https://github.com/chrystali2002/kids-practice-3rdgrade/`

## What's inside

```
index.html          ← home page (lists every subject and set)
reading/            ← reading practice sets
math/               ← math practice sets (coming soon)
```

## Adding a new practice set

1. Put the new `.html` file in `reading/` or `math/`. Use a short lowercase file name with dashes and no spaces, such as `math/grade3-fractions.html`.
2. Open `index.html` and add one line to the `SUBJECTS` list:
   ```js
   { title: "Fractions (10 questions)", file: "math/grade3-fractions.html", level: "Grade 3", about: "Short description." }
   ```
3. Commit the change. The site updates within a minute or two.

To link back to the home page from a new set, use `href="../index.html"`.

*Not affiliated with or endorsed by NWEA.*
