---
layout: post
title: Take 2: Working on local-ai-search project
featured-image: https://img.youtube.com/vi/p--kMaqjl3k/hqdefault.jpg
date: 2026-03-25  06:30 -0500
categories:  local-ai-search
---

## Summary
On this Wednesday AI stream, I kicked off the local-ai-search project — a local image search app powered by Reka Edge, a vision model running on my home server. Before writing any code, I used my new grill-me skill in OpenCode to stress-test my architecture decisions (Avalonia over Uno, Turso for DB, single folder, no thumbnails), then let the PRD-to-issues skill generate all the GitHub issues automatically. We wrapped up by validating the full pipeline with a quick .NET demo — sending images to the local Reka model and getting descriptions back, including one that called me "elderly" (it was the lighting!).
📺 - Twitch archive - stream no. 404


## Replay

{% include youtube.html id="p--kMaqjl3k" %}

<br/><!--more-->

### Project

All the code for this project is available on GitHub: local-ai-search - https://github.com/FBoucher/local-ai-search

### Game Results

- [@codebymistakes](https://www.twitch.tv/codebymistakes): 92.7
- [@surlydev](https://www.twitch.tv/surlydev): 90.31
- [@fboucheros](https://www.twitch.tv/fboucheros): 75.78
- [@lurkydev](https://www.twitch.tv/lurkydev): 74.71
- [@theunoriginaljerk](https://www.twitch.tv/theunoriginaljerk): 73.81
- [@therealsurlybot](https://www.twitch.tv/therealsurlybot): 71.97
- [@groversaurus](https://www.twitch.tv/groversaurus): 71.09
- [@garysgilet](https://www.twitch.tv/garysgilet): 68.25
- [@my_friend_asks](https://www.twitch.tv/my_friend_asks): 65.31
- [@undefined_process](https://www.twitch.tv/undefined_process): 52.01
- [@marcipopsis](https://www.twitch.tv/marcipopsis): 42.36
- [@jeffs_hat_stand](https://www.twitch.tv/jeffs_hat_stand): 23.47
- [@a_friend_asks](https://www.twitch.tv/a_friend_asks): 23.24
- [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat): 22.83
- [@jtsom](https://www.twitch.tv/jtsom): 21.33
- [@phrakberg](https://www.twitch.tv/phrakberg): 14.97
- [@mcnets](https://www.twitch.tv/mcnets): 0
- [@tbdgamer](https://www.twitch.tv/tbdgamer): 0
- [@coppersbeard](https://www.twitch.tv/coppersbeard): 0
- [@procrastoholik](https://www.twitch.tv/procrastoholik): 0
- [@cmgbeanie](https://www.twitch.tv/cmgbeanie): 0
- [@thecliptographer](https://www.twitch.tv/thecliptographer): 0
- [@dj_surly](https://www.twitch.tv/dj_surly): 0

#### Statistics

- 🏆Best score: [@codebymistakes](https://www.twitch.tv/codebymistakes) with 92.7
- 😭Biggest loser: [@coppersbeard](https://www.twitch.tv/coppersbeard) with 2 drops and no high score
- 🍀Luckiest: [@codebymistakes](https://www.twitch.tv/codebymistakes) with best score 92.7 and only 2 drops
- 🎖️Super participant: [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat) with 10 drops

### Notes/ References / Snippets

- Model: https://huggingface.co/RekaAI/reka-edge-2603
- Grill-Me Skill https://www.aihero.dev/my-grill-me-skill-has-gone-viral
