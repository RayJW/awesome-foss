# Awesome FOSS

This is a curated list of all the FOSS software I regularly use or follow to keep track of privacy respecting alternatives.

## Intro

In our current online world, most of our software choices are dominated by proprietary closed-source projects with the goal of locking users into their ecosystems and collecting as much user data as possible. This data can then be sold to advertisers to better target ads to certain groups. Additionally, this can create security issues because vulnerabilities are harder to find and diagnose for the community. Besides, if any of these tools were to shut down, all data and workflows revolving around them could potentially break or be lost on the next day.

This is why I created this list of FOSS (Free and Open Source Software) that you can use as a replacement for proprietary solutions.

### Categories

- **Everyday Software**
  - [Password Managers](#password-managers)

## Password Managers

Password managers are a very critical piece of software in our everyday lives, and everyone should use one. I would argue that using a FOSS password manager is very critical as it contains close to your whole digital identity and therefore represents a single point of failure for most of us. Using a well established open-source solution ensures that thousands of eyes have audited the source code and thoroughly searched for security vulnerabilities. It also gives the community the possibility to maintain an abandoned password manager until everyone has had the chance of moving away if a company behind an open-source password manager should ever stop operations.

| Software  | Description |
|-----------|-------------|
| [Bitwarden](https://bitwarden.com/) | Bitwarden is one of the biggest open-source password managers. It is easy to use, supports 2FA integration and is free for almost all features. The premium version only costs 10 USD/year. For a free self-hosted implementation, check [Vaultwarden](https://github.com/dani-garcia/vaultwarden) which is compatible with all upstream clients. |
| [Padloc](https://padloc.app/) | Padloc is another piece of open-source software which features end-to-end encryption and a client for all major platforms and browsers. The most essential features are free, and it has many features aimed at businesses or families in its premium versions. It's also possible to self-host Padloc with the use of Docker. |
| [Passbolt](https://www.passbolt.com/) | Passbolt is another solution which can be self-hosted or used on their cloud. Its primary use is collaboration work, and it has many convenience features for companies and big teams. |
| [KeePass](https://keepass.info/) | KeePass is one of the solutions that has been around the longest on this list. It is very well established and there are adaptions for pretty much every platform out there. It has no cloud syncing option, but it is very extensible. For bonus information check [awesome-keepass](https://github.com/lgg/awesome-keepass) made by @lgg. |

### Honorable mentions

- [Passwork](https://passwork.pro/) is another password manager option from Finland. It is primarily aimed at collaboration use in companies or teams. It is however on the pricier side and does not have a free version. The source code is also only auditable by customers.

## Contributing

Thanks for checking out my list! It is still work in progress and new information will gradually be added whenever I discover new awesome FOSS software. If you want to help contributions are very welcome and you can find all the information you need to get started in: [`CONTRIBUTING.md`](CONTRIBUTING.md)

## License

*Licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0.html)*
