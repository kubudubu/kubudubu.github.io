---
layout: default
title:  "Debugging with pry - cheatsheet"
date:   2019-07-12
---
## {{ page.title }} | {{ page.date | date: "%Y-%m-%d" }}

Have you ever tried it? <br />If not, you definitely should. Simple, clean and great. <br />Install `pry` for plain ruby or `pry-rails` for rails and start using it. 
Then, add breakpoint with `binding.pry` and you’re set.

Run code and use basic commands, such as: <br/>
`next` – which executes next line <br/>
`step` – which steps into next function call <br/>
`continue` – which continues code execution <br/>
`whereami` – which prints context lines around the breakpoint <br/>
`wtf?` – which prints the stacktrace <br/><br/>
… or any other inline ruby calls to check what you need in specific context.
Finish debugging session with `disable-pry`

Have fun!
