# Cybersecurity 101

## Core Concepts
  * Trust
  * Secrets
  * Anonymity
  * Authentication
  * Encryption
  	* Caesar cipher as a simple example
    * Symmetric/Asymmetric
    	* Symmetric = private key, Asymmetric = public key
    	* How do you share a secret (encryption key) over the internet securely?
  		* [Visual explanation of Public Key Cryptography](https://www.youtube.com/watch?v=YEBfamv-_do&feature=youtu.be&t=161)
  			* Hash
  			* One-way function
  * Threat model
  * There's no such thing as perfect security (the most secure email privacy is called PGP, or "Pretty Good Privacy")
  * Weakest link

## History
  * [The Thing](https://en.wikipedia.org/wiki/The_Thing_(listening_device))
  * Farraday Cube
  * War Games and Ronald Regan
  * Charges brought against Phil Zimmerman inventor of PGP

## CurrentEvents
  * [Wikileaks CIA Spy tools disclosures](https://wikileaks.org/ciav7p1/)
    * Put tape over your webcam
    * Q: Does this mean that the CIA has compromised Signal and WhatsApp?
    * A: No. If you put a lock on your door, but the burglar was already in your house, your lock's not been broken, but your house may be robbed.
  * [Spammergate](https://mackeeper.com/blog/post/339-spammergate-the-fall-of-an-empire)
  	* [Slowloris](https://en.wikipedia.org/wiki/Slowloris_(computer_security))
  * Heartbleed
  * SHA1 Hash Collision
  * [Dyn IoT DDoS attack](http://www.welivesecurity.com/2016/10/24/10-things-know-october-21-iot-ddos-attacks/)
    * Explain DDoS
    * Discuss security vulnerabilities of "smart devices"
  * AshleyMadison
  * Cloudbleed

## Vulnerabilities
  * Viruses, worms and malware
  	* Stuxnet
  * Backdoors
  * Spoofing
  * Phishing
  * MiTM
  * Eavesdropping
  * Privilege escalation
  * Legal mechanisms
  * Government Agencies
    * Use PIN, not fingerprint
  * Somebody has your computer
  * ISPs, Social Networks, Web Services
  * Data breaches
  	* Password reuse
  * Bruteforce

## Techniques & Technologies
  * Obscurity - communicate over a connection that is unknown
  * Encryption
    * "End to End"
  	* PGP/GPG
  	* Hashes
  	* Modular arithmetic, 1-way function
  	* SSL/HTTPS
  * 2 Factor Authentication
    * Something you have - Yubikey, Time-based Factors, Text message to your phone, etc.
    * Something you are - biometric data
  * Password managers
  * TOR
    * Talk about FBI's classified compromise of TOR
    * [http://boingboing.net/2016/07/01/researchers-find-over-100-spyi.html](http://boingboing.net/2016/07/01/researchers-find-over-100-spyi.html)
  * Dead drops
  * HTTPS
  * VPNs
  * Farraday Cube
  * Update Your Software

## Tools
  * Browsing - [TOR Browser](https://www.torproject.org/projects/torbrowser.html.en)
  * File Sharing - [Onion Share](https://onionshare.org/)
  * 2FA - [Authy](https://www.authy.com/)
  * 2FA - [twofactorauth.org](https://twofactorauth.org/)
  * Password manager - [LastPass](https://www.lastpass.com)
  * Messaging - [WhatsApp](https://www.whatsapp.com/)
  * Messaging (better) - [Signal](https://whispersystems.org/)
  * Email - [ProtonMail](https://protonmail.com/)
  * Email - [Thunderbird](https://www.mozilla.org/en-US/thunderbird/) with [GPG](https://www.gnupg.org/)
  * Payments - [Bitcoin](https://bitcoin.org/en/)
  * [Blockchain](https://en.wikipedia.org/wiki/Blockchain_(database))
  * [HaveIBeenPwned](https://www.haveibeenpwned.com)
  * VPNs - [TunnelBear](https://www.tunnelbear.com/)
  * [Yubikey](https://www.yubico.com/start/)
  * [Tails](https://tails.boum.org/)
  * [LittleSnitch](https://www.obdev.at/products/littlesnitch/index.html)
  * [MicroSnitch](https://www.obdev.at/products/microsnitch/index.html)
  * [Firefox Private Browsing](https://support.mozilla.org/t5/Protect-your-privacy/Private-Browsing-Use-Firefox-without-saving-history/ta-p/4473)
  * [Let's Encrypt](https://letsencrypt.org/)
  * [MalwareBytes](https://www.malwarebytes.com/)
  * [Pastebin](http://pastebin.com/)
  * [HTTPS Everywhere](https://www.eff.org/HTTPS-Everywhere)

## Further Info / Deep Dive
  * [https://github.com/drduh/macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
  * [Schneier on Security](https://www.schneier.com/)

## Uncategorized
  * [Keybase](https://keybase.io/)
  * [How to Set Up SSH Keys](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2)
  * [Password tips from The Intercept](https://theintercept.com/2015/03/26/passphrases-can-memorize-attackers-cant-guess/)
  * [70 Day Guide](https://medium.com/@TeacherC/90dayactionplan-ff86b1de6acb#.6l7nqso1u)
  * [Riseup](https://riseup.net/)
  * [EFF Security Starter Pack](https://ssd.eff.org/en/playlist/want-security-starter-pack)
  * [John Gilmore](http://www.toad.com/)
  * NSA malware names: POLARSNEEZE, ELIGIBLE BOMBSHELL, FOXACID, BADDECISION, MAGIC SQUIRREL, MAGICBEAN
  * [NSA Google Tips](https://www.wired.com/2013/05/nsa-manual-on-hacking-internet/)
  * [VPN Guide](https://medium.freecodecamp.com/how-to-set-up-a-vpn-in-5-minutes-for-free-and-why-you-urgently-need-one-d5cdba361907)
  * [Forensic description of major hacks carried out by Alexsey Belan](https://medium.com/@chrismcnab/alexseys-ttps-1204d9050551#.kq10afqxr)
  * [EFF Border Search Pocket Guide](https://www.eff.org/document/eff-border-search-pocket-guide)
  * [Cypherpunk Manifesto](https://w2.eff.org/Privacy/Crypto/Crypto_misc/cypherpunk.manifesto)
