# Security practices

## Full-disk Encryption

Our devices (computers, phones, tablets etc.) contain a lot of private and confidential data belonging to us and our clients. If you’re logged into your Obvious accounts (email, drive, remote servers etc.) on any device, you must take extra precaution that the data remains safe. As a general rule, you should try and limit the number of devices that have any work-related data.

Most modern Android and iOS devices support hardware encryption of data, and have it enabled by default. However, macOS computers do not have full-disk encryption enabled by default and you must enable it yourself — you should do this *as soon* as you get your computer!

In macOS, open System Preferences. Go to Security and find the tab called “FileVault” — that’s what Apple calls full-disk encryption. Once you enable it, the system will generate a decryption key that you should note down (ideally a physical medium; definitely not on the same computer!) and store somewhere safely. If this key is lost and you ever forget your password, it will be impossible to recover any data. The encryption process should take less than 30 minutes to finish, and you can keep working while it happens.

![FileVault in macOS Mojave](https://i.imgur.com/TEfaYDh.png)

### But why?

It is important to know why full-disk encryption is important and necessary. Most people are unaware that if you have a physical access to a computer (pretty any computer running Windows, macOS or Linux), and the storage is not encrypted... you can simply reset the administrator password and get access to all the files. Modern operating systems come with a recovery mode built in that allows this; the only way to truly secure your files is full-disk encryption. However, this can’t be done remotely so one needs the computer in front of them, which means this is a real possibility if your computer gets stolen. 

## Two-Factor Authentication

Whenever possible, you should use [two-factor authentication (2FA)](https://en.wikipedia.org/wiki/Multi-factor_authentication) for logging in to services. Normally, you only need a Username (or an email) and a Password to login to a service. Usernames are fairly easy to guess -- most people repeat email addresses and usernames across services, and many of those services publicly display this data. When it comes to passwords, most people repeat those too and (unfortunately) use something that is fairly easy to guess. Organisations have historically been bad at keeping user data safe. Passwords are stored using insecure methods, databases get hacked -- these are now normal occurrences in the news and it doesn't even surprise us. 

2FA lets people use a second factor for authentication. Indian banks and cards use SMS OTPs as a second factor all the time. It ensures that the user must know the full details of a card, and must also possess the phone-number registered against the card. Similarly, popular services like Gmail, Github, Slack etc. allow a _randomly-generated number_ to be used as a second factor, just like a bank's OTP.

A very popular, free of cost, OTP generation app is [Authy](https://authy.com/). Authy has helpful guides to setup 2FA on most services, and you should turn on 2FA for every service. It benefits you!

### Services we use that support 2FA

* [Google](https://gmail.com)
* [Slack](https://slack.com) 
* [Telegram](https://telegram.org/)
* [Github](https://github.com)  
* [Bitrise](https://bitrise.io) 
* [DigitalOcean](https://digitalocean.com) 
* [Lobsters](https://lobste.rs)
* [Instagram](https://instagram.com) 