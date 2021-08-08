---
title: Unifi Homelab
author: Dominik Lenhardt
date: 2021-08-08 18:45:00 +0100
categories: [Network, LAN, Tech]
tags: [network,lan,tech]
math: true
mermaid: true
toc: true
---

Auf der nachfolgenden Seite bekommt ihr ein Überblick über das grundlegende Setup meines Netzwerks zu hause und welche hürden damit verbunden waren/sind.

Da es allgemein genug gute Tutorials für das grundlegende Setup gibt, gehe ich hier auf die speziellen Dinge wie IPv6 (WAN und Firewall) und das erreichen des Modems über die Weboberfläche.

Da ich mich beruflich in dem Thema IT-Security und IT-Monitoring herumtreibe habe ich auf dem Cloudkey selbst noch ein Paar weitere Anwendungen laufen. Auf diese gehe ich in folgendem Artikel [KOMMT NOCH](https://onkeldom.github.io) näher ein.

Hier jetzt erstmal der Aufbau meines Heimnetzwerks

## Equipment

| Device                            | Type            | Link           |
|:----------------------------------|:----------------|---------------:|
| DryTek Vigor 166                  | VDSL Modem      | [Billiger.de](https://www.billiger.de/search?searchstring=drytek+vigor+166) |
| Ubiquiti Unifi Security Gateway   | Router/Firewall | [Billiger.de](https://www.billiger.de/search?searchstring=Ubiquiti+USG&filter=f_brand_2906942,f_category_2132,f_price_99x120) |
| Ubiquiti Unifi Switch 8P 60W      | Switch PoE      | [Billiger.de](https://www.billiger.de/search?searchstring=Ubiquiti+USW-8-60W) |
| Ubiquiti Unifi Switch Flex-Mini   | Switch PoE      | [Billiger.de](https://www.billiger.de/search?searchstring=Ubiquiti+unifi+switch+Flex-mini&filter=f_brand_2906942,f_category_2133) |
| Ubiquiti Unifi Access Point AC-LR | Access Point    | [Billiger.de](https://www.billiger.de/search?searchstring=Ubiquiti+UAP-AC-LR&filter=f_brand_2906942,f_category_111828,f_price_89x120) |
| Ubiquiti Unifi Cloudkey Gen1      | Controller      | N/A           |
| Gigaset Go-Box 100                | Telefonanlage   | [Billiger.de](https://www.billiger.de/search?searchstring=Gigaset+go-box+100) |

Von den Access Point habe ich zwei im Einsatz, da unsere Wohnung in einer U-Form ist und durch das Stahlbeton treppenhaus einfach überhaupt kein Signal kommt.

![Unify Homelab](/assets/img/upload/unify_homelab01.png)
