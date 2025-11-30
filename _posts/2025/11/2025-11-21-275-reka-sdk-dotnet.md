---
layout: post
title: Writing .NET SDK for Reka's AI API (stream 275)
featured-image: https://img.youtube.com/vi/iLk3XY8OVD4/hqdefault.jpg
date: 2025-11-21  06:30 -0500
categories:  reka-sdk-dotnet
---

## Summary

Worked through converting reused Reka API models into a proper .NET SDK NuGet package, setting up the new project structure, metadata, and tags, and refactoring NoteBookmark to consume it cleanly. Debugged the earlier Aspire timeout issue (fixed via custom resilience handler options) and validated the class moves and project references. Wrapped with initial commit and versioning groundwork; next step is automating publish and adding more API surface (speech, etc.).

📺 - Twitch archive - stream no.275

## Replay

{% include youtube.html id="iLk3XY8OVD4" %}

<br/><!--more-->

### Project

All the code for this project is available on GitHub: reka-sdk-dotnet - https://github.com/FBoucher/reka-sdk-dotnet

### Game Results

- [@groversaurus](https://www.twitch.tv/groversaurus): 0
- [@coppersbeard](https://www.twitch.tv/coppersbeard): 0
- [@smabuk](https://www.twitch.tv/smabuk): 0
- [@stoney_eagle](https://www.twitch.tv/stoney_eagle): 0
- [@theunoriginaljerk](https://www.twitch.tv/theunoriginaljerk): 6.52
- [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat): 8.56
- [@surlydev](https://www.twitch.tv/surlydev): 45.68
- [@therealsurlybot](https://www.twitch.tv/therealsurlybot): 48.68
- [@jtsom](https://www.twitch.tv/jtsom): 53.21
- [@cmgbeanie](https://www.twitch.tv/cmgbeanie): 57.02
- [@fboucheros](https://www.twitch.tv/fboucheros): 68.33
- [@codebymistakes](https://www.twitch.tv/codebymistakes): 73.52
- [@lurkydev](https://www.twitch.tv/lurkydev): 77.78
- [@undefined_process](https://www.twitch.tv/undefined_process): 84.48
- [@jeffs_hat_stand](https://www.twitch.tv/jeffs_hat_stand): 97.94

#### Statistics

- 🏆Best score: [@jeffs_hat_stand](https://www.twitch.tv/jeffs_hat_stand) with 97.94
- 😭Biggest loser: [@groversaurus](https://www.twitch.tv/groversaurus) with 8 drops and no high score
- 🍀Luckiest: [@jeffs_hat_stand](https://www.twitch.tv/jeffs_hat_stand) with best score 97.94 and only 8 drops
- 🎖️Super participant: [@surlydev](https://www.twitch.tv/surlydev) with 11 drops
