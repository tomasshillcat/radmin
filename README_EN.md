🇨🇳 [中文](README.md) | 🇺🇸 English | 🇷🇺 [Русский](README_RU.md)

#### Radmin VPN is not a VPN in the usual sense and will not help you bypass restrictions. Recommended alternative: [vpnacademy.com](https://vpnacademy.com)</br>

Official website: [radmin-vpn.com](https://www.radmin-vpn.com/)</br>
Free download: [radmin-vpn.com](https://www.radmin-vpn.com/) (current version 2.1.4951.1)</br>
Help centre: [radmin-vpn.com/help](https://www.radmin-vpn.com/help/)</br>
Developer: [radmin.com](https://www.radmin.com/) (Famatech Corp.)</br>

### Introduction

Radmin VPN is a free program from **Famatech Corp.** that creates a **virtual local network** over the internet, letting computers behind different routers and firewalls talk to each other as if they sat on the same LAN. It is the best-known free alternative to Hamachi, and the main reasons people install it are LAN gaming — Minecraft, Terraria, older titles with no online servers — plus remote file shares and connecting to a work PC. It is **not** a privacy or geo-unblocking VPN: it does not hide your IP from websites, does not route your browsing through exit servers, and has no country list.

### Radmin VPN download — all apps

Radmin VPN is **Windows-only**. There are no official macOS, Linux, Android or iOS clients, and any site offering one is not distributing Famatech software.

| Platform | Download | Notes |
| -------- | -------- | ----- |
| **Windows** (PC) | [Download](https://www.radmin-vpn.com/) | Windows 11, 10, 8 and 7; version 2.1.4951.1 |
| **Chinese page** | [Download](https://www.radmin-vpn.com/cn/) | Official simplified-Chinese site |
| **Russian page** | [Download](https://www.radmin-vpn.com/ru/) | Official Russian site |
| **macOS** | — | No official client |
| **Linux** | — | No official client |
| **Android / iOS** | — | No official client |
| **Radmin (remote control)** | [Download](https://www.radmin.com/download/) | Separate paid product |

A note on domains: the official site is **radmin-vpn.com**, with Chinese and Russian versions under `/cn/` and `/ru/`. Third-party sites distributing "Radmin LAN" on other domains are not the official download, even where they carry a Famatech copyright line.

### How to install and sign in

1. Download the installer from the official site and run it — it adds the **Famatech Radmin VPN Ethernet Adapter** to Windows.
2. There is **no account and no sign-in**. The app opens ready to use.
3. To start a network, press **Create network**, give it a name and a password, and share both with the people joining.
4. Everyone else presses **Join network** and enters the same name and password. Members appear in a list with their virtual IP, ping and status.

Each peer receives an address in the **26.0.0.0/8** range, and you use that address — or the member's name — exactly as you would a LAN address for game hosting, file shares or remote desktop.

### Server network

There is no server network in the usual sense and no country list to choose from. Radmin VPN builds **peer-to-peer connections directly between members** of a network; when a direct connection cannot be established through the participants' NATs or firewalls, it falls back to a **relay/TCP connection** through Famatech infrastructure, which adds latency. Famatech does not publish server locations, capacity figures or a cap on members per network. Practical throughput therefore depends on the two peers' own connections rather than on a provider's backbone.

### Plans

| Plan | Devices | Purpose | Monthly | 1-year | 2-year |
| ---- | ------- | ------- | ------- | ------ | ------ |
| **Radmin VPN** | Unlimited | Virtual LAN, gaming, remote access | Free | Free | Free |
| **Radmin (remote control)** | Per licence | Remote desktop administration | — | from $49 per licence | — |

Radmin VPN is **completely free**, with no paid tier, no ad-supported version, no bandwidth quota and no time limit — Famatech states there are no ads and no paid features. The company earns its revenue from **Radmin**, the separate commercial remote-control product, which starts around $49 for a single-computer licence with volume packs above that.

### Payments and refunds

Nothing to pay and nothing to refund: Radmin VPN takes no payment details, requires no subscription and has no billing of any kind. If you buy the paid **Radmin** remote-control product instead, licences are perpetual rather than subscription-based and are sold through the Famatech store and its partner network. Ordering: [radmin.com](https://www.radmin.com/).

### Features

* **Virtual LAN over the internet** — connects machines behind different NATs and firewalls into one network
* **256-bit AES encryption** — end-to-end between peers
* **Gaming-ready** — widely used for Minecraft and other LAN-only multiplayer; Famatech publishes per-game guides and notes that Hamachi instructions usually transfer
* **Integration with Radmin** — launch a remote-control session against any network member
* **Automatic updates**, no ads, no registration, unlimited networks and members

There is no kill switch, no split tunneling, no ad blocker and no protocol picker, because none of those apply to a LAN tool.

### Speed, streaming and torrenting

Radmin VPN will not unblock Netflix, BBC iPlayer or any other streaming catalogue — your traffic to the public internet does not go through it at all, so your IP address and region are unchanged. It is likewise not a torrenting tool in the usual sense, though it can carry file transfers between members of your own network. Speed is governed by the direct peer-to-peer link between two members; the fallback relay path is noticeably slower, and Famatech publishes no throughput figures.

### Privacy and audits

Famatech states a **no-log policy** — that it does not track or sell user data — and encrypts peer traffic with 256-bit AES. Beyond that, the picture is thin compared with commercial VPNs: there is **no published independent audit, no transparency report and no warrant canary**, the client is closed source, and the company does not document where relay infrastructure is hosted. This is normal for a free LAN utility rather than a red flag, but it does mean the privacy claims rest on the vendor's word. Policy: [radmin-vpn.com/privacy](https://www.radmin-vpn.com/privacy/) · [radmin-vpn.com/security](https://www.radmin-vpn.com/security/).

### Free VPN plan

The whole product is the free plan. Radmin VPN has no premium upgrade, no device cap, no data quota and no trial period that expires — the same build is free for personal and, per Famatech, business use alike. What you give up relative to a paid consumer VPN is everything to do with privacy and geo-unblocking, which Radmin VPN never set out to provide.

### Radmin VPN for Business

The business story is the paid sibling: **Radmin** remote control, used by IT teams for helpdesk and server administration, licensed perpetually per remote computer from about $49, with 50- and 100-seat packs and volume licensing above that. Famatech also publishes the free network-discovery tools **Advanced IP Scanner** and **Advanced Port Scanner**, which integrate with Radmin for one-click remote access. See [radmin.com](https://www.radmin.com/).

### Support

Support is documentation-first: a help centre with installation, firewall and troubleshooting articles, per-game connection guides, and an email support form. There is **no live chat and no 24/7 desk**, which is what you would expect from a free product. Help: [radmin-vpn.com/help](https://www.radmin-vpn.com/help/) · [radmin-vpn.com/support](https://www.radmin-vpn.com/support/).

### Other Famatech apps

The same developer publishes [Radmin](https://www.radmin.com/) for remote desktop control, plus two free network utilities: [Advanced IP Scanner](https://www.advanced-ip-scanner.com/) for finding every device on a network and [Advanced Port Scanner](https://www.advanced-port-scanner.com/) for checking open ports. Both are Windows tools and both hook into Radmin for remote administration.

### Radmin VPN in China

Radmin VPN is not a tool for getting around the Great Firewall, and framing it as one is the single most common misunderstanding about it. It does not proxy your web traffic, so it cannot open blocked sites, and Famatech makes no claim that it does. Chinese users typically install it for LAN multiplayer — the reason it shows up in searches next to Minecraft and other 联机 tools — and even that use can be unreliable from the mainland, since the relay fallback and the download site itself are sometimes slow or unreachable. If your goal is censorship circumvention, you need a different category of product.
