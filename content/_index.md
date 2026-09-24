---
title: Welcome to Durare!
description: A clean documentation and blog theme for your Hugo site based on Bootstrap 5.
content_blocks:
  - _bookshop_name: hero
    heading:
      title: Welcome to Durare!
      content: |-
        diasp.in/durare.org provides instant messaging service open for everyone seeking privacy for their day to day communication needs. We provide verifiable privacy through Free Software XMPP apps like Monocles Chat, Monal or Dino. Users of our service can talk to users of any XMPP service like prav.app, quicksy.im or poddery.com.
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/sunrise.jpg
      ratio: 16x9
    width: 8
    links:
      - title: Request an account now
        url: https://gethinode.com/docs
        icon: fas chevron-right
    orientation: horizontal
    justify: center

  - _bookshop_name: approach
    heading:
#      preheading: 
#      title: diasp.in/durare.org is a XMPP service, hosted just for you! 
      content: | 
        diasp.in/durare.org is a XMPP service,
        hosted just for you!
      align: center
    layout: split
    numbered: true
#    background:
#      color: body-tertiary
#      subtle: false
#    illustration:
#      image: /img/placeholder.png
#    orientation: stacked
#    icon_style: text-primary
#    padding: 0
#    align: center
    elements:
      - title: Free Software
        icon: 1
        content:  This XMPP service is powered by Prosody, which is Free Software. You can run it on your own. 
      - title: Own your data
        icon: 2
        content: Your data is yours. Make sure you enable end to end encryption for all your chats (Some clients like Monocles Chat do this by default, but for other clients you may need to do this manually). 

  - _bookshop_name: cards
    heading:
#      preheading: Preheading
#      title: Heading
      content: Use your diasp.in/durare.org username and password with any XMPP client, like
      align: center
    background:
      color: body-tertiary
      subtle: false
    orientation: stacked
    class: bg-body
    align: center
    elements:
      - title: Monocles Chat
        image: /img/monocles-chat.png
        content: Get it now.
        label: Label here
        link: https://durare.org
      - title: Gajim
        image: /img/placeholder.png
      - title: Monal
        image: /img/placeholder.png
---

{{< card-group padding="3" gutter="3" align="center">}}
    {{< card title="Monocles chat" icon="fab bootstrap" >}}
        Build fast, responsive sites with Bootstrap 5. Easily customize your site with the
        source Sass files.
    {{< /card >}}
    {{< card title="Full text search" icon="fas magnifying-glass" >}}
        Search your site with FlexSearch, a full-text search library with zero dependencies.
    {{< /card >}}
    {{< card title="Development tools" icon="fas code" >}}
        Use Node Package Manager to automate the build process and to keep track of
        dependencies.
    {{< /card >}}
{{< /card-group >}}
