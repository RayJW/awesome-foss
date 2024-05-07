# Awesome FOSS

Welcome to my open-source list! This list is a collection of links and information to open-source alternatives to proprietary software. My goal is to provide a resource for users to find and learn about open-source options for a variety of different applications and tools. I hope that this list will be a useful resource for anyone interested in open-source software.

[Jump to the content!](#everyday-software)

## Intro

In our current online world, most of our software choices are dominated by proprietary closed-source projects with the goal of locking users into their ecosystems and collecting as much user data as possible. This data can then be sold to advertisers to better target ads to certain groups. Additionally, this can create security issues because vulnerabilities are harder to find and diagnose for the community. Besides, if any of these tools were to shut down, all data and workflows revolving around them could potentially break or be lost on the next day.

This is why I created this list of FOSS (Free and Open Source Software) that you can use as a replacement for proprietary solutions.

### Table of Content

- [Awesome FOSS](#awesome-foss)
  - [Intro](#intro)
    - [Table of Content](#table-of-content)
  - [Everyday Software](#everyday-software)
    - [Password Managers](#password-managers)
      - [Honourable Mentions](#honourable-mentions)
    - [Two-Factor Authentication](#two-factor-authentication)
    - [Browsers](#browsers)
      - [Chromium Commentary](#chromium-commentary)
      - [Honourable Mentions](#honourable-mentions-1)
  - [Communication](#communication)
    - [Instant Messaging](#instant-messaging)
      - [Honourable Mentions](#honourable-mentions-2)
      - [Word of Caution](#word-of-caution)
    - [E-mail](#e-mail)
      - [E-mail Providers](#e-mail-providers)
        - [Honourable Mentions](#honourable-mentions-3)
        - [Word of Caution](#word-of-caution-1)
      - [E-mail Clients](#e-mail-clients)
    - [Community Platforms](#community-platforms)
  - [Productivity](#productivity)
    - [Office Suite](#office-suite)
    - [Collaboration Platforms](#collaboration-platforms)
    - [Video Conferencing](#video-conferencing)
    - [Remote Desktop](#remote-desktop)
  - [Creativity](#creativity)
    - [Photo Editing](#photo-editing)
    - [Video Editing](#video-editing)
    - [Digital Art](#digital-art)
    - [Design and Prototyping](#design-and-prototyping)
    - [3D Computer Graphics](#3d-computer-graphics)
      - [Computer-aided Design (CAD)](#computer-aided-design-cad)
  - [Media](#media)
    - [Media Players](#media-players)
    - [Podcatchers (Podcast Clients)](#podcatchers-podcast-clients)
  - [Development](#development)
    - [IDEs](#ides)
  - [Contributing](#contributing)
  - [License](#license)

## Everyday Software

### Password Managers

Password managers are a very critical piece of software in our everyday lives, and everyone should use one. I would argue that using a FOSS password manager is very critical as it contains close to your whole digital identity and therefore represents a single point of failure for most of us. Using a well established open-source solution ensures that thousands of eyes have audited the source code and thoroughly searched for security vulnerabilities. It also gives the community the possibility to maintain an abandoned password manager until everyone has had the chance of moving away if a company behind an open-source password manager should ever stop operations.

| Software  | Description |
|-----------|-------------|
| [Bitwarden](https://bitwarden.com) | Bitwarden is one of the biggest open-source password managers. It is easy to use, supports 2FA integration and is free for almost all features. The premium version only costs 10 USD/year. For a free self-hosted implementation, check [Vaultwarden](https://github.com/dani-garcia/vaultwarden) which is compatible with all upstream clients. |
| [Padloc](https://padloc.app) | Padloc is another piece of open-source software which features end-to-end encryption and a client for all major platforms and browsers. The most essential features are free, and it has many features aimed at businesses or families in its premium versions. It's also possible to self-host Padloc with the use of Docker. |
| [Passbolt](https://www.passbolt.com) | Passbolt is another solution which can be self-hosted or used on their cloud. Its primary use is collaboration work, and it has many convenience features for companies and big teams. |
| [KeePass](https://keepass.info) | KeePass is one of the solutions that has been around the longest on this list. It is very well established and there are adaptions for pretty much every platform out there. It has no cloud syncing option, but it is very extensible. For bonus information check [awesome-keepass](https://github.com/lgg/awesome-keepass) made by @lgg. |
| [pass](https://www.passwordstore.org) | Pass is the standard Unix password manager which follows the Unix philosophy by keeping every password in encrypted PGP files which are then managed by a Git repo. It has a multitude of clients and implementations, many of which are listed on their website. |

#### Honourable Mentions

- [Passwork](https://passwork.pro) is another password manager option from Finland. It is primarily aimed at collaboration use in companies or teams. It is however on the pricier side and does not have a free version. The source code is also only auditable by customers.

### Two-Factor Authentication

Two-factor authentication has gained a lot of attention in recent years. However, not everyone is still using this critical security measure to ensure your accounts stay safe. It is important to use a solution that offers the exporting and importing of keys to make sure one doesn't lose account access in case of device failure / loss.

| Software  | Description |
|-----------|-------------|
| [Authenticator](https://gitlab.gnome.org/World/Authenticator) (Linux) | Authenticator is a rust based open-source solution for Linux with a beautiful UI and many features. |
| [Aegis Authenticator](https://getaegis.app) (Android) | Free, secure and open-source app for Android. Offers a backup / restore feature and has a customizable UI. |
| [Authenticator Pro](https://github.com/jamie-mh/AuthenticatorPro) (Android) | Free and open-source 2FA app for Android featuring encrypted backups, icons, categories and a many options for customization. Also features a Wear OS companion app. |
| [Tofu](https://www.tofuauth.com) (iOS) | Tofu is an easy-to-use 2FA app designed specifically for iOS. |
| [2FAS](https://2fas.com) (iOS / Android / Browser) | This beautiful 2FA app is fully open-source and has privacy in mind at every step. It is available for both iOS and Android, and it also features a browser companion. |
| [Authenticator](https://mattrubin.me/authenticator) (iOS) | Authenticator is a simple, and open-source authenticator app for iOS that never connects to the internet. |
| [Authenticator](https://authenticator.cc) (Browser) | The Authenticator browser extension adds 2FA support right into your browser with both time, and HMAC-Based OTPs. |
| [Ente Auth](https://github.com/ente-io/ente/blob/main/auth/README.md) (Cross-platform) | Ente Auth is an offering by the open-source photo storage provider Ente. It offers everything one could need, cross-platform syncing with apps for iOS, Android, Windows, macOS, and Linux. They offer an option to import and export your data, your data is kept safe since everything is end-to-end encrypted. |
| [Bitwarden Authenticator](https://bitwarden.com/download/#bitwarden-authenticator-mobile) (iOS / Android) | This is a relatively new offering by the highly trusted team behind Bitwarden. While they already offered the option to store 2FA codes inside their password manager, this now provides you with the option to keep data separate from your passwords. |

### Browsers

Browsers are one of the most important tools of our daily life. They are also a huge privacy and security threat since we use them to interface with all sorts of untrusted third-party websites. Since many modern applications are switching to the easier web app solution, they are also becoming increasingly influential as we started using browsers for many private things, e.g. mail. Thus, it is very important to use a secure and private option to protect yourself from the many unknown dangers of the open web.

| Software  | Description |
|-----------|-------------|
| [Firefox](https://www.mozilla.org/firefox/browsers) | By far the most mainstream option is the Firefox browser. It delivers a very privacy conscious configuration out of the box and has sane defaults. Honestly, one can barely go wrong with Firefox. |
| [LibreWolf](https://librewolf.net) | For anyone wanting to go a step further LibreWolf is a great alternative as it is an independent fork of Firefox that aims to provide even better defaults increasing the privacy, security, and user freedom. However, site breakages could be more likely as it also includes an ad-blocker by default. |
| [Tor Browser](https://www.torproject.org) | Tor definitely provides the most anonymity and privacy out of all the options. By its unique design, it routes all traffic through multiple nodes, so no single point of failure can be used to track its users. It also has a highly secure config by default, taking into account almost all ways to track users across the internet. That, however, does come with a usability trade-off. |
| [Mullvad Browser](https://mullvad.net/browser) | This browser from the highly trusted Mullvad company has been created in collaboration with the Tor Project. It offers the strongest possible protection without the caveats of the Tor browser. It essentially has the same privacy and security features but doesn't route all traffic through the Tor network. Thus serving almost the same purpose as the Tor browser except for the clear web. |

#### Chromium Commentary

Google has shown time and time again that they are willing to abuse their browser monopoly to push technologies and features against the user's best interest. E.g. MV3 nerfing ad-blockers, killing JPEG XL support to push its own inferior WebP, and tracking users with proprietary Chromium features while also killing any competition by disabling cookies. While some of those things are still in progress, I cannot put any Chromium-based browsers in the superior options as currently no fork has shown the capabilities / resources necessary to create a Chromium fork without the controversies. For more info, check the [Contra Chrome Comic](https://contrachrome.com).

#### Honourable Mentions

[Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) is the only option I can somewhat recommend as it is a Chromium fork that completely removed all proprietary Google integration stuff and greatly increases your privacy.

[Brave Browser](https://brave.com) is another option. However, there have been a few controversies surrounding it, e.g. it started manipulating links by adding referral codes. This is a tremendous break of trust as you, the user, should decide what links you want to visit and not your browser. Finally, it's also still Chromium-based, thus vulnerable to all those issues I talked about above. This is why I can't really recommend using Brave.

## Communication

### Instant Messaging

Instant messaging has become the main way we communicate these days. Although the space has been dominated by WhatsApp and SMS for many years, it is time to end this dominance. In recent years, it has become increasingly clear, that it is time to start using encrypted messaging. In light of the many data leaks and spying scandals, people have come to realize that messages contain our thoughts, our friendships, and much more. Thus, it is important to use a messenger supporting end-to-end encryption with transparent business practices.

| Software  | Description |
|-----------|-------------|
| [Signal](https://signal.org) | This is probably the most popular, secure, open-source messaging app out there at the moment. It uses the waterproof [Signal Protocol](https://en.wikipedia.org/wiki/Signal_Protocol), and it sports features which match most of the less secure messaging services. It supports instant-messaging, voice and video calls, media and attachments, and even stories (which you can turn off completely in case you dislike them). Furthermore, it is completely free and has clients (that work independently of your phone) on almost every platform. Signal is recommended by Edward Snowden, and will soon support usernames, thus eliminating the need for a phone number. It is hands down the best solution for secure mainstream messaging. |
| [SimpleX](https://simplex.chat) | SimpleX is a unique messenger which is probably the one most compatible with the strongest thread models. It has no identifiers tied to users and offers the ability to create and delete profiles on the spot without losing existing contacts. This enables the segmentation of contacts and complete anonymity when connecting with new entities. |
| [Matrix](https://matrix.org) | This is the most commonly used messaging protocol in the decentralized world. What this means is that anyone can create their own server and decide what other servers he wants to connect with. That way you can ensure your data stays where you want it to stay, and you can still text, call, or video chat with anyone also using this protocol. The most famous Matrix client is [Element](https://element.io). Its features rival those of many other messengers, and it runs on almost anything. But since Matrix is just the protocol, you can use any client you want to chat. |
| [XMPP](https://xmpp.org) | This protocol, also known as Jabber, is a standard made for decentralized messaging. It has been in use for decades and used to be the base for many messaging apps until the Signal Protocol took over for the centralized solutions and Matrix for the decentralized messengers. |

#### Honourable Mentions

[Silence](https://silence.im) is a decent option if you are still bound to traditional SMS messaging, since it makes it easy to encrypt SMS/MMS. However, this is more of a workaround since internet-based messaging is much more flexible, faster, and more censorship resistant than SMS/MMS.

#### Word of Caution

While there are many messaging apps out there that claim to be secure, there are many options that do not provide perfect security and / or privacy. **I would not trust these!** A few examples are Telegram, Threema, Silent Phone, and Viber. These should not be used to communicate personal data as they have flaws, compromising their integrity.

### E-mail

First things first, e-mail is **not** secure! E-mail is a flawed form of communication, as it is possible for third parties, including governments, to intercept and read e-mails. This is particularly true for e-mails that are transmitted over unencrypted connections.
The [PRISM surveillance program](https://en.wikipedia.org/wiki/PRISM_(surveillance_program)), run by the National Security Agency (NSA) in the United States, is one example of how governments can access and analyze the e-mail and other electronic communications of individuals.
While there are ways to secure e-mail and make it more difficult for third parties to intercept messages, such as using end-to-end encryption, it is important to be aware that e-mail is not a completely secure form of communication and to be cautious about the information you share via e-mail.
I still provide a list of open-source, E2EE, and somewhat secure e-mail providers that do protect user data. This does not mean that you should rely on e-mail for sensitive information in most cases, though.

#### E-mail Providers

| Provider  | Description |
|-----------|-------------|
| [ProtonMail](https://proton.me/mail) | This is an open-source and E2EE e-mail service that is somewhat anonymous. It is based in Switzerland. They have a modern UI and native mobile apps. They offer a free plan that has everything you need to get you started and a premium option where you can get extras, like custom domains. Signing up requires no personal data, and you can access their service via Tor on their [.onion](https://protonirockerxow.onion) address. |
| [Tuta](https://tuta.com) | This open-source e-mail service is based in Germany and has a basic UI that is pretty intuitive for people moving over. They also offer secure, native mobile apps, and anonymous signup. Just like with ProtonMail, you get the possibility to sign up for their free service or their premium plan offering additional features. However, their encryption does not use OpenPGP, which means support can be flaky with other e-mail providers. |
| [mailbox.org](https://mailbox.org) | Mailbox.org is also based in Germany. They offer no free plan, but their standard service only costs €12/year. They are an eco-friendly service as their operations are 100% powered by eco-friendly energy. Furthermore, they also offer you to use your custom domain, e-mail encryption, proper account security, and encrypted mail storage. They don't have native e-mail clients, but they work well with any other client listed below. |

##### Honourable Mentions

There are many more good options for private mail. Some notable ones are [StartMail](https://www.startmail.com), [HushMail](https://www.hushmail.com), and [Disroot](https://disroot.org/services/email).

##### Word of Caution

- OpenPGP does not offer Perfect Forward Secrecy (PFS), since I disqualified instant messengers not supporting PFS, I also have to mention that here. This means that if the private key ever leaks, all previous data can easily be decrypted.
- Even when using end-to-end encrypted e-mail, not all information is encrypted. So, metadata will still inevitably be leaked.

#### E-mail Clients

| Software  | Description |
|-----------|-------------|
| [Mozilla Thunderbird](https://www.thunderbird.net) (Desktop) | As a free and open-source solution created and backed by Mozilla, Thunderbird is an excellent e-mail client for all major platforms that is customizable and easy to user. There is also the [Betterbird](https://www.betterbird.eu) fork, which aims to provide an even better experience with more bug fixes and features. |
| [RoundCube](https://roundcube.net) (Web) | This browser-based IMAP client features an application-like UI and has full functionality you would expect from an e-mail client. |
| [K-9 Mail](https://k9mail.app) (Android) | It was acquired by Thunderbird and is probably the feature-richest Android e-mail client you can find. It provides all the features you need for secure messaging, including OpenGPG capabilities for E2EE e-mails. |

### Community Platforms

When communicating with big communities of strangers a very specific feature set is required. In recent years Discord has overwhelmingly taken the position of the leader in this specific area. However, there are a bunch of security, and privacy concerns regarding Discord. Basically everything is logged, unencrypted, and your personal data is used for tracking / advertisement reasons. For a more laid out overview you can check [this Reddit post](https://www.reddit.com/r/privacy/comments/rsxeee/you_should_never_use_discord_and_heres_why). However, it doesn't have to be that way. There are open-source alternatives that respect your privacy.

| Software  | Description |
|-----------|-------------|
| [Revolt.Chat](https://revolt.chat) | Although, still in public beta Revolt.Chat already features an impressive repertoire of features. It is the closest to a Discord alternative you will probably get and has an impressive looking roadmap. It has a much more open approach than Discord, featuring community themes, and plugins without the risk of getting banned for using a modified client. Furthermore, it respects your privacy and collects no personal data, and it even has plans for full E2EE for direct, and group messaging. |

## Productivity

### Office Suite

Everyone needs an office suite occasionally. Software like Microsoft Office, and Google Docs have become in disposable in our world. However, there is no reason why such important software should be hidden behind subscriptions, paywalls, and data hogging services. Now is the time better than ever to switch over to a solution supporting open standards and protecting your data at no cost! Especially as many schools / governments recently decided that cloud office solutions are unfit for sensitive data like that of children.

| Software  | Description |
|-----------|-------------|
| [LibreOffice](https://www.libreoffice.org) (Desktop) | This is probably by far the most commonly used Office alternative. It has a ton of features, is open-source, regularly receives new updates, and feels great on every desktop platform. With a bit of tweaks, the compatibility with Microsoft Office works great, and the interface can be made surprisingly similar. For more information about that, “The Linux Experiment” has a great [video](https://www.youtube.com/watch?v=G0che2Az9hw) on the topic. |
| [ONLYOFFICE](https://www.onlyoffice.com) (Desktop / Mobile / Web) | This is another office suite which is commonly used among FOSS users. Its looks are very close to Microsoft Office 2013, and it runs on almost all platforms, it has great Microsoft Office compatibility and a lot of features, including real-time collaboration if you have an online document server. |
| [Collabora Office](https://www.collaboraoffice.com) (Desktop / Mobile) | Collabora Office is made by Collabora who are among the most active LibreOffice contributors! Their goal is to bring LibreOffice to the Web and Mobile, and their office suite has a lot of enterprise and government focused features. |

### Collaboration Platforms

Online team collaboration has been at the forefront of our lives for some time now, and it is increasingly clear, that it is here to stay. Thus, it is very unfortunate that many of the most popular options, like Slack, Microsoft Teams, and Google for Work have serious privacy issues. Luckily, there are great open-source alternatives out there to stay in control of your data.

| Software  | Description |
|-----------|-------------|
| [Rocket.Chat](https://www.rocket.chat) | Self-hosted, cross-platform, and feature-rich. Rocket.Chat has a fast, intuitive UI and should feel right at home for most users that have experience with other collaboration platforms. This is an ideal solution for teams looking to take their organization to the next level with a wide variety of integrations. |
| [Mattermost](https://mattermost.com) | One of the preffered solutions for technical teams. Mattermost has an open-source edition and can be self-hosted. It is a great Slack alternative and has many integrations while featuring a native client for all major platforms. |

### Video Conferencing

In light of the enormous amount of [security issues with Zoom](https://www.tomsguide.com/news/zoom-security-privacy-woes), and many other mainstream options, it becomes clear that we need open, private, and secure video calling. What solution works best for you depends on many things like usability, features, and security requirements.

| Software  | Description |
|-----------|-------------|
| [Jitsi Meet](https://jitsi.org) | Is the open-source video calling app that has it all. Creating an account is optional to use this software offering encrypted and free video calling available on the web, the desktop, and mobile. You are free to use the public, your own self-hosted, [or any other community hosted Jitsi instance](https://jitsi.github.io/handbook/docs/community/community-instances) for your calls. |
| [Jami](https://jami.net) | This is a free and open-source, distributed video calling and screen sharing platform that heavily focuses on security. Jami is peer-to-peer, and features full E2EE including PFS for all your communications. It has apps for all major platforms, including mobile. |
| [BigBlueButton](https://bigbluebutton.org) | This pedagogic-centric virtual classroom is ideal for people that are searching for a self-hosted, open-source solution featuring many classroom-like features. It sports features like breakout rooms, and multi-user whiteboards which make online teaching a breeze. |

### Remote Desktop

Remote Desktop solutions are a great way to help others with problems they can't solve themselves, or simply to control your device while you are not next to it. Even though there are a lot of commercial solutions, the inherent risk of not knowing where essentially everything about your computer, including all the keystrokes you enter and the things you look at go to, is big. That's why I recommend choosing an open-source solution to make sure your data stays with you.

| Software  | Description |
|-----------|-------------|
| [RustDesk](https://rustdesk.com) | RustDesk is an amazing open-source remote desktop software because it works straight out of the box but still gives you the option to choose your own rendezvous server, including a self-hosted one that they offer for download, or you can even write your own one because the protocol is fully open-source like everything else! |

## Creativity

### Photo Editing

Open-source photo editing software is important for users who want to have more control over their digital creations. This allows users to create unique and personalized workflows that can be tailored to their specific projects. Additionally, open-source photo editing software is often free and can be used by anyone, regardless of their financial resources. This makes it an accessible option for users who cannot afford proprietary software or don't want to be at the grace of exploitative companies like Adobe. Overall, open-source photo editing software empowers users to take control of their creative process and produce high-quality digital content without being limited by the constraints of proprietary software.

| Software  | Description |
|-----------|-------------|
| [Darktable](https://www.darktable.org) | Darktable is an open-source photography workflow application which offers a lighttable to collect your raw images in a database where you can manage them by tagging, rating and much more. On top of that, it offers the darkroom, which gives you all the tools to develop and enhance your raw images. It is a great alternative to Adobe Lightroom and offers virtually unlimited creative freedom. |
| [GIMP](https://www.gimp.org) | The GNU Image Manipulation Program (GIMP) is a cross-platform image editor. You can use it for photo editing, drawing and graphics design. One of the main advantages of GIMP is its flexibility and extensibility. Users can create and install plugins and scripts to customize the software and extend its functionality. |

### Video Editing

Open-source video editing software is essential for anyone looking to create, edit, or produce video content without relying on proprietary software. With the rise of social media and online video platforms, video content has become more prevalent than ever before. Open-source video editing software provides users with tools and features to cut, trim, and arrange video footage, add special effects and transitions, and export finished videos in a variety of formats, all while maintaining a commitment to open-source principles. Whether you're a professional videographer or an amateur content creator, open-source video editing software is a must-have tool for bringing your ideas to life on screen while promoting free and open collaboration.

| Software  | Description |
|-----------|-------------|
| [Kdenlive](https://kdenlive.org) | Kdenlive is a fully fletched open-source video editor. It has everything one could wish for including great compatibility with a multitude of audio / video formats, multi-track editing, effects and transitions and much more! |
| [Olive](https://olivevideoeditor.org) | Olive is another great choice for a non-linear video editor and it is aiming to provide a fully-featured alternative to professional video editing. They have been hard at work releasing their second major version featuring a full rewrite. |

### Digital Art

Digital art and painting software has revolutionized the way artists create and share their work. With the power of digital tools, artists can create stunning artwork with precision, speed, and flexibility. From painting to drawing to sculpting, digital art software provides artists with an array of customizable brushes, colour palettes, and layer management tools to support their creative workflows. Open-source digital art software in particular allows artists to have greater control over their tools and techniques, while fostering a community of collaboration and innovation.

| Software  | Description |
|-----------|-------------|
| [Krita](https://krita.org) | Krita is an open-source digital painting software designed for concept art, texture and matte painters, and illustrations. It offers a range of customizable brushes, colour palettes, and layer management tools to support creative workflows. |
| [Inkscape](https://inkscape.org) | Inkscape is a powerful open-source vector graphics editor that allows users to create and edit scalable vector graphics. It supports a variety of file formats, including SVG, PDF, EPS, and AI, and provides users with a range of tools and features for creating and manipulating vector graphics. |
| [Pinta](https://www.pinta-project.com/) | While perhaps a less sophisticated than the other options mentioned, Pinta is a quite powerful option with the goal to stay intuitive and easy to use. It works on basically all desktop OSes and offers almost all the functionality needed for basic image edits and drawing. |

### Design and Prototyping

Design and prototyping is an important step in software development and assists in creating software great for everyone, right in the spirit of open-source. Choosing a solution focusing on open-source makes sure you get great compatibility with other software thanks to a commitment to open standards, and it enables everyone and all teams no matter their resources to create great solutions competing with the big players.

| Software  | Description |
|-----------|-------------|
| [Penpot](https://penpot.app) | Penpot is a free and open-source alternative to Figma. You can self-host it if you want to deploy it locally for your team, and thanks to its many features focused on collaboration, everyone from designers to developers can create great things with Penpot. It is a great example of why we need open-source alternatives because the buyout of Figma has exposed a lot of people whose livelihood depends on their work to predatory practices and pricing of Adobe without a warning. |

### 3D Computer Graphics

3D computer graphics software is essential for anyone looking to create 3D models, animations, and visual effects. From film and TV to video games and product design, 3D computer graphics play a vital role in modern visual media. Open-source 3D computer graphics software provides users with powerful tools and features for modelling, rigging, animation, and rendering, while fostering a community of collaboration and innovation. Whether you're a professional animator or a hobbyist artist, open-source solutions will help you bring your creativity to life, no matter your resources.

| Software  | Description |
|-----------|-------------|
| [Blender](https://www.blender.org) | Blender is probably one of the best examples of how open-source software can just be plain better. They have become the de-facto standard in the CG world and put forth an impressive development speed without charging their users or limiting their ability to make profit. |

#### Computer-aided Design (CAD)

| Software  | Description |
|-----------|-------------|
| [FreeCAD](https://www.freecad.org) | FreeCAD is an open-source parametric 3D modeler made to design real-life objects of all sizes. It is designed to support a wide range of uses, including but not limited to product design, mechanical engineering, and architecture. It has a lot of amazing features and people of all skills will feel right at home thanks to its intuitive and modular design. |
| [LibreCAD](https://librecad.org) | LibreCAD is another great choice for open-source 2D-CAD work. It can work with DXF, DWG, and SVG files while maintaining a highly customizable user interface with dozens of translations available. |
| [OpenSCAD](https://openscad.org) | OpenSCAD is a software for creating solid 3D CAD models. Unlike most other 3D modelling software, it does not focus on the artistic aspects, but instead on the CAD aspects. This is why its features are great for 3D models of machine parts and more. |
| [KiCAD](https://www.kicad.org) | KiCad is an open-source electronics design automation suite. It is designed to support the user in PCB design, it has a very capable schematic, component and layout editor. In addition to that it has a useful 3d Viewer to integrate the electronics into a mechanical design. |

## Media

### Media Players

From watching movies over binging series to listening to your favorite album - for all those things you need a good and reliable media player. Because of their broad support of different audio & video formats, FOSS media players are highly regarded by consumers regardless of the genre.

| Software  | Description |
|-----------|-------------|
| [MPV](https://mpv.io) | MPV is a media player software primarily used through a Command-line interface, supporting a wide range of media formats. With its many configuration options and keyboard based operation, it was designed with more advanced users in mind, but the numerous GUIs and the online documentation allow beginners to enjoy the tool too. |
| [VLC](https://www.videolan.org/vlc/index.html) | VLC is another media player supporting almost any format imaginable. It has a user-friendly interface and can be used by anyone easily. It doesn't quite offer the same ability to customize every degree of your player as MPV, but even for advanced users, it is still a great choice. |

### Podcatchers (Podcast Clients)

Traditionally, podcasts are distributed through an RSS feed, to which podcast clients (also called podcatchers) can subscribe. It would only make sense to pair this distributed and open way to share media with a client that is open as well, right?

| Software  | Description |
|-----------|-------------|
| [AntennaPod](https://antennapod.org) (Android) | Delivered over the Google Play Store and F-Droid, AntennaPod is a feature-rich podcatcher that delivers everything a podcast listener desires. |
| [Kasts](https://apps.kde.org/kasts) (Desktop)| Developed by the KDE community, Kasts is a neat solution for listening podcasts on your desktop. Nothing more, nothing less. |

## Development

As software development continues to shape our world, it's increasingly important to ensure that the tools we use to create that software are trustworthy, secure, and transparent. Open-source not only encourages collaboration and innovation, but it also allows developers to ensure that the software they use meets their needs and is free from hidden backdoors or malicious code. By using open-source development tools, developers can have greater control over their development workflows and ensure that the software they create is secure, reliable, and respects user privacy while also staying safe themselves.

### IDEs

IDEs is what developers use to create code. People spend a considerable amount of time creating things they love in these text editors. For that reason it is important that they are modular so they can fit everyones needs and more importantly, so they don't spy on you. Luckily there a lot of great options out there!

| Software  | Description |
|-----------|-------------|
| [VSCodium](https://vscodium.com) | Everyone probably knows VS Code. However, not everyone knows that it is made by Microsoft. That means it includes proprietary third party trackers and telemetry, which not everyone might like. VSCodium is the fully open-source alternative, which removes everything that is not open-source, including all trackers from VS Code. |
| [Pulsar](https://pulsar-edit.dev) | Atom was another great option in the IDE space. But, ever since Microsoft bought GitHub everyone probably expected them to stop development eventually. Out of the ashes of Atom rose Pulsar, a fully open-source community driven fork which aims to be everything that Atom was and more. This might be your option if you don't like the idea of VS Code being made by Microsoft. |
| [Lapce](https://lapce.dev) | In case all the Chromium based editors are not your thing, Lapce is an amazing alternative. It is written in Rust and thus compiles to be a native option with GPU acceleration and low resource use. On top of that, their native Vim like editing and WASI plugin system means you can do whatever you want with it. |

## Contributing

Thanks for checking out my list! It is still very much work in progress and new information will gradually be added whenever I discover new awesome FOSS software. If you want to help, contributions are very welcome, and you can find all the information you need to get started in: [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

*Licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0.html)*
