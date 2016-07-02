---
author: []
related: []
publisher:
  url: 'http://bitcoin.stackexchange.com'
  name: Stackexchange
  favicon: 'http://cdn.sstatic.net/Sites/bitcoin/img/favicon.ico?v=0910168c5c65'
  domain: bitcoin.stackexchange.com
keywords:
  - connections
  - nodes
  - bitcoin-cli
  - client
  - inbound
  - bytes
  - synced
  - headers
  - getnettotals
  - transactions
description: >-
  I found the easiest way to do this (version 0.12) is to issue the command (not
  case sensitive): bitcoin-cli getblockchaininfo Then, compare the blocks
  received field, to the headers field. The blocks received should increase
  steadily until it matches the headers field, at which point the client is
  synced.
inLanguage: en
app_links:
  - url: >-
      se-zaphod://bitcoin.stackexchange.com/questions/46245/check-status-of-daemon
    namespace: twitter
    type: ipad
    name: Stack Exchange iOS
    id: '871299723'
  - url: >-
      se-zaphod://bitcoin.stackexchange.com/questions/46245/check-status-of-daemon
    namespace: twitter
    type: iphone
    name: Stack Exchange iOS
    id: '871299723'
  - url: 'http://bitcoin.stackexchange.com/questions/46245/check-status-of-daemon'
    namespace: twitter
    type: googleplay
    name: Stack Exchange Android
    id: com.stackexchange.marvin
isBasedOnUrl: 'http://bitcoin.stackexchange.com/questions/46245/check-status-of-daemon'
title: Check status of daemon?
datePublished: '2016-07-02T17:16:32.394Z'
dateModified: '2016-07-02T10:37:43.787Z'
starred: false
sourcePath: _posts/2016-07-02-check-status-of-daemon.md
inFeed: true
hasPage: false
inNav: false
_context: 'http://schema.org'
_type: MediaObject

---
<article style=""><h1>Check status of daemon?</h1><p>I found the easiest way to do this (version 0.12) is to issue the command (not case sensitive): bitcoin-cli getblockchaininfo Then, compare the blocks received field, to the headers field. The blocks received should increase steadily until it matches the headers field, at which point the client is synced.</p><img src="http://cdn.sstatic.net/Sites/bitcoin/img/apple-touch-icon.png?v=a43e5a337e6b&amp;a" /></article>