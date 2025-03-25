# ElderlyAR: Blockchain-basiertes Archiv für Zeitzeugenberichte

## Whitepaper

# 1. Einleitung

## 1.1 Hintergrund und Zielsetzung

ElderlyAR repräsentiert eine innovative Lösung zur digitalen Bewahrung von Zeitzeugenberichten und persönlichen Geschichten älterer Generationen. Unser Ansatz kombiniert modernste Blockchain-Technologie mit benutzerfreundlichen Schnittstellen, um ein kostengünstiges, aber technisch robustes System zur Langzeitarchivierung zu schaffen. Als EU-gefördertes Freizeitprojekt mit begrenztem Budget zielt ElderlyAR darauf ab, einen nachhaltigen Beitrag zur Bewahrung lokaler Geschichte zu leisten und gleichzeitig ein Modell für zukünftige Archivierungsinitiativen zu etablieren.

Die strategische Integration dezentraler Speichertechnologien und kryptografischer Verifizierungsmethoden ermöglicht:

- Persistente Langzeitverfügbarkeit der gesammelten Zeitzeugenberichte ohne zentrale Infrastruktur
- Kryptografisch gesicherten Schutz vor Datenverlust und Manipulation
- Kostenneutrale Archivierung nach initialer Investition ohne wiederkehrende Betriebsausgaben
- Barrierefreien, plattformunabhängigen Zugang für Forschung, Bildung und interessierte Öffentlichkeit

## 1.2 Herausforderungen traditioneller Archivierungsmethoden

Konventionelle Archivierungsansätze weisen mehrere inhärente Limitationen auf, die ihre langfristige Effektivität einschränken:

- **Zentralisierte Infrastruktur**: Single Points of Failure durch zentralisierte Datenspeicherung erhöhen das Risiko von Totalverlusten bei institutionellem Versagen oder technischen Ausfällen
- **Lineare Kostenstruktur**: Kontinuierlich anfallende Kosten für Webhosting, Cloud-Speicher und Systemwartung gefährden die langfristige Verfügbarkeit bei Finanzierungsengpässen
- **Technologische Obsoleszenz**: Proprietäre Formate und Systeme werden mit fortschreitender technologischer Entwicklung zunehmend unzugänglich
- **Eingeschränkte Zugänglichkeit**: Institutionelle oder technische Barrieren limitieren den demokratischen Zugang zu archivierten Inhalten
- **Manipulationsanfälligkeit**: Fehlende kryptografische Integritätssicherung ermöglicht nachträgliche, nicht nachvollziehbare Veränderungen

ElderlyAR adressiert diese Herausforderungen durch ein dezentrales, blockchain-basiertes Architekturmodell, das inhärente Unveränderlichkeit, dauerhafte Verfügbarkeit und vollständige Kostenneutralität nach der initialen Einrichtungsphase gewährleistet.

# 2. Technologische Architektur

## 2.1 Blockchain & Speicherstrategie

Die technische Infrastruktur von ElderlyAR basiert auf einem mehrschichtigen Ansatz mit [ArDrive.io](http://ardrive.io/) als primärer Schnittstelle zu permanenten Speichertechnologien:

### 2.1.1 ArDrive Distributed Storage Layer

ArDrive bildet das Fundament unserer Speicherarchitektur und fungiert als benutzerfreundliche Schnittstelle zur Arweave-Blockchain:

- **Permanente Datenpersistenz**: Unveränderliche Speicherung auf der Arweave-Blockchain mit mathematisch garantierter Langzeitverfügbarkeit
- **Intuitive Benutzeroberfläche**: Dateisystem-ähnliche Interaktionsmodelle für vereinfachten Zugang zu komplexer Blockchain-Technologie
- **Einmaliges Finanzierungsmodell**: Perpetual Storage Endowment-Mechanismus eliminiert wiederkehrende Speicherkosten
- **Hierarchische Datenorganisation**: Flexible Ordnerstrukturen mit Metadaten-Anreicherung für optimale Auffindbarkeit
- **Granulare Zugriffssteuerung**: Differenzierte Public/Private Drive-Konfigurationen für maßgeschneiderte Datenschutzmodelle
- **Kryptografische Integritätssicherung**: Automatische Hash-Verifizierung und Blockchain-Verankerung für manipulationssichere Archivierung

### 2.1.2 Arweave Permanent Web Protocol

Arweave fungiert als zugrundeliegende Blockchain-Infrastruktur mit spezialisierten Eigenschaften für Langzeitdatenspeicherung:

- **SPoRA Konsensus-Algorithmus**: Succinct Proofs of Random Access bieten energieeffizienten, sicheren Konsensus für Datenspeicherung
- **Blockweave-Architektur**: Innovative Datenstruktur verbindet Blöcke nicht nur linear, sondern auch mit zufälligen historischen Blöcken für erhöhte Sicherheit
- **Endowment-basiertes Wirtschaftsmodell**: Einmalige Speichergebühren finanzieren permanente Datenhaltung über 200+ Jahre durch mathematisch modellierte Anreizmechanismen
- **Content-adressierbare Speicherung**: Datenzugriff über kryptografische Hashes statt physische Lokationen für erhöhte Resilienz
- **HTTP-Gateway-Infrastruktur**: Standardisierte Zugriffsprotokolle ermöglichen nahtlose Integration in bestehende Web-Ökosysteme

### 2.1.3 Polygon Metadata Indexing Layer

Polygon dient als kosteneffiziente Metadaten-Indexierungsschicht mit folgenden technischen Eigenschaften:

- **EVM-Kompatibilität**: Vollständige Unterstützung der Ethereum Virtual Machine für robuste Smart Contract-Funktionalität
- **PoS-Konsensus**: Energieeffizienter Proof-of-Stake-Mechanismus mit minimalen Transaktionskosten
- **Hochdurchsatz-Architektur**: Verarbeitung von 7.000+ Transaktionen pro Sekunde für responsive Metadatenabfragen
- **Sidechain-Topologie**: Sicherheitsverankerung an Ethereum-Mainnet bei gleichzeitiger Kosteneffizienz
- **Interoperabilität**: Standardisierte Schnittstellen für nahtlose Integration mit anderen Blockchain-Ökosystemen
- **Mikroökonomisches Gebührenmodell**: Transaktionskosten im Sub-Cent-Bereich ermöglichen granulare Metadatenaktualisierungen

## 2.2 Systemkomponenten und technische Spezifikationen

| Komponente | Technologie | Technische Spezifikation | Funktion |
| --- | --- | --- | --- |
| Primärspeicherung | ArDrive Community Drive | Arweave-Integration, hierarchische Dateisystemabstraktion, permanente URI-Generierung | Unveränderliche Langzeitspeicherung von Medieninhalten und Metadaten |
| Blockchain-Infrastruktur | Arweave Blockweave | SPoRA-Konsensus, 700+ Miner-Netzwerk, 5KB Blockheader, 384-bit SHA-384 Hashing | Kryptografisch gesicherte Datenpersistenzschicht mit ökonomischen Anreizen |
| Metadaten-Index | Polygon Smart Contracts | Solidity v0.8.9, ERC-721 kompatibel, Gas-optimierte Datenstrukturen | Effiziente Indizierung, Verknüpfung und Abfrage von Archivbeständen |
| Zugangsschicht | Progressive Web App | React.js, Service Workers, IndexedDB-Caching, Responsive Design | Plattformunabhängige Benutzeroberfläche mit Offline-Funktionalität |
| Deployment-Infrastruktur | GitHub Pages | Statisches Hosting, CI/CD-Pipeline, Custom Domain-Integration | Kostenfreie Bereitstellung der Benutzeroberfläche |

## 2.3 Technischer Workflow und Datenfluss

Der Datenfluss im ElderlyAR-System folgt einem präzise definierten Prozessmodell:

1. **Akquisitionsphase**:
    - Strukturierte Erfassung von Zeitzeugenberichten in standardisierten Textformaten
    - Digitalisierung analoger Fotografien mit optimierten Scan-Parametern
    - Systematische Metadaten-Extraktion und -Anreicherung (temporale, geografische und thematische Attribute)
    - Validierung auf semantische Konsistenz und technische Kompatibilität
2. **Präprozessierung und Optimierung**:
    - **Bildoptimierung**: Rauschreduktion, Schärfeoptimierung, Konvertierung in WebP mit adaptiven Kompressionsparametern
    - **Textoptimierung**: Semantische Strukturierung durch Markdown-Auszeichnung, UTF-8-Normalisierung
    - **Metadaten-Standardisierung**: Konformität mit Dublin Core, temporale Normalisierung nach ISO 8601, geografische Kodierung nach GeoJSON
3. **ArDrive-Persistenzprozess**:
    - **Drive-Konfiguration**: Erstellung eines dedizierten Community Drives, Definition hierarchischer Ordnerstrukturen
    - **Upload-Sequenz**: Stapelverarbeitung, Transaktionsbündelung, automatische Generierung permanenter Arweave-URIs
4. **Polygon-Indexierungsprozess**:
    - **Smart Contract-Interaktion**: Registrierung strukturierter Metadaten, permanente Verknüpfungen zu ArDrive-Speicherorten
    - Gas-optimierte Batch-Transaktionen für Kosteneffizienz

# 3. Datenstruktur & Speicherung

## 3.1 ArDrive-Speicherkonzept und Datenorganisation

Die Daten werden in einer sorgfältig konzipierten Struktur auf ArDrive organisiert, die sowohl menschliche Navigierbarkeit als auch maschinelle Verarbeitbarkeit optimiert:

### 3.1.1 Drive-Architektur und Hierarchiemodell

- **Community Drive-Topologie**: Öffentliches ArDrive mit transparenten Zugriffsrechten für maximale Zugänglichkeit
- **Hierarchische Organisationsstruktur**:

```
  ElderlyAR/
  ├── Geschichten/
  │   ├── Geschichte_001/
  │   │   ├── metadata.json       # Strukturierte Metadaten im JSON-LD-Format
  │   │   ├── inhalt.md           # Primärtext im Markdown-Format
  │   │   ├── manifest.json       # Inhaltsverzeichnis mit Integritätshashes
  │   │   └── bilder/
  │   │       ├── bild_001.webp   # Optimiertes Hauptbild
  │   │       ├── bild_001_thumb.webp  # Thumbnail-Variante
  │   │       └── bild_002.webp   # Weiteres Bild
  │   ├── Geschichte_002/
  │   │   └── ...
  │   └── ...
  ├── Thematische_Sammlungen/     # Kuratierte thematische Gruppierungen
  │   ├── Nachkriegszeit/
  │   │   ├── index.json          # Sammlungsbeschreibung und Inhaltsverzeichnis
  │   │   └── referenzen.json     # Verweise auf zugehörige Geschichten
  │   └── ...
  ├── Metadaten/                  # Globale Metadatenstrukturen
  │   ├── master_index.json       # Vollständiger Inhaltsindex
  │   └── tags_taxonomy.json      # Hierarchische Schlagwortklassifikation
  └── Dokumentation/              # Projektdokumentation
      ├── benutzerhandbuch.pdf    # Anleitung für Endnutzer
      └── technische_dokumentation.md # Entwicklerdokumentation

```

### 3.1.2 Dateiorganisation und Formatspezifikationen

- **Bildmaterial**:
    - **Primärformat**: WebP mit adaptiver Qualitätseinstellung (75-85%)
    - **Auflösungsparameter**: Standardisierte Breite von 1200px bei variablem Seitenverhältnis
    - **Varianten**: Automatisch generierte Thumbnails (240px) für Vorschauansichten
- **Textuelle Inhalte**:
    - **Primärformat**: Markdown mit standardisierter Auszeichnungssyntax
    - **Strukturelle Semantik**: Hierarchische Gliederung mit semantischen Überschriftenebenen
    - **Zeichenkodierung**: UTF-8 mit BOM für universelle Kompatibilität
- **Metadaten-Strukturen**:
    - **Primärformat**: JSON-LD für semantische Interoperabilität
    - **Schema-Konformität**: Dublin Core und [Schema.org](http://schema.org/) Vokabulare
    - **Temporale Kodierung**: ISO 8601 für Datums- und Zeitangaben
    - **Geografische Referenzierung**: GeoJSON für Ortsangaben mit Koordinaten

## 3.2 Metadaten-Architektur und Polygon-Integration

Die Metadaten-Schicht auf Polygon implementiert ein hochoptimiertes System zur strukturierten Indizierung und effizienten Abfrage aller archivierten Inhalte:

### 3.2.1 Metadaten-Schema und semantische Struktur

```json
{
  "@context": "<https://schema.org/>",
  "@type": "ArchiveItem",
  "id": "geschichte_001",
  "identifier": {
    "@type": "PropertyValue",
    "propertyID": "ArDriveTransactionID",
    "value": "pJlNuJFH9JTVw_wJxK3KnZ_zQvKQWF9QN4ef_5bSRHo"
  },
  "name": "Erinnerungen an die Nachkriegszeit",
  "description": "Persönliche Erlebnisse aus dem Berlin der Nachkriegsjahre mit Fokus auf Alltagsleben und Wiederaufbau.",
  "author": {
    "@type": "Person",
    "name": "Anonym (auf Wunsch)",
    "birthDate": "1935-04-12"
  },
  "contentLocation": {
    "@type": "Place",
    "name": "Berlin, Deutschland",
    "geo": {
      "@type": "GeoCoordinates",
      "latitude": 52.5200,
      "longitude": 13.4050
    }
  },
  "temporalCoverage": "1945-05/1950-12",
  "dateCreated": "1947-05-12",
  "dateArchived": "2025-03-01T14:32:17Z",
  "keywords": ["Nachkriegszeit", "Berlin", "Alltag", "Wiederaufbau", "Trümmerfrauen"],
  "ardriveMetadata": {
    "driveId": "8b7e460b-e7a3-4c4c-82c6-61d5195b4407",
    "folderPath": "/ElderlyAR/Geschichten/Geschichte_001",
    "fileCount": 8,
    "totalSize": 1458732
  },
  "associatedMedia": [
    {
      "@type": "ImageObject",
      "contentUrl": "<https://arweave.net/pJlNuJFH9JTVw_wJxK3KnZ_zQvKQWF9QN4ef_5bSRHo/bilder/bild_001.webp>",
      "thumbnailUrl": "<https://arweave.net/pJlNuJFH9JTVw_wJxK3KnZ_zQvKQWF9QN4ef_5bSRHo/bilder/bild_001_thumb.webp>",
      "description": "Trümmerlandschaft in Berlin-Mitte, Sommer 1946",
      "width": 1200,
      "height": 800,
      "encodingFormat": "image/webp"
    }
  ]
}

```

### 3.2.2 Smart Contract-Implementierung

Die Polygon-basierte Metadatenindizierung wird durch einen optimierten Smart Contract realisiert:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.9;

/**
 * @title ElderlyARRegistry
 * @dev Optimierter Smart Contract zur Verwaltung von Zeitzeugenberichten
 */
contract ElderlyARRegistry {
    // Strukturierte Metadaten mit optimierter Speichernutzung
    struct StoryMetadata {
        string title;           // Titel des Berichts
        string location;        // Ort des Berichts
        uint256 date;           // Datum als UNIX-Timestamp
        string ardriveId;       // ArDrive Transaktion ID
        string folderPath;      // Pfad innerhalb des ArDrive
        string[] tags;          // Thematische Tags
        uint256 timestamp;      // Zeitpunkt der Registrierung
    }

    // Hauptspeicherstrukturen
    mapping(bytes32 => StoryMetadata) private _stories;
    bytes32[] private _storyIds;

    // Optimierte Indizierungsstrukturen
    mapping(string => bytes32[]) private _tagIndex;
    mapping(string => bytes32[]) private _locationIndex;
    mapping(uint256 => bytes32[]) private _yearIndex;

    // Zugriffssteuerung
    mapping(address => bool) public authorizedAddresses;
    address public owner;

    // Events für externe Indexierung
    event StoryRegistered(bytes32 indexed id, string title, string ardriveId, string folderPath);
    event TagAdded(bytes32 indexed storyId, string tag);

    // Konstruktor und Modifikatoren
    constructor() {
        owner = msg.sender;
        authorizedAddresses[msg.sender] = true;
    }

    modifier onlyAuthorized() {
        require(authorizedAddresses[msg.sender] || msg.sender == owner, "Nicht autorisiert");
        _;
    }

    // Kernfunktionen
    /**
     * @dev Registriert einen neuen Zeitzeugenbericht
     * @param title Titel des Berichts
     * @param location Ort des Berichts
     * @param date Datum des Berichts (UNIX-Timestamp)
     * @param ardriveId ArDrive Transaktion ID
     * @param folderPath Pfad innerhalb des ArDrive
     * @param tags Thematische Tags
     * @return id Eindeutige ID des registrierten Berichts
     */
    function registerStory(
        string calldata title,
        string calldata location,
        uint256 date,
        string calldata ardriveId,
        string calldata folderPath,
        string[] calldata tags
    ) external onlyAuthorized returns (bytes32) {
        // Generiere eindeutige ID basierend auf Inhaltshash
        bytes32 id = keccak256(abi.encodePacked(title, location, date, ardriveId));
        // Speichere Hauptmetadaten
        _stories[id] = StoryMetadata({
            title: title,
            location: location,
            date: date,
            ardriveId: ardriveId,
            folderPath: folderPath,
            tags: tags,
            timestamp: block.timestamp
        });
        // Aktualisiere Indizes
        _storyIds.push(id);
        _locationIndex[location].push(id);
        _yearIndex[date / 31536000 + 1970].push(id); // Jahr aus UNIX-Timestamp
        for (uint i = 0; i < tags.length; i++) {
            _tagIndex[tags[i]].push(id);
            emit TagAdded(id, tags[i]);
        }
        emit StoryRegistered(id, title, ardriveId, folderPath);
        return id;
    }

    // Abfragefunktionen
    /**
     * @dev Ruft Metadaten eines Berichts ab
     * @param id ID des Berichts
     * @return Strukturierte Metadaten des Berichts
     */
    function getStory(bytes32 id) external view returns (
        string memory title,
        string memory location,
        uint256 date,
        string memory ardriveId,
        string memory folderPath,
        string[] memory tags,
        uint256 timestamp
    ) {
        StoryMetadata storage story = _stories[id];
        require(bytes(story.title).length > 0, "Bericht nicht gefunden");
        return (
            story.title,
            story.location,
            story.date,
            story.ardriveId,
            story.folderPath,
            story.tags,
            story.timestamp
        );
    }

    /**
     * @dev Ruft Berichte nach Tag ab
     * @param tag Zu suchender Tag
     * @param offset Startposition für Paginierung
     * @param limit Maximale Anzahl zurückzugebender Einträge
     * @return ids Array von Bericht-IDs mit dem angegebenen Tag
     * @return total Gesamtanzahl verfügbarer Einträge
     */
    function getStoriesByTag(string calldata tag, uint256 offset, uint256 limit)
        external
        view
        returns (bytes32[] memory ids, uint256 total)
    {
        bytes32[] storage allIds = _tagIndex[tag];
        total = allIds.length;
        // Paginierung implementieren
        uint256 resultCount = limit;
        if (offset >= total) {
            return (new bytes32[](0), total);
        }
        if (offset + limit > total) {
            resultCount = total - offset;
        }
        // Ergebnisarray erstellen
        ids = new bytes32[](resultCount);
        for (uint256 i = 0; i < resultCount; i++) {
            ids[i] = allIds[offset + i];
        }
        return (ids, total);
    }
}

```

## 3.3 Sicherheit & Datenintegrität

ElderlyAR implementiert ein mehrschichtiges Sicherheitskonzept zur Gewährleistung von Datenintegrität und Authentizität:

- **ArDrive/Arweave-Sicherheitsmechanismen**:
    - Kryptografische Verkettung aller Transaktionen
    - Verteilter Konsensus über unabhängige Miner
    - Permanente Verfügbarkeitsgarantie durch ökonomische Anreize
- **Polygon-Sicherheitsmaßnahmen**:
    - Smart Contract-Sicherheit mit Zugriffskontrollen
    - Proof-of-Stake-Validierung mit hohem Sicherheitsniveau
    - Ethereum-Checkpointing für zusätzliche Sicherheitsverankerung
- **Integritätsverifizierung**:
    - Lückenlose Nachverfolgbarkeit von Originaldaten bis zur Präsentation
    - Kryptografische Beweise für Datenunveränderlichkeit
    - Automatisierte Integritätsprüfungen bei jedem Datenzugriff

# 4. Kostenmodell & Finanzierung

## 4.1 Detaillierte Kostenaufstellung

ElderlyAR ist speziell für ein sehr begrenztes Budget von 500€ konzipiert. Die folgende Aufstellung zeigt die präzisen Kosten für die Implementierung und den Betrieb:

### 4.1.1 ArDrive/Arweave Permanentspeicherkosten

| Datentyp | Optimierte Größe | Quantität | Aggregierte Datenmenge | Kostenprojektion (USD) |
| --- | --- | --- | --- | --- |
| Hochauflösende Fotografien | 500-700 KB | 200 | 100-140 MB | 0,90-1,26 |
| Textuelle Dokumentation | 40-60 KB | 200 | 8-12 MB | 0,072-0,108 |
| Strukturierte Metadaten | 0,5-1 KB | 200 | 0,1-0,2 MB | 0,0009-0,0018 |
| Thumbnail-Varianten | 30-50 KB | 200 | 6-10 MB | 0,054-0,090 |
| **Gesamtsumme** |  |  | **114,1-162,2 MB** | **1,03-1,46** |

Bei einem Preis von 9,00 USD pro GB (Stand: Januar 2025) würden die Gesamtkosten für die Speicherung von 114,1-162,2 MB Daten etwa 1,03-1,46 USD betragen.

**Technische Optimierungsstrategien:**

- **Bildoptimierungspipeline**:
    - Perceptual optimization mit adaptiver Qualitätseinstellung
    - WebP-Kodierung mit optimalen Kompressionsparametern
    - Automatische Größenanpassung auf standardisierte Dimensionen
- **Textuelle Komprimierungsverfahren**:
    - Minifizierung von Markup-Elementen
    - UTF-8-Normalisierung für konsistente Zeichenkodierung
    - Optimierte Markdown-Syntax für minimalen Overhead

### 4.1.2 Polygon Transaktionskosten

| Transaktionstyp | Gas-Verbrauch | Kosten pro Transaktion (USD)* | Transaktionsvolumen | Aggregierte Kosten (USD) |
| --- | --- | --- | --- | --- |
| Smart Contract-Deployment | 1,200,000 - 1,500,000 | 0.010 - 0.015 | 1 | 0.010 - 0.015 |
| Einzelregistrierung | 80,000 - 120,000 | 0.0008 - 0.0012 | 50 | 0.040 - 0.060 |
| Batch-Registrierung (10 Einträge) | 200,000 - 250,000 | 0.002 - 0.0025 | 15 | 0.030 - 0.038 |
| **Gesamtsumme** |  |  |  | **0.080 - 0.113** |
- Basierend auf durchschnittlichem Gas-Preis von 30 Gwei und MATIC-Preis von $0.33 (März 2025)

### 4.1.3 Infrastruktur und Betriebskosten

| Service | Funktionalität | Kostenstruktur (USD) |
| --- | --- | --- |
| GitHub Pages | Statisches Web-Hosting | 0.00 (kostenlos) |
| ArDrive Web App | Benutzeroberfläche für ArDrive | 0.00 (kostenlos) |
| Public Arweave Gateway | HTTP-Zugriff auf Arweave-Inhalte | 0.00 (kostenlos) |
| **Gesamtsumme** |  | **0.00** |

### 4.1.4 Aggregierte Kostenprojektion

| Kostenkategorie | Kostenspanne (USD) | Kostenspanne (EUR)* |
| --- | --- | --- |
| ArDrive/Arweave Permanentspeicherung | 1,03 - 1,46 | 0,94 - 1,33 |
| Polygon Transaktionen | 0,080 - 0,113 | 0,07 - 0,10 |
| Infrastruktur und Betrieb | 0,00 | 0,00 |
| **Gesamtsumme** | **1,11 - 1,57** | **1,01 - 1,43** |
- Umrechnungskurs: 1 USD = 0,91 EUR

## 4.2 Langfristige Kostenneutralität

Die ElderlyAR-Architektur gewährleistet vollständige Kostenneutralität nach der initialen Investitionsphase:

- **Endowment-Mechanismus**: Einmalige Zahlung finanziert permanente Speicherung über 200+ Jahre
- **Statische Komponenten**: GitHub Pages bietet unbegrenzte kostenfreie Hosting-Dauer für öffentliche Repositories
- **Dezentrale Zugriffspunkte**: Multiple öffentliche Gateways für Arweave-Inhalte
- **Wartungsfreie Smart Contracts**: Unveränderliche Blockchain-Deployment ohne Aktualisierungsbedarf

### 4.2.1 Vergleichende Kostenanalyse

Im Vergleich zu traditionellen Archivierungslösungen bietet ElderlyAR signifikante langfristige Kostenvorteile:

| Zeitraum | ElderlyAR (EUR) | Cloud-basiertes Archiv (EUR)* | On-Premise-Lösung (EUR)** | Einsparung vs. Cloud | Einsparung vs. On-Premise |
| --- | --- | --- | --- | --- | --- |
| 1 Jahr | 1,01 - 1,43 | 60 - 90 | 300 - 450 | 98% - 99% | 99,5% - 99,7% |
| 5 Jahre | 1,01 - 1,43 | 300 - 450 | 600 - 900 | 99,5% - 99,7% | 99,8% - 99,9% |
| 10 Jahre | 1,01 - 1,43 | 600 - 900 | 1.200 - 1.800 | 99,8% - 99,9% | 99,9% - 99,95% |
| 25 Jahre | 1,01 - 1,43 | 1.500 - 2.250 | 3.000 - 4.500 | 99,9% - 99,95% | 99,97% - 99,98% |

*Cloud-basiertes Archiv: Jährliche Kosten für Speicher, Bandbreite, Backups und minimale Wartung für eine vergleichbare Datenmenge (ca. 150 MB)

**On-Premise-Lösung: Initiale Hardware plus jährliche Kosten für Strom, Wartung, Backups und periodische Hardware-Erneuerung für eine kleine Archivlösung

### 4.2.2 Skalierungspotenzial innerhalb des Budgetrahmens

Der substantielle Budgetpuffer von über 90% des verfügbaren Budgets ermöglicht signifikante Skalierungspotenziale:

| Szenario | Datenvolumen | Geschätzte Kosten (EUR) | Verbleibender Budgetpuffer (EUR) | Pufferanteil |
| --- | --- | --- | --- | --- |
| Aktueller Plan | ~150 MB | 1,01 - 1,43 | 498,57 - 498,99 | 99,7% - 99,8% |
| Skalierung 5x | ~750 MB | 5,05 - 7,15 | 492,85 - 494,95 | 98,6% - 99,0% |
| Skalierung 10x | ~1,5 GB | 10,10 - 14,30 | 485,70 - 489,90 | 97,1% - 98,0% |
| Skalierung 50x | ~7,5 GB | 50,50 - 71,50 | 428,50 - 449,50 | 85,7% - 89,9% |
| Maximale Ausnutzung | ~165 GB | ~500,00 | ~0,00 | 0% |

# 5. Technische Implementierung

## 5.1 ArDrive-Integration

Die Integration mit ArDrive bildet das technische Fundament für die permanente Datenspeicherung:

### 5.1.1 ArDrive SDK-Implementierung

```jsx
/**
 * Hochleistungs-Upload-Manager für ArDrive mit optimierter Fehlerbehandlung
 * und intelligenter Transaktionsplanung
 */
class ArDriveUploadManager {
  /**
   * Initialisiert den Upload-Manager mit den erforderlichen Konfigurationen
   * @param {Object} config - Konfigurationsparameter
   * @param {Object} config.wallet - Arweave JWK-Wallet für Transaktionssignierung
   * @param {string} config.communityDriveId - ID des Ziel-Community-Drives
   * @param {number} config.maxRetries - Maximale Anzahl von Wiederholungsversuchen
   * @param {number} config.concurrentUploads - Anzahl gleichzeitiger Uploads
   */
  constructor(config) {
    this.wallet = config.wallet;
    this.communityDriveId = config.communityDriveId;
    this.maxRetries = config.maxRetries || 3;
    this.concurrentUploads = config.concurrentUploads || 5;
    // ArDrive-Client initialisieren
    this.arDrive = new ArDrive(this.wallet);
    this.uploadPlanner = new ArFSUploadPlanner();
    // Statistik-Tracking
    this.stats = {
      totalUploaded: 0,
      totalFiles: 0,
      successfulUploads: 0,
      failedUploads: 0,
      retries: 0
    };
  }

  /**
   * Erstellt eine optimierte Ordnerstruktur auf ArDrive
   * @param {Object} structure - Hierarchische Ordnerstruktur-Definition
   * @returns {Promise<Object>} Mapping von logischen Pfaden zu ArDrive-Folder-IDs
   */
  async createFolderStructure(structure) {
    const folderMap = new Map();
    folderMap.set('/', this.communityDriveId);
    // Rekursive Funktion zur Ordnererstellung
    const createFolders = async (parentPath, parentId, children) => {
      for (const [name, subChildren] of Object.entries(children)) {
        const path = `${parentPath}${name}/`;
        // Ordner erstellen
        const createFolderTx = await this.arDrive.createFolder({
          parentFolderId: parentId,
          folderName: name,
          driveId: this.communityDriveId
        });
        folderMap.set(path, createFolderTx.id);
        // Rekursiv Unterordner erstellen
        if (subChildren && typeof subChildren === 'object') {
          await createFolders(path, createFolderTx.id, subChildren);
        }
      }
    };
    await createFolders('/', this.communityDriveId, structure);
    return Object.fromEntries(folderMap);
  }

  /**
   * Lädt eine Sammlung von Dateien auf ArDrive hoch
   * @param {Array<Object>} files - Array von Dateiobjekten mit Metadaten
   * @param {Object} options - Upload-Optionen
   * @returns {Promise<Array<Object>>} Upload-Ergebnisse mit Transaktions-IDs
   */
  async uploadFiles(files, options = {}) {
    this.stats.totalFiles += files.length;
    // Dateien in Batches aufteilen für optimale Verarbeitung
    const batches = this._createOptimalBatches(files, options.batchSize || 10);
    const results = [];
    for (const batch of batches) {
      // Upload-Planer für den Batch konfigurieren
      for (const file of batch) {
        await this.uploadPlanner.addFileToUpload({
          sourceFilePath: file.path,
          destFolderId: file.folderId,
          driveId: this.communityDriveId,
          customMetaTags: this._createMetadataTags(file.metadata)
        });
      }
      // Batch mit Wiederholungslogik hochladen
      try {
        const batchResults = await this._uploadWithRetry(
          () => this.arDrive.uploadAllEntities(
            this.uploadPlanner.getPlannedUploadEntities()
          ),
          this.maxRetries
        );
        // Ergebnisse verarbeiten und zurückgeben
        // ...
      } catch (error) {
        console.error(`Batch upload failed: ${error.message}`);
        // Fehlerbehandlung
      }
    }
    return results;
  }
  // Weitere Hilfsmethoden...
}

```

## 5.2 Polygon Smart Contract-Interaktion

Die Interaktion mit dem Polygon-basierten Metadaten-Smart Contract erfolgt über eine optimierte Client-Bibliothek:

```jsx
/**
 * Client-Bibliothek für die Interaktion mit dem ElderlyAR-Registry Smart Contract
 */
class ElderlyARRegistryClient {
  /**
   * Initialisiert den Registry-Client
   * @param {Object} config - Konfigurationsparameter
   * @param {string} config.contractAddress - Adresse des Registry-Contracts
   * @param {string} config.rpcUrl - URL des Polygon RPC-Endpunkts
   * @param {string} config.privateKey - Optional: Private Key für schreibende Operationen
   */
  constructor(config) {
    this.contractAddress = config.contractAddress;
    this.rpcUrl = config.rpcUrl;
    // Provider und Contract-Instanz initialisieren
    this.provider = new ethers.providers.JsonRpcProvider(this.rpcUrl);
    // Wallet für Transaktionen initialisieren, falls Private Key vorhanden
    if (config.privateKey) {
      this.wallet = new ethers.Wallet(config.privateKey, this.provider);
      this.contract = new ethers.Contract(
        this.contractAddress,
        ElderlyARRegistry.abi,
        this.wallet
      );
    } else {
      // Nur-Lese-Zugriff ohne Wallet
      this.contract = new ethers.Contract(
        this.contractAddress,
        ElderlyARRegistry.abi,
        this.provider
      );
    }
    // Cache für häufige Abfragen
    this.cache = {
      storyCount: null,
      storyCountTimestamp: 0,
      stories: new Map(),
      storiesByTag: new Map(),
      storiesByLocation: new Map()
    };
  }

  /**
   * Registriert einen neuen Zeitzeugenbericht im Smart Contract
   * @param {Object} storyData - Daten des zu registrierenden Berichts
   * @returns {Promise<Object>} Transaktionsergebnis mit ID
   */
  async registerStory(storyData) {
    if (!this.wallet) {
      throw new Error('Schreibzugriff erfordert einen Private Key');
    }
    // Gas-Preis optimieren
    const gasPrice = await this._getOptimizedGasPrice();
    // Transaktion vorbereiten und senden
    const tx = await this.contract.registerStory(
      storyData.title,
      storyData.location,
      storyData.date instanceof Date ? Math.floor(storyData.date.getTime() / 1000) : storyData.date,
      storyData.ardriveId,
      storyData.folderPath,
      storyData.tags || [],
      {
        gasPrice,
        gasLimit: 300000 // Konservatives Gas-Limit
      }
    );
    // Auf Bestätigung warten und Ergebnis zurückgeben
    // ...
  }

  /**
   * Ruft einen Zeitzeugenbericht anhand seiner ID ab
   * @param {string} id - ID des abzurufenden Berichts
   * @param {Object} options - Abfrageoptionen
   * @returns {Promise<Object>} Berichtsdaten
   */
  async getStory(id, options = {}) {
    // Cache-Prüfung, falls aktiviert
    if (options.useCache !== false && this.cache.stories.has(id)) {
      const cachedStory = this.cache.stories.get(id);
      const now = Date.now();
      // Cache-Eintrag verwenden, wenn er nicht älter als 5 Minuten ist
      if (now - cachedStory.timestamp < 5 * 60 * 1000) {
        return cachedStory.data;
      }
    }
    // Daten vom Smart Contract abrufen
    const [title, location, date, ardriveId, folderPath, tags, timestamp] =
      await this.contract.getStory(id);
    // Daten in strukturiertes Objekt umwandeln und zurückgeben
    // ...
  }
  // Weitere Methoden für verschiedene Abfragen...
}

```

## 5.3 Frontend-Implementierung

Die Benutzeroberfläche von ElderlyAR ist als Progressive Web App implementiert, die einen intuitiven Zugang zu den archivierten Inhalten ermöglicht:

```jsx
/**
 * Hauptkomponente der ElderlyAR-Anwendung
 * Implementiert das Routing und die globale Zustandsverwaltung
 */
function App() {
  // Globaler Anwendungszustand
  const [state, dispatch] = useReducer(appReducer, initialState);
  const { loading, error, theme, language } = state;

  // Initialisierung der Anwendung
  useEffect(() => {
    async function initializeApp() {
      try {
        dispatch({ type: 'SET_LOADING', payload: true });

        // Registry-Client initialisieren
        const registryClient = new ElderlyARRegistryClient({
          contractAddress: process.env.REACT_APP_CONTRACT_ADDRESS,
          rpcUrl: process.env.REACT_APP_RPC_URL
        });

        // Grundlegende Daten laden
        const storyCount = await registryClient.getTotalStoryCount();

        dispatch({
          type: 'INITIALIZE_SUCCESS',
          payload: { registryClient, storyCount }
        });
      } catch (error) {
        console.error('Initialization error:', error);
        dispatch({
          type: 'INITIALIZE_ERROR',
          payload: error.message
        });
      }
    }

    initializeApp();
  }, []);

  // Render-Funktion mit Routing und Komponenten
  // ...
}

/**
 * Detailansicht eines einzelnen Zeitzeugenberichts
 */
function StoryDetailPage() {
  // URL-Parameter für die Story-ID
  const { id } = useParams();
  const { state } = useContext(AppContext);
  const { registryClient } = state;
  // Lokaler Zustand
  const [story, setStory] = useState(null);
  const [content, setContent] = useState(null);
  const [images, setImages] = useState([]);
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState(null);

  // Bericht und zugehörige Inhalte laden
  useEffect(() => {
    async function loadStoryData() {
      try {
        setLoading(true);
        // Metadaten vom Smart Contract abrufen
        const storyData = await registryClient.getStory(id);
        setStory(storyData);

        // Inhalte von ArDrive abrufen
        const contentResponse = await fetch(`https://arweave.net/${storyData.ardriveId}/${storyData.folderPath}/inhalt.md`);
        if (!contentResponse.ok) {
          throw new Error(`Failed to load content: ${contentResponse.statusText}`);
        }
        const contentText = await contentResponse.text();
        setContent(contentText);

        // Manifest abrufen, um verfügbare Bilder zu finden
        const manifestResponse = await fetch(`https://arweave.net/${storyData.ardriveId}/${storyData.folderPath}/manifest.json`);
        if (manifestResponse.ok) {
          const manifest = await manifestResponse.json();
          // Bilder aus dem Manifest extrahieren
          const imageEntries = manifest.files.filter(file =>
            file.path.startsWith('bilder/') &&
            (file.path.endsWith('.webp') || file.path.endsWith('.jpg') || file.path.endsWith('.png'))
          );
          // Bildinformationen strukturieren
          const imageData = imageEntries.map(entry => ({
            path: entry.path,
            fullPath: `https://arweave.net/${storyData.ardriveId}/${storyData.folderPath}/${entry.path}`,
            contentType: entry.contentType,
            size: entry.size
          }));
          setImages(imageData);
        }
      } catch (error) {
        console.error('Error loading story:', error);
        setError(error.message);
      } finally {
        setLoading(false);
      }
    }
    if (id && registryClient) {
      loadStoryData();
    }
  }, [id, registryClient]);

  // Render-Logik für verschiedene Zustände
  if (loading) {
    return <LoadingIndicator />;
  }
  if (error) {
    return <ErrorMessage message={error} />;
  }
  if (!story) {
    return <NotFoundMessage />;
  }

  // Markdown in HTML konvertieren
  const contentHtml = content ? marked.parse(content) : '';
  return (
    <div className="story-detail-container">
      <h1 className="story-title">{story.title}</h1>

      <div className="story-metadata">
        <div className="metadata-item">
          <IconLocation />
          <span>{story.location}</span>
        </div>
        <div className="metadata-item">
          <IconCalendar />
          <span>{new Date(story.date).toLocaleDateString()}</span>
        </div>
      </div>

      {/* Tags anzeigen */}
      <div className="story-tags">
        {story.tags.map(tag => (
          <span key={tag} className="tag-badge">{tag}</span>
        ))}
      </div>

      {/* Hauptbild anzeigen, falls vorhanden */}
      {images.length > 0 && (
        <div className="story-main-image">
          <img
            src={images[0].fullPath}
            alt={story.title}
            loading="lazy"
          />
        </div>
      )}

      {/* Inhalt anzeigen */}
      <div
        className="story-content"
        dangerouslySetInnerHTML={{ __html: contentHtml }}
      />

      {/* Bildergalerie anzeigen, falls mehrere Bilder vorhanden */}
      {images.length > 1 && (
        <div className="story-gallery">
          <h2>Bildergalerie</h2>
          <div className="image-grid">
            {images.map((image, index) => (
              <div key={image.path} className="gallery-item">
                <img
                  src={image.fullPath}
                  alt={`Bild ${index + 1}`}
                  loading="lazy"
                />
              </div>
            ))}
          </div>
        </div>
      )}

      {/* Permanente Links */}
      <div className="permanent-links">
        <h3>Permanente Speicherung</h3>
        <div className="links-container">
          <a
            href={`https://arweave.net/${story.ardriveId}`}
            target="_blank"
            rel="noopener noreferrer"
          >
            Auf Arweave ansehen
          </a>
        </div>
      </div>
    </div>
  );
}

/**
 * Suchseite für Zeitzeugenberichte
 */
function SearchPage() {
  // URL-Parameter für vorausgefüllte Suche
  const location = useLocation();
  const navigate = useNavigate();
  const queryParams = new URLSearchParams(location.search);

  // Globaler Zustand
  const { state } = useContext(AppContext);
  const { registryClient } = state;

  // Lokaler Zustand
  const [searchParams, setSearchParams] = useState({
    type: queryParams.get('type') || 'tag',
    query: queryParams.get('query') || queryParams.get('tag') || '',
    location: queryParams.get('location') || '',
    yearFrom: queryParams.get('yearFrom') || '',
    yearTo: queryParams.get('yearTo') || ''
  });
  const [results, setResults] = useState([]);
  const [pagination, setPagination] = useState({
    total: 0,
    offset: 0,
    limit: 10,
    hasMore: false
  });
  const [loading, setLoading] = useState(false);
  const [error, setError] = useState(null);

  // Suche durchführen
  const performSearch = async (offset = 0) => {
    try {
      setLoading(true);
      setError(null);
      let searchResults;
      // Je nach Suchtyp unterschiedliche API-Aufrufe
      switch (searchParams.type) {
        case 'tag':
          if (!searchParams.query.trim()) {
            throw new Error('Bitte geben Sie einen Suchbegriff ein');
          }
          searchResults = await registryClient.getStoriesByTag(
            searchParams.query.trim(),
            { offset, limit: pagination.limit }
          );
          break;
        case 'location':
          if (!searchParams.location.trim()) {
            throw new Error('Bitte geben Sie einen Ort ein');
          }
          searchResults = await registryClient.getStoriesByLocation(
            searchParams.location.trim(),
            { offset, limit: pagination.limit }
          );
          break;
        // Weitere Suchtypen...
      }

      // Ergebnisse setzen
      if (offset === 0) {
        setResults(searchResults.stories);
      } else {
        // Bei "Mehr laden" anhängen
        setResults(prev => [...prev, ...searchResults.stories]);
      }
      setPagination(searchResults.pagination);
    } catch (error) {
      console.error('Search error:', error);
      setError(error.message);
    } finally {
      setLoading(false);
    }
  };

  // Suchformular absenden
  const handleSubmit = (e) => {
    e.preventDefault();
    performSearch();
  };

  return (
    <div className="search-page-container">
      <h1>Zeitzeugenberichte durchsuchen</h1>

      {/* Suchformular */}
      <form onSubmit={handleSubmit} className="search-form">
        {/* Suchtyp-Auswahl */}
        <div className="search-type-selector">
          <button
            type="button"
            className={`search-type-button ${searchParams.type === 'tag' ? 'active' : ''}`}
            onClick={() => setSearchParams(prev => ({ ...prev, type: 'tag' }))}
          >
            Nach Thema
          </button>
          <button
            type="button"
            className={`search-type-button ${searchParams.type === 'location' ? 'active' : ''}`}
            onClick={() => setSearchParams(prev => ({ ...prev, type: 'location' }))}
          >
            Nach Ort
          </button>
        </div>

        {/* Dynamische Eingabefelder je nach Suchtyp */}
        {searchParams.type === 'tag' && (
          <div className="input-group">
            <label htmlFor="query">Thema oder Schlagwort:</label>
            <input
              type="text"
              id="query"
              name="query"
              value={searchParams.query}
              onChange={e => setSearchParams(prev => ({ ...prev, query: e.target.value }))}
              placeholder="z.B. Nachkriegszeit, Berlin, Alltag"
            />
          </div>
        )}

        {searchParams.type === 'location' && (
          <div className="input-group">
            <label htmlFor="location">Ort:</label>
            <input
              type="text"
              id="location"
              name="location"
              value={searchParams.location}
              onChange={e => setSearchParams(prev => ({ ...prev, location: e.target.value }))}
              placeholder="z.B. Berlin, München, Hamburg"
            />
          </div>
        )}

        <button type="submit" className="search-button" disabled={loading}>
          {loading ? 'Suche läuft...' : 'Suchen'}
        </button>
      </form>

      {/* Suchergebnisse */}
      {error && (
        <div className="error-message">{error}</div>
      )}
      {!error && results.length === 0 && !loading && (
        <div className="no-results">Keine Ergebnisse gefunden</div>
      )}
      {results.length > 0 && (
        <div className="search-results">
          <h2>Suchergebnisse ({pagination.total})</h2>
          <div className="results-list">
            {results.map(story => (
              <div key={story.id} className="result-item">
                <h3>
                  <Link to={`/story/${story.id}`}>{story.title}</Link>
                </h3>
                <div className="result-metadata">
                  <span>{story.location}</span>
                  <span>{new Date(story.date).toLocaleDateString()}</span>
                </div>
                <div className="result-tags">
                  {story.tags.map(tag => (
                    <span key={tag} className="tag-badge">{tag}</span>
                  ))}
                </div>
              </div>
            ))}
          </div>
          {pagination.hasMore && (
            <button
              className="load-more-button"
              onClick={() => performSearch(pagination.offset + pagination.limit)}
              disabled={loading}
            >
              {loading ? 'Lade...' : 'Weitere Ergebnisse laden'}
            </button>
          )}
        </div>
      )}
    </div>
  );
}

```

# 6. Fazit & Ausblick

ElderlyAR demonstriert, dass auch mit einem sehr begrenzten Budget von 500€ eine technisch solide und zukunftssichere Archivierung von Zeitzeugenberichten möglich ist. Durch den Einsatz von ArDrive, Arweave und Polygon schaffen wir ein nachhaltiges System, das ohne weitere Finanzierung fortbestehen kann.

Die tatsächlichen Kosten von nur etwa 1,01-1,43€ für die Speicherung von 200 Geschichten mit Fotos bieten einen außerordentlichen Spielraum für zukünftige Erweiterungen. Mit diesem Budget könnten problemlos tausende weitere Geschichten archiviert werden, ohne die finanziellen Grenzen zu überschreiten. Nach Projektende bleiben die archivierten Inhalte dauerhaft verfügbar und können von zukünftigen Generationen genutzt werden - ohne laufende Kosten oder Wartungsaufwand. Diese äußerst kostengünstige Permanentspeicherung macht ElderlyAR zu einer besonders nachhaltigen und zukunftssicheren Lösung für die Bewahrung kulturellen Erbes.

## 6.1 Potenzielle Erweiterungen

Mit dem verbleibenden Budget  könnten folgende Erweiterungen umgesetzt werden:

- Erhöhung der Anzahl archivierter Geschichten (40.000+ möglich)
- Integration von Audio- und Videoaufnahmen
- Mehrsprachige Benutzeroberfläche
- Erweiterte Suchfunktionen mit KI-Unterstützung

## 6.2 Langfristige Vision

ElderlyAR soll als Modellprojekt dienen, das zeigt, wie moderne Technologie kostengünstig für kulturelle Bewahrung eingesetzt werden kann. Die dezentrale, selbsterhaltende Natur des Systems gewährleistet, dass die gesammelten Geschichten für kommende Generationen erhalten bleiben – ein digitales Erbe, das ohne fortlaufende Finanzierung oder aktive Wartung Bestand hat.