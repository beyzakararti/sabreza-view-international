# Offline and local-network use

The current app needs a working network path between the controller and the PC for live screen control, terminal commands, file transfer and fresh system readings. It does not provide remote control without any communication path.

| Situation | Current behavior |
| --- | --- |
| You are outside; the home PC has no internet or other reachable network path | Live remote access stops. Mobile data on the phone alone does not restore the home's connection. |
| The phone and PC share a Wi-Fi network with no internet | Local networking can support remote control in principle, but this release has no ready-to-use offline LAN mode. The service listens on loopback by default, and the supplied firewall configuration blocks direct LAN access. |
| The PC is powered off or asleep | This app cannot serve a live desktop. No integrated Wake-on-LAN feature was found in the audited source. |
| A previously used phone loses access to the PC | The offline page can show a previously stored PC location with its measurement time and accuracy, when that data was shared and cached. It is not live tracking. |
| A local program is already running on the PC | It can continue independently if it does not need the unavailable network. You cannot monitor or control it remotely without a reachable connection. Cloud AI tools and push services still depend on their own networks. |

A future LAN mode should preserve device pairing, PIN checks and encryption, provide a trusted local address, and clearly separate cached data from live data. It must not simply disable authentication or expose the existing HTTP service on every network interface. This is a development option, not an implemented feature or a request to change your current installation.

The browser offline page requires prior successful loading and service-worker installation. Location is only the last shared measurement. Map tiles and external map links may still need internet. Offline phones cannot receive a new revocation or deletion until they reconnect.

Code audit: international source revision `907a5b255fe2838210cd40d316e65b0c334ffdfd`, `server/config.js`, `server/index.js`, `bin/supervise.js`, `public/sw.js`, and `public/offline.js`. The existing two offline-location tests passed locally on 2026-11-24. No physical-device offline LAN test was performed.
