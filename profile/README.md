# CertKit

**Certificate management for people with better things to do.**

## The Problem

We're going to have to start renewing [certificates every 47 days](https://www.certkit.io/47-day-certs). By 2030, we'll probably be rotating certs daily.

Your options today:
- **CertBot** - Works great for one server, until you stop paying attention and it breaks.
- **Cert Manager** - Perfect if your entire world is Kubernetes and YAML is your love language.
- **DigiCert/Sectigo** - Starting at $call-us-so-we-can-upsell-you per year.
- **That bash script Terry wrote** - Terry left in 2019. Nobody knows how it works.

## What We Built

CertKit handles the entire certificate lifecycle so you don't have to:

✓ **Automatic discovery** - Finds all your issued certificates, even that Jenkins box from 2018  
✓ **Multi-environment deployment** - Linux, Windows, Kubernetes, cloud providers, that server under Bob's desk  
✓ **DNS validation without the nightmare** - We only touch TXT records, not your entire DNS  
✓ **Alerts where you actually look** - Slack, Teams, email, wherever  
✓ **A dashboard that doesn't suck** - See what's expiring without SSH-ing into 12 servers  

## Who This Is For

SysAdmins and DevOps teams who are tired of:
- Certificate expiration fire drills
- Maintaining homegrown renewal infrastructure  
- Explaining to management why the cert expired (again)
- Paying enterprise prices for basic automation

## Current Status

🚀 **In Beta** - Free during beta, with preferential pricing for early adopters.

We're onboarding teams who manage 10+ certificates and want to stop thinking about them.

## Get Started

[Join the beta](https://www.certkit.io/) and let us handle your certificate hell.

## The Team

Built by the [TrackJS](https://trackjs.com) team. We've been running production infrastructure since 2013. We got tired of certificate management, so we fixed it.

## Questions?

- 📧 [hello@certkit.io](mailto:hello@certkit.io)
- 🌐 [certkit.io](https://www.certkit.io)
- 📖 [Blog](https://www.certkit.io/blog)

---

*Because your time is better spent on literally anything else than certificate management.*