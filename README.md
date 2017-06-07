# Bhutan NOG 2017 Security Workshop 2017.06.06-09

## Daily Schedule

 Session  | Time
:----------|:------------- 
Session 1 |09:00 - 10:30
Tea       |10:30 - 11:00
Session 2 |11:00 - 12:30
Lunch     |12:30 - 13:30
Session 3 |13:30 - 15:00
Tea       |15:00 - 15:30
Session 4 |15:30 - 17:00

## Instructors

 Instructor | Name | Affiliation | Country
:-----------|:--------------------|:-------------|:--------------
**alisha** | Alisha Gurung | [Bhutan Telcom](https://bt.bt) | Bhutan
**maz**    | Yoshinobu (Maz) Matzusaki | [Internet Initiative Japan](http://www.iij.ad.jp) | Japan
**randy**  | Randy Bush  |  [Internet Initiative Japan](http://www.iij.ad.jp) | Japan

## Tools

If you run a datacenter or a significant office LAN, you should look
seriously at running a few [Canaries](https://canary.tools/); and a
[Guide for Deploying
Canaries](http://blog.thinkst.com/2017/04/a-guide-to-birding-aka-tips-for.html).

[pfSense](https://www.pfsense.org/), a free Firewall, VPN, ... solution.

## Movies!

Some time during the week, please watch Haroon Meer's excellent keynote,
[Learning the wrong lessons from
Offense](//[http://t2.fi/2017/02/05/haroon-meer-keynote-2016/), from the
t2’16 Infosec Conference in Helsinki.

## Official Song

[Spyin’ NSA](http://www.anagram.com/jcrap/Volume**9/spyin.pdf) - by Keith Alexander, Daniel J. Bernstein, Timo Kasper, Tanja Lange, and Peter Schwabe

## Agenda

Day/Session | Topic | Instructor | Material
:----------------|:---------------------|:-------------------|:-------------------------
|             |                         |                      |
|             |                         |                      |
**Day 1**  |**Topic**             |**Instructor**           |**Materials**
|             |                         |                      |
Session 0     | Intro                   | randy                | [1-0-1 Intro](1-0-1.intro.pdf)
|              | - admin                 |                      |
|              | - agenda                |                      |
|              | - materials and resources |                    |
|              | - facilities and wireless |                    |
Session 1     | Assets & Threat Models  | randy              | [1-1-1 Assets, Threats, Pragmatics](1-1-1.AssetsThreats.pdf)
|             | - what assets are we protecting? |             |
|             | - from what kinds of attackers? |              |
|             | .. kiddies              |                      |
|             | .. financial gain       |                      |
|             | .. nation state (you're dead) |                |
|             | Threat Pragmatics       |                      |
|             | . to network infrastructure (routing, wiretap, ...) | |
|             | . to service infrastructure (dns, mail, ...)    | |
|             | . to users              |                      |
|             | Social Engineering      |                      |
Session 2     | Cryptography            | randy                | [1-2-1 Crypto Overview](1-2-1.Crypto-Overview.pdf)
|             | - symmetric encryption  |                      |
|             | - asymmetric encryption |                      |
|             | - digital signatures    |                      |
|             | - hash functions        |                      |
|             | - certificates & trust anchors |               |
Session 3-4   | Cryptography Applications / PGP | maz          |
|             | - checksum              | maz                  | [1-3-1 checksum](1-3-1.checksum.pdf)
|             |                         |                      | [1-3-1 hello-unix.dat](hello-unix.dat)
|             |                         |                      | [1-3-1 hello-win.dat](hello-win.dat)
|             | - PGP Lab               | maz & alisha         | [1-3-2 PGP](1-3-2.pgp.pdf)
|             |                         |                      | [1-3-2 email-header](1-3-2.email-headers.pdf)
|             |                         |                      | [1-3-2 mailvelope](1-3-2.mailvelope.pdf)
|             |                         |                      |
**Day 2**  |**Topic**             |**Instructor**           |**Materials**
|             |                         |                      |
Session 1     | Cryptography Applications |                    |
|             | - ssh                   | randy                | [2-1-1 SSH](2-1-1.ssh.pdf)
|             | - ssh lab           | alisha and maz            | [2-1-2 SSH Lab](2-1-2.ssh-lab.pdf)
Session 2     | Wireshark               | maz                  | [2-2-1 wireshark](2-2-1.packetdump.pdf)
|             | - wireshark lab         | maz & alsiha         | [2-2-1 wireshark lab](2-2-1.packetdump-data.zip)
Session 3     | Cryptography Applications | maz                |
|             | - VPNs, IPsec, TLS       |                     | [2-3-1 VPN IPsec TLS](2-3-1.vpn-tls.pdf)
Session 4     | OpenVPN & pfSense       | randy                | [2-4-1 OpenVPN lab](2-4-1.openvpn.pdf)
|             |                         |                      |
|             |                         |                      |
**Day 3**  |**Topic**             |**Instructor**           |**Materials**
|             |                         |                      |
Session 1     | Network Infrastructure  |                |
|             | - overview | cristel | [3-1-1 rtrs-switches](3-1-1.rtrs-switches.pdf)
|             | - data plane            | cristel               |  [3-1-2 Filtering at border](3-1-2.Filtering-at-border.pdf)
|             | - Logging and Monitoring | maz              | [3-1-3 Logging Monitoring](3-1-3.logging-monitoring.pdf)
Session 2     | anomaly and firewalls | maz                |
|             | - anomaly      |                     | [3-2-1 anomaly](3-2-1.anomaly.pdf)
|             | - fierwalls      |                     | [3-2-2 firewalls](3-2-2.firewalls.pdf)
Session 3     | DNS & DNS Security      | randy                |
|             | - DNS                   |                      | [3-4-1 DNS](DNS.pptx)
|             | - DNS Security          |                      | [3-4-2 DNS Security](DNS**Security.pptx)
|             | - DNS Rate Limiting     |                      | [3-4-3 DNS Rate Limiting](3-4-3.dns-rate-limit.pdf)
Session 4     | nmap                    | maz                  |
|             |                         |                      |
|             |                         |                      |
**Day 4**  |**Topic**             |**Instructor**           |**Materials**
|             |                         |                      |
Session 1     | DNS & DNS Security      | alisha               |
|             | - DNS                   |                      | [4-1-1 DNS](DNS.pptx)
|             | - DNS Security          |                      | [4-1-2 DNS Security](DNS**Security.pptx)
|             | - DNS Rate Limiting     | randy                | [4-1-3 DNS Rate Limiting](4-1-3.dns-rate-limit.pdf)
Session 2     |IDS                      |                   |
|             | - IDS pragmatics - snort | cristel                   | [4-2-1.snort](4-2-1.snort.pdf)
|             | - IDS pragmatics - snort-lab | cristel & pappu                    | [4-2-2.snort-lab](4-2-2.snort-lab.pdf) | [4-2-3.snort**lab**answer](4-2-3.snort**lab**answer.rtf)
Session 3     | Protecting Hosts from Net | maz                |
|             | - hosts                 |                      | [4-3-1 Hosts](4-3-1.host.pdf)
Session 4     | Virus, Mail and Browsing |                     |
|             | - Anti-virus            | maz                  | [4-4-1 Anti-virus](4-4-1.anti-virus.pdf)
|             | - Safe Mail Practices   | randy                | [4-4-2 Safer Mail](4-4-2.safer-mail.pdf)
|             | - Safe Browsing Practices | randy              | [4-4-3 Safer browsing](4-4-3.safer-browsing.pdf)
|             | - File & Disk Encryption | randy               | [4-4-4 File & Disk Encryption](4-4-4.file-encrypt.pdf)
|             |                         |                      |
|             |                         |                      |
**Day 5**  |**Topic**             |**Instructor**           |**Materials**
|             |                         |                      |
Session 1     | Inter-Host Protocols    |                      |
|             | - sftp, ...             | randy                | [4-5-1 sftp & scp](4-5-1.scp+sftp.pdf)
|             | - Covert Channels, TOR, Steganography | cristel   | [5-1-2 Covert Channels](5-1-2.Covert-Channels.pdf)
Session 2     | Inter-Network Cooperation | maz                |
|             | - Communities and Cooperation |                | [5-2-1 Security Communities](5-2-1.cooperation.pdf)
Session 3 & 4 | Dessert                    | randy                |
|             | Protecting Routing Protocols | randy           | [Protecting Routing Protocols](160219.routing-protocols.pdf)
|             | Telco vs Internet & Complexity | randy         | [Complexity](6-6-6.complexity.pdf)
|             | Critical Infrastructure and SW Eng | randy     | [Critical Infrastructure and Software Engineering](6-6-6.dagstuhl-CI.pdf)
|             |                         |                      |
|             |                         |                      |
**Day 6**  |**Topic**             |**Instructor**           |**Materials**
|             |                         |                      |
Session 1     | Virtual Box & pfSense  | randy                | [6-1-1 Install VirtualBox & pfSense](6-1-1.vbox-pfsense.pdf)
Session 2     | Configure OpenVPN       | randy                | [6-1-2 Configure OpenVPN Server](6-1-2.openvpn-server.pdf)
|             |                         |                      |
