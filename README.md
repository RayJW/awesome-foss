# Awesome FOSS

Welcome to my open-source list! This list is a collection of links and information to open-source alternatives to proprietary software. My goal is to provide a resource for users to find and learn about open-source options for a variety of different applications and tools. I hope that this list will be a useful resource for anyone interested in open-source software.

## Intro

In our current online world, most of our software choices are dominated by proprietary closed-source projects with the goal of locking users into their ecosystems and collecting as much user data as possible. This data can then be sold to advertisers to better target ads to certain groups. Additionally, this can create security issues because vulnerabilities are harder to find and diagnose for the community. Besides, if any of these tools were to shut down, all data and workflows revolving around them could potentially break or be lost on the next day.

This is why I created this list of FOSS (Free and Open Source Software) that you can use as a replacement for proprietary solutions.

### Categories

- **[Everyday Software](#everyday-software)**
  - [Password Managers](#password-managers)
  - [2FA](#two-factor-authentication)
  - [Browsers](#browsers)
- **[Communication](#communication)**
  - [Instant Messaging](#instant-messaging)
  - [E-Mail](#e-mail)
    - [E-Mail Providers](#e-mail-providers)
    - [E-Mail Clients](#e-mail-clients)
- **[Productivity](#productivity)**
  - [Collaboration Platforms](#collaboration-platforms)

## Everyday Software

### Password Managers

Password managers are a very critical piece of software in our everyday lives, and everyone should use one. I would argue that using a FOSS password manager is very critical as it contains close to your whole digital identity and therefore represents a single point of failure for most of us. Using a well established open-source solution ensures that thousands of eyes have audited the source code and thoroughly searched for security vulnerabilities. It also gives the community the possibility to maintain an abandoned password manager until everyone has had the chance of moving away if a company behind an open-source password manager should ever stop operations.

| Software  | Description |
|-----------|-------------|
| [Bitwarden](https://bitwarden.com/) | Bitwarden is one of the biggest open-source password managers. It is easy to use, supports 2FA integration and is free for almost all features. The premium version only costs 10 USD/year. For a free self-hosted implementation, check [Vaultwarden](https://github.com/dani-garcia/vaultwarden) which is compatible with all upstream clients. |
| [Padloc](https://padloc.app/) | Padloc is another piece of open-source software which features end-to-end encryption and a client for all major platforms and browsers. The most essential features are free, and it has many features aimed at businesses or families in its premium versions. It's also possible to self-host Padloc with the use of Docker. |
| [Passbolt](https://www.passbolt.com/) | Passbolt is another solution which can be self-hosted or used on their cloud. Its primary use is collaboration work, and it has many convenience features for companies and big teams. |
| [KeePass](https://keepass.info/) | KeePass is one of the solutions that has been around the longest on this list. It is very well established and there are adaptions for pretty much every platform out there. It has no cloud syncing option, but it is very extensible. For bonus information check [awesome-keepass](https://github.com/lgg/awesome-keepass) made by @lgg. |

#### Honourable Mentions

- [Passwork](https://passwork.pro/) is another password manager option from Finland. It is primarily aimed at collaboration use in companies or teams. It is however on the pricier side and does not have a free version. The source code is also only auditable by customers.

### Two-Factor Authentication

Two-factor authentication has gained a lot of attention in recent years. However, not everyone is still using this critical security measure to ensure your accounts stay safe. It is important to use a solution that offers the exporting and importing of keys to make sure one doesn't lose account access in case of device failure / loss.

| Software  | Description |
|-----------|-------------|
| [WinAuth](https://winauth.github.io/winauth/) (Windows) | WinAuth is a portable 2FA solution that supports counter and time-based authenticators. However development has stopped in 2017. |
| [Authenticator](https://gitlab.gnome.org/World/Authenticator) (Linux) | Authenticator is a rust based open-source solution for Linux with a beautiful UI and many features. |
| [Aegis Authenticator](https://getaegis.app/) (Android) | Free, secure and open-source app for Android. Offers a backup / restore feature and has a customizable UI. |
| [Authenticator Pro](https://github.com/jamie-mh/AuthenticatorPro) (Android) | Free and open-source 2FA app for Android featuring encrypted backups, icons, categories and a many options for customization. Also features a Wear OS companion app. |
| [Tofu](https://www.tofuauth.com/) (iOS) | Tofu is an easy-to-use 2FA app designed specifically for iOS. |
| [Raivo](https://raivo-otp.com/) (iOS / MacOS) | Raivo OTP is a beautiful 2FA app with icon support that is natively made for iOS and macOS with on- and offline backups. |
| [Authenticator](https://mattrubin.me/authenticator/) (iOS) | Authenticator is a simple, and open-source authenticator app for iOS that never connects to the internet. |
| [Authenticator](https://authenticator.cc/) (Browser) | The Authenticator browser extension adds 2FA support right into your browser with both time, and HMAC-Based OTPs. |

#### Honourable Mentions

[Authy](https://authy.com/) (**proprietary**) is a very widely used 2FA application because of its sync capabilities. I, however, discourage the use of Authy as it is completely closed-source, and it is not possible to extract your seeds, which means you can **not** easily switch to another application.

### Browsers

Browsers are one of the most important tools of our daily life. They are also a huge privacy and security threat since we use them to interface with all sorts of untrusted third-party websites. Since many modern applications are switching to the easier web app solution, they are also becoming increasingly influential as we started using browsers for many private things, e.g. mail. Thus, it is very important to use a secure and private option to protect yourself from the many unknown dangers of the open web.

| Software  | Description |
|-----------|-------------|
| [Firefox](https://www.mozilla.org/en-US/firefox/browsers/) | By far the most mainstream option is the Firefox browser. It delivers a very privacy conscious configuration out of the box and has sane defaults. Honestly, one can barely go wrong with Firefox. |
| [LibreWolf](https://librewolf.net/) | For anyone wanting to go a step further LibreWolf is a great alternative as it is an independent fork of Firefox that aims to provide even better defaults increasing the privacy, security, and user freedom. However, site breakages could be more likely as it also includes an ad-blocker by default. |
| [Tor Browser](https://www.torproject.org/) | Tor definitely provides the most anonymity and privacy out of all the options. By its unique design, it routes all traffic through multiple nodes, so no single point of failure can be used to track its users. It also has a highly secure config by default, taking into account almost all ways to track users across the internet. That, however, does come with a usability trade-off. |

#### Chromium Commentary

Google has shown time and time again that they are willing to abuse their browser monopoly to push technologies and features against the user's best interest. E.g. MV3 nerfing ad-blockers, killing JPEG XL support to push its own inferior WebP, and tracking users with proprietary Chromium features while also killing any competition by disabling cookies. While some of those things are still in progress, I cannot put any Chromium-based browsers in the superior options as currently no fork has shown the capabilities / resources necessary to create a Chromium fork without the controversies. For more info, check the [Contra Chrome Comic](https://contrachrome.com/).

#### Honourable Mentions

[Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) is the only option I can somewhat recommend as it is a Chromium fork that completely removed all proprietary Google integration stuff and greatly increases your privacy.

[Brave Browser](https://brave.com/) is another option. However, there have been a few controversies surrounding it, e.g. it started manipulating links by adding referral codes. This is a tremendous break of trust as you, the user, should decide what links you want to visit and not your browser. Finally, it's also still Chromium-based, thus vulnerable to all those issues I talked about above. This is why I can't really recommend using Brave.

## Communication

### Instant Messaging

Instant messaging has become the main way we communicate these days. Although the space has been dominated by WhatsApp and SMS for many years, it is time to end this dominance. In recent years, it has become increasingly clear, that it is time to start using encrypted messaging. In light of the many data leaks and spying scandals, people have come to realize that messages contain our thoughts, our friendships, and much more. Thus, it is important to use a messenger supporting end-to-end encryption with transparent business practices.

| Software  | Description |
|-----------|-------------|
| [Signal](https://signal.org/) | This is probably the most popular, secure, open-source messaging app out there at the moment. It uses the waterproof [Signal Protocol](https://en.wikipedia.org/wiki/Signal_Protocol), and it sports features which match most of the less secure messaging services. It supports instant-messaging, voice and video calls, media and attachments, and even stories (which you can turn off completely in case you dislike them). Furthermore, it is completely free and has clients (that work independently of your phone) on almost every platform. Signal is recommended by Edward Snowden, and will soon support usernames, thus eliminating the need for a phone number. It is hands down the best solution for secure mainstream messaging. |
| [Matrix](https://matrix.org/) | This is the most commonly used messaging protocol in the decentralized world. What this means is that anyone can create their own server and decide what other servers he wants to connect with. That way you can ensure your data stays where you want it to stay, and you can still text, call, or video chat with anyone also using this protocol. The most famous Matrix client is [Element](https://element.io/). Its features rival those of many other messengers, and it runs on almost anything. But since Matrix is just the protocol, you can use any client you want to chat. |
| [XMPP](https://xmpp.org/) | This protocol, also known as Jabber, is a standard made for decentralized messaging. It has been in use for decades and used to be the base for many messaging apps until the Signal Protocol took over for the centralized solutions and Matrix for the decentralized messengers. |

#### Honourable Mentions

[Silence](https://silence.im/) is a decent option if you are still bound to traditional SMS messaging, since it makes it easy to encrypt SMS/MMS. However, this is more of a workaround since internet-based messaging is much more flexible, faster, and more censorship resistant than SMS/MMS.

#### Word of Caution

While there are many messaging apps out there that claim to be secure, there are many options that do not provide perfect security and / or privacy. **I would not trust these!** A few examples are Telegram, Threema, Silent Phone, and Viber. These should not be used to communicate personal data as they have flaws, compromising their integrity.

### E-mail

First things first, e-mail is **not** secure! Email is not a secure form of communication, as it is possible for third parties, including governments, to intercept and read emails. This is particularly true for emails that are transmitted over unencrypted connections.
The [PRISM surveillance program](https://en.wikipedia.org/wiki/PRISM_(surveillance_program)), run by the National Security Agency (NSA) in the United States, is one example of how governments can access and analyze the email and other electronic communications of individuals.
While there are ways to secure email and make it more difficult for third parties to intercept messages, such as using end-to-end encryption, it is important to be aware that email is not a completely secure form of communication and to be cautious about the information you share via email.
I still provide a list of open-source, E2EE, and somewhat secure e-mail providers that do protect user data. This does not mean that you should rely on e-mail for sensitive information in most cases, though.

#### E-mail Providers

| Provider  | Description |
|-----------|-------------|
| [ProtonMail](https://proton.me/mail) | This is an open-source and E2EE e-mail service that is somewhat anonymous. It is based in Switzerland. They have a modern UI and native mobile apps. They offer a free plan that has everything you need to get you started and a premium option where you can get extras, like custom domains. Signing up requires no personal data, and you can access their service via Tor on their [.onion](https://protonirockerxow.onion/) address. |
| [Tutanota](https://tutanota.com/) | This open-source e-mail service is based in Germany and has a basic UI that is pretty intuitive for people moving over. They also offer secure, native mobile apps, and anonymous signup. Just like with ProtonMail, you get the possibility to sign up for their free service or their premium plan offering additional features. However, their encryption does not use OpenPGP, which means support can be flaky with other e-mail providers. |
| [mailbox.org](https://mailbox.org/en/) | Mailbox.org is also based in Germany. They offer no free plan, but their standard service only costs €12/year. They are an eco-friendly service as their operations are 100% powered by eco-friendly energy. Furthermore, they also offer you to use your custom domain, e-mail encryption, proper account security, and encrypted mail storage. They don't have native e-mail clients, but they work well with any other client listed below. |

##### Honourable Mentions

There are many more good options for private mail. Some notable ones are [StartMail](https://www.startmail.com/en/), [HushMail](https://www.hushmail.com/), [Skiff](https://skiff.com/), and [Disroot](https://disroot.org/en/services/email).

##### Word of Caution

- OpenPGP does not offer Perfect Forward Secrecy (PFS), since I disqualified instant messengers not supporting PFS, I also have to mention that here. This means that if the private key ever leaks, all previous data can easily be decrypted.
- Even when using end-to-end encrypted e-mail, not all information is encrypted. So, metadata will still inevitably be leaked.

#### E-mail Clients

| Software  | Description |
|-----------|-------------|
| [Mozilla Thunderbird](https://www.thunderbird.net/en-US/) (Desktop) | As a free and open-source solution created and backed by Mozilla, Thunderbird is an excellent e-mail client for all major platforms that is customizable and easy to user. There is also the [Betterbird](https://www.betterbird.eu/) fork, which aims to provide an even better experience with more bug fixes and features. |
| [RoundCube](https://roundcube.net/) (Web) | This browser-based IMAP client features an application-like UI and has full functionality you would expect from an e-mail client. |
| [K-9 Mail](https://k9mail.app/) (Android) | It was acquired by Thunderbird and is probably the feature-richest Android e-mail client you can find. It provides all the features you need for secure messaging, including OpenGPG capabilities for E2EE e-mails. |

## Productivity

### Collaboration Platforms

Online team collaboration has been at the forefront of our lives for some time now, and it is increasingly clear, that it is here to stay. Thus, it is very unfortunate that many of the most popular options, like Slack, Microsoft Teams, Discord, and Google for Work have serious privacy issues. Luckily, there are great open-source alternatives out there to stay in control of your data.

| Software  | Description |
|-----------|-------------|
| [Rocket.Chat](https://www.rocket.chat/) | Self-hosted, cross-platform, and feature-rich. Rocket.Chat has a fast, intuitive UI and should feel right at home for most users that have experience with other collaboration platforms. This is an ideal solution for teams looking to take their organization to the next level with a wide variety of integrations. |
| [Mattermost](https://mattermost.com/) | One of the preffered solutions for technical teams. Mattermost has an open-source edition and can be self-hosted. It is a great Slack alternative and has many integrations while featuring a native client for all major platforms. |

## Contributing

Thanks for checking out my list! It is still very much work in progress and new information will gradually be added whenever I discover new awesome FOSS software. If you want to help, contributions are very welcome, and you can find all the information you need to get started in: [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

*Licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0.html)*
