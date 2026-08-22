# ModPack21.exe Analysis 




 Modpack21.exe: A Discord token stealer that hides its payload in 'snapshot/app.js' inside a 'Node.js' pkg and exfiltrates stolen tokens and credentials via webhooks.

Lab: Flare VM (On Windows 10 VM) & Remnux

Tools: Wireshark, Procmon, INetSim, pefile

## Findings:
Payload hidden in 'snapshot/app.js', proving pkg overlay

Token Harvesting via 'parseTokens()' and exfiltration via Axios



## IOCs:
SHA256: af367ea3e5ddecfc3c9a2b0a4729d4e55fe91cab80e0db37d9fb27f80af9c82c

## Report:
[Full Report](report/ModPack21-report.pdf)

