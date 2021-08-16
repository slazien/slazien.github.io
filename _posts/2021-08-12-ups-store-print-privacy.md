---
layout: post
title: Your local post office is (probably) a privacy nightmare
---

## An (extra)ordinary visit
So here's a little story for today. The other day I needed to print some documents at a local UPS store. After arriving, I quickly found out that the only options are:

- Use the PCs to download the docs and send the printing job to the printers there
OR
- Send an email to a store employee who would print them out for me

For the privacy and security-conscious ones among us, this should already raise huge red flags:

- What if you log in to your email inbox and forget to log off, realizing only a couple hours or days later?
- What if there is a physical keylogger capturing your login details?
- What if someone pointed the OS to make DNS reuqests to a malicious DNS server, routing you to malicious websites despite you typing in the right URL?
- How do you really ensure that the employee deleted the email you sent them containing your sensitive documents?

These are just a few things that come to mind, and all of them are *very* real possibilities. It's extremely unlikely that I'm the only one who has ever thoughts of this, and given the number of varous post office stores offering printing services in the US alone, and the number of bad actors out there, I would be very surprised if at least some of those things are not happening as I'm typing this. "Oh, come on, Windows 10 has a firewall that's on by default" you might say. At least in that UPS store it was *disabled*, which is of course a can of worms from a security standpoint.

Have you ever thought "I want to start my life all over again"? Well, your local post office with printing service might got you covered. If you're into identity theft, simply go to the `Downloads` folder on the PC and copy all the files there onto your pendrive (be a good person and **don't do that**).

## Let's see who you really are
I was absolutely terrified at just how sensitive information was left in that folder, and by the sheer number of documents. Even without opening any of the files, I saw insurance policy details, student IDs, driver's license and passport photocopies, and many more. Put some of these things together and you're giving the bad guys more than they need to steal your identity and literally turn your life upside down. Your perfect credit score that you worked so hard for over the years? Yeah, that's gone, and with it so many things that follow. Access to your bank account and your money? You'll certainly find out once your internet stops working and your landlord comes knocking at your door for that overdue rent payment.

## But I *really* need to print *now*
In general, you should always treat machines that you don't trust as compromised. This leads to the simplest "fix" for this security nightmare - just don't use printing services at post office locations, period. Get your own computer and printer.

The above is easier said than done, though. Perhaps you've just moved to a new apartment and you don't have your printer there yet. What are the next best things you can do, if you *really* can't wait? Here are some ways to minimize the risks:

### Ask your neighbours to print your stuff for you (make sure you trust them!)
Side benefit: you'll get to know them better, and [according to the Benjamin Franklin effect](https://effectiviology.com/benjamin-franklin-effect/), doing favours for someone makes a person like them more!

### Bring your own stuff
Bring your own laptop to the post office, add the printer, and send the printing job to the printer
This might not always be possible, in case you can't (or don't want to) connect to the post office's local network

If you're less extreme, bring your own keyboard if you're worried about physical keyloggers (still - check the USB ports for any suspicious dongles). People might look at you in a weird way if you really bring your own keyboard. However, if you really want to avoid physical keyloggers, that's the safest option

### Don't download
Instead of downloading the file, many browsers allow you to open the file without persisting it to disk. This is what you should generally use, since even after downloading the file and removing it from `Trash`, it can still technically be recovered.

### 2-factor authentication
Make sure that whichever accounts you log in on the post office PC have 2FA enabled, and that you change passwords for all of them after you come back home
Remeber, we're assuming that these machines have been compromised. Changing a couple of passwords is easy these days, especially if you're using a password manager. There's really no excuse.

The above are all short-term fixes, however. What can be done in the long term?

## Back to the basics
Most people don't follow the latest developments in software security, nor should they have to in order to ensure their data is safe. So, what can be done to prevent `Downloads` folders being full of highly sensitive informaiton just waiting to be exploited?

### Account logoff process changes
A simple fix is to implement software security measures such as wiping the contents of `Downloads` or, even better, the entire account, after logging off. I would imagine this is a standard feature of guest accounts on Windows 10, so I'm surprised it didn't function at the UPS store.

### 2-factor authentication enforcement
This one is obvious - if you *have to* use these PCs, at the very least have 2FA enabled for the accounts you log in on them.

### Raising awareness
The files left in the `Downloads` folder are a direct consequence of people not removing them from there. Therefore, educating people on basic security and privacy topics should continue and even increase in intensity, as the massive move to the digital space goes on around the world. Although this option is slow and costly, remember this: prevention is always better than treatment.

Stay safe out there!