# Sudoku

A static mock website for a Sudoku game, built with pure HTML and CSS.

**Live Site:** https://zxiaoyii.github.io/sudoku/
**Repository:** https://github.com/zxiaoyii/sudoku

---

## Pages

- Home — landing page with game title and preview grid
- Play — game selection page with Hard and Easy listings
- Hard Game — 9x9 Sudoku grid with timer
- Easy Game — 6x6 Sudoku grid with timer
- Rules — game instructions and credits
- High Scores — leaderboard with made-up usernames
- Login — username and password form
- Register — account creation form

---

## Writeup

**What was the most challenging piece of this assignment? Did you find it easy or challenging to work with HTML and CSS? How long did this overall assignment take you?**

Honestly the trickiest part was getting the Sudoku grid to look right — specifically making the subgrid borders show up correctly using CSS classes. I kept second-guessing which cells needed `border-right` vs `border-bottom` and had to go back and fix it a few times. I already had some HTML/CSS background so it wasn't too bad overall, but it still took me around 5 hours once I factored in all the pages and mobile adjustments.

**What decisions did you make when you made your site mobile friendly?**

The main thing I did was move the navbar to the bottom of the screen on mobile, since that's how most apps work and it just feels more natural on a phone. I also shrank down the grid cells, font sizes, and padding so nothing gets cut off on smaller screens. I tested it using Chrome DevTools with the iPhone 12 Pro size to make sure everything looked okay.

**What did you take into account when you developed the design of your website? Is there anything that you're particularly proud of?**

I went with a soft pink and cream color scheme because I wanted it to feel light and easy on the eyes rather than the typical dark puzzle game aesthetic. I used CSS variables so the colors stay consistent everywhere without having to repeat myself. I'm pretty happy with how the pages all feel like they belong together — same card style, same spacing, same font throughout.

**Given more time or resources, what additional features would you add to your site in the future?**

The obvious next step is adding JavaScript so the game actually works — a real timer, input validation, and a win condition. I'd also like to add more puzzle variations and maybe a way to save your progress. A working login and leaderboard system would make it feel like a real product.

**How many hours did you spend on this assignment?**

Around 5 hours.

**Fonts and Libraries Used**

- [Poppins](https://fonts.google.com/specimen/Poppins) via Google Fonts
- No other libraries or frameworks were used
- Sudoku preview image on homepage from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Sudoku_Puzzle_by_L2G-20050714_standardized_layout.svg) (public domain)
