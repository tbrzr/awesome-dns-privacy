# Awesome DNS Privacy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools, resolvers, blocklists and references for private, encrypted and filtered DNS.

DNS queries reveal every site a device contacts. This list collects software and services for encrypting DNS, blocking ads and trackers at the resolver, and checking that it works.

## Contents

- [Resolvers and servers (self-hosted)](#resolvers-and-servers-self-hosted)
- [Public encrypted resolvers](#public-encrypted-resolvers)
- [Blocklists](#blocklists)
- [Testing and diagnostics](#testing-and-diagnostics)
- [Tools](#tools)
- [Specifications](#specifications)
- [Related privacy tools](#related-privacy-tools)
- [Contributing](#contributing)
- [Disclosure](#disclosure)

## Resolvers and servers (self-hosted)

- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - Network-wide ad and tracker blocking DNS server with DoH, DoT and DoQ support.
- [Blocky](https://github.com/0xERR0R/blocky) - Fast DNS proxy and ad blocker written in Go, configured with a single YAML file.
- [CoreDNS](https://github.com/coredns/coredns) - Plugin-based DNS server, the default in Kubernetes.
- [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) - Flexible local DNS proxy supporting DNSCrypt, DoH and Anonymized DNS.
- [dnsdist](https://github.com/PowerDNS/pdns) - DNS load balancer and filtering front end from PowerDNS.
- [Knot Resolver](https://github.com/CZ-NIC/knot-resolver) - Caching, validating recursive resolver from CZ.NIC.
- [Pi-hole](https://github.com/pi-hole/pi-hole) - Network-wide ad blocking via a local DNS sinkhole, built for small devices.
- [Technitium DNS Server](https://github.com/TechnitiumSoftware/DnsServer) - Authoritative and recursive DNS server with a web UI and DoH, DoT and DoQ.
- [Unbound](https://github.com/NLnetLabs/unbound) - Validating, recursive, caching resolver; a common upstream for AdGuard Home and Pi-hole.

## Public encrypted resolvers

- [Cloudflare 1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - Public resolver with DoH and DoT.
- [Mullvad DNS](https://mullvad.net/en/help/dns-over-https-and-dns-over-tls) - Public DoH and DoT resolvers with optional ad, tracker and malware blocking.
- [NextDNS](https://nextdns.io/) - Hosted, configurable DNS filtering with per-profile settings.
- [Quad9](https://quad9.net/) - Non-profit resolver that blocks known malicious domains.

## Blocklists

- [1Hosts](https://github.com/badmojr/1Hosts) - Blocklists in several strictness levels.
- [HaGeZi DNS Blocklists](https://github.com/hagezi/dns-blocklists) - Multi-level blocklists covering ads, trackers, malware and more.
- [OISD](https://oisd.nl/) - Blocklist aimed at blocking ads and trackers without breaking sites.
- [StevenBlack/hosts](https://github.com/StevenBlack/hosts) - Consolidated hosts file merged from several reputable sources.

## Testing and diagnostics

- [BrowserLeaks DNS](https://browserleaks.com/dns) - Shows which DNS servers your browser is actually using.
- [dnscheck.tools](https://www.dnscheck.tools/) - Shows your resolver, DNSSEC and encrypted DNS status.
- [dnsleaktest.com](https://www.dnsleaktest.com/) - Detects DNS leaks when using a VPN or encrypted resolver.
- [DNSViz](https://dnsviz.net/) - Visualizes DNSSEC authentication chains and finds configuration errors.

## Tools

- [DNS Block Test](https://github.com/tbrzr/dns-block-test) - Checks which of 54 ad, tracker and malware domains your resolver blocks. Maintained by the list author.
- [dog](https://github.com/ogham/dog) - Command-line DNS client with DoH and DoT support.

## Specifications

- [RFC 7858: DNS over TLS](https://www.rfc-editor.org/rfc/rfc7858) - Specification for DNS over TLS (DoT).
- [RFC 8484: DNS over HTTPS](https://www.rfc-editor.org/rfc/rfc8484) - Specification for DNS over HTTPS (DoH).
- [RFC 9250: DNS over QUIC](https://www.rfc-editor.org/rfc/rfc9250) - Specification for DNS over QUIC (DoQ).

## Related privacy tools

- [Burn](https://github.com/tbrzr/burn) - Self-hosted burn-after-read notes with client-side AES-GCM encryption; the key stays in the URL fragment. Maintained by the list author.
- [Snip](https://github.com/tbrzr/snip) - Self-hosted link shortener with an optional private mode that encrypts the destination in the browser. Maintained by the list author.

## Contributing

Pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Disclosure

This list is maintained by the author of Burn, Snip and DNS Block Test, which are included above and marked as such. Every entry follows the same inclusion rules as everyone else's.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related rights to this work.
