# Awesome FOSS

This is a curated list of all the FOSS software I regularly use or follow to keep track of privacy respecting alternatives.

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

## Everyday Software

### Password Managers

Password managers are a very critical piece of software in our everyday lives, and everyone should use one. I would argue that using a FOSS password manager is very critical as it contains close to your whole digital identity and therefore represents a single point of failure for most of us. Using a well established open-source solution ensures that thousands of eyes have audited the source code and thoroughly searched for security vulnerabilities. It also gives the community the possibility to maintain an abandoned password manager until everyone has had the chance of moving away if a company behind an open-source password manager should ever stop operations.

| Software  | Description |
|-----------|-------------|
| [Bitwarden](https://bitwarden.com/) | Bitwarden is one of the biggest open-source password managers. It is easy to use, supports 2FA integration and is free for almost all features. The premium version only costs 10 USD/year. For a free self-hosted implementation, check [Vaultwarden](https://github.com/dani-garcia/vaultwarden) which is compatible with all upstream clients. |
| [Padloc](https://padloc.app/) | Padloc is another piece of open-source software which features end-to-end encryption and a client for all major platforms and browsers. The most essential features are free, and it has many features aimed at businesses or families in its premium versions. It's also possible to self-host Padloc with the use of Docker. |
| [Passbolt](https://www.passbolt.com/) | Passbolt is another solution which can be self-hosted or used on their cloud. Its primary use is collaboration work, and it has many convenience features for companies and big teams. |
| [KeePass](https://keepass.info/) | KeePass is one of the solutions that has been around the longest on this list. It is very well established and there are adaptions for pretty much every platform out there. It has no cloud syncing option, but it is very extensible. For bonus information check [awesome-keepass](https://github.com/lgg/awesome-keepass) made by @lgg. |

### Honourable Mentions

- [Passwork](https://passwork.pro/) is another password manager option from Finland. It is primarily aimed at collaboration use in companies or teams. It is however on the pricier side and does not have a free version. The source code is also only auditable by customers.

## Two-Factor Authentication

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

### Honourable Mentions

[Authy](https://authy.com/) (**proprietary**) is a very widely used 2FA application because of its sync capabilities. I, however, discourage the use of Authy as it is completely closed-source, and it is not possible to extract your seeds, which means you can **not** easily switch to another application.

## Browsers

Browsers are one of the most important tools of our daily life. They are also a huge privacy and security threat since we use them to interface with all sorts of untrusted third-party websites. Since many modern applications are switching to the easier web app solution, they are also becoming increasingly influential as we started using browsers for many private things, e.g. mail. Thus, it is very important to use a secure and private option to protect yourself from the many unknown dangers of the open web.

| Software  | Description |
|-----------|-------------|
| [Firefox](https://www.mozilla.org/en-US/firefox/browsers/) | By far the most mainstream option is the Firefox browser. It delivers a very privacy conscious configuration out of the box and has sane defaults. Honestly, one can barely go wrong with Firefox. |
| [LibreWolf](https://librewolf.net/) | For anyone wanting to go a step further LibreWolf is a great alternative as it is an independent fork of Firefox that aims to provide even better defaults increasing the privacy, security, and user freedom. However, site breakages could be more likely as it also includes an ad-blocker by default. |
| [Tor Browser](https://www.torproject.org/) | Tor definitely provides the most anonymity and privacy out of all the options. By its unique design, it routes all traffic through multiple nodes, so no single point of failure can be used to track its users. It also has a highly secure config by default, taking into account almost all ways to track users across the internet. That, however, does come with a usability trade-off. |

### Chromium Commentary

Google has shown time and time again that they are willing to abuse their browser monopoly to push technologies and features against the user's best interest. E.g. MV3 nerfing ad-blockers, killing JPEG XL support to push its own inferior WebP, and tracking users with proprietary Chromium features while also killing any competition by disabling cookies. While some of those things are still in progress, I cannot put any Chromium-based browsers in the superior options as currently no fork has shown the capabilities / resources necessary to create a Chromium fork without the controversies. For more info, check the [Contra Chrome Comic](https://contrachrome.com/).

### Honourable Mentions

[Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) is the only option I can somewhat recommend as it is a Chromium fork that completely removed all proprietary Google integration stuff and greatly increases your privacy.

[Brave Browser](https://brave.com/) is another option. However, there have been a few controversies surrounding it, e.g. it started manipulating links by adding referral codes. This is a tremendous break of trust as you, the user, should decide what links you want to visit and not your browser. Finally, it's also still Chromium-based, thus vulnerable to all those issues I talked about above. This is why I can't really recommend using Brave.

## Communication

### Instant Messaging

## Contributing

Thanks for checking out my list! It is still very much work in progress and new information will gradually be added whenever I discover new awesome FOSS software. If you want to help, contributions are very welcome, and you can find all the information you need to get started in: [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

*Licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0.html)*
