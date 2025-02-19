---
title: Diode App
layout: page
class: header--white
permalink: /solutions/app/
redirect_from:
- /products/d-drive/


### Hero
hero:
  class: hero--rounded hero--smaller
  animated: true
  heading: Team collaboration on&nbsp;Diode&nbsp;App.
  subheading: Secure collaboration around IT/OT/IP work product.
  buttons:
  - title: DOWNLOAD APP
    url: "/download/#app"
  image: hero/app.webp


### Story: For Teams
story:
  animated: false
  class: story--next
  title: Operate protected
  heading: For teams.
  content: |
    The Diode App creates secure tunnels between your team members that form a "security perimeter" (a Zone).  Each Zone has built-in collaboration and visualization capabilities. The app is a decentralized “local first” solution that doesn’t rely on third party servers - your team will be operating in one of the most protected environments possible.
  
    The Diode Network ensures that not even Diode has access to your team’s communications, information, or activity.
  buttons:
  - title: See how teams are using the app
    class: btn--blank btn--arrow
    url: "/teams/"
  image:
    src: story/app-full.webp
    alt: App
    class: network-wide


### Features
features:
  animated: false
  image:
    src: story/for-teams.webp
  after:
    src: story/protected.svg
  list:
  - title: Secure Chat and Files
    content: |
      Communications and structured information are at the core of everything teams do.  That’s why we built direct messaging, group chat, and file syncing into the core of the Diode App. All capabilities are fully end-to-end encrypted, ensuring that your team operates at only the highest security level available. 

  - title: Use for
    content: |
      Chat, files, notes, wiki, secure sites, web portals
  
      Communicate, reference, annotate, manage, and collaborate - everything a team working with real world IT, OT, or web assets requires.
    buttons:
    - title: DOWNLOAD
      url: "/download/#app"
    - title: SCHEDULE A DEMO
      class: btn--blank btn--arrow
      url: "https://diodedemo.paperform.co/"
      target: _blank

  - title: Connect From Anywhere
    content: |
      Collaborating with Diode is like using a VPN and collaboration tool built in one.  This allows your team to connect from anywhere in the world. And, if they happen to be in the same office, their devices direct-connect to carry on the conversation without even touching the Internet.
      
  -

  - title: Secure Web Portals
    content: |
      Sometimes you need to share, or collect, information with people who don't have Diode installed - via a share link accessible from any web browser. This is a great way to exchange information securely with customers, partners, and vendors when operating in a regulated industry. Creating a secure web portal can be done with a single click on any file or folder you'd like to make available.
      
  -

  - title: Protected Identities
    content: |
      Diode doesn’t require any personally identifiable information from you or your team to sign up and get going - all a Diode account requires is a pseudo anonymous username. Whether your team members use a single device or multiple linked devices, they can all be managed via self-custody credentials that are never stored on a server. 


### Box: Our solutions
solutions:
  animated: false
  class: box--orange
  title: No third parties means Zero&nbsp;Leakage&trade;
  heading: Our solutions.
  solutions:
  - title: CLI
    icon: "icons/cli.svg"
    content: The Diode CLI is a headless tool for OT, IT, and IoT devices. It can be used stand-alone to secure autonomous systems, and/or in concert with team members using the Diode App.
    button:
      title: Find Out More
      class: "btn--blank btn--arrow"
      url: "/solutions/cli/"
  - title: Vault
    icon: "icons/vault.svg"
    content: The Diode Vault is an autonomous tool that combines both App and CLI features in a small box or cloud appliance. 24-7 availability, backup, and geo-access for your team and assets.
    button:
      title: Find Out More
      class: "btn--blank btn--arrow"
      url: "/solutions/vault/"
  - title: Network
    icon: "icons/network.svg"
    content: The Diode Network is the world’s leading Smart Network - a new generation of zero trust software defined networks based on hardened blockchain technology. Think ad hoc E2EE perimeters.
    button:
      title: Find Out More
      class: "btn--blank btn--arrow"
      url: "/solutions/network/"

---

{%- include hero.liquid -%}

{%- include story.liquid -%}

---

{%- include features.liquid -%}

{%- include box.liquid data="solutions" -%}
