<br>

I'm a product and application security engineer, mostly mobile and AI. 100+ assessments across Android, iOS, web and LLM systems for banks, fintechs and enterprises, tested against OWASP and CIS. Mobile is where I'm deepest. I also do physical red teaming and social engineering.

I'd rather build a tool than wait for one. When Android 14 broke certificate injection for assessments, I wrote **TrustMeDarling**. When the control software for my Linux laptop turned out to be Windows-only, I wrote **strixctl**. When my desktop had no proper snipping tool, I wrote **snip**. Right now I'm building agentic tooling for the repetitive parts of an assessment, from triage to reporting.

<br>

## Things I've built

| | | |
|:--|:--|:--|
| [**TrustMeDarling**](https://github.com/TheKimi7/TrustMeDarling) | Puts user-installed CA certificates into the system trust store on Android 14+, so traffic interception works again. | `Magisk` `Bash` |
| [**SeQueL**](https://github.com/TheKimi7/SeQueL) | sqlite3 on Android test devices, for poking at app databases mid-assessment. | `Magisk` `Bash` |
| [**strixctl**](https://github.com/TheKimi7/strixctl) | Battery limit, fan curves and four-zone RGB for ASUS ROG laptops on Linux. GTK3, no daemon, no root at runtime. | `Python` `GTK3` |
| [**snip**](https://github.com/TheKimi7/snip) | Win+Shift+S and PowerToys-style text extraction for Cinnamon on X11. Runs entirely on the machine: no network, no telemetry, no root. | `Python` `GTK3` `Tesseract` |

<br>

## Writing

Notes from real assessments, written for whoever is setting up the same thing next.

- [Rooting an Android Phone with Magisk](https://pranavrajendran.com/blog/rooting-an-android-phone-with-magisk) <sub>Sep 2026</sub>
- [Building strixctl: Armoury Crate for Linux... (sort of)](https://pranavrajendran.com/blog/building-strixctl) <sub>Sep 2026</sub>
- [Getting Started with Mobile VAPT: iOS Setup Guide](https://pranavrajendran.com/blog/getting-started-with-ios-vapt) <sub>Sep 2025</sub>
- [What Are Split APKs and How to Work with Them](https://pranavrajendran.com/blog/what-are-split-apks) <sub>Aug 2025</sub>
- [Getting Started with Mobile VAPT: Android Setup Guide](https://pranavrajendran.com/blog/getting-started-with-android-vapt) <sub>Jul 2025</sub>

<br>

## Toolbox

| | |
|:--|:--|
| **Mobile** | `Frida` `Objection` `Magisk` `LSPosed` `MobSF` `Drozer` `JADX` `APKTool` `ADB` |
| **AI and LLM** | `Prompt injection` `Agent tool abuse` `n8n` `OWASP Top 10 for LLMs` |
| **Web and API** | `Burp Suite` `Postman` `REST` `GraphQL` `JWT` `OAuth 2.0` |
| **Infra and cloud** | `Nmap` `Nessus` `Metasploit` `Wireshark` `AWS` `CIS Benchmarks` |
| **Red teaming** | `Physical red teaming` `Social engineering` |
| **Building** | `Python` `Bash` `JavaScript` `Java` `Kotlin` `Ghidra` `Docker` |
| **Operating systems** | `Kali` `AthenaOS` `BlackArch` `Android` `iOS` `macOS` `Windows` |

Certified: **CEH v13**, EC-Council, 2026.

<br>
