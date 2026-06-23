# multi-search-engine — 17 search engines without API keys

> Access 17 search engines — 8 domestic Chinese + 9 international — through simple web_fetch calls. No API keys, no accounts, no rate limits.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
multi-search-engine v2.0.1 provides URL patterns for 17 search engines that agents can query via `web_fetch`. Chinese engines include Baidu, Bing CN/INT, 360, Sogou, WeChat search, Toutiao, and Jisilu. International engines include Google, Google HK, DuckDuckGo, Yahoo, Startpage, Brave, Ecosia, Qwant, and WolframAlpha. Privacy-respecting engines (DDG, Startpage, Brave, Ecosia, Qwant) are flagged. Advanced search operators work on supported engines.

## Features
**8 domestic engines:** Baidu, Bing CN, Bing INT, 360, Sogou, WeChat/Sogou, Toutiao, Jisilu
**9 international:** Google, Google HK, DuckDuckGo, Yahoo, Startpage, Brave, Ecosia, Qwant, WolframAlpha
**Advanced operators:** `site:`, `filetype:`, `intitle:`, `inurl:`, date range, exact phrase
**WolframAlpha** for knowledge/computation queries

## Usage / Quick Start
```javascript
// Basic search
web_fetch({url: "https://www.google.com/search?q=your+query"})

// Site-specific
web_fetch({url: "https://www.google.com/search?q=site:github.com+react"})

// WolframAlpha knowledge query
web_fetch({url: "https://www.wolframalpha.com/input?i=population+of+vietnam"})
```

## Trigger Keywords (OpenClaw)
search web, multi search, 17 search engines, search without API, google search, baidu search, wolframalpha

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
