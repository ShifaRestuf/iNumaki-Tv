# iNumakiTV for Android TV & Google TV

iNumakiTV is Android TV application for watching your favorite anime series and movies on your Android TV, It also runs on non-TV Android devices (Phones and Tablets) with some UI limitations.

> Source data is from *one anime streaming website* and I don't have any affiliation with it, and it may break on site updates.
> Take a look at source code for more info

## Donation & More Information
![Play Info](https://media.discordapp.net/attachments/1179424658907472013/1200263369932939304/DONATE.png?ex=65c58b5f&is=65b3165f&hm=e4e57a7d025211891dc9e8b5935679c7eff1f034d25234ab6f44dfaea48b2369&) <width="200">

[Donate Here - https://ko-fi.com/giokabaneri]


**Detail Information :** [https://giokabaneri.netlify.app/](https://giokabaneri.netlify.app/)

**Discussion on Discord :** [https://discord.gg/VGtGtRedGR](https://discord.com/invite/RRjfaHrNmz)

## Features
- **NEW** - Soft-subtitle & Auto Translate to **134 Languages** (Only for supported contents)
- **NEW** - Settings panel
- **NEW** - Change Theme Color & Animation performance
- **NEW** - Soft-subtitle Text Style Configuration
- **NEW** - Playback Speed (0.5x - 3.00x)
- **NEW** - Include Non-Japan Anime Settings
- Search and Advance Search with Genre & Anime Type filters
- Auto Next episode
- Auto Skip Intro & Outro
- Auto Skip Filler Episode
- Genre & Type Tags
- Video display style ( Centered, Fit, Scaled ) for non widescreen videos.
- Easy to navigate with Android TV Remote
- Home Anime List
  - Hot
  - Recently Updated
  - Dub Update
  - Top Anime
  - Trending Episodes
  - Random Anime
  - Watchlist Anime – You can set anime as favorite to watch
  - Watch History – All anime has been watched before with last timestamp
- List of episodes and seasons for show
- Recommendation anime for current show
- Support for Android TV / Google TV home list and PlayNext
- All Watchlist & History is saved locally – I don’t have any server to save your watch & history 🤣 So don’t worry.

## Open Source
Source code is a Discord https://discord.com/invite/RRjfaHrNmz ). 
Release of source code may make *source website* prevent this apps to run, but hope it work fine for long, and you will help me update it when it break 😂.

And Please Contribute your bugfixes, reports & suggestions for next better update. If you find it useful, donation is welcome.

## WebView Based?
Yes, it was webview based application. UI and Data Fetch Method is using webview, because I don't have access to *source website* database, I just load the web in headless webview and fetch site data info with javascript injection, because it's not possible to use only http client to get data.

Almost all data need javascript to make it available (It's not pure HTML that can easily parsed from text). The site also use **QUIC** rather than HTTP1X, so I need to include **CronetEngine** to make it works.

But the good news is **iNumakiTV** will block any analytics and ads domain (dns) when requesting & fetching data. All data like watchlist & watch history also stored local in **localStorage**.

## Screenshot Coming Soon
More screenshot is available in my website: bit.ly/D-1301
Here only a couple screenshot:

![Play Info](https://media.discordapp.net/attachments/1192437024980996176/1200259608527253605/1700545662903.jpg?ex=65c587de&is=65b312de&hm=800951dc53942b787f5c2c22fefd1b72f7ace8192449769e11b48422baeb2871&)

## License
**Copyright 2024 Giokabaneri (https://giokabaneri.netlify.app)**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
