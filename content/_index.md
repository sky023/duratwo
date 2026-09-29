---
title: Welcome to Durare!
description: A clean documentation and blog theme for your Hugo site based on Bootstrap 5.
content_blocks:
  - _bookshop_name: hero
    heading:
      title: Welcome to Durare!
      content: |
              {{< mark >}}durare.org{{< /mark >}} provides instant messaging service open for everyone seeking privacy for their day to day communication needs.
              We provide verifiable privacy through Free Software XMPP apps like Monocles Chat, Monal or Dino.
              Users of our service can talk to users of any XMPP service like [prav.app](https://prav.app), [monocles.de](https://monocles.de) or any providers listed at [XMPP Providers](https://providers.xmpp.net/).
 
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/xmpp-logo.svg
#      ratio: 16x9
    width: 8
    links:
      - title: Request an account now
        url: https://durare.org
        icon: fas chevron-right
    orientation: horizontal
    justify: center

  - _bookshop_name: approach
    heading:
#     preheading: 
#     title: durare.org is a XMPP service, hosted just for you! 
      content: | 
        {{< mark >}}durare.org{{< /mark >}} is a XMPP service,
        hosted just for you!
#      cols: 1
      align: center
    layout: split
#   numbered: true
#    background:
#     color: body-primary
#     subtle: false
#   illustration:
#     image: /img/placeholder.png
#   orientation: stacked
#    icon_style: text-primary
    padding: 4
#    align: center
    justify: center
    width: 8
    elements:
      - title: Free Software
        icon: fab xmpp
        content:  This XMPP service is powered by Prosody, which is Free Software. You can run it on your own. 
      - title: Own your data
        icon: server
        content: Your data is yours. Make sure you enable end to end encryption for all your chats (Some clients like Monocles Chat do this by default, but for other clients you may need to do this manually). 

  - _bookshop_name: cards
    cols: 4
    heading:
#      preheading: Preheading
#      title: Heading
      content: Use your diasp.in/durare.org username and password with any XMPP client, like
      align: center
    background:
      color: body-tertiary
      subtle: false
    orientation: stacked
#    icon_style: text-primary
#    fluid: true
    align: center
    justify: center
    width: 8
    padding: 2
    elements:
      - title: Conversations
        image: /img/conversations.png
        content: > 
                  [![Conversations on Google Play](/img/googleplay.png)](https://play.google.com/store/apps/details?id=eu.siacs.conversations)
                  [![Conversations chat on F-Droid](/img/fdroid.png)](https://f-droid.org/packages/eu.siacs.conversations/) 
      - title: Monocles chat
        image: /img/monocles-chat.png
        content: >
                  [![Monocles chat on Google Play](/img/googleplay.png)](https://play.google.com/store/apps/details?id=eu.monocles.chat)
                  [![Monocles chat on F-Droid](/img/fdroid.png)](https://f-droid.org/packages/de.monocles.chat/)
      - title: Gajim
        image: /img/gajim.svg
        content: "[Download Gajim for PC](https://gajim.org/download)"
      - title: Monal
        image: /img/monal.png
        content: >
                  [![Monal on Apple App Store](/img/applestore.png)](https://apps.apple.com/us/app/monal-xmpp-chat/id317711500)

  - _bookshop_name: approach
    cols: 1
    heading:
#      preheading: Preheading
      title: Expenses and funding
      content: List of incoming and outgoing expenses
#    layout: split
#    numbered: true
    justify: center
    width: 8
    elements:
      - title: | 
        content: |
                  > [!NOTE]
                  > Baserow form comes here


  - _bookshop_name: cards
    id: donate
    heading:
#      preheading: Preheading
      title: Help us sustain!
      content: Consider making a donation to keep the service running.
#      align: start
    background:
      color: body
      subtle: false
    orientation: horizontal
    icon_style: text-primary
#    align: center
    justify: center
    padding: 0
    width: 8
    cols: 1

    elements:
      - title: Top-up our server at Hetzner 
        icon: 1
        content: >
          We rely on Hetzner to host our virtual servers. Hetzner is based in Germany and our servers are hosted in their Helsinki data center in Finland. You can directly credit our hosting account which will be used to pay invoices. This has the lowest payment fees and currency conversion rate, and is the recommended way.
          International bank transfer (pay using Wise, Revolut, or from your bank account)  


          Bank details: Deutsche Bank AG Nuremberg  

          Legal Name: Hetzner Online GmbH  

          IBAN: DE92 7607 0012 0750 0077 00  

          BIC: DEUTDEMM760  

          Hetzner Customer ID: K0698488224 (Please mention this in wire transfer comment field)

  - _bookshop_name: cards
#    heading:
#      preheading: Preheading
#      title: Heading
#      content: Cards content. It supports multiple lines.
#      align: start
    background:
      color: body
      subtle: false
    orientation: horizontal
    icon_style: text-primary
    align: start
    justify: center
    padding: 0
    width: 8
    cols: 2
#    link_type: button
    elements:
      - title: Donate at Open Collective
        icon: 2
        content: |
                If international bank transfer to Hetzner bank account is not possible, then you can donate at Open Collective.  
                {{< button color="primary" href="https://opencollective.com/diasp-in" button-size="sm" icon="chevron-right" outline="true">}}Open Collective{{< /button >}}
#        link: https://opencollective.com/diasp-in/

      - title: Donate at Razorpay
        icon: 3
        content: |
                Indian residents can use various modes of payment including UPI  
                {{< button color="primary" href="https://pages.razorpay.com/pl_Nvo3N8wV0YpoX5/view" button-size="sm" icon="chevron-right" outline="true">}}Razorpay{{< /button >}}  

  - _bookshop_name: approach
    heading:
      title: Join us!
#      content: |
#              Help us to fix, improve and maintain things.  
#              {{< button color="primary" href="https://app.formbricks.com/s/jkdfbemz2dku35gm8nczc4f7" button-size="sm" icon="chevron-right" >}}Volunteer now! {{< /button >}}
      align: start
    background:
      color: body-tertiary
      subtle: false
    orientation: stacked
#    icon_style: text-primary
    padding: 0
    cols: 2
    align: start
    justify: center
    width: 8
    elements:
      - title: |
        content: |  
                Fill the volunteer form to contact us.  
                {{< button color="primary" href="https://app.formbricks.com/s/jkdfbemz2dku35gm8nczc4f7" button-size="sm" icon="chevron-right" >}}Volunteer now! {{< /button >}}
      - title: |
        content: |  
                Check open issues at our Gitlab repo.  
                {{< button color="primary" href="gitlab.com/piratemovin/diasp.in/-/issues" button-size="sm" icon="chevron-right" >}}Gitlab repo{{< /button >}}

  - _bookshop_name: cards
    heading:
#      preheading: Preheading
#      title: Join us
#      content: Cards content. It supports multiple lines.
      align: start
#    fluid: true
    background:
      color: body-tertiary
      subtle: false
    bg_class: body-tertiary
    orientation: horizontal
    align: start
    justify: center
    width: 8
    padding: 0
    cols: 2
    elements:
      - title: Durare status
        content: |
                |                 |                 |
                | -------------   | :-------------:	|
                | XMPP Provider   | [![Durare at XMPP Provider](https://data.xmpp.net/providers/v2/badges/durare.org.svg)](https://providers.xmpp.net/provider/durare.org/)	|
                | XMPP Compliance |  |
                | XMPP Network Graph | [![Durare at XMPP Network Graph](https://xmppnetwork.goodbytes.im/badge/durare.org.svg)](https://xmppnetwork.goodbytes.im) | 

      - title: |
        content: |

                <a href="https://app.greenweb.org/api/v3/greencheckimage/durare.org?nocache=true"
                       title="View XMPP compliance details"
                       target="_blank"
                       rel="noopener">
                      <img
                        src="https://app.greenweb.org/api/v3/greencheckimage/durare.org?nocache=true"
                        alt="Durare at Green">
                    </a>




  - _bookshop_name: approach
    heading:
#      preheading: Preheading
      title: History
      content: | 
#    layout: center
#    numbered: true
    cols: 2
    justify: center
    width: 8
    padding: 0
    elements:
      - title: Diasp
        content: |  
                  This project originally began as diasp.in, a Diaspora pod hosted in India. 
                  We later added XMPP and Matrix services. 
                  Hamara Linux, our hosting sponsor, could not continue offering their data center in India for long and we had to move hosting outside India.  


                  Later, we had to shut down matrix and diaspora due to lack of volunteers.
                  Recently, new volunteers joined the team to continue the XMPP service.
                  New accounts will be created on durare.org domain as diasp.in accounts are tied to diaspora accounts and it was not easy to migrate existing users to an XMPP only setup.
                  Today, although it is not accepting new account sign ups, it is still active for its old users.

                    > [!NOTE]
                    > XMPP Compliance Badge here

                    > [!NOTE]
                    > Federation badge here

      - title: Poddery
        content: |
                  Poddery XMPP service is also hosted on Durare's server.
                  Poddery was a combined offering of Diaspora social, Matrix and XMPP messaging service.
                  Due to lack of volunteers, like with Diasp.in, its Diaspora service was shut down, and only XMPP service was moved to Durare's server.
                  Its Matrix service is still managed by FSCI, and only XMPP server is managed by Durare team.
                  Poddery XMPP also doesn't accept new account sign ups, but it is active for its old users.
                  In future we would like to enable signs on both Diasp and Poddery.  

                  > [!NOTE]
                  > XMPP Compliance Badge here

                  > [!NOTE]
                  > Federation badge here


  - _bookshop_name: cards
#    heading:
#      preheading: Preheading
#      title: Heading
#      content: Cards content. It supports multiple lines.
#      align: start
    background:
      color: body-tertiary
      subtle: false
    cols: 3
    align: center
    justify: center
    width: 4
    padding: 0 
    elements:
      - title: | 
        content: |
                Hosted by  

                [![Indian Pirates](/img/indianpirates.svg)](https://pirates.org.in/)
      - title: | 
        content: | 
                Supported by 

                [![NMG 2026](/img/nmg.png)](https://thejeshgn.com/projects/nagarathna-memorial-grant/) 
      - title: | 
        content: |
                Payment Partner  

                [![Navodaya World](/img/navodaya.png)](https://navodaya.world/) 

---


