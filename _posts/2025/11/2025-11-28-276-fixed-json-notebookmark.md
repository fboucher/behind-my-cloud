---
layout: post
title: AI & C# in NoteBookmark - Let's display those suggestions (stream 276)
featured-image: https://img.youtube.com/vi/7tY91YC0G94/hqdefault.jpg
date: 2025-11-28  06:30 -0500
categories:  notebookmark
---

## Summary

Worked on NoteBookmark’s AI-powered suggestions: wired up parameter binding, fixed JSON property names, and got deserialization flowing so the grid displays fetched posts cleanly. Revisited the Aspire timeout quirk (using a custom resilience handler) and continued migrating shared models into my new ReKa .NET SDK NuGet for reuse. Next, I’m considering a small safety loop to auto-fix malformed JSON via AI when responses come back truncated.

📺 - Twitch archive - stream no.276

## Replay

{% include youtube.html id="7tY91YC0G94" %}

<br/><!--more-->

### Project

All the code for this project is available on GitHub: notebookmark - https://github.com/FBoucher/notebookmark

### Game Results

- [@undefined_process](https://www.twitch.tv/undefined_process): 0
- [@lurkydev](https://www.twitch.tv/lurkydev): 0
- [@cmgbeanie](https://www.twitch.tv/cmgbeanie): 0
- [@marcusvoicecoder](https://www.twitch.tv/marcusvoicecoder): 0
- [@smirking_squiggly](https://www.twitch.tv/smirking_squiggly): 21.56
- [@gamlor](https://www.twitch.tv/gamlor): 23.24
- [@jeffs_hat_stand](https://www.twitch.tv/jeffs_hat_stand): 52.12
- [@groversaurus](https://www.twitch.tv/groversaurus): 58.80
- [@codebymistakes](https://www.twitch.tv/codebymistakes): 61.19
- [@tetedampoule66](https://www.twitch.tv/tetedampoule66): 63.76
- [@mcnets](https://www.twitch.tv/mcnets): 68.41
- [@therealsurlybot](https://www.twitch.tv/therealsurlybot): 76.00
- [@coppersbeard](https://www.twitch.tv/coppersbeard): 88.27
- [@jtsom](https://www.twitch.tv/jtsom): 90.46
- [@theunoriginaljerk](https://www.twitch.tv/theunoriginaljerk): 91.08
- [@surlydev](https://www.twitch.tv/surlydev): 94.79
- [@fboucheros](https://www.twitch.tv/fboucheros): 96.77
- [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat): 97.30

#### Statistics

- 🏆Best score: [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat) with 97.30
- 😭Biggest loser: [@undefined_process](https://www.twitch.tv/undefined_process) with 5 drops and no high score
- 🍀Luckiest: [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat) with best score 97.30 and only 5 drops
- 🎖️Super participant: [@mcnets](https://www.twitch.tv/mcnets) with 16 drops

### Notes/ References / Snippets

- https://www.frankysnotes.com/2025/11/ask-ai-from-anywhere-no-gui-no-heavy.html
