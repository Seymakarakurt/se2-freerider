# se2-freerider

## 📌 Projektbeschreibung
**se2-freerider** ist ein Java-Projekt, das mit **Maven** verwaltet wird. Es enthält Skripte zur Konfiguration und zum Starten des Projekts.

## 📦 Inhalt des Repositories
- `.env.sh` - Shell-Skript für Umgebungsvariablen.
- `.run.sh` - Shell-Skript zum Starten des Projekts.
- `pom.xml` - Maven-Projektdatei zur Verwaltung von Abhängigkeiten und Build-Prozessen.
- `src/` - Quellcode des Projekts.
- `target/` - Build-Ordner mit den kompilierten Dateien.

## 🚀 Installation & Nutzung

### 🔹 Voraussetzungen
- **Java 17+** ([Download](https://adoptium.net/))
- **Maven** ([Download](https://maven.apache.org/download.cgi))

### 🔹 Repository klonen
```sh
git clone https://github.com/Seymakarakurt/se2-freerider.git
cd se2-freerider
```

### 🔹 Abhängigkeiten installieren
```sh
mvn clean install
```

### 🔹 Anwendung starten
```sh
bash .run.sh
```

### 🔹 Projekt kompilieren und ausführen
Falls kein `.run.sh` vorhanden ist:
```sh
mvn package
java -jar target/*.jar
```

## ⚙️ Entwicklung
Falls Änderungen am Code vorgenommen wurden, kann das Projekt mit folgendem Befehl neu gebaut werden:
```sh
mvn clean package
```

Entwickelt von Seyma Karakurt
