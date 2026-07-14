<div align="center">

# 🛡️ Escape Chat Control

### Mass surveillance is being sold to Europe as child protection. The world's top cryptographers say it doesn't even work, and it breaks security for everyone.

### This is a plain-English guide to **what's really happening**, **how adults reclaim their privacy**, and **how parents actually protect their kids**, without scanning everyone's private messages.

<br>



![Focus](https://img.shields.io/badge/focus-EU%20Chat%20Control-critical?style=flat-square)




![Stance](https://img.shields.io/badge/stance-evidence--based-blueviolet?style=flat-square)




![Level](https://img.shields.io/badge/level-beginner%20friendly-brightgreen?style=flat-square)




![Tools](https://img.shields.io/badge/tools-FOSS%20%26%20privacy%20first-blue?style=flat-square)




![License](https://img.shields.io/badge/license-CC%20BY--SA%204.0-lightgrey?style=flat-square)




![Updated](https://img.shields.io/badge/updated-July%202026-informational?style=flat-square)



<br>

**Three parts:** &nbsp; 🧠 [Part 1: What it is & why it fails](#-part-1-what-chat-control-is-and-why-the-experts-say-it-doesnt-work) &nbsp;•&nbsp; 🔐 [Part 2: Adults, reclaim privacy](#-part-2-for-adults-reclaim-your-privacy) &nbsp;•&nbsp; 👪 [Part 3: Parents, protect your kids](#-part-3-for-parents-protect-your-kids-yourself)

</div>

---

## ⚡ The short version

> **Two laws share the "Chat Control" nickname.** The mild one (**1.0**) came back on **9 July 2026**: it lets platforms *voluntarily* scan **unencrypted** messages for known abuse images, until **3 April 2028**. The dangerous one (**2.0**), mandatory scanning that reaches *inside* your encrypted apps via **client-side scanning**, is **not law yet**. Talks resume **September 2026**.
>
> Here's the part the headlines miss: **the scanning technology 2.0 needs is already running on your phone today**, just pointed at something harmless for now. So "end-to-end encryption protects me" is only true until the thing doing the scanning sits *before* the encryption, on your device. That's not paranoia; it already ships (see Part 1).
>
> **500+ of the world's leading security scientists say this approach is technically infeasible, trivially evaded by actual criminals, and a danger to democracy.** Real-world data backs them: the overwhelming majority of machine-flagged reports are *not even criminally relevant*.
>
> Protecting children is not the same as scanning everyone. This guide shows the alternative that **actually works**: strong privacy for adults, and **targeted, parent-led protection** for kids.

---

# 🧠 Part 1: What Chat Control is, and why the experts say it doesn't work

## The two things people call "Chat Control"

**🟡 Chat Control 1.0 (active now).** A temporary exception to EU privacy rules (Regulation 2021/1232). It **permits, not requires**, providers to scan **unencrypted** content (Gmail, iCloud Mail, Instagram/Messenger DMs, Discord DMs, Snapchat, Skype, Xbox) for *already-known* abuse images, using hash matching. Re-approved 9 July 2026, runs to 3 April 2028. End-to-end encrypted apps were formally carved out.

**🔴 Chat Control 2.0 (the CSA Regulation): proposed, not law.** The *permanent, mandatory* version. In its most aggressive form it pushes providers toward **client-side scanning (CSS)**: software that inspects your messages **on your own device, before they're encrypted**. That punches straight through end-to-end encryption. Five negotiation rounds have failed; the EU Council's own legal advisors warned in June 2026 it likely breaches **Article 7 of the EU Charter**. Signal has said it will **leave the EU** rather than implement it.

## ⚠️ The uncomfortable truth: client-side scanning is already being normalized

You cannot assume "it's not law yet, so nothing is scanning my device." The plumbing is already here, deployed *voluntarily* by Big Tech, for now aimed at benign goals:

- **Meta / Instagram** runs **on-device machine learning** that detects nudity in DMs. In Meta's own words, because it happens on the device, it **works inside end-to-end encrypted chats**, where Meta otherwise can't see the image. It's **on by default for under-18s**, rolled out globally.
- **Apple** ships **Communication Safety** (now "Sensitive Content Warning"): on-device detection of nudity in Messages and other apps. Apple *did* build full CSAM client-side scanning in 2021, then **abandoned it in December 2022** after security experts and rights groups warned it was too dangerous. The detection engine stayed; only the "report you to authorities" part was dropped.

Read that carefully: **the exact architecture Chat Control 2.0 would mandate (scan on the device, before encryption) is already installed and running on hundreds of millions of phones.** Right now it blurs a photo for the user. The only changes 2.0 asks for are *who it reports to* and *whether you can turn it off*. That's why "encryption exempts me" is a fragile promise, and why this fight matters even while 2.0 is still "just a proposal."

## 🔬 Why the experts say it fundamentally doesn't work

This isn't fringe opinion. It's the consensus of the people who *built* modern cryptography.

**"Bugs in Our Pockets" (2021, updated 2024):** fifteen of the most eminent names in the field (Hal Abelson, Ross Anderson, Ron Rivest, Bruce Schneier, Whitfield Diffie, Carmela Troncoso and others) concluded that client-side scanning, *by its very nature*, creates serious security and privacy risks for all of society, while the help it gives law enforcement is at best problematic. It can **fail, be evaded, and be abused**, and once the scanner sits in your OS it has the same reach as spyware: it can be repurposed to watch anything.

**500+ scientists across 34 countries (open letters 2023 to 2025)**, including Bart Preneel (KU Leuven) and Carmela Troncoso (EPFL), called the plan **technically infeasible**. Their core findings:

- 🎯 **The error rates are impossible at scale.** State-of-the-art detectors produce unacceptable false-positive and false-negative rates. Applied to hundreds of millions of users, that means **millions of innocent people wrongly flagged**, and investigators buried in noise.
- 🕳️ **It doesn't catch the criminals.** Hash matching only finds *already-known* images; it's blind to new or AI-generated material. And detectors are **trivially evaded**: a criminal makes a tiny modification and slips through. So it fails at its one job while surveilling everyone else.
- 🎭 **"AI will fix it" is false.** There is no machine-learning method that reliably detects *unknown* abuse material without a large volume of errors.
- 💣 **It's a single point of failure.** A scanner mandated onto every device is a **high-value target** for hackers and hostile states: one exploit, everyone's phone.
- 🗝️ **It's a blueprint for authoritarianism.** Once the machinery exists to scan for one thing, it can be re-pointed at anything: protest, dissent, journalism. The scientists explicitly warn of **function creep and abuse by less democratic regimes**.

## 📉 The real-world numbers already prove the point

- Swiss federal police reported that **around 80%** of machine-flagged reports were **not criminally relevant**.
- Reporting on Meta's EU data found that roughly **half** of Chat Control alerts were flagged as **not criminally relevant**, and a large share of resulting investigations targeted **minors themselves**.
- About **99%** of Meta's reports concerned **previously-known** material, meaning the system mostly recycles old findings rather than uncovering new abuse.

## ⚖️ Even the courts and the victims disagree with it

- **EU Council Legal Service (June 2026):** suspicionless scanning likely violates the Charter's right to private life.
- **European Court of Human Rights, *Podchasov v. Russia* (Feb 2024):** weakening encryption to enable mass access breaches human rights.
- **Abuse survivors** (e.g. Alexander Hanff) have publicly stated that indiscriminate scanning **did not help victims**, and that privacy is part of what lets victims come forward safely.

## 🧭 So why does it keep coming back?

Because blanket scanning is *cheap and comfortable for governments*: it outsources the work to tech companies and quietly expands surveillance infrastructure. Real child protection (targeted investigation of actual suspects, fast removal of known material, properly funded police, prevention and education) is **harder work**. Mass surveillance is the illusion of safety, not the substance of it.

> **Bottom line:** you don't have to choose between children and encryption. The experts, the courts, the European Parliament's own position, and survivors all point the same way: **targeted** protection, not **universal** scanning. Parts 2 and 3 are what that looks like in practice.

---

# 🔐 Part 2: For adults, reclaim your privacy

The goal is simple: **get your private life off the services that scan it, and onto tools that can't.** Pick based on who you actually need to reach. A secure app only helps if your contacts use it too.

> 🧰 **Want the full toolbox?** This guide keeps the essentials tight on purpose. For a much larger, categorised catalogue of privacy-respecting apps and services, see the companion project: **[Freedom Apps Privacy](https://github.com/freedomappsprivacy/Freedom-apps-privacy)**.

## 💬 Messengers

| App | Why | Notes |
|---|---|---|
| 🥇 **Signal** | The default. Strong E2EE on by default, non-profit, open-source, easy for family. | Needs a phone number. Linux/Android/iOS/desktop. https://signal.org |
| 🛡️ **Molly** | Hardened Signal fork on **F-Droid**: same network, extra security, encrypted-at-rest. | Best on de-Googled Android. https://molly.im |
| 🕵️ **SimpleX** | **No user IDs at all**: best metadata protection available. | Sync still rough. https://simplex.chat |
| 🔑 **Threema** | Sign up with nothing; random ID. EU-based, polished. | Small one-off cost. https://threema.ch |
| 🌐 **Element / Matrix** | Open, federated, **self-hostable**. Great for communities. | More setup. https://element.io |
| 📡 **Briar** | Works offline via Tor / Wi-Fi / Bluetooth. A backup channel. | Android-first. https://briarproject.org |

> ⏳ **Session** was a popular anonymous option, but its foundation announced it's **winding down in mid-2026**. Prefer **SimpleX** for the "anonymous, no phone number" role until things settle.

**Avoid for anything private:** Telegram (normal chats are **not** E2EE, only manual "Secret Chats", never groups), plus Instagram/Messenger DMs, Snapchat, Discord DMs. Fine for public/community use; not for secrets.

## ✉️ Email

- **🇨🇭 Proton Mail:** Swiss, outside the EU & 14-Eyes; full ecosystem (Mail/Calendar/Drive/VPN/Pass). https://proton.me
- **🇩🇪 Tuta:** German, fully open-source, encrypts subject + body + attachments + calendar + contacts. On **F-Droid** with Google-free push, the cleanest pick on GrapheneOS. https://tuta.com

> 💡 Email is only fully encrypted **between users of the same service** (or via PGP / a password link). Mail sent to a Gmail address still lands in a scannable inbox. For truly private exchange, use a **messenger**, not email.

## ☁️ Cloud & backups

Cloud files were **always** scannable. Encrypt them **before** upload so the provider sees only gibberish.

- **Cryptomator:** easy encrypted vaults on any cloud. https://cryptomator.org
- **rclone crypt:** CLI encryption + sync for power users; **RCX** (F-Droid) is a good mobile front-end. https://rclone.org/crypt/
- **Proton Drive / Tuta Drive:** built-in E2EE if you'd rather not DIY.

## 🧱 Everyday hygiene

- **DNS:** a private resolver (**NextDNS**, **Quad9**) over DoT/DoH cuts what your ISP sees.
- **VPN:** hides your IP and traffic from the ISP. It does **not** encrypt your chats. That's the app's job. Use both.
- **Passwords + 2FA:** a manager (**Bitwarden**, **KeePassXC**) + an authenticator (**Aegis**) instead of SMS codes.
- **Move your circle, not just yourself.** Encryption is a two-person handshake, so invite the 5 people you message most.

## 🐧 De-Googled / Linux notes

Everything above runs cleanly on **GrapheneOS** and **Linux**. On GrapheneOS: Molly-FOSS, SimpleX, Tuta (F-Droid, Google-free push), RCX. On Linux: Signal Desktop, Element, SimpleX, Cryptomator, rclone are all first-class. Self-hosters can run **Matrix (Synapse/Conduit)** or **XMPP + OMEMO** and own the whole pipe.

---

# 👪 Part 3: For parents, protect your kids yourself

**The core principle:** children, especially under-16s, should **not** have the unrestricted, adult internet. But the way to achieve that is **targeted protection at the level of the family, the device, and the network**, *not* a government scanning every citizen's private messages. **The responsibility, and the control, belongs to parents.** This is exactly the model experts and the EU Parliament favour: protect the child directly, don't surveil the whole population.

Build it in **layers**, each one privacy-respecting and age-appropriate.

## 🌐 Layer 1: The network (blocks the worst before it loads)

**NextDNS** (which many privacy-minded households already run) has a full **Parental Control** section:

- Block whole categories: **pornography, gambling, dating, piracy**.
- Block **specific high-risk apps/sites** by name (TikTok, Snapchat, specific games, etc.).
- Force **SafeSearch** (Google/Bing/DuckDuckGo) and **YouTube Restricted Mode**.
- Set **Recreation Time** schedules, e.g. block certain services during school and bedtime.

Why it fits: it works **device-wide or network-wide**, and it **filters access without reading messages**. It's a gate, not a wiretap.

## 📱 Layer 2: The device / operating system

Use the built-in controls; they're robust and free:

- **Apple Screen Time** (iPhone/iPad): app-install approval, content & age limits, downtime, and **uninstall protection** so a child can't remove other safety apps.
- **Google Family Link** (Android): approve app installs, set screen-time and bedtime, location, remote lock.
- **Microsoft Family Safety** (Windows/Xbox): screen time, content filters, activity reports.

## 🧩 Layer 3: Platform "teen accounts" (age-appropriate by default)

- **Instagram / Facebook / Messenger Teen Accounts + Family Center**: teens under 18 default to stricter 13+ settings they can't loosen without a parent; nudity protection is on by default; Family Center gives a one-stop view and lets you approve setting changes. Set up at familycenter.meta.com.
- **Discord Family Center:** *don't block Discord outright; supervise it.* Here's exactly what it does and doesn't do, so you're not caught out:

| ✅ Parents **can** see | ❌ Parents **cannot** see |
|---|---|
| Servers joined, new friends added | **Message content**: no chat logs, ever |
| Who the teen messaged/called + when | What was said in **voice channels** (unmonitored) |
| Time spent, call minutes, purchases | Anything older than **7 days** |
| Weekly email summary | Anything before the teen **opted in** (it's consent-based; teens can disconnect) |

  Pair it with these Discord settings: **restrict DMs to friends only**, turn **content filters** to strictest, and keep the conversation open. Family Center is *oversight*, not a leash, and voice chat + DMs are where predators operate, so the settings and the talking matter more than the dashboard.

## 🐕 Layer 4: Privacy-respecting alert monitoring (the "smoke alarm", not CCTV)

If you want a genuine safety net for older kids **without** reading everything they type, **Bark** is the closest thing to a privacy-preserving monitor:

- AI scans texts, email, and 30+ apps (Instagram, Snapchat, Discord, YouTube…) and **only alerts you to genuinely concerning content**: grooming, predators, explicit material, self-harm, severe bullying.
- It **doesn't stream every message to you**. Instead it flags snippets around a real concern and keeps normal teen life private. This is deliberately *awareness, not surveillance*.
- **Limits to know:** weaker on iPhone (Apple's restrictions), it **alerts rather than blocks** (pair with Layer 1 for blocking), and a determined teen can find workarounds. Subscription-based.

This model (**detect danger, don't record everything**) is exactly the principle experts want applied to society as a whole: targeted, proportionate, and respectful of the person being protected.

## 🚩 High-risk services to flag (age-appropriate guidance)

- **Discord:** stranger DMs + unmonitored **voice**. Supervise via Family Center; lock DMs to friends.
- **Snapchat:** disappearing messages + location sharing (Snap Map). High grooming/sextortion vector.
- **Instagram / TikTok DMs:** stranger contact, sextortion scams. Use Teen Accounts.
- **Random-chat / random-video apps** (Omegle-style): pair strangers with children. Block at the DNS layer.
- **Roblox / large game chats:** predators use in-game chat and Discord hand-offs. Use platform parental controls.
- **Telegram:** large unmoderated public groups; treat as adult space.

> ⚠️ **A crucial nuance for parents:** the safest adult messengers in Part 2 (Signal, SimpleX…) are **end-to-end encrypted and cannot be monitored**. That's the whole point of them. So for a *young child*, the answer is **not** "install Signal." It's **device + network controls + age-appropriate accounts + honest conversation**. As they mature, you loosen the controls and lean on trust. Encryption is a tool for autonomy, and you grant it as autonomy is earned.

## 🧠 The bridge back to Part 1

Notice what Layers 1 to 4 have in common: they protect a **specific child**, chosen by a **specific parent**, at a **proportionate** level, and none of them requires scanning **everyone else's** private messages. That's the entire argument. **Child safety and universal privacy are not enemies.** The failure of Chat Control isn't that it tries to protect kids. It's that it does so by treating 450 million Europeans as suspects, while barely touching the criminals it claims to target. There is a better way, and it starts at home.

---

## ✅ Quick-start checklists

**Adults**
- [ ] Installed **Signal / Molly / SimpleX / Threema** and invited close contacts
- [ ] Moved private mail to **Proton** or **Tuta**
- [ ] Stopped putting sensitive things in **Gmail / Instagram DM / Discord DM / Snapchat**
- [ ] Set up **Cryptomator** or **rclone crypt**
- [ ] Switched 2FA from **SMS** to an **authenticator app**

**Parents**
- [ ] **NextDNS** parental filtering + SafeSearch + YouTube Restricted Mode
- [ ] **Screen Time / Family Link** with install approval + uninstall protection
- [ ] **Teen Accounts** on Instagram/Meta; **Discord Family Center** + DMs restricted to friends
- [ ] Considered **Bark** as an alert-based safety net for older teens
- [ ] Blocked random-chat apps; had the honest conversation

---

## 📣 Want to change the law itself?

- **Fight Chat Control:** MEP contact tools and live status. https://fightchatcontrol.eu
- **Patrick Breyer** (tracks every vote). https://www.patrick-breyer.de/en/
- **EDRi** (European Digital Rights). https://edri.org
- **The scientists' open letters.** https://csa-scientist-open-letter.org
- Contact **your MEPs** before the **September 2026** trilogue on Chat Control 2.0.

---

## 🔗 Related project

For a far larger, categorised catalogue of privacy-respecting apps and services, see the companion repo: **[Freedom Apps Privacy](https://github.com/freedomappsprivacy/Freedom-apps-privacy)**.

## ⚠️ Disclaimer

Educational information about **lawful privacy and child-safety tools**, not legal advice, and not a guide to evading legitimate, targeted criminal investigation. Using end-to-end encryption is legal across the EU. Laws and app details change fast; **verify current status before relying on anything here.** Figures and dates reflect reporting available in **July 2026**.

## 📚 Key sources

- Abelson, Anderson, Rivest, Schneier, Diffie, Troncoso et al., *Bugs in Our Pockets: The Risks of Client-Side Scanning* (Journal of Cybersecurity, 2024)
- Open letters of 300 to 500+ scientists (2023 to 2025), csa-scientist-open-letter.org
- Meta & Apple on-device detection: Meta Help Center / newsroom; Apple via WIRED, MacRumors, AppleInsider
- Vote mechanics July 2026: Euronews, The Register, byteiota, Brussels Signal, Patrick Breyer
- Provider docs: Signal, Molly, SimpleX, Threema, Element, Briar, Proton, Tuta, Cryptomator, rclone, NextDNS, Discord Family Center, Bark

## 🤝 Contributing

PRs welcome: fix a fact, add a vetted tool, sharpen a beginner explanation. Keep it **accurate, sourced, and jargon-light.** Tools should be open-source or independently audited where possible, and never recommended beyond what their encryption actually delivers.

<div align="center">

<br>

*Privacy is a right under Article 7 of the EU Charter of Fundamental Rights.*
*Protecting children and protecting everyone's privacy are the same fight, done properly.*

**⭐ Star this repo, and share it with the people you message most.**

</div>
