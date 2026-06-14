# Terminal Basics

An interactive course that teaches 15 essential Linux commands in a simulated terminal — built as a single HTML file that runs anywhere.

**Live:** https://type-pwd.vercel.app/

## What it does

Walks an absolute beginner through `pwd`, `ls`, `cd`, `mkdir`, `touch`, `cp`, `mv`, `rm`, `cat`, `less`, `grep`, `find`, `chmod`, `ps`, and `kill` — one lesson each, gated by a hands-on challenge against a persistent fake filesystem.

## Features

- Fully functional simulated shell: realistic caret, command history, tab completion, output redirection, color-coded output
- Persistent in-browser filesystem — files created in lesson 5 still exist in lesson 8
- A real pager for `less`, regex matching for `grep`, octal and symbolic modes for `chmod`, runaway processes to find and kill for `ps`/`kill`
- Sequentially unlocked lessons with a sticky progress rail and a cheatsheet drawer that fills in as you learn
- Vercel-style design crossed with a CRT terminal aesthetic, toggleable scanlines
- Completion page with fireworks, a Linus Torvalds quote, and share buttons
- Fully keyboard accessible, respects `prefers-reduced-motion`

## Tech

Single HTML file. Tailwind via CDN. Vanilla JavaScript. No build step, no dependencies, no server. Double-click the file to run it locally.

## License

MIT
