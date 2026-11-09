# KartenScan für SideStore

## Updates

Füge die [KartenScan-Quelle](https://raw.githubusercontent.com/korny551/kartenscan-sidestore/main/source.json) in SideStore hinzu. Du kannst von einer älteren KartenScan-Version direkt auf die aktuelle Version wechseln.

Falls SideStore kein Update anbietet, aktiviere LocalDevVPN und öffne diese Adresse auf deinem iPhone in Safari. Lass KartenScan installiert, damit SideStore die vorhandene App aktualisieren kann.

```text
sidestore://install?url=https%3A%2F%2Fraw.githubusercontent.com%2Fkorny551%2Fkartenscan-sidestore%2Fmain%2FKartenScan.ipa
```

Der feste Installationslink lädt die [aktuelle IPA](https://raw.githubusercontent.com/korny551/kartenscan-sidestore/main/KartenScan.ipa).

## Neue Version veröffentlichen

Veröffentliche die versionierte IPA, den neuen Eintrag in `source.json` und `KartenScan.ipa` gemeinsam in einem Commit. Die beiden IPA-Pfade müssen auf dieselbe Datei im Git-Verlauf zeigen. Die bisherigen Einträge in `source.json` behalten ihre versionierten Download-Adressen.
