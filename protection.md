# Protection Steps
We already covered some of these, but nice to have a list

## Don't Panic
* Take a deep breath
* Go slow or slower
* Hangup and block, don't answer, don't read
* [Snopes](https://www.snopes.com/) Use the search
* Ask someone you trust

## Scam Time: Even Texas says hang up
[Customs and Border Protection scam](https://www.cbp.gov/newsroom/local-media-release/cbp-public-phone-scam-continues-target-citizens)
* Notice that they never leave a message
* They don't want you to hang up
* Want something immediately
* Payment in gift cards, crypto, wire transfer always bad
* Caller ID can be spoofed (we could fix this but choose broken)

## Generic means spam
If something is generic, it is a mass attempt to get free money

## Specific means accountable
If someone has something specific, it's probably illegal and trackable

## Safe contact
* Go to the agency web site on a safe browser and look up the contact number
* Do not go to anything a scammer could control
* Could be a good time to [look at the certificate chain](./browsers.md#certificates)
* My wife's contact routine (official law enforcement)

## Backups
Already mentioned, but do think about data you care about and choose a backup method
* Old school, make regular copies
    - This is what I do  
    Important data goes on mirrored disk. Then copied weekly or more to RAID NAS (another failure tolerant storage). Then copied to an external drive each month. That drive is put in a fire safe. Then last months drive is given to a friend to store (used to be at work).
* Encrypted
* Apple and Google offer backups
* Push the data you care about to the location you have backups running
* Check regularly  
Maybe a reminder for 1/1 each year to check that your backups are still working

## Virtual Machines
Quick example with Virtual Box
* Prevents:
    - Local device takeover
    - Some fingerprinting
    - Local storage access
    - Some privilege escalation
* No help with:
    - ISP tracking
    - Proxy man-in-the-middle
    - Logging in
* When would you use this?
    - Safer use of something like OpenClaw
    - Low trust trial
* Other types
    - Docker
    - AWS or other cloud rentals
    - Cloud services, we use Google CoLab for the Python course

## ~~Scam Time:~~ Actually, Hack with Us
Competition Launch: AI Agent Security: Multi-Step Tool Attacks
[A Kaggle Competition](./kaggle_competition.md)
* Trying to come up with new attacks to create defenses
* A bit like bug bounties
* Kaggle uses Google Colab
* Seems to echo early Claud model access a bit

## Passwords
Good password habits and other things that look like passwords
* Passwords
    - Make them good
    - Make them all different
    - Use a tool
* MFA (Multi Factor Authentication)
    - Something you have and something you know
    - Text
    - Phone app (Google has one)
    - Certificates (work places and schools often use this)
    - 1-time keys
    - Email
* Passkeys Passphrases Biometrics
    - Used with a certificate per device
* Keyrings
    - Used with browsers and OSs
    - Needs high trust of the provider
* Encryption
    - Makes storage unreadable
    - symmetric vs. public/private

## Minimize
* Stay with the official app store
* Don't install extensions or plug-ins
* Don't install apps and uninstall when not needed
* If you need to try 10 things, use a VM