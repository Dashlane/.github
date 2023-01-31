# Dashlane: Under the Hood

We are the creators of the Dashlane Password Manager. In our public repositories you will find the source code for our mobile apps. We have also developed a [CLI version of Dashlane](https://github.com/Dashlane/dashlane-cli), while not officially supported it is created by us at Dashlane.


Many of the technical details of our product can be found in our white paper here:

[Dashlane White Paper](https://www.dashlane.com/download/whitepaper-en.pdf)

Details in the white paper include:

- The use of [Argon2](https://github.com/P-H-C/phc-winner-argon2) for key derivation
- How 2FA is used to protect account access on a new device
- The use of public-key cryptography for sharing items between Dashlane accounts
- How zero-knowledge is ensured when enabling SSO login with Dashlane

## Our Apps

|  App |  Download link |
|---|---|
| Dashlane Password Manager   |  [Download on the Chrome Web Store](https://chrome.google.com/webstore/detail/dashlane-%E2%80%94-password-manag/fdjamakpfbbddfjaooikfcpapjohcfmg)</br>[Download on the App Store](https://apps.apple.com/app/dashlane/id517914548)</br>[Download on the Google Play Store](https://play.google.com/store/apps/details?id=com.dashlane)
| Dashlane Authenticator   |  [Download on the App Store](https://apps.apple.com/app/dashlane-authenticator/id1582978196)</br>[Download on the Google Play Store](https://play.google.com/store/apps/details?id=com.dashlane.authenticator) |

Note: The Dashlane Authenticator mobile apps integrate with our Dashlane Password Manager apps, allow easy access to TOTP codes while at the same time linking them to credentials in Dashlane.
