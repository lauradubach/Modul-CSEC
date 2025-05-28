# Container-Sicherheit

## Namespaces
Namespaces isolieren die Sichtbarkeit von Systemressourcen (z. B. Prozesse, Netzwerke, Benutzer, Mountpoints) für Container.

**Ziel:** Container "denken", sie laufen allein auf dem System. Sie können z. B. nur ihre eigenen Prozesse sehen, nicht die anderer Container oder des Hosts.

## Cgroups (Control Groups)
Cgroups beschränken und kontrollieren die Nutzung von Systemressourcen wie CPU, RAM, I/O etc.

**Ziel:** Ein Container kann nicht zu viele Ressourcen verbrauchen oder das Hostsystem durch Überlastung stören.

## OCI-Images (Open Container Initiative)
OCI definiert Standards für Container-Images und Laufzeitumgebungen.

**Ziel:** Container-Images sind portabel, reproduzierbar und vertrauenswürdig – wichtig für Sicherheit und Interoperabilität.

## Network
Container nutzen eigene Netzwerk-Namespaces, oft über virtuelle Bridges.

**Ziel:** Netzwerkzugriffe zwischen Containern, dem Host oder außen werden kontrolliert, z. B. durch Firewall-Regeln, isolierte Subnetze oder Service-Meshes.

https://gitlab.com/ch-tbz-wb/Stud/csec/-/blob/doa_itcne24/2_Unterrichtsressourcen/A/README.md