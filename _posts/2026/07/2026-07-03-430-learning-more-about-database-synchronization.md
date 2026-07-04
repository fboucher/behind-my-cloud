---
layout: post
title: Learning more about database synchronization
featured-image: https://img.youtube.com/vi/mJ5d3ITtgsE/hqdefault.jpg
date: 2026-07-03  06:30 -0500
categories:  NoteBookmark
---

## Summary
In this stream, Frank dove into the tricky world of database synchronization for his Maui app, NotebookMark, focusing on how to handle offline comments without losing data. He spent some quality time debugging Visual Studio environment issues and leveraging Gemini and a variety of Hermes-powered AI agents to refactor his sync services and logic. Despite a few hurdles with Android emulators and build errors, the session was a productive blend of technical exploration and chill Friday vibes.

📺 - Twitch archive - stream no. 430


## Replay

{% include youtube.html id="mJ5d3ITtgsE" %}

<br/><!--more-->

### Project

All the code for this project is available on GitHub: NoteBookmark - https://github.com/FBoucher/NoteBookmark

### Game Results

- [@groversaurus](https://www.twitch.tv/groversaurus): 92.77
- [@fboucheros](https://www.twitch.tv/fboucheros): 86.44
- [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat): 70.38
- [@csharptitan](https://www.twitch.tv/csharptitan): 0
- [@gamlor](https://www.twitch.tv/gamlor): 0
- [@tbdgamer](https://www.twitch.tv/tbdgamer): 0
- [@therealsurlybot](https://www.twitch.tv/therealsurlybot): 0
- [@surlydev](https://www.twitch.tv/surlydev): 0
- [@garysgilet](https://www.twitch.tv/garysgilet): 0
- [@procrastoholik](https://www.twitch.tv/procrastoholik): 0
- [@undefined_process](https://www.twitch.tv/undefined_process): 0
- [@a_friend_asks](https://www.twitch.tv/a_friend_asks): 0
- [@jtsom](https://www.twitch.tv/jtsom): 0

#### Statistics

- 🏆Best score: [@groversaurus](https://www.twitch.tv/groversaurus) with 92.77
- 😭Biggest loser: [@gamlor](https://www.twitch.tv/gamlor) with 3 drops and no high score
- 🍀Luckiest: [@groversaurus](https://www.twitch.tv/groversaurus) with best score 92.77 and only 5 drops
- 🎖️Super participant: [@fboucheros](https://www.twitch.tv/fboucheros) with 5 drops

### Notes/ References / Snippets

- Send App to Emulator: dotnet build src/NoteBookmark.MauiApp/NoteBookmark.MauiApp.csproj -t:Run -f net10.0-android
