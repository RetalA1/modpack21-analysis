# ModPack21.exe Analysis 




 Modpack21.exe: Discord token stealer using Node.js 'pkg' with hidden payload in 'snapshot/app.js'

Lab: Flare VM (On Windows 10 VM) & Remnux

Tools: Wireshark, Procmon, INetSim, pefile

## Findings:
Payload hidden in 'snapshot/app.js', proving pkg overlay

Token Harvesting via 'parseTokens()' and exfiltration via Axios

Malware sinkholed to '10.0.0.3' (Remnux) with 0 bytes exfiltrated

## IOCs:
SHA256: af367ea3e5ddecfc3c9a2b0a4729d4e55fe91cab80e0db37d9fb27f80af9c82c



