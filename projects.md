---
layout: default
title: Projects
permalink: /projects/

<h1 class="section-title">Stream Projects</h1>

<p style="font-size: 1.125rem; color: var(--text-secondary);">This repository keeps track of all work done on the stream. The complete list of the streams is available in the journal, here are those where I worked on specific projects.</p>

<p style="text-align: center; margin: 2rem 0;">
  <a href="https://www.twitch.tv/fboucheros" class="cta-button">🎮 Watch on Twitch</a>
</p>

![Stream_Screenshots][Stream_Screenshots]

<h2 id="projectlist" class="section-title" style="margin-top: 3rem;">Projects</h2>

<div style="columns: 2; column-gap: 2rem; margin-bottom: 3rem;">
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#2d6-dungeon-app">2d6-dungeon-app</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#azunzipeverything">AzUnzipEverything</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#azpics">AzPics</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#azvideoconverter">Azure-Automatic-Video-Converter</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#azurlshortener">AzUrlShortener</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#az-subscription-cleaner">Az Subscription Cleaner</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#blind2021">Blind2021 (aka Project Dover)</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#check-in-doc-mcp">CheckInDoc MCP</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#cloudbot">CloudBot</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#frame-fisher">Frame Fisher</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#learning">Learning</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#maintenance">OSS Maintenance</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#myclippings-parser">MyClippings-Parser</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#n8n-nodes-reka">n8n-nodes-reka</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#NoteBookmark">NoteBookmark</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#not-a-dog-workshop">Not-a-Dog-Workshop</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#readingnotes">Reading Notes</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#reka-sdk-dotnet">Reka.SDK for .NET</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#tinyblazoradmin">TinyBlazorAdmin</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#triavia">Triavia the Trivia game</a></div>
  <div style="break-inside: avoid; margin-bottom: 0.5rem;">• <a href="#use-r-vote">Use-R-Vote (aka outspoken)</a></div>
</div>

## Projects Detail

<div class="project-card" id="tinyblazoradmin">
  <h3>TinyBlazorAdmin <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>
  
  <p>Admin tools for Azure Url Shortener using Blazor Single Page Application (webassembly)</p>

  <img src="https://github.com/FBoucher/TinyBlazorAdmin/raw/main/medias/TinyBlazorAdmin.png" alt="TinyBlazorAdmin cover" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/TinyBlazorAdmin" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["tinyblazoradmin"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="azurlshortener">
  <h3>AzUrlShortener <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>An simple and easy budget friendly Url Shortener for anyone. It runs in Azure (Microsoft cloud) in your subscription.</p>

  <img src="https://github.com/FBoucher/stream-projects/raw/main/medias/Url%20Shortener_800.png" alt="AzUrlShortener cover" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/AzUrlShortener" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["azurlshortener"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>
<div class="project-card" id="triavia">
  <h3>Triavia the Trivia game <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>A trivia game to play with the viewers while streaming.</p>

  <div class="project-links">
    <a href="https://github.com/FBoucher/triavia" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["triavia"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="blind2021">
  <h3>Blind2021 (aka Project Dover) <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Text-based adventure game, in a near future where you and your glasses companion are exploring your environment. Based on the ProjectDover. Using AI to simplify commands (talk humans AI translate to game commands)</p>

  <img src="https://github.com/FBoucher/ProjectDover/raw/master/medias/Text-Based-Game_800.png" alt="Blind2021 cover" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/ProjectDover" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["blind2021"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="use-r-vote">
  <h3>Use-R-Vote (aka outspoken) <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>An online request/idea voting platform manage by the community. You pitch your idea the community vote on it. The most popular get picked.</p>

  <img src="https://raw.githubusercontent.com/FBoucher/use-r-vote/master/medias/user-r-vote_800.png" alt="Use-R-Vote cover" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/use-r-vote" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["use-r-vote"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="cloudbot">
  <h3>CloudBot <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Simple Twitch chatbot for Twitch Stream, build with Comfy.JS. First, it was a pretext to learn (or refresh) my JavaScript knowledge, but it became quickly fun to add more and more feature to it. Have a look customize it. make suggestion... this is pure fun. :)</p>

  <img src="https://github.com/FBoucher/CloudBot/raw/main/medias/cloudbot_logo.png" alt="CloudBot logo" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/CloudBot" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["cloudbot"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="not-a-dog-workshop">
  <h3>Not-a-Dog-Workshop <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>This workshop is for beginners who would like to learn more about the cloud and then try some available services. Today artificial intelligence (AI) can benefit a lot of our applications and most of the time it's easier than we think to implement it.</p>

<img src="https://github.com/FBoucher/Not-a-Dog-Workshop/raw/master/medias/workshopHeader.png" alt="sample" width="400"/>

🔗 [https://github.com/FBoucher/Not-a-Dog-Workshop](https://github.com/FBoucher/Not-a-Dog-Workshop)

<table>
<thead>
  <tr>
    <th style="width:85px">Date</th>
    <th>Title</th>
  </tr>
</thead>
    {% for post in site.categories["not-a-dog-workshop"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}" class="post-link"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>



<div class="project-card" id="az-subscription-cleaner">
  <h3>Az Subscription Cleaner <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>The Simple way to keep your Azure Subscription "clean". This run on a schedule and automatically delete all "expired" resources inside your Azure Subscription, and nothing else. A Resource is "expired" when it has a tag expireOn older then the current date.</p>
  <img src="https://raw.githubusercontent.com/FBoucher/AzSubscriptionCleaner/main/medias/AzSubscriptionCleaner.png" alt="sample" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/AzSubscriptionCleaner" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
<thead>
  <tr>
    <th style="width:85px">Date</th>
    <th>Title</th>
  </tr>
</thead>
    {% for post in site.categories["az-subscription-cleaner"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div><div class="project-card" id="myclippings-parser">
  <h3>MyClippings-Parser <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>As simple as it could be, a .Net Core parser for the Amazon Kindle's "My Clippings.txt" file. The current version support the "Kindle Paperwhite". Transforming the flat file into an Array JSON Objects.</p>
  <div class="project-links">
    <a href="https://github.com/FBoucher/MyClippings-Parser" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
<thead>
  <tr>
    <th style="width:85px">Date</th>
    <th>Title</th>
  </tr>
</thead>
    {% for post in site.categories["myclippings-parser"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div><div class="project-card" id="azunzipeverything">
  <h3>AzUnzipEverything <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>A simple Azure Function to Unzip files from a blob storage container to another one The following features are supported in this current version: 1. Supported Archive Types: .zip, .rar *Archive support is currently implemented using the <a href="https://github.com/adamhathcock/sharpcompress">sharpcompress</a> library* 2. Password protected zip files *The current solution provisions an Azure KeyVault instance for storing the zip archive(s) password used during the unzipping process. If password protected zip files are uploaded to the blob storage container, this would be the password used when attempting to un-zip the files into the destination storage container.**</p>
  <div class="project-links">
    <a href="https://github.com/FBoucher/AzUnzipEverything" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
<thead>
  <tr>
    <th style="width:85px">Date</th>
    <th>Title</th>
  </tr>
</thead>
    {% for post in site.categories["azunzipeverything"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div><div class="project-card" id="azpics">
  <h3>AzPics <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Az Pics is a simple solution to manage your pictures and images. It will levrage multiple Azure services and demonstrate the best practices in Azure. This is a project for only session.</p>
  <img src="https://github.com/FBoucher/AzPics/raw/master/medias/AzPics_300px.png" alt="AzPic Logo" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/AzPics" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
<thead>
  <tr>
    <th style="width:85px">Date</th>
    <th>Title</th>
  </tr>
</thead>
    {% for post in site.categories["azpics"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div><div class="project-card" id="azvideoconverter">
  <h3>Azure-Automatic-Video-Converter <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>An automatic video converter using Azure Medias Services (AMS) with Azure Functions & Azure Logic Apps, running in the cloud.</p>
  <div class="project-links">
    <a href="https://github.com/FBoucher/Azure-Automatic-Video-Converter" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
<thead>
  <tr>
    <th style="width:85px">Date</th>
    <th>Title</th>
  </tr>
</thead>
    {% for post in site.categories["azvideoconverter"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div><div class="project-card" id="readingnotes">
  <h3>Reading Notes <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>A Solution to get online blog posts cleaned and sent to your eReader. Collect your notes and generate a ReadingNotes blog post, with all the notes to took about those articles.</p>
  <img src="https://raw.githubusercontent.com/FBoucher/ReadingNotes/master/module-pre-reading/medias/GettingPostToEReader.png" alt="schema of the pre-reading flow" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/fboucher/readingnotes" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
  <thead>
    <tr>
      <th style="width:85px">Date</th>
      <th>Title</th>
    </tr>
  </thead>
    {% for post in site.categories["readingnotes"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div><div class="project-card" id="learning">
  <h3>Learning <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Sometimes there is no real projects. It's about an experiment or to learn a new technologies. Here are regrouped those streams.</p>
  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
  <thead>
    <tr>
      <th style="width:85px">Date</th>
      <th>Title</th>
    </tr>
  </thead>
    {% for post in site.categories["learning"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div>

<div class="project-card" id="2d6-dungeon-app">
  <h3>2D6 Dungeon App <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p><a href="https://drgames.co.uk/2d6-dungeon-a-classic-dungeon-crawler-solo-player-game/">2D6 Dungeon</a> is a classic style dungeon crawler, print and play, roll and write game designed for solo play. You explore randomly generated dungeon rooms, fight monsters and collect treasure as you gain experience and strive to become a legendary adventurer. Every adventure and dungeon is unique. It was created by DR Games and it's a paper and dices game.</p>

  <p>This project is a digital version of the game, with creator's approval. It's a web application that allows you to play the game on your computer or mobile device. It's a work in progress. I progress by iteration improving the code, the structure at each pass.</p>

  <img src="https://raw.githubusercontent.com/FBoucher/2d6-dungeon-app/main/medias/new_adventure.png" alt="2D6 Dungeon App new adventure screen" style="width: 100%; max-width: 500px; border-radius: 12px; margin: 1rem 0;"/>

  <div class="project-links">
    <a href="https://github.com/FBoucher/2d6-dungeon-app" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:85px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["2d6-dungeon-app"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="NoteBookmark">
  <h3>Note Bookmark <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Note Bookmark is a website to keep tracks of the things you read. It's a new spin of my reading notes project. The goal is to build it with a CICD, using Blazor with FluentUI-Blazor, Minimal API, Azure Container Apps, Azure Table Storage, and .NET Aspire when working locally.</p>

  <div class="project-links">
    <a href="https://github.com/FBoucher/NoteBookmark" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
  <thead>
    <tr>
      <th style="width:85px">Date</th>
      <th>Title</th>
    </tr>
  </thead>
    {% for post in site.categories["NoteBookmark"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div>

<div class="project-card" id="maintenance">
  <h3>OSS Maintenance <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Those are the streams when we work on making the streams better. Setting-up tools, boards, and other things</p>

  <div class="project-links">
    <a href="https://github.com/users/FBoucher/projects/15/" class="project-link">🔗 OSS Maintenance Boards</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:90px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["maintenance"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="check-in-doc-mcp">
  <h3>CheckInDoc MCP <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>CheckInDoc MCP, is a MCP server to check/search in the specific documentation website that YOU set in configuration. Using Reka AI Research. It could be used by developers to search only on the documentation they prefer instead of the entire web. Another use case would be enterprise that could be hosting this MCP server set to search in their documentation and offer it to their users/clients/developers.</p>

  <div class="project-links">
    <a href="https://github.com/FBoucher/check-in-doc-mcp" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:90px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["check-in-doc-mcp"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="reka-sdk-dotnet">
  <h3>Reka.SDK for .NET <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Official .NET SDK for integrating Reka AI APIs into your .NET applications.</p>

  <div class="project-links">
    <a href="http://github.com/reka-ai/reka-sdk-dotnet" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
    <tr>
      <th style="width:90px">Date</th>
      <th>Title</th>
    </tr>
  </thead>
    {% for post in site.categories["reka-sdk-dotnet"] %}
    <tr>
        <td> {{ post.date | date: "%F" }} </td>
        <td> 
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
        </td>
    </tr>
    {% endfor %}
</table>
</div>

<div class="project-card" id="frame-fisher">
  <h3>Frame Fisher <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>App that search across multiple videos using AI.</p>

  <div class="project-links">
    <a href="http://github.com/fboucher/frame-fisher" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:90px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["frame-fisher"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

<div class="project-card" id="n8n-nodes-reka">
  <h3>n8n Nodes Reka <a href="#projectlist" style="font-size: 0.875rem; float: right;">🔝</a></h3>

  <p>Custom n8n nodes to use Reka's AI in our workflows.</p>

  <div class="project-links">
    <a href="http://github.com/fboucher/n8n-nodes-reka" class="project-link">🔗 GitHub Repository</a>
  </div>

  <h4 style="margin-top: 1.5rem; color: var(--text-secondary); font-size: 1rem;">Related Streams</h4>
  <table>
    <thead>
      <tr>
        <th style="width:90px">Date</th>
        <th>Title</th>
      </tr>
    </thead>
      {% for post in site.categories["n8n-nodes-reka"] %}
      <tr>
          <td> {{ post.date | date: "%F" }} </td>
          <td> 
              <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
          </td>
      </tr>
      {% endfor %}
  </table>
</div>

[Stream_Screenshots]: /medias/Stream_Screenshots.png