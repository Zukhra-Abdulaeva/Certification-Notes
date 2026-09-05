# PHASE 0 — IT-BASIS
### 30 Days = 270 Learning Units

**Verbindliches Learning-Unit-Modell**

1. **Theory**
2. **Context / Why**
3. **Admin / Professional Extension**
4. **Guided Practice**
5. **Independent Challenge**
6. **External Practice**
7. **Verification**

---

# 🔥 DAY 1 — HARDWARE FUNDAMENTALS DAY

## 1 — Linux/IT: CPU

- **Theory:** CPU, Cores, Threads, Clock Speed, Instruction Execution und grundlegende CPU-Architekturen.
- **Context / Why:** Die CPU führt Instruktionen aus und bestimmt wesentlich, wie Prozesse und Threads verarbeitet werden.
- **Admin / Professional Extension:** `lscpu`, `/proc/cpuinfo`, Architektur und CPU-Topologie untersuchen.
- **Guided Practice:** `lscpu` ausführen und Modell, Architektur, Kerne und Threads identifizieren.
- **Independent Challenge:** Die CPU eines Linux-Systems analysieren und erklären, wie viele physische und logische CPUs vorhanden sind.
- **External Practice:** Linux-System-Information-Übung durchführen.
- **Verification:** CPU, Core, Thread und Architektur ohne Hilfe erklären und `lscpu` interpretieren.

## 2 — Linux/IT: RAM

- **Theory:** RAM, virtueller Speicher, Swap, Buffer und Cache.
- **Context / Why:** Arbeitsspeicher beeinflusst unmittelbar die Performance laufender Prozesse und das Verhalten des Systems unter Last.
- **Admin / Professional Extension:** `free`, `/proc/meminfo`, Swap-Analyse und Memory Monitoring.
- **Guided Practice:** Speicherzustand mit `free -h` untersuchen.
- **Independent Challenge:** Used, Available, Cache und Swap eines Systems analysieren und erklären.
- **External Practice:** Linux-Memory-Exercise durchführen.
- **Verification:** Einen Speicherzustand diagnostizieren und die wichtigsten Werte erklären.

## 3 — Linux/IT: Storage

- **Theory:** HDD, SSD, NVMe, Kapazität, Latenz und I/O.
- **Context / Why:** Storage beeinflusst Bootzeiten, Datenzugriff, Datenbanken, Logs und Serverperformance.
- **Admin / Professional Extension:** `/dev`, Block Devices und `lsblk`.
- **Guided Practice:** Mit `lsblk` vorhandene Speichergeräte untersuchen.
- **Independent Challenge:** Geeigneten Storage für verschiedene Serverrollen auswählen und begründen.
- **External Practice:** Linux-Storage-Exercise durchführen.
- **Verification:** Storage-Technologien und ihre wichtigsten Eigenschaften erklären.

## 4 — Linux/IT: BIOS/UEFI

- **Theory:** Firmware, POST, BIOS, UEFI und Boot Order.
- **Context / Why:** Firmware initialisiert Hardware und leitet den Startvorgang des Betriebssystems ein.
- **Admin / Professional Extension:** Firmware → Bootloader → Kernel als Boot Chain verstehen.
- **Guided Practice:** Boot-Konfiguration eines Testsystems untersuchen.
- **Independent Challenge:** Den vollständigen Bootprozess vom Einschalten bis zum Kernel beschreiben.
- **External Practice:** Linux-Boot/System-Lab durchführen.
- **Verification:** BIOS/UEFI, Bootloader und Betriebssystem eindeutig unterscheiden.

## 5 — Python: Variablen

- **Theory:** Variablen, Datentypen, Assignment und grundlegender Scope.
- **Context / Why:** Variablen sind Grundlage für spätere System- und Administrationsautomation.
- **Admin / Professional Extension:** Systeminformationen in Variablen speichern und weiterverarbeiten.
- **Guided Practice:** Werte speichern, verändern und ausgeben.
- **Independent Challenge:** Ein kleines System-Info-Skript erstellen.
- **External Practice:** Python-Variablen-Übungen durchführen.
- **Verification:** Variable, Wert und Datentyp erklären.

## 6 — Git: init + commit

- **Theory:** Repository, Working Tree, Staging Area und Commit.
- **Context / Why:** Git ermöglicht nachvollziehbare und versionierte Entwicklung.
- **Admin / Professional Extension:** Kleine technische Änderungen sauber versionieren.
- **Guided Practice:** Repository initialisieren, Dateien hinzufügen und ersten Commit erstellen.
- **Independent Challenge:** Drei logisch getrennte Commits erzeugen.
- **External Practice:** Interaktive Git-Grundlagenübung.
- **Verification:** Working Tree → Staging → Commit erklären.

## 7 — Docker: Container

- **Theory:** Container, Prozessisolation und Unterschied zu virtuellen Maschinen.
- **Context / Why:** Container ermöglichen reproduzierbare und isolierte Anwendungen.
- **Admin / Professional Extension:** Container-Lifecycle und Host-/Container-Grenzen verstehen.
- **Guided Practice:** Container starten, untersuchen und stoppen.
- **Independent Challenge:** Erklären, welche Ressourcen vom Host und welche vom Container genutzt werden.
- **External Practice:** Docker-Container-Lab.
- **Verification:** Grundprinzip der Container-Isolation erklären.

## 8 — Kubernetes: Pod

- **Theory:** Pod als kleinste Deployment-Einheit von Kubernetes.
- **Context / Why:** Kubernetes verwaltet Container nicht isoliert, sondern über Pods.
- **Admin / Professional Extension:** Pod-Lifecycle und grundlegende Pod-Konfiguration.
- **Guided Practice:** Einen einfachen Pod starten und untersuchen.
- **Independent Challenge:** Pod und Container klar voneinander unterscheiden.
- **External Practice:** Kubernetes-Pod-Lab.
- **Verification:** Zweck und grundlegenden Lifecycle eines Pods erklären.

## 9 — AI: LLM

- **Theory:** Tokens, Parameter, Training, Inference und Context Window.
- **Context / Why:** LLMs bilden später die Grundlage für AI-gestützte Automation und Wissenssysteme.
- **Admin / Professional Extension:** Unterschied zwischen Modell, Prompt, Kontext und Inference verstehen.
- **Guided Practice:** Unterschiedliche Prompts testen.
- **Independent Challenge:** Halluzinationen erkennen und mögliche Ursachen analysieren.
- **External Practice:** LLM-Grundlagenübung.
- **Verification:** Training und Inference unterscheiden.

---

# 🔥 DAY 2 — OPERATING SYSTEM DAY

## 1 — Linux/IT: Kernel

- **Theory:** Kernel, User Space und Hardware-Abstraktion.
- **Context / Why:** Der Kernel vermittelt zwischen Anwendungen und Hardware.
- **Admin / Professional Extension:** `uname -a`, `/proc` und `/sys`.
- **Guided Practice:** Kernel-Version und Architektur untersuchen.
- **Independent Challenge:** Die Grenze zwischen Kernel Space und User Space erklären.
- **External Practice:** Linux-Fundamentals-Lab.
- **Verification:** Rolle des Kernels ohne Hilfe erklären.

## 2 — Linux/IT: Processes

- **Theory:** Prozess, PID, Parent/Child und Prozesszustände.
- **Context / Why:** Jeder laufende Prozess benötigt Ressourcen und muss administrativ beobachtbar sein.
- **Admin / Professional Extension:** `ps`, `/proc/PID`.
- **Guided Practice:** Laufende Prozesse untersuchen.
- **Independent Challenge:** Parent-Prozess eines Programms identifizieren.
- **External Practice:** Process-Lab.
- **Verification:** PID und Prozesszustand erklären.

## 3 — Linux/IT: Services

- **Theory:** Daemon, Service und Prozess.
- **Context / Why:** Serverdienste müssen automatisch gestartet, überwacht und kontrolliert werden können.
- **Admin / Professional Extension:** systemd und `systemctl`.
- **Guided Practice:** Status eines vorhandenen Services untersuchen.
- **Independent Challenge:** Prozess und Service anhand eines realen Beispiels unterscheiden.
- **External Practice:** systemd-Service-Lab.
- **Verification:** Service-Lifecycle erklären.

## 4 — Linux/IT: Filesystem Structure

- **Theory:** FHS und zentrale Verzeichnisse `/etc`, `/var`, `/usr`, `/home`, `/boot`, `/dev`, `/proc`, `/sys`.
- **Context / Why:** Administratoren müssen Konfigurationen, Logs, Programme, Userdaten und Kernelinformationen schnell finden.
- **Admin / Professional Extension:** FHS und Zweck der Verzeichnisse.
- **Guided Practice:** Zentrale Verzeichnisse untersuchen.
- **Independent Challenge:** Für Konfiguration, Logs und Userdaten den richtigen Speicherort bestimmen.
- **External Practice:** Linux-Filesystem-Lab.
- **Verification:** Zentrale FHS-Verzeichnisse erklären.

## 5 — Python: Funktionen

- **Theory:** Funktionen, Parameter und Rückgabewerte.
- **Context / Why:** Funktionen machen Automationscode wiederverwendbar.
- **Admin / Professional Extension:** Systeminformationen über Funktionen kapseln.
- **Guided Practice:** Funktionen mit Parametern und `return` schreiben.
- **Independent Challenge:** Systeminformationen über mehrere Funktionen ausgeben.
- **External Practice:** Python-Functions-Exercises.
- **Verification:** `return` und `print` unterscheiden.

## 6 — Git: commit → push

- **Theory:** Lokales und entferntes Repository.
- **Context / Why:** Änderungen müssen sicher mit einem Remote-Repository synchronisiert werden.
- **Admin / Professional Extension:** Lokale Änderungen kontrolliert veröffentlichen.
- **Guided Practice:** Commit erstellen und pushen.
- **Independent Challenge:** Lokalen und entfernten Zustand vergleichen.
- **External Practice:** Git-Remote-Exercise.
- **Verification:** Vollständigen Commit-to-Push-Workflow erklären.

## 7 — Docker: Images

- **Theory:** Images, Layers und Immutable Infrastructure.
- **Context / Why:** Images bilden reproduzierbare Grundlagen für Container.
- **Admin / Professional Extension:** Image-Versionierung und Image-Inspection.
- **Guided Practice:** Image pull, run und inspect durchführen.
- **Independent Challenge:** Image und Container anhand ihres Lebenszyklus erklären.
- **External Practice:** Docker-Image-Lab.
- **Verification:** Image-Lifecycle erklären.

## 8 — Kubernetes: Services

- **Theory:** Service-Abstraktion, Selector und Ports.
- **Context / Why:** Pods sind dynamisch; Services bieten stabile Erreichbarkeit.
- **Admin / Professional Extension:** Service Discovery und Port Mapping.
- **Guided Practice:** Pod über einen Service erreichbar machen.
- **Independent Challenge:** Pod-IP und Service-IP erklären.
- **External Practice:** Kubernetes-Service-Lab.
- **Verification:** Service Discovery erklären.

## 9 — AI: Prompts

- **Theory:** Instruction, Context, Constraints und Output Format.
- **Context / Why:** Gute Prompts beeinflussen Qualität, Zuverlässigkeit und Reproduzierbarkeit von AI-Ausgaben.
- **Admin / Professional Extension:** Prompts für technische Aufgaben strukturieren.
- **Guided Practice:** Mehrere Promptvarianten vergleichen.
- **Independent Challenge:** Einen schlechten Prompt systematisch verbessern.
- **External Practice:** Prompt-Engineering-Exercise.
- **Verification:** Eine gute Promptstruktur erklären.

---

# 🔥 DAY 3 — TERMINAL DAY

## 1 — Linux/IT: ls

- **Theory:** `ls`, Optionen, Verzeichnisinhalte und Dateiinformationen.
- **Context / Why:** `ls` gehört zu den wichtigsten Diagnose- und Navigationswerkzeugen.
- **Admin / Professional Extension:** `ls -la`, Permissions, Owner, Group, Size und Timestamps.
- **Guided Practice:** `/etc`, `/var` und `/home` untersuchen.
- **Independent Challenge:** Einen unbekannten Verzeichnisinhalt vollständig analysieren.
- **External Practice:** Linux-CLI-Lab.
- **Verification:** `ls -la` sicher interpretieren.

## 2 — Linux/IT: cd

- **Theory:** Absolute und relative Pfade, `.`, `..` und `~`.
- **Context / Why:** Sichere Navigation ist Grundlage jeder Linux-Administration.
- **Admin / Professional Extension:** Pfade korrekt und reproduzierbar verwenden.
- **Guided Practice:** Zwischen mehreren Verzeichnissen navigieren.
- **Independent Challenge:** Eine Aufgabe ausschließlich mit relativen Pfaden lösen.
- **External Practice:** Filesystem-Navigation-Exercise.
- **Verification:** Absolute und relative Pfade erklären.

## 3 — Linux/IT: cp / mv

- **Theory:** Kopieren, Verschieben und Umbenennen.
- **Context / Why:** Dateien und Konfigurationen müssen sicher verwaltet und gesichert werden.
- **Admin / Professional Extension:** `cp`, `cp -r`, `mv` und Backup-Strategien.
- **Guided Practice:** Dateien und Verzeichnisse kopieren und verschieben.
- **Independent Challenge:** Ein kleines Konfigurationsbackup erstellen.
- **External Practice:** Linux-file-management-Lab.
- **Verification:** `cp` und `mv` korrekt einsetzen.

## 4 — Linux/IT: rm

- **Theory:** Löschen mit `rm`, rekursives Löschen und Wildcards.
- **Context / Why:** Falsches Löschen kann Systeme und Daten dauerhaft beschädigen.
- **Admin / Professional Extension:** Sichere Löschstrategien und Vorsicht mit `rm -rf`.
- **Guided Practice:** In einem Testverzeichnis Dateien selektiv löschen.
- **Independent Challenge:** Bestimmte Dateien löschen, ohne andere Dateien zu entfernen.
- **External Practice:** Safe-file-deletion-Exercise.
- **Verification:** Erklären, warum `rm -rf` besonders gefährlich ist.

## 5 — Python: Loops

- **Theory:** `for`, `while` und Iteration.
- **Context / Why:** Schleifen ermöglichen automatisierte Verarbeitung vieler Dateien oder Systemobjekte.
- **Admin / Professional Extension:** Dateien oder Systeminformationen automatisiert verarbeiten.
- **Guided Practice:** Listen mit `for` und Bedingungen verarbeiten.
- **Independent Challenge:** Dateien anhand bestimmter Kriterien klassifizieren.
- **External Practice:** Python-loop-exercises.
- **Verification:** `for` und `while` unterscheiden.

## 6 — Git: Branches

- **Theory:** Branch, HEAD und parallele Entwicklung.
- **Context / Why:** Änderungen können isoliert entwickelt werden.
- **Admin / Professional Extension:** Feature-Branch-Workflow.
- **Guided Practice:** Branch erstellen, ändern und mergen.
- **Independent Challenge:** Zwei parallele Änderungen in separaten Branches durchführen.
- **External Practice:** Git-branching-Lab.
- **Verification:** Zweck eines Branches erklären.

## 7 — Docker: Registry

- **Theory:** Registry, Repository, Image und Tag.
- **Context / Why:** Container Images müssen gespeichert, versioniert und verteilt werden.
- **Admin / Professional Extension:** `pull`, `tag`, `push`.
- **Guided Practice:** Image aus einer Registry beziehen.
- **Independent Challenge:** Image mit Versionstag versehen und Workflow erklären.
- **External Practice:** Docker-registry-exercise.
- **Verification:** Registry, Repository und Image unterscheiden.

## 8 — Kubernetes: Deployments

- **Theory:** Desired State, Replica und Rollout.
- **Context / Why:** Kubernetes hält gewünschte Anwendungszustände automatisch aufrecht.
- **Admin / Professional Extension:** Deployment, Scaling und Updates.
- **Guided Practice:** Deployment erstellen und skalieren.
- **Independent Challenge:** Deployment aktualisieren und Rollout beobachten.
- **External Practice:** Kubernetes-deployment-Lab.
- **Verification:** Desired State und Replica-Konzept erklären.

## 9 — AI: Embeddings

- **Theory:** Embeddings, Vektoren und semantische Ähnlichkeit.
- **Context / Why:** Embeddings ermöglichen semantische Suche und spätere RAG-Systeme.
- **Admin / Professional Extension:** Vektorbasierte Ähnlichkeit verstehen.
- **Guided Practice:** Texte mit unterschiedlicher Bedeutung vergleichen.
- **Independent Challenge:** Erklären, warum semantisch ähnliche Texte ähnliche Embeddings erhalten.
- **External Practice:** Embedding-Exercise.
- **Verification:** Embedding und klassisches Keyword Matching unterscheiden.

---

# 🔥 DAY 4 — PROCESSES DAY

## 1 — Linux/IT: ps

- **Theory:** Prozesslisten, PID und Prozessinformationen.
- **Context / Why:** Administratoren müssen laufende Prozesse identifizieren können.
- **Admin / Professional Extension:** `ps aux`, `ps -ef`, Prozesshierarchien.
- **Guided Practice:** Prozesse anzeigen und nach Namen suchen.
- **Independent Challenge:** Einen Prozess inklusive Parent identifizieren.
- **External Practice:** Process-management-Lab.
- **Verification:** Einen `ps`-Output interpretieren.

## 2 — Linux/IT: top / htop

- **Theory:** Live-Prozessmonitoring, CPU, RAM und Load.
- **Context / Why:** Monitoring ist Grundlage der Performance-Diagnose.
- **Admin / Professional Extension:** CPU-/Memory-intensive Prozesse erkennen.
- **Guided Practice:** `top` ausführen und Prozesse sortieren.
- **Independent Challenge:** Einen Ressourcenverbraucher identifizieren und Ursache untersuchen.
- **External Practice:** Linux-monitoring-Lab.
- **Verification:** CPU-, Memory- und Load-Werte erklären.

## 3 — Linux/IT: kill / Signals

- **Theory:** Signals, SIGTERM, SIGKILL und Prozessbeendigung.
- **Context / Why:** Hängende oder fehlerhafte Prozesse müssen kontrolliert beendet werden.
- **Admin / Professional Extension:** `kill`, `killall`, Signalverhalten.
- **Guided Practice:** Einen Testprozess mit SIGTERM beenden.
- **Independent Challenge:** Unterschied zwischen SIGTERM und SIGKILL erklären und demonstrieren.
- **External Practice:** Process-signal-exercise.
- **Verification:** Signalmechanismus erklären.

## 4 — Linux/IT: systemctl Basics

- **Theory:** systemd und Service-Management.
- **Context / Why:** Linux-Serverdienste müssen zentral verwaltet werden.
- **Admin / Professional Extension:** `systemctl status/start/stop`.
- **Guided Practice:** Service untersuchen und kontrollieren.
- **Independent Challenge:** Fehlerhaften Servicezustand analysieren.
- **External Practice:** systemd-Lab.
- **Verification:** `systemctl` sicher für grundlegende Aufgaben einsetzen.

## 5 — Python: Classes

- **Theory:** Klassen, Objekte, Attribute und Methoden.
- **Context / Why:** Objektorientierung hilft bei größeren Automationsprogrammen.
- **Admin / Professional Extension:** Systeminformationen als Objekt modellieren.
- **Guided Practice:** Einfache `SystemInfo`-Klasse erstellen.
- **Independent Challenge:** Ein Systemobjekt mit mehreren Methoden modellieren.
- **External Practice:** Python-OOP-Exercise.
- **Verification:** Klasse und Objekt unterscheiden.

## 6 — Git: Merge

- **Theory:** Fast-forward, Merge Commit und Konflikte.
- **Context / Why:** Parallele Entwicklung muss kontrolliert zusammengeführt werden.
- **Admin / Professional Extension:** Merge-Konflikte analysieren.
- **Guided Practice:** Zwei Branches erstellen und zusammenführen.
- **Independent Challenge:** Einen einfachen Merge-Konflikt erzeugen und lösen.
- **External Practice:** Git-merge-Lab.
- **Verification:** Merge-Prozess erklären.

## 7 — Docker: Volumes

- **Theory:** Persistente Containerdaten und Volumes.
- **Context / Why:** Container sind kurzlebig; wichtige Daten müssen außerhalb des Container-Layers liegen.
- **Admin / Professional Extension:** Docker Volumes und Mounts.
- **Guided Practice:** Volume erstellen und in Container mounten.
- **Independent Challenge:** Daten über Container-Neustart hinweg erhalten.
- **External Practice:** Docker-volume-Lab.
- **Verification:** Container-Dateisystem und persistentes Volume unterscheiden.

## 8 — Kubernetes: ConfigMaps

- **Theory:** Konfigurationsdaten außerhalb des Container-Images.
- **Context / Why:** Konfiguration sollte unabhängig vom Image verwaltet werden.
- **Admin / Professional Extension:** ConfigMap-Erstellung und Injection.
- **Guided Practice:** ConfigMap erstellen und in Pod einbinden.
- **Independent Challenge:** ConfigMap und Secret sinnvoll unterscheiden.
- **External Practice:** Kubernetes-ConfigMap-Lab.
- **Verification:** Zweck einer ConfigMap erklären.

## 9 — AI: Text Classification

- **Theory:** Klassen, Labels und Klassifikationsmodelle.
- **Context / Why:** Klassifikation wird für Tickets, Logs und automatische Sortierung genutzt.
- **Admin / Professional Extension:** Technische Logs nach Fehlertypen klassifizieren.
- **Guided Practice:** Texte mehreren Klassen zuordnen.
- **Independent Challenge:** Fehlklassifikationen analysieren.
- **External Practice:** Text-classification-Exercise.
- **Verification:** Classification und Generation unterscheiden.

---

# 🔥 DAY 5 — SERVICES DAY

## 1 — systemctl start/stop

- **Theory:** Service Lifecycle und Zustandsänderungen.
- **Context / Why:** Administratoren müssen Dienste kontrolliert starten und stoppen können.
- **Admin / Professional Extension:** `systemctl start`, `stop`, `restart`.
- **Guided Practice:** Testservice starten und stoppen.
- **Independent Challenge:** Servicezustand nach mehreren Lifecycle-Änderungen dokumentieren.
- **External Practice:** systemd-service-exercise.
- **Verification:** Start, Stop und Restart unterscheiden.

## 2 — systemctl status

- **Theory:** Service State, PID, Aktivierungsstatus und Fehlermeldungen.
- **Context / Why:** `status` ist ein zentraler erster Schritt bei Serviceproblemen.
- **Admin / Professional Extension:** `systemctl status` mit Journalanalyse kombinieren.
- **Guided Practice:** Einen Servicezustand untersuchen.
- **Independent Challenge:** Fehlerhinweise aus einem Statusoutput identifizieren.
- **External Practice:** Service-diagnosis-Lab.
- **Verification:** Einen `systemctl status`-Output erklären.

## 3 — journalctl Logs

- **Theory:** Systemd Journal und strukturierte Logabfrage.
- **Context / Why:** Logs sind entscheidend für Fehleranalyse.
- **Admin / Professional Extension:** `journalctl -u`, `-f`, `--since`.
- **Guided Practice:** Logs eines Services filtern.
- **Independent Challenge:** Ursache eines simulierten Servicefehlers anhand des Journals finden.
- **External Practice:** journalctl-Lab.
- **Verification:** Gezielt relevante Logs abrufen.

## 4 — Service Files

- **Theory:** systemd Unit Files und zentrale Sektionen.
- **Context / Why:** Eigene Services müssen reproduzierbar definiert werden.
- **Admin / Professional Extension:** `[Unit]`, `[Service]`, `[Install]`.
- **Guided Practice:** Einen einfachen Testservice erstellen.
- **Independent Challenge:** Service mit korrektem Startverhalten definieren.
- **External Practice:** systemd-unit-exercise.
- **Verification:** Aufbau einer Unit erklären.

## 5 — Python: OOP

- **Theory:** Klassen, Objekte, Methoden und Kapselung.
- **Context / Why:** OOP strukturiert komplexere Automation.
- **Admin / Professional Extension:** Systemobjekte modellieren.
- **Guided Practice:** Mehrere Klassen erstellen und verwenden.
- **Independent Challenge:** Kleine technische Anwendung objektorientiert strukturieren.
- **External Practice:** Python-OOP-Lab.
- **Verification:** Vorteile und Grenzen von OOP erklären.

## 6 — Git: Rebase

- **Theory:** Rebase und lineare Historie.
- **Context / Why:** Rebase kann Entwicklungszweige sauber auf aktuellen Stand bringen.
- **Admin / Professional Extension:** Unterschied zu Merge.
- **Guided Practice:** Branch auf aktuellen Main-Stand rebasen.
- **Independent Challenge:** Rebase durchführen und Historie analysieren.
- **External Practice:** Git-rebase-exercise.
- **Verification:** Rebase und Merge unterscheiden.

## 7 — Docker: Networks

- **Theory:** Container-Netzwerke und virtuelle Netzwerkinterfaces.
- **Context / Why:** Container müssen miteinander und mit externen Systemen kommunizieren.
- **Admin / Professional Extension:** Bridge-Netzwerke und Container-DNS.
- **Guided Practice:** Zwei Container in einem gemeinsamen Netzwerk verbinden.
- **Independent Challenge:** Netzwerkkommunikation zwischen Containern erklären.
- **External Practice:** Docker-networking-Lab.
- **Verification:** Container-Netzwerkgrundlagen erklären.

## 8 — Kubernetes: Secrets

- **Theory:** Secrets und sensible Konfigurationsdaten.
- **Context / Why:** Zugangsdaten dürfen nicht als normale Konfiguration behandelt werden.
- **Admin / Professional Extension:** Secret Injection und Sicherheitsgrenzen.
- **Guided Practice:** Secret erstellen und in Pod verwenden.
- **Independent Challenge:** Secret und ConfigMap für ein Szenario korrekt einsetzen.
- **External Practice:** Kubernetes-Secrets-Lab.
- **Verification:** Secret und ConfigMap unterscheiden.

## 9 — AI: Tokenization

- **Theory:** Tokens, Tokenisierung und Tokenverbrauch.
- **Context / Why:** Tokenisierung beeinflusst Kontextgröße und Kosten von LLM-Aufrufen.
- **Admin / Professional Extension:** Token Limits und technische Promptplanung.
- **Guided Practice:** Unterschiedliche Texte hinsichtlich Tokenisierung vergleichen.
- **Independent Challenge:** Einen Prompt hinsichtlich Tokenverbrauch optimieren.
- **External Practice:** Tokenization-Exercise.
- **Verification:** Token und Zeichen/Wörter unterscheiden.

---

# 🔥 DAY 6 — VIRTUALIZATION DAY

## 1 — Hypervisor

- **Theory:** Hypervisor, Type 1 und Type 2.
- **Context / Why:** Hypervisor ermöglichen mehrere virtuelle Systeme auf einem Host.
- **Admin / Professional Extension:** Virtualisierungsschicht und Ressourcenverteilung.
- **Guided Practice:** VM-Hypervisor identifizieren.
- **Independent Challenge:** Type-1- und Type-2-Hypervisor vergleichen.
- **External Practice:** Virtualization-Lab.
- **Verification:** Rolle eines Hypervisors erklären.

## 2 — VM vs Container

- **Theory:** VM-Hardwarevirtualisierung und Container-Prozessisolation.
- **Context / Why:** Die Wahl beeinflusst Isolation, Ressourcenverbrauch und Deployment.
- **Admin / Professional Extension:** Sicherheits- und Betriebsunterschiede.
- **Guided Practice:** VM und Container vergleichen.
- **Independent Challenge:** Für drei Szenarien die passende Technologie auswählen.
- **External Practice:** VM/container comparison exercise.
- **Verification:** Grundlegende Unterschiede erklären.

## 3 — CPU Virtualization

- **Theory:** vCPU, Scheduling und CPU Overcommit.
- **Context / Why:** Virtuelle CPUs müssen auf physische CPU-Ressourcen abgebildet werden.
- **Admin / Professional Extension:** CPU Allocation und Performance.
- **Guided Practice:** vCPU-Konfiguration einer VM untersuchen.
- **Independent Challenge:** Überbelegung und deren Auswirkungen erklären.
- **External Practice:** CPU virtualization lab.
- **Verification:** vCPU und physische CPU unterscheiden.

## 4 — Memory Virtualization

- **Theory:** Virtueller Speicher, VM Memory und Ballooning.
- **Context / Why:** Speicher muss zwischen Host und Gast effizient verteilt werden.
- **Admin / Professional Extension:** Memory Allocation und Overcommit.
- **Guided Practice:** VM-Speicherkonfiguration untersuchen.
- **Independent Challenge:** Auswirkungen zu hoher Memory Allocation erklären.
- **External Practice:** Virtual-memory exercise.
- **Verification:** Memory Virtualization erklären.

## 5 — Python: Files

- **Theory:** Dateien öffnen, lesen, schreiben und schließen.
- **Context / Why:** Automation verarbeitet häufig Konfigurationen und Logs.
- **Admin / Professional Extension:** Sichere Dateioperationen.
- **Guided Practice:** Textdatei lesen und schreiben.
- **Independent Challenge:** Eine Logdatei automatisch auswerten.
- **External Practice:** Python-file-I/O-Lab.
- **Verification:** File-I/O korrekt erklären.

## 6 — Git: Tags

- **Theory:** Tags und feste Versionspunkte.
- **Context / Why:** Releases und stabile Zustände müssen eindeutig markiert werden.
- **Admin / Professional Extension:** Annotated Tags.
- **Guided Practice:** Tag erstellen und anzeigen.
- **Independent Challenge:** Eine Versionierung mit mehreren Tags aufbauen.
- **External Practice:** Git-tags-exercise.
- **Verification:** Branch und Tag unterscheiden.

## 7 — Docker: Compose

- **Theory:** Multi-Container-Anwendungen und deklarative Konfiguration.
- **Context / Why:** Mehrere abhängige Container benötigen reproduzierbare Orchestrierung.
- **Admin / Professional Extension:** Compose Services, Networks und Volumes.
- **Guided Practice:** Kleine Multi-Container-Anwendung starten.
- **Independent Challenge:** Zwei Services inklusive Netzwerk konfigurieren.
- **External Practice:** Docker Compose Lab.
- **Verification:** Zweck von Compose erklären.

## 8 — Kubernetes: Autoscaling

- **Theory:** Horizontal Pod Autoscaler und Metrics.
- **Context / Why:** Anwendungen müssen sich dynamisch an Last anpassen können.
- **Admin / Professional Extension:** HPA und Resource Requests.
- **Guided Practice:** HPA-Konfiguration untersuchen.
- **Independent Challenge:** Skalierungsverhalten bei steigender Last erklären.
- **External Practice:** Kubernetes HPA Lab.
- **Verification:** Zweck von Autoscaling erklären.

## 9 — AI: Summarization

- **Theory:** Abstraktion, Zusammenfassung und Informationsverdichtung.
- **Context / Why:** Große technische Informationen können automatisiert verdichtet werden.
- **Admin / Professional Extension:** Logs und technische Dokumentation zusammenfassen.
- **Guided Practice:** Texte mit unterschiedlichen Promptstrategien zusammenfassen.
- **Independent Challenge:** Informationsverlust einer Zusammenfassung analysieren.
- **External Practice:** Summarization exercise.
- **Verification:** Gute und schlechte Zusammenfassungen unterscheiden.

---

# 🔥 DAY 7 — UBUNTU INSTALLATION DAY

## 1 — ISO Download

- **Theory:** ISO-Images, Distribution Releases und Checksums.
- **Context / Why:** Ein Administrator muss Installationsmedien auf Integrität prüfen.
- **Admin / Professional Extension:** SHA-Checksums und vertrauenswürdige Quellen.
- **Guided Practice:** Ubuntu-ISO und Prüfsumme untersuchen.
- **Independent Challenge:** Integrität eines Installationsimages verifizieren.
- **External Practice:** Linux-installation-preparation lab.
- **Verification:** ISO und Checksum korrekt erklären.

## 2 — Boot USB

- **Theory:** Bootable Media, UEFI und Boot Device Selection.
- **Context / Why:** Betriebssysteminstallation beginnt mit korrekt vorbereitetem Bootmedium.
- **Admin / Professional Extension:** UEFI/USB Boot.
- **Guided Practice:** Bootmedium vorbereiten und Bootoptionen untersuchen.
- **Independent Challenge:** Bootproblem systematisch diagnostizieren.
- **External Practice:** Linux boot-media exercise.
- **Verification:** Bootmedium und Bootloader unterscheiden.

## 3 — Ubuntu Installation

- **Theory:** Distribution, Installation, Partitionierung, User und Hostname.
- **Context / Why:** Eine reproduzierbare Serverinstallation ist Grundlage der Administration.
- **Admin / Professional Extension:** Ubuntu Server Setup.
- **Guided Practice:** Ubuntu in VM installieren.
- **Independent Challenge:** Eine grundlegende Serverinstallation selbstständig durchführen.
- **External Practice:** Ubuntu installation lab.
- **Verification:** Installationsablauf erklären.

## 4 — Network Configuration

- **Theory:** Netzwerkinterface, IP, Gateway und DNS.
- **Context / Why:** Ein Server benötigt funktionierende Netzwerkkonnektivität.
- **Admin / Professional Extension:** Netplan und grundlegende Linux-Netzwerkkonfiguration.
- **Guided Practice:** Netzwerkparameter untersuchen.
- **Independent Challenge:** Netzwerkfehler anhand der Konfiguration diagnostizieren.
- **External Practice:** Linux networking lab.
- **Verification:** IP, Gateway und DNS unterscheiden.

## 5 — Python: Exceptions

- **Theory:** Exceptions, `try`, `except`, `finally`.
- **Context / Why:** Automation muss mit erwartbaren Fehlern umgehen können.
- **Admin / Professional Extension:** Robuste Systemskripte.
- **Guided Practice:** Fehlerbehandlung implementieren.
- **Independent Challenge:** Datei- und Netzwerkfehler kontrolliert behandeln.
- **External Practice:** Python exception exercise.
- **Verification:** Exception Handling erklären.

## 6 — Git: Workflow

- **Theory:** Working Tree, Branch, Commit, Pull und Push.
- **Context / Why:** Ein standardisierter Workflow verhindert unkontrollierte Änderungen.
- **Admin / Professional Extension:** Kleine technische Projekte versionieren.
- **Guided Practice:** Vollständigen Git-Workflow durchführen.
- **Independent Challenge:** Eine Änderung vom ersten Edit bis zum Remote durchführen.
- **External Practice:** Git workflow lab.
- **Verification:** Workflow ohne Hilfe erklären.

## 7 — Docker: Build

- **Theory:** Dockerfile, Build Context und Image.
- **Context / Why:** Anwendungen müssen reproduzierbar paketiert werden.
- **Admin / Professional Extension:** Build Layers und einfache Optimierung.
- **Guided Practice:** Eigenes Image bauen.
- **Independent Challenge:** Ein kleines Python-Programm containerisieren.
- **External Practice:** Docker build lab.
- **Verification:** Dockerfile → Image → Container erklären.

## 8 — Kubernetes: Deployment

- **Theory:** YAML, Deployment, Replica und Desired State.
- **Context / Why:** Kubernetes beschreibt Infrastruktur deklarativ.
- **Admin / Professional Extension:** `kubectl apply`, rollout und scaling.
- **Guided Practice:** Deployment erstellen.
- **Independent Challenge:** Deployment skalieren und aktualisieren.
- **External Practice:** Kubernetes deployment exercise.
- **Verification:** Deklaratives Deployment erklären.

## 9 — AI: API Calls

- **Theory:** API, Request, Response, Authentication und JSON.
- **Context / Why:** AI wird in Automation häufig über APIs integriert.
- **Admin / Professional Extension:** Secrets und Environment Variables.
- **Guided Practice:** Einen einfachen API-Aufruf nachvollziehen.
- **Independent Challenge:** API-Antwort analysieren und Fehlerfälle bestimmen.
- **External Practice:** AI API exercise.
- **Verification:** Request und Response erklären.

---

# 🔥 DAY 8 — LINUX FILESYSTEM DAY

## 1 — `/etc`

- **Theory:** Systemweite Konfiguration.
- **Context / Why:** Viele zentrale Linux-Dienste werden über `/etc` konfiguriert.
- **Admin / Professional Extension:** Typische Dateien wie `/etc/hosts`, `/etc/passwd` und Service-Konfigurationen.
- **Guided Practice:** `/etc` untersuchen.
- **Independent Challenge:** Konfigurationsdateien für mehrere Dienste identifizieren.
- **External Practice:** Linux `/etc` exercise.
- **Verification:** Zweck von `/etc` erklären.

## 2 — `/var`

- **Theory:** Variable Daten, Logs, Cache und Spools.
- **Context / Why:** Laufzeitdaten wachsen dynamisch und müssen überwacht werden.
- **Admin / Professional Extension:** `/var/log`, `/var/cache`, `/var/lib`.
- **Guided Practice:** `/var` untersuchen.
- **Independent Challenge:** Ursache eines wachsenden `/var`-Verzeichnisses analysieren.
- **External Practice:** Linux filesystem lab.
- **Verification:** `/var` und `/etc` unterscheiden.

## 3 — `/usr`

- **Theory:** Userland-Programme, Libraries und Daten.
- **Context / Why:** Moderne Linux-Systeme trennen Systemdaten logisch von variablen Daten.
- **Admin / Professional Extension:** `/usr/bin`, `/usr/sbin`, `/usr/lib`, `/usr/share`.
- **Guided Practice:** `/usr` untersuchen.
- **Independent Challenge:** Programm und zugehörige Ressourcen finden.
- **External Practice:** FHS exercise.
- **Verification:** Hauptbereiche von `/usr` erklären.

## 4 — `/home`

- **Theory:** User Home Directories und persönliche Daten.
- **Context / Why:** Benutzer benötigen getrennte Bereiche für persönliche Dateien und Konfiguration.
- **Admin / Professional Extension:** Ownership und versteckte Dateien.
- **Guided Practice:** Home Directory untersuchen.
- **Independent Challenge:** Berechtigungen eines Home-Verzeichnisses analysieren.
- **External Practice:** Linux user-home exercise.
- **Verification:** Zweck von `/home` erklären.

## 5 — Python: Modules

- **Theory:** Module, Imports und Namespace.
- **Context / Why:** Größere Programme müssen in wiederverwendbare Komponenten zerlegt werden.
- **Admin / Professional Extension:** Standardbibliothek und eigene Module.
- **Guided Practice:** Eigenes Modul erstellen und importieren.
- **Independent Challenge:** Automation in mehrere Module aufteilen.
- **External Practice:** Python modules lab.
- **Verification:** Module und Packages unterscheiden.

## 6 — Git: Pull Requests

- **Theory:** Branch Review, Pull Request und Integration.
- **Context / Why:** Änderungen werden vor Integration geprüft.
- **Admin / Professional Extension:** Review-orientierter Workflow.
- **Guided Practice:** Branch erstellen und Pull Request vorbereiten.
- **Independent Challenge:** Änderung mit Beschreibung und Review-Kontext vorbereiten.
- **External Practice:** Git collaboration exercise.
- **Verification:** Zweck eines Pull Requests erklären.

## 7 — Docker: Healthcheck

- **Theory:** Healthchecks und Containerzustand.
- **Context / Why:** Ein laufender Container bedeutet nicht automatisch, dass die Anwendung funktioniert.
- **Admin / Professional Extension:** `HEALTHCHECK`.
- **Guided Practice:** Healthcheck definieren und Status beobachten.
- **Independent Challenge:** Geeigneten Healthcheck für einen Service entwickeln.
- **External Practice:** Docker healthcheck lab.
- **Verification:** Prozesszustand und Application Health unterscheiden.

## 8 — Kubernetes: Liveness Probes

- **Theory:** Liveness Probe und Container-Restart.
- **Context / Why:** Kubernetes muss fehlerhafte Container erkennen können.
- **Admin / Professional Extension:** Probe-Konfiguration.
- **Guided Practice:** Liveness Probe untersuchen.
- **Independent Challenge:** Verhalten bei absichtlich fehlerhafter Anwendung analysieren.
- **External Practice:** Kubernetes probes lab.
- **Verification:** Liveness und Prozessstatus unterscheiden.

## 9 — AI: Embeddings

- **Theory:** Semantische Vektorrepräsentation.
- **Context / Why:** Embeddings ermöglichen Suche über Bedeutung statt nur Zeichenketten.
- **Admin / Professional Extension:** Grundlage für RAG.
- **Guided Practice:** Semantisch ähnliche Texte vergleichen.
- **Independent Challenge:** Keyword-Suche und semantische Suche vergleichen.
- **External Practice:** Embedding exercise.
- **Verification:** Zweck von Embeddings erklären.

---

# 🔥 DAY 9 — PERMISSIONS BASICS DAY

## 1 — chmod

- **Theory:** Read, Write, Execute und symbolische/numerische Notation.
- **Context / Why:** Permissions schützen Dateien und Services.
- **Admin / Professional Extension:** `chmod`, `755`, `644`.
- **Guided Practice:** Permissions in Testverzeichnissen ändern.
- **Independent Challenge:** Passende Rechte für mehrere Dateien festlegen.
- **External Practice:** Linux permissions lab.
- **Verification:** Permission-Bits interpretieren.

## 2 — chown

- **Theory:** Owner und Group Ownership.
- **Context / Why:** Zugriffsrechte hängen von Besitzverhältnissen ab.
- **Admin / Professional Extension:** `chown`, rekursive Ownership.
- **Guided Practice:** Testdateien unterschiedlichen Usern/Groups zuordnen.
- **Independent Challenge:** Ownership-Problem diagnostizieren.
- **External Practice:** Ownership exercise.
- **Verification:** Owner und Group erklären.

## 3 — Groups

- **Theory:** Primary und Secondary Groups.
- **Context / Why:** Gruppen ermöglichen skalierbare Rechteverwaltung.
- **Admin / Professional Extension:** `id`, `groups`, `/etc/group`.
- **Guided Practice:** Gruppen eines Users untersuchen.
- **Independent Challenge:** Zugriff über Gruppenmitgliedschaft modellieren.
- **External Practice:** Linux user/group lab.
- **Verification:** Primary und Secondary Group unterscheiden.

## 4 — umask

- **Theory:** Default Permission Mask.
- **Context / Why:** Neue Dateien sollen automatisch mit sicheren Standardrechten entstehen.
- **Admin / Professional Extension:** `umask`.
- **Guided Practice:** Unterschiedliche umask-Werte untersuchen.
- **Independent Challenge:** Sicheren Default für Dateien und Verzeichnisse bestimmen.
- **External Practice:** umask exercise.
- **Verification:** Wirkung von umask erklären.

## 5 — Python: Dictionaries

- **Theory:** Key-Value-Strukturen.
- **Context / Why:** Systemdaten werden häufig strukturiert als Schlüssel-Werte gespeichert.
- **Admin / Professional Extension:** Konfigurations- und Systemdaten modellieren.
- **Guided Practice:** Dictionary erstellen und verändern.
- **Independent Challenge:** Systeminformationen als Dictionary darstellen.
- **External Practice:** Python dictionaries lab.
- **Verification:** Dictionary und Liste unterscheiden.

## 6 — Git: Stash

- **Theory:** Temporäres Sichern nicht committeter Änderungen.
- **Context / Why:** Arbeit kann unterbrochen werden, ohne unfertige Änderungen zu committen.
- **Admin / Professional Extension:** `git stash`, `pop`, `list`.
- **Guided Practice:** Änderungen stashen und wiederherstellen.
- **Independent Challenge:** Workflow mit Branchwechsel und Stash durchführen.
- **External Practice:** Git stash exercise.
- **Verification:** Sinn und Grenzen von Stash erklären.

## 7 — Docker: Logs

- **Theory:** Container stdout/stderr und Logs.
- **Context / Why:** Containerdiagnose benötigt nachvollziehbare Laufzeitinformationen.
- **Admin / Professional Extension:** `docker logs`.
- **Guided Practice:** Containerlogs untersuchen.
- **Independent Challenge:** Fehler anhand eines Logs lokalisieren.
- **External Practice:** Docker logging lab.
- **Verification:** Containerlogs korrekt interpretieren.

## 8 — Kubernetes: Namespaces

- **Theory:** Kubernetes Namespaces und logische Isolation.
- **Context / Why:** Ressourcen müssen in größeren Clustern organisiert werden.
- **Admin / Professional Extension:** `kubectl get ns`, Kontext und Ressourcenbereiche.
- **Guided Practice:** Ressourcen in mehreren Namespaces untersuchen.
- **Independent Challenge:** Sinnvolle Namespace-Struktur für ein Szenario entwerfen.
- **External Practice:** Kubernetes namespaces lab.
- **Verification:** Namespace-Zweck erklären.

## 9 — AI: Text Generation

- **Theory:** Generative Modelle und probabilistische Ausgabe.
- **Context / Why:** Textgenerierung ist eine zentrale LLM-Funktion.
- **Admin / Professional Extension:** Promptsteuerung und Output-Kontrolle.
- **Guided Practice:** Unterschiedliche Generierungsaufgaben testen.
- **Independent Challenge:** Generierte Antworten auf Konsistenz und Halluzination prüfen.
- **External Practice:** Text-generation exercise.
- **Verification:** Generation und Classification unterscheiden.

---

# 🔥 DAY 10 — PROCESSES & SYSTEMD ADVANCED DAY

## 1 — systemd

- **Theory:** systemd als Init- und Service-Manager.
- **Context / Why:** systemd steuert große Teile des Linux-Systemstarts und Servicebetriebs.
- **Admin / Professional Extension:** Manager, Units und Targets.
- **Guided Practice:** systemd-Units untersuchen.
- **Independent Challenge:** Zusammenhang zwischen Boot und Services erklären.
- **External Practice:** systemd architecture lab.
- **Verification:** Rolle von systemd erklären.

## 2 — Services

- **Theory:** Service-Lifecycle.
- **Context / Why:** Services müssen starten, stoppen, aktiviert und überwacht werden.
- **Admin / Professional Extension:** `enable`, `disable`, `start`, `restart`.
- **Guided Practice:** Testservice verwalten.
- **Independent Challenge:** Boot-Aktivierung eines Services analysieren.
- **External Practice:** service-management exercise.
- **Verification:** Runtime- und Boot-Aktivierung unterscheiden.

## 3 — Logs

- **Theory:** Journal und Syslog.
- **Context / Why:** Logs liefern Beweise für Systemzustände und Fehler.
- **Admin / Professional Extension:** Journalfilter und klassische Logs.
- **Guided Practice:** Logs nach Zeit und Service filtern.
- **Independent Challenge:** Einen Fehler aus mehreren Logquellen rekonstruieren.
- **External Practice:** Linux logging lab.
- **Verification:** Relevante Logs gezielt finden.

## 4 — Timers

- **Theory:** systemd timers und zeitgesteuerte Tasks.
- **Context / Why:** Automatische Wartungsaufgaben benötigen Scheduling.
- **Admin / Professional Extension:** Timer Units.
- **Guided Practice:** Einen einfachen Timer untersuchen.
- **Independent Challenge:** Automatische Wartungsaufgabe modellieren.
- **External Practice:** systemd timer exercise.
- **Verification:** Timer und Service zusammen erklären.

## 5 — Python: JSON

- **Theory:** JSON-Struktur, Objekte, Arrays und Datentypen.
- **Context / Why:** APIs und Konfigurationssysteme verwenden häufig JSON.
- **Admin / Professional Extension:** JSON mit Python verarbeiten.
- **Guided Practice:** JSON laden, verändern und speichern.
- **Independent Challenge:** API-ähnliche Daten automatisiert auswerten.
- **External Practice:** Python JSON lab.
- **Verification:** JSON und Python-Dictionary zuordnen.

## 6 — Git: Cherry-pick

- **Theory:** Einzelnen Commit übernehmen.
- **Context / Why:** Bestimmte Änderungen müssen manchmal unabhängig übernommen werden.
- **Admin / Professional Extension:** Cherry-pick und Konflikte.
- **Guided Practice:** Commit in anderen Branch übernehmen.
- **Independent Challenge:** Gezielt nur eine Änderung übertragen.
- **External Practice:** Git cherry-pick exercise.
- **Verification:** Cherry-pick und Merge unterscheiden.

## 7 — Docker: Multi-stage Builds

- **Theory:** Mehrstufige Image-Builds.
- **Context / Why:** Produktionsimages sollen klein und sicher sein.
- **Admin / Professional Extension:** Build- und Runtime-Stage trennen.
- **Guided Practice:** Einfachen Multi-stage-Build untersuchen.
- **Independent Challenge:** Image-Größe durch Multi-stage verbessern.
- **External Practice:** Docker build optimization lab.
- **Verification:** Zweck von Multi-stage Builds erklären.

## 8 — Kubernetes: Ingress

- **Theory:** Ingress und HTTP Routing.
- **Context / Why:** Externe HTTP-Kommunikation muss kontrolliert auf Services geleitet werden.
- **Admin / Professional Extension:** Host-/Path-Routing.
- **Guided Practice:** Einfachen Ingress analysieren.
- **Independent Challenge:** Routing für zwei Services entwerfen.
- **External Practice:** Kubernetes ingress lab.
- **Verification:** Ingress und Service unterscheiden.

## 9 — AI: RAG Basics

- **Theory:** Retrieval, Context und Generation.
- **Context / Why:** RAG verbindet LLMs mit externem Wissen.
- **Admin / Professional Extension:** Dokumente → Embeddings → Retrieval → Prompt.
- **Guided Practice:** Einfachen RAG-Ablauf konzeptionell nachvollziehen.
- **Independent Challenge:** RAG und reines LLM erklären und vergleichen.
- **External Practice:** RAG fundamentals exercise.
- **Verification:** Die vier grundlegenden RAG-Schritte erklären.

---

# 🔥 DAY 11 — BOOT PROCESS DAY

## 1 — POST

- **Theory:** Power-On Self-Test und Hardwareinitialisierung.
- **Context / Why:** POST prüft grundlegende Hardware vor dem OS-Start.
- **Admin / Professional Extension:** Hardwarefehler und Firmwaremeldungen.
- **Guided Practice:** POST-Phase konzeptionell nachvollziehen.
- **Independent Challenge:** Bootprobleme vor dem Bootloader einordnen.
- **External Practice:** Boot-process exercise.
- **Verification:** POST erklären.

## 2 — BIOS/UEFI → Bootloader

- **Theory:** Firmware übergibt Kontrolle an Bootloader.
- **Context / Why:** Diese Übergabe verbindet Hardwareinitialisierung und OS-Start.
- **Admin / Professional Extension:** EFI System Partition.
- **Guided Practice:** Boot Chain analysieren.
- **Independent Challenge:** BIOS/UEFI und Bootloader voneinander abgrenzen.
- **External Practice:** Linux boot lab.
- **Verification:** Boot Chain korrekt beschreiben.

## 3 — GRUB

- **Theory:** GRUB als Linux-Bootloader.
- **Context / Why:** GRUB lädt Kernel und kann Bootoptionen beeinflussen.
- **Admin / Professional Extension:** GRUB-Konfiguration und Kernelparameter.
- **Guided Practice:** GRUB-Menü und Einträge untersuchen.
- **Independent Challenge:** Zweck eines Kernelparameters erklären.
- **External Practice:** GRUB exercise.
- **Verification:** Rolle von GRUB erklären.

## 4 — Kernel Loading

- **Theory:** Kernel, initramfs und Root Filesystem.
- **Context / Why:** Der Kernel muss Hardware und frühen Userspace initialisieren.
- **Admin / Professional Extension:** initramfs und frühe Bootdiagnose.
- **Guided Practice:** Bootprozess konzeptionell verfolgen.
- **Independent Challenge:** Von GRUB bis systemd erklären.
- **External Practice:** Linux boot troubleshooting lab.
- **Verification:** Kernel Loading erklären.

## 5 — Python: try/except

- **Theory:** Exception Handling und Fehlerpfade.
- **Context / Why:** Robuste Automation darf bei erwartbaren Fehlern nicht unkontrolliert abbrechen.
- **Admin / Professional Extension:** Datei-, Netzwerk- und Prozessfehler.
- **Guided Practice:** Mehrere Exception-Typen behandeln.
- **Independent Challenge:** Fehlerbehandlung für ein Systemskript entwickeln.
- **External Practice:** Python exception lab.
- **Verification:** Exception Flow erklären.

## 6 — Git: Revert

- **Theory:** Commit rückgängig machen ohne Historie zu löschen.
- **Context / Why:** Fehlerhafte Änderungen müssen sicher zurückgenommen werden.
- **Admin / Professional Extension:** `git revert`.
- **Guided Practice:** Änderung committen und revertieren.
- **Independent Challenge:** Revert gegenüber Reset erklären.
- **External Practice:** Git revert exercise.
- **Verification:** Revert und Reset unterscheiden.

## 7 — Docker: ENTRYPOINT vs CMD

- **Theory:** Container Start Command und Argumente.
- **Context / Why:** Falsche Command-Konfiguration kann Container unbrauchbar machen.
- **Admin / Professional Extension:** `ENTRYPOINT`, `CMD`, Override-Verhalten.
- **Guided Practice:** Beide Varianten testen.
- **Independent Challenge:** Geeignete Kombination für eine Anwendung wählen.
- **External Practice:** Docker command configuration lab.
- **Verification:** ENTRYPOINT und CMD erklären.

## 8 — Kubernetes: Readiness Probes

- **Theory:** Readiness und Traffic-Zulassung.
- **Context / Why:** Ein gestarteter Container ist nicht zwangsläufig bereit für Traffic.
- **Admin / Professional Extension:** Readiness vs Liveness.
- **Guided Practice:** Readiness Probe untersuchen.
- **Independent Challenge:** Unterschiedliches Fehlverhalten von Readiness und Liveness analysieren.
- **External Practice:** Kubernetes probes lab.
- **Verification:** Readiness und Liveness unterscheiden.

## 9 — AI: Prompt Structure

- **Theory:** Rolle, Aufgabe, Kontext, Einschränkungen und Ausgabeformat.
- **Context / Why:** Strukturierte Prompts erhöhen Zuverlässigkeit.
- **Admin / Professional Extension:** Technische Prompts für Diagnoseaufgaben.
- **Guided Practice:** Prompt in strukturierte Bestandteile zerlegen.
- **Independent Challenge:** Einen unklaren technischen Prompt verbessern.
- **External Practice:** Prompt-engineering exercise.
- **Verification:** Promptbestandteile erklären.

---

# 🔥 DAY 12 — KERNEL DEEP DAY

## 1 — Monolithic vs Microkernel

- **Theory:** Kernel-Architekturen und ihre Trade-offs.
- **Context / Why:** Architektur beeinflusst Performance, Isolation und Wartbarkeit.
- **Admin / Professional Extension:** Linux als überwiegend monolithischer Kernel mit modularen Komponenten.
- **Guided Practice:** Architekturen vergleichen.
- **Independent Challenge:** Vor- und Nachteile erklären.
- **External Practice:** OS architecture exercise.
- **Verification:** Beide Modelle unterscheiden.

## 2 — Kernel Modules

- **Theory:** Loadable Kernel Modules.
- **Context / Why:** Hardware- und Funktionserweiterungen können dynamisch geladen werden.
- **Admin / Professional Extension:** `lsmod`, `modinfo`.
- **Guided Practice:** Geladene Module untersuchen.
- **Independent Challenge:** Funktion eines Moduls identifizieren.
- **External Practice:** Linux kernel modules lab.
- **Verification:** Kernelmodul erklären.

## 3 — Interrupts

- **Theory:** Hardware Interrupts und Interrupt Handling.
- **Context / Why:** Hardware muss dem Kernel Ereignisse signalisieren können.
- **Admin / Professional Extension:** Interrupts und Performance.
- **Guided Practice:** Interruptinformationen untersuchen.
- **Independent Challenge:** Interrupt-basierten I/O-Ablauf erklären.
- **External Practice:** OS interrupt exercise.
- **Verification:** Zweck eines Interrupts erklären.

## 4 — Syscalls

- **Theory:** System Calls und User-/Kernel-Space-Grenze.
- **Context / Why:** Anwendungen benötigen kontrollierten Zugriff auf Kernel-Funktionen.
- **Admin / Professional Extension:** `strace`.
- **Guided Practice:** Ein Programm mit `strace` untersuchen.
- **Independent Challenge:** Einige System Calls identifizieren und erklären.
- **External Practice:** Linux syscall lab.
- **Verification:** System Call erklären.

## 5 — Python: Modules Import

- **Theory:** Importmechanismus, Module Search Path und Namespaces.
- **Context / Why:** Saubere Modulstruktur verhindert unübersichtlichen Code.
- **Admin / Professional Extension:** `sys.path`.
- **Guided Practice:** Importverhalten untersuchen.
- **Independent Challenge:** Eigenes Package strukturiert importieren.
- **External Practice:** Python import exercise.
- **Verification:** Importauflösung erklären.

## 6 — Git: diff

- **Theory:** Unterschiede zwischen Working Tree, Staging und Commits.
- **Context / Why:** Vor einem Commit müssen Änderungen kontrolliert geprüft werden.
- **Admin / Professional Extension:** `git diff`, `git diff --staged`.
- **Guided Practice:** Änderungen vergleichen.
- **Independent Challenge:** Einen unerwarteten Unterschied lokalisieren.
- **External Practice:** Git diff lab.
- **Verification:** Beide diff-Varianten erklären.

## 7 — Docker: Layers

- **Theory:** Image Layers und Build Cache.
- **Context / Why:** Layer beeinflussen Buildzeit, Speicher und Deployment.
- **Admin / Professional Extension:** Layer-Reihenfolge optimieren.
- **Guided Practice:** Image-Layer untersuchen.
- **Independent Challenge:** Dockerfile hinsichtlich Cache-Nutzung optimieren.
- **External Practice:** Docker layers lab.
- **Verification:** Layer-Prinzip erklären.

## 8 — Kubernetes: DaemonSets

- **Theory:** DaemonSet und Node-bezogene Pods.
- **Context / Why:** Bestimmte Dienste müssen auf jedem oder ausgewählten Nodes laufen.
- **Admin / Professional Extension:** Logging- und Monitoring-Agenten.
- **Guided Practice:** DaemonSet untersuchen.
- **Independent Challenge:** Einsatzszenario entwickeln.
- **External Practice:** Kubernetes DaemonSet lab.
- **Verification:** Deployment und DaemonSet unterscheiden.

## 9 — AI: Embeddings → Meaning

- **Theory:** Semantische Repräsentation und Distanz.
- **Context / Why:** Bedeutung kann für Suche und Retrieval mathematisch vergleichbar gemacht werden.
- **Admin / Professional Extension:** Similarity Search.
- **Guided Practice:** Ähnliche und unähnliche Texte vergleichen.
- **Independent Challenge:** Grenzen semantischer Ähnlichkeit analysieren.
- **External Practice:** Embedding similarity exercise.
- **Verification:** Embedding-Distanz konzeptionell erklären.

---

# 🔥 DAY 13 — MEMORY MANAGEMENT DAY

## 1 — RAM Allocation

- **Theory:** Speicherzuweisung für Prozesse.
- **Context / Why:** Prozesse benötigen kontrollierten virtuellen Speicher.
- **Admin / Professional Extension:** Virtueller Adressraum und Memory Monitoring.
- **Guided Practice:** Prozessspeicher beobachten.
- **Independent Challenge:** Memory Usage mehrerer Prozesse vergleichen.
- **External Practice:** Linux memory lab.
- **Verification:** Prozessspeicher erklären.

## 2 — Swap

- **Theory:** Swap und Auslagerung.
- **Context / Why:** Swap kann bei Speicherdruck zusätzlichen virtuellen Speicher bereitstellen.
- **Admin / Professional Extension:** `swapon`, `swapoff`, `free`.
- **Guided Practice:** Swap-Zustand untersuchen.
- **Independent Challenge:** Auswirkungen von hohem Swap-Verbrauch erklären.
- **External Practice:** Linux swap exercise.
- **Verification:** RAM und Swap unterscheiden.

## 3 — Buffers / Cache

- **Theory:** Page Cache, Buffers und verfügbare Speicherkapazität.
- **Context / Why:** Linux nutzt RAM aktiv zur Beschleunigung von I/O.
- **Admin / Professional Extension:** `free`, `/proc/meminfo`.
- **Guided Practice:** Cache-Werte beobachten.
- **Independent Challenge:** Erklären, warum hoher Cache-Verbrauch nicht automatisch ein Problem bedeutet.
- **External Practice:** Linux memory-cache lab.
- **Verification:** Cache und tatsächlich belegten Speicher unterscheiden.

## 4 — `/proc/meminfo`

- **Theory:** Kernel-exportierte Memory-Informationen.
- **Context / Why:** `/proc` bietet detaillierte Laufzeitinformationen.
- **Admin / Professional Extension:** relevante Felder analysieren.
- **Guided Practice:** `/proc/meminfo` untersuchen.
- **Independent Challenge:** Memory-Zustand aus `/proc/meminfo` ableiten.
- **External Practice:** `/proc` analysis exercise.
- **Verification:** Wichtige Memory-Felder erklären.

## 5 — Python: Lists

- **Theory:** Listen, Indexierung und Iteration.
- **Context / Why:** Listen eignen sich für geordnete Mengen von Systemobjekten.
- **Admin / Professional Extension:** Prozesse oder Dateien als Listen verarbeiten.
- **Guided Practice:** Listen erstellen und durchlaufen.
- **Independent Challenge:** Eine Liste von Systemobjekten filtern.
- **External Practice:** Python list exercise.
- **Verification:** Liste korrekt verwenden.

## 6 — Git: reset soft/hard

- **Theory:** HEAD, Index und Working Tree.
- **Context / Why:** Git-Zustände müssen gezielt korrigiert werden können.
- **Admin / Professional Extension:** `reset --soft` vs `--hard`.
- **Guided Practice:** In Testrepository verschiedene Resets durchführen.
- **Independent Challenge:** Auswirkungen auf Working Tree und Staging erklären.
- **External Practice:** Git reset lab.
- **Verification:** Soft und Hard Reset unterscheiden.

## 7 — Docker: Memory Limits

- **Theory:** Container Memory Constraints.
- **Context / Why:** Ein einzelner Container darf einen Host nicht unkontrolliert belasten.
- **Admin / Professional Extension:** Memory Limits und OOM-Verhalten.
- **Guided Practice:** Memory Limit setzen.
- **Independent Challenge:** Verhalten bei Überschreitung analysieren.
- **External Practice:** Docker resource-limit lab.
- **Verification:** Zweck von Memory Limits erklären.

## 8 — Kubernetes: Resource Limits

- **Theory:** Requests und Limits.
- **Context / Why:** Kubernetes benötigt Ressourceninformationen für Scheduling und Stabilität.
- **Admin / Professional Extension:** CPU/Memory Requests und Limits.
- **Guided Practice:** Resource-Konfiguration untersuchen.
- **Independent Challenge:** Sinnvolle Werte für eine Anwendung bestimmen.
- **External Practice:** Kubernetes resource lab.
- **Verification:** Requests und Limits unterscheiden.

## 9 — AI: Token Limits

- **Theory:** Context Window und Token Limits.
- **Context / Why:** Zu große Eingaben können Modelle und APIs begrenzen.
- **Admin / Professional Extension:** Prompt-/Context-Optimierung.
- **Guided Practice:** Kurze und lange Eingaben vergleichen.
- **Independent Challenge:** Technische Dokumentation für begrenzten Kontext aufteilen.
- **External Practice:** Token-limit exercise.
- **Verification:** Context Window erklären.

---

# 🔥 DAY 14 — CPU SCHEDULING DAY

## 1 — Scheduler

- **Theory:** CPU Scheduler, Runnable Tasks und Scheduling.
- **Context / Why:** Viele Prozesse konkurrieren um begrenzte CPU-Zeit.
- **Admin / Professional Extension:** Scheduling-Verhalten beobachten.
- **Guided Practice:** CPU-intensive Prozesse untersuchen.
- **Independent Challenge:** Scheduling unter Last erklären.
- **External Practice:** Linux scheduler lab.
- **Verification:** Grundprinzip des Schedulers erklären.

## 2 — nice / renice

- **Theory:** Process Priority und Nice Value.
- **Context / Why:** CPU-intensive Prozesse können priorisiert oder zurückgestellt werden.
- **Admin / Professional Extension:** `nice`, `renice`.
- **Guided Practice:** Priorität eines Testprozesses verändern.
- **Independent Challenge:** Auswirkungen auf CPU-Zeit beobachten.
- **External Practice:** Linux priority exercise.
- **Verification:** Nice Value erklären.

## 3 — Load Average

- **Theory:** Load Average und Runnable/Waiting Tasks.
- **Context / Why:** Load ist ein wichtiger Indikator für Systemauslastung.
- **Admin / Professional Extension:** `uptime`, `top`.
- **Guided Practice:** Load Average beobachten.
- **Independent Challenge:** Load im Verhältnis zu CPU-Anzahl interpretieren.
- **External Practice:** Linux performance lab.
- **Verification:** Load Average korrekt interpretieren.

## 4 — top/htop Deep

- **Theory:** CPU-, Memory- und Prozessmetriken.
- **Context / Why:** Live-Diagnose benötigt mehrere korrelierte Kennzahlen.
- **Admin / Professional Extension:** Sortieren, Prozessauswahl und Diagnose.
- **Guided Practice:** System unter Last untersuchen.
- **Independent Challenge:** Ursache eines simulierten Performanceproblems finden.
- **External Practice:** Monitoring challenge.
- **Verification:** Performanceproblem mit `top`/`htop` eingrenzen.

## 5 — Python: Nested Dictionaries

- **Theory:** Verschachtelte Datenstrukturen.
- **Context / Why:** API- und Systemdaten sind oft hierarchisch strukturiert.
- **Admin / Professional Extension:** Strukturierte technische Informationen.
- **Guided Practice:** Nested Dictionary erstellen und auslesen.
- **Independent Challenge:** Komplexe Systemdaten modellieren.
- **External Practice:** Python data structures exercise.
- **Verification:** Verschachtelte Daten korrekt verarbeiten.

## 6 — Git: Squash

- **Theory:** Mehrere Commits zu einem logischen Commit zusammenführen.
- **Context / Why:** Saubere Historien verbessern Nachvollziehbarkeit.
- **Admin / Professional Extension:** Interactive Rebase.
- **Guided Practice:** Mehrere Testcommits squashen.
- **Independent Challenge:** Unordentliche Historie in sinnvolle Commits überführen.
- **External Practice:** Git history exercise.
- **Verification:** Squashing erklären.

## 7 — Docker: CPU Limits

- **Theory:** CPU Constraints und Scheduling.
- **Context / Why:** Container müssen Ressourcen fair nutzen.
- **Admin / Professional Extension:** CPU Quotas.
- **Guided Practice:** CPU Limit setzen und beobachten.
- **Independent Challenge:** Verhalten unter CPU-Last analysieren.
- **External Practice:** Docker CPU lab.
- **Verification:** CPU Limit erklären.

## 8 — Kubernetes: HPA

- **Theory:** Horizontal Pod Autoscaler.
- **Context / Why:** Workloads können automatisch auf Last reagieren.
- **Admin / Professional Extension:** Metrics und Resource Requests.
- **Guided Practice:** HPA-Konfiguration untersuchen.
- **Independent Challenge:** Skalierungsstrategie für einen Service entwerfen.
- **External Practice:** Kubernetes HPA challenge.
- **Verification:** HPA-Ablauf erklären.

## 9 — AI: Model Latency

- **Theory:** Inference Latency und Antwortzeit.
- **Context / Why:** AI-Systeme müssen auch hinsichtlich Performance bewertet werden.
- **Admin / Professional Extension:** Inputgröße, Modellgröße und API-Latenz.
- **Guided Practice:** Antwortzeiten verschiedener Anfragen vergleichen.
- **Independent Challenge:** Ursachen hoher Latenz identifizieren.
- **External Practice:** AI performance exercise.
- **Verification:** Latency und Throughput unterscheiden.

---

# 🔥 DAY 15 — STORAGE DEEP DAY

## 1 — `/dev/sda`, `/dev/nvme`

- **Theory:** Block Devices, Gerätedateien und Linux Device Naming.
- **Context / Why:** Administratoren müssen Storage-Geräte eindeutig identifizieren können.
- **Admin / Professional Extension:** `/dev`, `lsblk`, `blkid`, NVMe-Namensschema.
- **Guided Practice:** Mit `lsblk` und `blkid` Geräte untersuchen.
- **Independent Challenge:** Unbekannten Storage-Aufbau dokumentieren.
- **External Practice:** Linux storage/block-device lab.
- **Verification:** `sda`, `nvme0n1`, Partition und Filesystem unterscheiden.

## 2 — Partitions

- **Theory:** Partitionen, Partition Tables und GPT.
- **Context / Why:** Partitionierung strukturiert Datenträger für Betriebssystem und Daten.
- **Admin / Professional Extension:** `fdisk`, `parted`, GPT.
- **Guided Practice:** Partitionierung mit `lsblk` und `fdisk -l` analysieren.
- **Independent Challenge:** Partitionierungsaufbau erklären.
- **External Practice:** Linux partitioning exercise.
- **Verification:** GPT, Partition, Filesystem und Mountpoint unterscheiden.

## 3 — ext4 vs XFS

- **Theory:** Filesystem, Journaling, ext4 und XFS.
- **Context / Why:** Filesystemwahl beeinflusst Performance, Administration und Recovery.
- **Admin / Professional Extension:** `lsblk -f`, `df -T`.
- **Guided Practice:** Vorhandene Filesysteme identifizieren.
- **Independent Challenge:** Filesystem für mehrere Serverrollen auswählen.
- **External Practice:** Linux filesystem comparison lab.
- **Verification:** ext4 und XFS vergleichen.

## 4 — mount / umount

- **Theory:** Mountpoint und Einbindung eines Filesystems.
- **Context / Why:** Linux stellt Filesysteme über den Verzeichnisbaum bereit.
- **Admin / Professional Extension:** `mount`, `umount`, `findmnt`, `/etc/fstab`.
- **Guided Practice:** Testfilesystem mounten und wieder aushängen.
- **Independent Challenge:** Bestehenden Mount-Aufbau analysieren.
- **External Practice:** Linux mount lab.
- **Verification:** Device, Filesystem und Mountpoint verbinden.

## 5 — Python: File Read/Write

- **Theory:** File I/O, Context Manager und Fehlerbehandlung.
- **Context / Why:** Automation verarbeitet Konfigurations- und Logdateien.
- **Admin / Professional Extension:** Sichere und reproduzierbare File-Operationen.
- **Guided Practice:** Dateien lesen und schreiben.
- **Independent Challenge:** Logdatei analysieren und Ergebnis speichern.
- **External Practice:** Python file-I/O lab.
- **Verification:** File-I/O und Context Manager erklären.

## 6 — Git: Remote Branches

- **Theory:** Remote Tracking Branches und Synchronisation.
- **Context / Why:** Mehrere Entwickler arbeiten mit einem gemeinsamen Remote-Zustand.
- **Admin / Professional Extension:** `fetch`, Remote Branches und Tracking.
- **Guided Practice:** Remote Branches untersuchen.
- **Independent Challenge:** Lokalen Branch mit Remote synchronisieren.
- **External Practice:** Git remote exercise.
- **Verification:** Local Branch und Remote Tracking Branch unterscheiden.

## 7 — Docker: Bind Mounts

- **Theory:** Host Path und Container Mount.
- **Context / Why:** Daten und Konfiguration können direkt zwischen Host und Container geteilt werden.
- **Admin / Professional Extension:** Persistence und Security.
- **Guided Practice:** Bind Mount erstellen.
- **Independent Challenge:** Geeigneten Mount für einen Service bestimmen.
- **External Practice:** Docker bind-mount lab.
- **Verification:** Volume und Bind Mount unterscheiden.

## 8 — Kubernetes: PV/PVC

- **Theory:** PersistentVolume und PersistentVolumeClaim.
- **Context / Why:** Kubernetes-Anwendungen benötigen persistenten Storage.
- **Admin / Professional Extension:** Storage Abstraction.
- **Guided Practice:** PVC und Storage-Anforderung analysieren.
- **Independent Challenge:** Persistent Storage für einen Service modellieren.
- **External Practice:** Kubernetes storage lab.
- **Verification:** PV und PVC erklären.

## 9 — AI: Dataset Basics

- **Theory:** Dataset, Samples, Features und Labels.
- **Context / Why:** Daten bilden die Grundlage von ML-Systemen.
- **Admin / Professional Extension:** Data Quality.
- **Guided Practice:** Kleines Dataset untersuchen.
- **Independent Challenge:** Datenprobleme und mögliche Bias-Quellen identifizieren.
- **External Practice:** Dataset fundamentals exercise.
- **Verification:** Sample, Feature und Label unterscheiden.

---

# 🔥 DAY 16 — FILE SYSTEM PERMISSIONS DAY

## 1 — chmod Deep

- **Theory:** Symbolische/numerische Permissions und rekursive Änderungen.
- **Context / Why:** Fehlerhafte Permissions können Sicherheitsprobleme verursachen.
- **Admin / Professional Extension:** `chmod`, `755`, `644`, rekursive Anwendung.
- **Guided Practice:** Permissions in Teststruktur verändern.
- **Independent Challenge:** Sichere Permission-Struktur erstellen.
- **External Practice:** Linux permission challenge.
- **Verification:** Permission-Maske sicher lesen und setzen.

## 2 — chown Deep

- **Theory:** Ownership und rekursive Änderungen.
- **Context / Why:** Dienste müssen auf Daten zugreifen können, ohne unnötige Rechte zu besitzen.
- **Admin / Professional Extension:** `chown`, Ownership Security.
- **Guided Practice:** Testdateien Usern/Groups zuordnen.
- **Independent Challenge:** Ownership-Problem eines Serviceverzeichnisses lösen.
- **External Practice:** Ownership lab.
- **Verification:** Sicherheitsauswirkungen falscher Ownership erklären.

## 3 — Sticky Bit

- **Theory:** Sticky Bit und gemeinschaftlich beschreibbare Verzeichnisse.
- **Context / Why:** Gemeinsame Verzeichnisse benötigen kontrolliertes Löschen.
- **Admin / Professional Extension:** `/tmp`, `chmod +t`.
- **Guided Practice:** Sticky Bit untersuchen.
- **Independent Challenge:** Verhalten mehrerer Benutzer in Shared Directory analysieren.
- **External Practice:** Special-permissions lab.
- **Verification:** Sticky Bit erklären.

## 4 — setuid / setgid

- **Theory:** Special Permission Bits und privilegierte Ausführung.
- **Context / Why:** Special Bits können Prozesse mit erweiterten Rechten ausführen.
- **Admin / Professional Extension:** `find` zur Suche nach Special Permissions.
- **Guided Practice:** Special Bits auf Testsystemen untersuchen.
- **Independent Challenge:** Sicherheitsrisiken analysieren.
- **External Practice:** Linux special-permissions exercise.
- **Verification:** setuid und setgid unterscheiden.

## 5 — Python: Classes Deep

- **Theory:** Inheritance, Composition und Encapsulation.
- **Context / Why:** Komplexe Automation benötigt strukturierte Modelle.
- **Admin / Professional Extension:** Admin-Objekte modellieren.
- **Guided Practice:** Klassenhierarchie erstellen.
- **Independent Challenge:** Systemressourcen objektorientiert modellieren.
- **External Practice:** Python OOP lab.
- **Verification:** Inheritance und Composition unterscheiden.

## 6 — Git: Conflict Resolution

- **Theory:** Merge Conflicts und Conflict Markers.
- **Context / Why:** Parallele Änderungen können dieselben Codebereiche betreffen.
- **Admin / Professional Extension:** Konflikte kontrolliert lösen.
- **Guided Practice:** Konflikt erzeugen, analysieren und lösen.
- **Independent Challenge:** Konflikt ohne Schritt-für-Schritt-Anleitung lösen.
- **External Practice:** Git conflict lab.
- **Verification:** Konfliktursache und Lösung erklären.

## 7 — Docker: Security Context

- **Theory:** Container User, Root und Capabilities.
- **Context / Why:** Container sollten möglichst mit minimalen Privilegien laufen.
- **Admin / Professional Extension:** Non-root Containers.
- **Guided Practice:** Container als Non-root User ausführen.
- **Independent Challenge:** Security-Verbesserungen für einen Container identifizieren.
- **External Practice:** Container security lab.
- **Verification:** Root und Non-root Container vergleichen.

## 8 — Kubernetes: RBAC Basics

- **Theory:** Role, RoleBinding und ServiceAccount.
- **Context / Why:** Clusterzugriff muss nach Least Privilege geregelt werden.
- **Admin / Professional Extension:** Kubernetes RBAC.
- **Guided Practice:** Einfache Role und RoleBinding analysieren.
- **Independent Challenge:** Minimal erforderliche Rechte modellieren.
- **External Practice:** Kubernetes RBAC lab.
- **Verification:** Role und RoleBinding erklären.

## 9 — AI: Access Control

- **Theory:** Benutzer, Rollen, Datenzugriff und API-Berechtigungen.
- **Context / Why:** AI-Systeme können sensible Informationen verarbeiten.
- **Admin / Professional Extension:** Least Privilege und Zugriffstrennung.
- **Guided Practice:** Zugriffsszenario analysieren.
- **Independent Challenge:** Sichere Rechteverteilung für ein AI-System entwerfen.
- **External Practice:** AI security exercise.
- **Verification:** Authentication und Authorization unterscheiden.

---

# 🔥 DAY 17 — LOGS DAY

## 1 — journalctl Filters

- **Theory:** Zeit-, Service- und Severity-Filter.
- **Context / Why:** Große Logs müssen gezielt eingeschränkt werden.
- **Admin / Professional Extension:** `-u`, `-b`, `--since`, `-p`.
- **Guided Practice:** Service-Logs gezielt filtern.
- **Independent Challenge:** Fehlerzeitraum und Ursache bestimmen.
- **External Practice:** journalctl challenge.
- **Verification:** Relevante Filter selbstständig einsetzen.

## 2 — syslog

- **Theory:** Syslog, Facilities und Severity.
- **Context / Why:** Klassische Linux-Systeme verwenden weiterhin Syslog-basierte Logging-Architekturen.
- **Admin / Professional Extension:** Syslog-Dateien und rsyslog.
- **Guided Practice:** Syslog-Aufbau untersuchen.
- **Independent Challenge:** Facility und Severity eines Logeintrags erklären.
- **External Practice:** Syslog lab.
- **Verification:** Syslog-Grundprinzip erklären.

## 3 — `/var/log`

- **Theory:** System-, Authentication- und Application Logs.
- **Context / Why:** `/var/log` enthält wichtige Diagnoseinformationen.
- **Admin / Professional Extension:** Logdateien gezielt analysieren.
- **Guided Practice:** Verschiedene Logs untersuchen.
- **Independent Challenge:** Ursache eines Problems aus Logdateien bestimmen.
- **External Practice:** Linux log-analysis exercise.
- **Verification:** Typische Logquellen nennen.

## 4 — logrotate

- **Theory:** Rotation, Retention und Compression.
- **Context / Why:** Logs können Datenträger schnell füllen.
- **Admin / Professional Extension:** logrotate-Konfiguration.
- **Guided Practice:** Rotationseinstellungen untersuchen.
- **Independent Challenge:** Log-Retention für einen Service planen.
- **External Practice:** logrotate lab.
- **Verification:** Logrotation erklären.

## 5 — Python: Logging

- **Theory:** Log Levels, Handlers und Formatters.
- **Context / Why:** Automation muss diagnostizierbare Ausgaben erzeugen.
- **Admin / Professional Extension:** Structured Logging.
- **Guided Practice:** Python-Logging konfigurieren.
- **Independent Challenge:** Automation mit sinnvollen Log Levels entwickeln.
- **External Practice:** Python logging exercise.
- **Verification:** Logging statt `print` erklären.

## 6 — Git: Bisect

- **Theory:** Binary Search in Git History.
- **Context / Why:** Fehlerursachen können über viele Commits verteilt sein.
- **Admin / Professional Extension:** `git bisect`.
- **Guided Practice:** Fehlerhaften Commit finden.
- **Independent Challenge:** Bisect auf Testrepository anwenden.
- **External Practice:** Git bisect lab.
- **Verification:** Bisect-Prinzip erklären.

## 7 — Docker: Logs Deep

- **Theory:** stdout/stderr und Logging Drivers.
- **Context / Why:** Containerdiagnose basiert häufig auf standardisierten Streams.
- **Admin / Professional Extension:** Logging Drivers und Persistenz.
- **Guided Practice:** Containerlogs detailliert untersuchen.
- **Independent Challenge:** Fehler nur anhand von Containerlogs lokalisieren.
- **External Practice:** Docker logging exercise.
- **Verification:** stdout/stderr und Application Logs unterscheiden.

## 8 — Kubernetes: Events

- **Theory:** Kubernetes Events und Cluster-Aktivitäten.
- **Context / Why:** Events liefern Hinweise bei Scheduling- und Runtime-Problemen.
- **Admin / Professional Extension:** `kubectl describe`, Events.
- **Guided Practice:** Events eines Pods untersuchen.
- **Independent Challenge:** Fehler anhand von Events eingrenzen.
- **External Practice:** Kubernetes troubleshooting lab.
- **Verification:** Events sinnvoll zur Diagnose einsetzen.

## 9 — AI: Log Parsing

- **Theory:** Strukturierte Extraktion aus technischen Logs.
- **Context / Why:** AI kann große Logmengen bei Analyse und Klassifikation unterstützen.
- **Admin / Professional Extension:** Log Automation.
- **Guided Practice:** Logeinträge nach Mustern klassifizieren.
- **Independent Challenge:** Fehlerkategorien aus Logdaten ableiten.
- **External Practice:** Log-analysis AI exercise.
- **Verification:** Parsing, Extraction und Classification unterscheiden.

---

# 🔥 DAY 18 — NETWORKING BASICS DAY

## 1 — IP Addressing

- **Theory:** IPv4, IPv6 und Netzwerkadressen.
- **Context / Why:** IP ermöglicht Kommunikation zwischen Systemen.
- **Admin / Professional Extension:** `ip addr`.
- **Guided Practice:** Interfaces und IP-Adressen untersuchen.
- **Independent Challenge:** Netzwerkinterfaces eines Systems dokumentieren.
- **External Practice:** Linux IP lab.
- **Verification:** IP-Adresse und Interface erklären.

## 2 — Netmask / CIDR

- **Theory:** Subnet Mask und CIDR.
- **Context / Why:** CIDR bestimmt Netzwerk- und Hostanteile.
- **Admin / Professional Extension:** `/24`, `/16` und Subnetze.
- **Guided Practice:** CIDR-Netze analysieren.
- **Independent Challenge:** Hosts und Netzwerkbereich bestimmen.
- **External Practice:** Subnetting exercise.
- **Verification:** CIDR korrekt interpretieren.

## 3 — Gateway

- **Theory:** Default Gateway und Routing.
- **Context / Why:** Kommunikation außerhalb des lokalen Netzes benötigt Routing.
- **Admin / Professional Extension:** `ip route`.
- **Guided Practice:** Routing Table untersuchen.
- **Independent Challenge:** Ursache eines fehlenden Gateways diagnostizieren.
- **External Practice:** Linux routing lab.
- **Verification:** Default Route erklären.

## 4 — DNS Resolution

- **Theory:** DNS, Names und IP-Auflösung.
- **Context / Why:** Menschen verwenden Namen, Systeme benötigen IP-Adressen.
- **Admin / Professional Extension:** `/etc/resolv.conf`, `/etc/hosts`, `host`.
- **Guided Practice:** DNS-Auflösung untersuchen.
- **Independent Challenge:** DNS-Problem systematisch diagnostizieren.
- **External Practice:** DNS troubleshooting exercise.
- **Verification:** DNS und Routing unterscheiden.

## 5 — Python: requests

- **Theory:** HTTP Requests und Responses.
- **Context / Why:** Automation kommuniziert häufig mit Web APIs.
- **Admin / Professional Extension:** Status Codes und Timeouts.
- **Guided Practice:** HTTP-Anfrage durchführen.
- **Independent Challenge:** API Response analysieren.
- **External Practice:** Python HTTP lab.
- **Verification:** Request und Response erklären.

## 6 — Git: fetch vs pull

- **Theory:** Remote Synchronization.
- **Context / Why:** Änderungen vom Remote müssen kontrolliert übernommen werden.
- **Admin / Professional Extension:** `fetch` vs `pull`.
- **Guided Practice:** Remote Updates abrufen.
- **Independent Challenge:** Lokalen Branch bewusst synchronisieren.
- **External Practice:** Git remote exercise.
- **Verification:** fetch und pull unterscheiden.

## 7 — Docker: Ports

- **Theory:** Host Ports und Container Ports.
- **Context / Why:** Netzwerkdienste in Containern müssen erreichbar gemacht werden.
- **Admin / Professional Extension:** Port Publishing.
- **Guided Practice:** Containerport veröffentlichen.
- **Independent Challenge:** Ursache eines nicht erreichbaren Services analysieren.
- **External Practice:** Docker networking lab.
- **Verification:** Containerport und Hostport unterscheiden.

## 8 — Kubernetes: Services Deep

- **Theory:** ClusterIP, Selector und Service Discovery.
- **Context / Why:** Pods sind dynamisch und benötigen stabile Abstraktion.
- **Admin / Professional Extension:** Service Types.
- **Guided Practice:** Service und Endpoints untersuchen.
- **Independent Challenge:** Kommunikation zwischen zwei Workloads erklären.
- **External Practice:** Kubernetes service lab.
- **Verification:** Service Discovery erklären.

## 9 — AI: API Calls

- **Theory:** API-basierte Modellkommunikation.
- **Context / Why:** AI-Funktionen werden häufig als Services integriert.
- **Admin / Professional Extension:** Authentication, JSON und Error Handling.
- **Guided Practice:** API Request analysieren.
- **Independent Challenge:** Fehlerhafte API-Anfrage diagnostizieren.
- **External Practice:** AI API exercise.
- **Verification:** AI API Workflow erklären.

---

# 🔥 DAY 19 — UBUNTU CONFIGURATION DAY

## 1 — hostnamectl

- **Theory:** Hostname und Systemidentität.
- **Context / Why:** Server müssen eindeutig identifizierbar sein.
- **Admin / Professional Extension:** `hostnamectl`.
- **Guided Practice:** Hostname untersuchen.
- **Independent Challenge:** Sinnvolle Servernamenskonvention entwickeln.
- **External Practice:** Linux hostname lab.
- **Verification:** Hostname und DNS Name unterscheiden.

## 2 — timedatectl

- **Theory:** Systemzeit, Zeitzone und NTP.
- **Context / Why:** Zeitkorrektheit ist für Logs, Security und verteilte Systeme wichtig.
- **Admin / Professional Extension:** `timedatectl`.
- **Guided Practice:** Zeitzone und Synchronisation untersuchen.
- **Independent Challenge:** Zeitproblem diagnostizieren.
- **External Practice:** Linux time-management exercise.
- **Verification:** Zeitzone und Zeit-Synchronisation erklären.

## 3 — Network Configuration

- **Theory:** Interfaces, IP-Konfiguration und Netplan.
- **Context / Why:** Netzwerk ist zentrale Grundlage von Serverbetrieb.
- **Admin / Professional Extension:** Netplan und `ip`.
- **Guided Practice:** Konfiguration untersuchen.
- **Independent Challenge:** Netzwerkfehler eingrenzen.
- **External Practice:** Ubuntu networking lab.
- **Verification:** Netzwerk-Konfigurationsablauf erklären.

## 4 — apt update/upgrade

- **Theory:** Package Manager, Repository, Paketindex und Updates.
- **Context / Why:** Systeme benötigen kontrollierte Softwareverwaltung und Sicherheitsupdates.
- **Admin / Professional Extension:** `apt update`, `apt upgrade`, `apt install`, `apt remove`.
- **Guided Practice:** Paketindex aktualisieren und Paketinformationen untersuchen.
- **Independent Challenge:** Paketproblem diagnostizieren.
- **External Practice:** Linux package-management lab.
- **Verification:** `update` und `upgrade` unterscheiden.

## 5 — Python: Packages / venv

- **Theory:** Packages, pip und virtuelle Umgebungen.
- **Context / Why:** Abhängigkeiten müssen reproduzierbar isoliert werden.
- **Admin / Professional Extension:** `venv` und Dependency Management.
- **Guided Practice:** Virtuelle Umgebung erstellen.
- **Independent Challenge:** Kleines Projekt mit isolierten Dependencies aufbauen.
- **External Practice:** Python packaging lab.
- **Verification:** Package und Virtual Environment erklären.

## 6 — Git: Tags Deep

- **Theory:** Lightweight und Annotated Tags.
- **Context / Why:** Releases müssen nachvollziehbar markiert werden.
- **Admin / Professional Extension:** Versionierung.
- **Guided Practice:** Beide Tag-Arten vergleichen.
- **Independent Challenge:** Release-Historie strukturieren.
- **External Practice:** Git tagging exercise.
- **Verification:** Geeigneten Tag-Typ auswählen.

## 7 — Docker: Update Strategy

- **Theory:** Image Update und Container Replacement.
- **Context / Why:** Container werden typischerweise ersetzt statt im laufenden Container aktualisiert.
- **Admin / Professional Extension:** Immutable Deployment.
- **Guided Practice:** Image aktualisieren und Container neu erstellen.
- **Independent Challenge:** Sichere Update-Strategie entwerfen.
- **External Practice:** Docker update lab.
- **Verification:** Immutable Update erklären.

## 8 — Kubernetes: Rollout

- **Theory:** Deployment Revision und Rollout.
- **Context / Why:** Änderungen sollen kontrolliert und beobachtbar ausgerollt werden.
- **Admin / Professional Extension:** `kubectl rollout`.
- **Guided Practice:** Deployment aktualisieren.
- **Independent Challenge:** Rollout beobachten und gegebenenfalls zurückrollen.
- **External Practice:** Kubernetes rollout lab.
- **Verification:** Rollout und Rollback erklären.

## 9 — AI: Environment Setup

- **Theory:** Dependencies, API Keys und Environment Variables.
- **Context / Why:** AI-Anwendungen benötigen reproduzierbare Umgebungen.
- **Admin / Professional Extension:** Secrets nicht direkt im Code speichern.
- **Guided Practice:** Testumgebung konfigurieren.
- **Independent Challenge:** Sichere Environment-Konfiguration erstellen.
- **External Practice:** AI development setup exercise.
- **Verification:** Konfiguration und Secrets unterscheiden.

---

# 🔥 DAY 20 — SERVICES ADVANCED DAY

## 1 — systemd Units

- **Theory:** Unit-Typen und Unit-Struktur.
- **Context / Why:** systemd verwaltet mehr als nur Services.
- **Admin / Professional Extension:** Service, Timer, Target, Mount.
- **Guided Practice:** Verschiedene Units untersuchen.
- **Independent Challenge:** Unit-Abhängigkeiten analysieren.
- **External Practice:** systemd unit lab.
- **Verification:** Unit-Typen erklären.

## 2 — Dependencies

- **Theory:** Unit Dependencies und Ordering.
- **Context / Why:** Services müssen in sinnvoller Reihenfolge starten.
- **Admin / Professional Extension:** `After`, `Before`, `Requires`, `Wants`.
- **Guided Practice:** Abhängigkeiten untersuchen.
- **Independent Challenge:** Startproblem aufgrund falscher Abhängigkeit analysieren.
- **External Practice:** systemd dependency exercise.
- **Verification:** Ordering und Requirement unterscheiden.

## 3 — Timers

- **Theory:** Timer Scheduling.
- **Context / Why:** Wiederkehrende Administration kann automatisiert werden.
- **Admin / Professional Extension:** Timer Units.
- **Guided Practice:** Timer-Konfiguration untersuchen.
- **Independent Challenge:** Wartungsjob modellieren.
- **External Practice:** systemd timer lab.
- **Verification:** Timer-Ablauf erklären.

## 4 — Service Debugging

- **Theory:** Status, Logs und Dependencies als Diagnosequellen.
- **Context / Why:** Servicefehler müssen systematisch statt zufällig untersucht werden.
- **Admin / Professional Extension:** `systemctl status`, `journalctl`, `systemctl cat`.
- **Guided Practice:** Simulierten Servicefehler analysieren.
- **Independent Challenge:** Fehlerursache ohne direkte Anleitung finden.
- **External Practice:** Linux service troubleshooting lab.
- **Verification:** Troubleshooting-Reihenfolge erklären.

## 5 — Python: Error Handling

- **Theory:** Exceptions, Fehlerklassen und kontrollierte Fehlerbehandlung.
- **Context / Why:** Produktionsautomation muss vorhersehbar auf Fehler reagieren.
- **Admin / Professional Extension:** Exit Codes und Logging.
- **Guided Practice:** Fehlerfälle implementieren.
- **Independent Challenge:** Robustheit eines bestehenden Scripts verbessern.
- **External Practice:** Python error-handling exercise.
- **Verification:** Exception und Exit Code unterscheiden.

## 6 — Git: Reflog

- **Theory:** HEAD-Bewegungen und Reflog.
- **Context / Why:** Versehentlich verlorene Commits können häufig wiedergefunden werden.
- **Admin / Professional Extension:** `git reflog`.
- **Guided Practice:** HEAD-Bewegungen untersuchen.
- **Independent Challenge:** Einen verlorenen Commit wiederfinden.
- **External Practice:** Git recovery lab.
- **Verification:** Reflog erklären.

## 7 — Docker: Restart Policies

- **Theory:** Container Restart Behaviour.
- **Context / Why:** Services müssen nach Fehlern oder Host-Neustarts definiert reagieren.
- **Admin / Professional Extension:** `always`, `unless-stopped`, `on-failure`.
- **Guided Practice:** Restart Policies testen.
- **Independent Challenge:** Policy für verschiedene Services auswählen.
- **External Practice:** Docker restart-policy lab.
- **Verification:** Restart Policies unterscheiden.

## 8 — Kubernetes: Rollout Strategies

- **Theory:** Rolling Updates und kontrollierte Änderungen.
- **Context / Why:** Produktionssysteme benötigen möglichst unterbrechungsfreie Deployments.
- **Admin / Professional Extension:** RollingUpdate-Parameter.
- **Guided Practice:** Rollout untersuchen.
- **Independent Challenge:** Deploymentstrategie für einen Service planen.
- **External Practice:** Kubernetes rollout strategy lab.
- **Verification:** Rolling Update erklären.

## 9 — AI: Debugging Prompts

- **Theory:** Prompt-Debugging und reproduzierbare Testfälle.
- **Context / Why:** AI-Ausgaben sind oft sensibel gegenüber Eingabestruktur.
- **Admin / Professional Extension:** Prompt-Versionierung und Testfälle.
- **Guided Practice:** Fehlerhaften Prompt analysieren.
- **Independent Challenge:** Prompt systematisch verbessern.
- **External Practice:** Prompt-debugging exercise.
- **Verification:** Promptänderung und Ergebnisänderung begründen.

---

# 🔥 DAY 21 — VIRTUALIZATION ADVANCED DAY

## 1 — KVM

- **Theory:** Kernel-based Virtual Machine.
- **Context / Why:** KVM ist zentrale Linux-Virtualisierungstechnologie.
- **Admin / Professional Extension:** Hardware-assisted Virtualization.
- **Guided Practice:** KVM-Unterstützung prüfen.
- **Independent Challenge:** KVM-Architektur erklären.
- **External Practice:** KVM lab.
- **Verification:** KVM und Hypervisor-Begriff einordnen.

## 2 — QEMU

- **Theory:** QEMU als Emulator und Virtualizer.
- **Context / Why:** QEMU stellt virtuelle Hardware für Gastbetriebssysteme bereit.
- **Admin / Professional Extension:** QEMU + KVM.
- **Guided Practice:** VM-Konfiguration untersuchen.
- **Independent Challenge:** Rolle von QEMU und KVM unterscheiden.
- **External Practice:** QEMU virtualization exercise.
- **Verification:** QEMU/KVM Zusammenspiel erklären.

## 3 — virt-manager

- **Theory:** GUI-Verwaltung virtueller Maschinen.
- **Context / Why:** Administration kann über standardisierte Managementwerkzeuge erfolgen.
- **Admin / Professional Extension:** VM, Network und Storage Management.
- **Guided Practice:** VM über virt-manager untersuchen.
- **Independent Challenge:** VM-Ressourcen konfigurieren.
- **External Practice:** Virtual machine management lab.
- **Verification:** Grundlegende VM-Verwaltung durchführen.

## 4 — cloud-init

- **Theory:** Automatisierte Erstkonfiguration von Cloud-/VM-Systemen.
- **Context / Why:** Server sollen reproduzierbar und automatisiert provisioniert werden.
- **Admin / Professional Extension:** User, SSH Keys, Packages und Commands.
- **Guided Practice:** cloud-init-Konfiguration analysieren.
- **Independent Challenge:** Grundlegende Serverinitialisierung automatisieren.
- **External Practice:** cloud-init lab.
- **Verification:** Zweck von cloud-init erklären.

## 5 — Python: subprocess

- **Theory:** Externe Prozesse aus Python starten.
- **Context / Why:** Automation muss häufig vorhandene Linux-Kommandos integrieren.
- **Admin / Professional Extension:** `subprocess.run`, Return Codes und Security.
- **Guided Practice:** Linux-Befehl aus Python aufrufen.
- **Independent Challenge:** Command Output sicher verarbeiten.
- **External Practice:** Python subprocess exercise.
- **Verification:** Prozessstart und Return Code erklären.

## 6 — Git: Hooks

- **Theory:** Git Hooks und automatisierte Aktionen.
- **Context / Why:** Qualitätsprüfungen können automatisch vor oder nach Git-Aktionen erfolgen.
- **Admin / Professional Extension:** pre-commit Hooks.
- **Guided Practice:** Einfachen Hook erstellen.
- **Independent Challenge:** Automatische Prüfung eines Projekts integrieren.
- **External Practice:** Git hooks lab.
- **Verification:** Zweck von Hooks erklären.

## 7 — Docker: Build Optimization

- **Theory:** Layer Cache, Context und Image Size.
- **Context / Why:** Optimierte Images reduzieren Build- und Deploymentkosten.
- **Admin / Professional Extension:** `.dockerignore`, Layer Ordering.
- **Guided Practice:** Build analysieren.
- **Independent Challenge:** Imagegröße reduzieren.
- **External Practice:** Docker optimization challenge.
- **Verification:** Drei konkrete Optimierungsmaßnahmen erklären.

## 8 — Kubernetes: Operators

- **Theory:** Kubernetes Operator Pattern.
- **Context / Why:** Komplexe Anwendungen können über deklarative Automatisierung verwaltet werden.
- **Admin / Professional Extension:** Custom Resources und Controller.
- **Guided Practice:** Operator-Konzept untersuchen.
- **Independent Challenge:** Anwendungsfall für einen Operator entwerfen.
- **External Practice:** Kubernetes operator fundamentals.
- **Verification:** Operator-Prinzip erklären.

## 9 — AI: Model Structure

- **Theory:** Modellarchitektur, Parameter, Layers und Inference.
- **Context / Why:** Technische AI-Systeme müssen nicht als Black Box verstanden werden.
- **Admin / Professional Extension:** Modellgröße und Ressourcenbedarf.
- **Guided Practice:** Vereinfachte Modellstruktur untersuchen.
- **Independent Challenge:** Zusammenhang zwischen Modellgröße und Inference erklären.
- **External Practice:** AI model architecture exercise.
- **Verification:** Parameter, Layer und Inference unterscheiden.

---

# 🔥 DAY 22 — TERMINAL ADVANCED DAY

## 1 — grep

- **Theory:** Textsuche und Pattern Matching.
- **Context / Why:** Logs und Konfigurationsdateien müssen schnell durchsucht werden.
- **Admin / Professional Extension:** `grep`, Optionen und reguläre Ausdrücke.
- **Guided Practice:** Logdateien nach Mustern durchsuchen.
- **Independent Challenge:** Bestimmte Fehlerarten aus Logs extrahieren.
- **External Practice:** grep challenge.
- **Verification:** `grep` sicher einsetzen.

## 2 — find

- **Theory:** Rekursive Dateisuche und Suchkriterien.
- **Context / Why:** Dateien müssen nach Name, Typ, Größe oder Zeit gefunden werden.
- **Admin / Professional Extension:** `find` mit `-name`, `-type`, `-size`, `-mtime`.
- **Guided Practice:** Dateien nach mehreren Kriterien suchen.
- **Independent Challenge:** Bestimmte Dateien in unbekannter Struktur finden.
- **External Practice:** find exercise.
- **Verification:** Suchkriterien korrekt kombinieren.

## 3 — awk

- **Theory:** Feldbasierte Textverarbeitung.
- **Context / Why:** Strukturierte Kommandoausgaben können automatisiert ausgewertet werden.
- **Admin / Professional Extension:** Spalten extrahieren und filtern.
- **Guided Practice:** Mehrspaltige Daten verarbeiten.
- **Independent Challenge:** Systeminformationen automatisiert extrahieren.
- **External Practice:** awk lab.
- **Verification:** Grundprinzip von `awk` erklären.

## 4 — sed

- **Theory:** Stream Editor und Texttransformation.
- **Context / Why:** Konfigurationsdateien können automatisiert bearbeitet werden.
- **Admin / Professional Extension:** Suchen und Ersetzen.
- **Guided Practice:** Testdatei bearbeiten.
- **Independent Challenge:** Wiederholbare Konfigurationsänderung formulieren.
- **External Practice:** sed exercise.
- **Verification:** Zweck von `sed` erklären.

## 5 — Python: Regex

- **Theory:** Regular Expressions und Pattern Matching.
- **Context / Why:** Automation muss häufig strukturierte Informationen aus Text extrahieren.
- **Admin / Professional Extension:** Log Parsing.
- **Guided Practice:** Regex in Python verwenden.
- **Independent Challenge:** IPs oder Error Codes aus Logs extrahieren.
- **External Practice:** Python regex lab.
- **Verification:** Regex Pattern erklären.

## 6 — Git: Advanced diff

- **Theory:** Detaillierte Versionsvergleiche.
- **Context / Why:** Fehler müssen häufig über Unterschiede zwischen Zuständen gefunden werden.
- **Admin / Professional Extension:** Commit-, Branch- und Staging-Vergleiche.
- **Guided Practice:** Mehrere diff-Varianten durchführen.
- **Independent Challenge:** Unerwartete Änderung lokalisieren.
- **External Practice:** Git diff challenge.
- **Verification:** Unterschiedliche diff-Ebenen erklären.

## 7 — Docker: Entrypoint Logic

- **Theory:** Container Start Logic und Shell/Exec Form.
- **Context / Why:** Falsche Entrypoint-Logik kann Signal- und Prozessverhalten beeinträchtigen.
- **Admin / Professional Extension:** PID 1 und Signal Handling.
- **Guided Practice:** Unterschiedliche Entrypoints testen.
- **Independent Challenge:** Robustes Entrypoint-Script erstellen.
- **External Practice:** Docker entrypoint lab.
- **Verification:** Entrypoint-Verhalten erklären.

## 8 — Kubernetes: Logs Deep

- **Theory:** Container Logs, Pod Logs und Multi-Container Pods.
- **Context / Why:** Kubernetes-Anwendungen müssen pro Container diagnostizierbar sein.
- **Admin / Professional Extension:** `kubectl logs`, `-c`, `--previous`.
- **Guided Practice:** Pod Logs untersuchen.
- **Independent Challenge:** CrashLoopBackOff anhand von Logs analysieren.
- **External Practice:** Kubernetes logging challenge.
- **Verification:** Relevante Logquelle auswählen.

## 9 — AI: Text Parsing

- **Theory:** Extraktion, Strukturierung und Transformation von Text.
- **Context / Why:** AI kann unstrukturierte technische Informationen in strukturierte Daten überführen.
- **Admin / Professional Extension:** Logs, Tickets und Dokumentation.
- **Guided Practice:** Textfelder extrahieren.
- **Independent Challenge:** Unstrukturierten technischen Text in strukturierte Informationen überführen.
- **External Practice:** AI text parsing exercise.
- **Verification:** Parsing und Generation unterscheiden.

---

# 🔥 DAY 23 — PROCESSES EXPERT DAY

## 1 — cgroups

- **Theory:** Control Groups und Ressourcenbegrenzung.
- **Context / Why:** Linux kann Ressourcen von Prozessgruppen kontrollieren.
- **Admin / Professional Extension:** CPU, Memory und I/O Limits.
- **Guided Practice:** cgroup-Konzept untersuchen.
- **Independent Challenge:** Ressourcenbegrenzung für einen Workload erklären.
- **External Practice:** Linux cgroups lab.
- **Verification:** cgroups erklären.

## 2 — namespaces

- **Theory:** Linux Namespaces und Isolation.
- **Context / Why:** Containerisierung basiert wesentlich auf Namespace-Isolation.
- **Admin / Professional Extension:** PID, Network, Mount und User Namespaces.
- **Guided Practice:** Namespace-Konzept untersuchen.
- **Independent Challenge:** Mehrere Namespace-Typen erklären.
- **External Practice:** Linux namespaces exercise.
- **Verification:** Namespace und cgroup unterscheiden.

## 3 — Process Isolation

- **Theory:** Prozesssichtbarkeit und Ressourcenisolation.
- **Context / Why:** Isolation reduziert Konflikte und Sicherheitsrisiken.
- **Admin / Professional Extension:** Zusammenspiel von namespaces und cgroups.
- **Guided Practice:** Isolation konzeptionell untersuchen.
- **Independent Challenge:** Containerisolation erklären.
- **External Practice:** Linux isolation lab.
- **Verification:** Prozessisolation erklären.

## 4 — Resource Limits

- **Theory:** Limits und kontrollierter Ressourcenverbrauch.
- **Context / Why:** Ein Prozess darf ein System nicht unkontrolliert dominieren.
- **Admin / Professional Extension:** `ulimit` und cgroups.
- **Guided Practice:** Limits untersuchen.
- **Independent Challenge:** Ressourcenstrategie für einen Service entwickeln.
- **External Practice:** Linux resource-limit exercise.
- **Verification:** Hard und Soft Limits unterscheiden.

## 5 — Python: multiprocessing

- **Theory:** Prozesse, Process Pool und parallele Ausführung.
- **Context / Why:** CPU-intensive Aufgaben können parallelisiert werden.
- **Admin / Professional Extension:** Ressourcenverbrauch und Prozessmanagement.
- **Guided Practice:** Mehrere Python-Prozesse starten.
- **Independent Challenge:** Aufgabe parallelisieren und Performance vergleichen.
- **External Practice:** Python multiprocessing lab.
- **Verification:** Threading und Multiprocessing konzeptionell unterscheiden.

## 6 — Git: Cherry-pick Deep

- **Theory:** Commit-Transfer und Abhängigkeiten.
- **Context / Why:** Einzelne Fixes müssen manchmal gezielt übertragen werden.
- **Admin / Professional Extension:** Konflikte und Commit-Abhängigkeiten.
- **Guided Practice:** Mehrere Commits selektiv übertragen.
- **Independent Challenge:** Abhängiges Commit-Set analysieren.
- **External Practice:** Git cherry-pick challenge.
- **Verification:** Risiken von Cherry-pick erklären.

## 7 — Docker: cgroups

- **Theory:** Docker-Ressourcenlimits basieren auf Linux-Ressourcensteuerung.
- **Context / Why:** Container benötigen kontrollierte Ressourcen.
- **Admin / Professional Extension:** CPU/Memory Constraints.
- **Guided Practice:** Containerlimits untersuchen.
- **Independent Challenge:** Verhalten eines Containers unter Limits erklären.
- **External Practice:** Docker resource control lab.
- **Verification:** Docker und cgroups verbinden.

## 8 — Kubernetes: Resource Quotas

- **Theory:** Namespace Resource Quotas.
- **Context / Why:** Teams und Workloads müssen Clusterressourcen begrenzen.
- **Admin / Professional Extension:** ResourceQuota.
- **Guided Practice:** Quota-Konfiguration analysieren.
- **Independent Challenge:** Quota für Team-Namespace planen.
- **External Practice:** Kubernetes quota lab.
- **Verification:** ResourceQuota und Container Limit unterscheiden.

## 9 — AI: Parallel Inference

- **Theory:** Parallele Modellanfragen und Batch Processing.
- **Context / Why:** AI-Systeme müssen bei mehreren Anfragen effizient arbeiten.
- **Admin / Professional Extension:** Throughput, Latency und Ressourcen.
- **Guided Practice:** Mehrere Inference-Anfragen konzeptionell vergleichen.
- **Independent Challenge:** Parallelisierungsvor- und Nachteile analysieren.
- **External Practice:** AI inference exercise.
- **Verification:** Latency und Throughput erklären.

---

# 🔥 DAY 24 — LINUX ARCHITECTURE DAY

## 1 — FHS

- **Theory:** Filesystem Hierarchy Standard.
- **Context / Why:** Standardisierte Pfade machen Linux-Systeme administrierbar.
- **Admin / Professional Extension:** `/etc`, `/usr`, `/var`, `/home`, `/boot`, `/dev`, `/proc`, `/sys`.
- **Guided Practice:** FHS-Struktur analysieren.
- **Independent Challenge:** Speicherort unbekannter Daten bestimmen.
- **External Practice:** FHS lab.
- **Verification:** FHS ohne Hilfe erklären.

## 2 — systemd Architecture

- **Theory:** systemd Manager, Units, Targets und Dependencies.
- **Context / Why:** Systemstart und Serviceverwaltung bilden einen zentralen Teil moderner Linux-Administration.
- **Admin / Professional Extension:** Unit Graph und Targets.
- **Guided Practice:** Unit-Abhängigkeiten untersuchen.
- **Independent Challenge:** Boot-/Service-Ablauf erklären.
- **External Practice:** systemd architecture lab.
- **Verification:** systemd Architektur erklären.

## 3 — Kernel Architecture

- **Theory:** Kernel Space, Modules, Syscalls und Hardware.
- **Context / Why:** Verständnis der Kernelarchitektur erleichtert Troubleshooting.
- **Admin / Professional Extension:** `/proc`, `/sys`, `strace`.
- **Guided Practice:** Kernelinformationen untersuchen.
- **Independent Challenge:** Anwendung → Syscall → Kernel → Hardware erklären.
- **External Practice:** Linux kernel architecture exercise.
- **Verification:** Kernelarchitektur erklären.

## 4 — OS Layers

- **Theory:** Hardware, Kernel, Libraries, User Space und Applications.
- **Context / Why:** Fehler können nur zuverlässig diagnostiziert werden, wenn die Schichten verstanden werden.
- **Admin / Professional Extension:** Layer-basierte Fehlersuche.
- **Guided Practice:** Systemkomponenten Schichten zuordnen.
- **Independent Challenge:** Fehler auf eine Schicht eingrenzen.
- **External Practice:** OS architecture lab.
- **Verification:** OS-Layer erklären.

## 5 — Python Architecture

- **Theory:** Scripts, Modules, Packages, Environment und Runtime.
- **Context / Why:** Automation muss wartbar strukturiert werden.
- **Admin / Professional Extension:** Virtual Environments und Dependencies.
- **Guided Practice:** Kleine Python-Projektstruktur erstellen.
- **Independent Challenge:** Bestehendes Script modularisieren.
- **External Practice:** Python architecture exercise.
- **Verification:** Python-Projektstruktur erklären.

## 6 — Git Repo Structure

- **Theory:** Working Tree, `.git`, Objects, References und History.
- **Context / Why:** Git speichert mehr als nur Dateiversionen.
- **Admin / Professional Extension:** Repository-Struktur verstehen.
- **Guided Practice:** `.git`-Struktur untersuchen.
- **Independent Challenge:** Zusammenhang zwischen Commit und Repository Objects erklären.
- **External Practice:** Git internals lab.
- **Verification:** Grundstruktur eines Git-Repositories erklären.

## 7 — Docker Architecture

- **Theory:** Client, Daemon, Images, Containers und Registry.
- **Context / Why:** Docker besteht aus mehreren technischen Komponenten.
- **Admin / Professional Extension:** Docker Engine.
- **Guided Practice:** Docker-Komponenten untersuchen.
- **Independent Challenge:** Image bis laufendem Container erklären.
- **External Practice:** Docker architecture lab.
- **Verification:** Docker Architecture erklären.

## 8 — Kubernetes Cluster Architecture

- **Theory:** Control Plane, Nodes, API Server, Scheduler und Controllers.
- **Context / Why:** Kubernetes ist ein verteiltes System.
- **Admin / Professional Extension:** Control Plane vs Worker.
- **Guided Practice:** Clusterkomponenten zuordnen.
- **Independent Challenge:** Deployment-Ablauf durch den Cluster erklären.
- **External Practice:** Kubernetes architecture lab.
- **Verification:** Clusterarchitektur erklären.

## 9 — AI Model Architecture

- **Theory:** Input, Tokenization, Layers, Parameters und Output.
- **Context / Why:** Modellarchitektur beeinflusst Verhalten und Ressourcenverbrauch.
- **Admin / Professional Extension:** Inference Pipeline.
- **Guided Practice:** Modellfluss analysieren.
- **Independent Challenge:** Input bis Output erklären.
- **External Practice:** AI architecture exercise.
- **Verification:** Modellpipeline erklären.

---

# 🔥 DAY 25 — LINUX SECURITY BASICS DAY

## 1 — sudo

- **Theory:** Privilege Escalation und sudo.
- **Context / Why:** Administratorrechte müssen kontrolliert vergeben werden.
- **Admin / Professional Extension:** sudoers und Least Privilege.
- **Guided Practice:** `sudo`-Nutzung analysieren.
- **Independent Challenge:** Sichere Rechtevergabe für einen Admin-User modellieren.
- **External Practice:** Linux sudo lab.
- **Verification:** sudo und root unterscheiden.

## 2 — PAM

- **Theory:** Pluggable Authentication Modules.
- **Context / Why:** Linux verwendet modulare Authentifizierungsmechanismen.
- **Admin / Professional Extension:** PAM-Konfiguration und Authentifizierungsfluss.
- **Guided Practice:** PAM-Konzept untersuchen.
- **Independent Challenge:** Authentication Flow erklären.
- **External Practice:** Linux PAM fundamentals.
- **Verification:** PAM-Rolle erklären.

## 3 — SSH Keys

- **Theory:** Public-Key Authentication.
- **Context / Why:** SSH ist zentral für sichere Remote-Administration.
- **Admin / Professional Extension:** SSH Keys und Authorized Keys.
- **Guided Practice:** Key-Pair-Konzept nachvollziehen.
- **Independent Challenge:** Passwort- und Key-Authentifizierung vergleichen.
- **External Practice:** SSH fundamentals lab.
- **Verification:** Public und Private Key unterscheiden.

## 4 — Firewall Basics

- **Theory:** Packet Filtering und Firewall Rules.
- **Context / Why:** Netzwerkdienste müssen gezielt erreichbar sein.
- **Admin / Professional Extension:** UFW-Konzept.
- **Guided Practice:** Firewall-Regeln analysieren.
- **Independent Challenge:** Minimal notwendige Ports für einen Server bestimmen.
- **External Practice:** Linux firewall lab.
- **Verification:** Firewall Rule erklären.

## 5 — Python Secure Coding

- **Theory:** Input Validation, Secrets und sichere Defaults.
- **Context / Why:** Automation kann Sicherheitslücken verursachen.
- **Admin / Professional Extension:** Command Injection und Secret Handling.
- **Guided Practice:** Unsicheren Code analysieren.
- **Independent Challenge:** Code sicherer machen.
- **External Practice:** Secure Python exercise.
- **Verification:** Zwei konkrete Sicherheitsverbesserungen erklären.

## 6 — Git Signed Commits

- **Theory:** Signierte Commits und Vertrauensprüfung.
- **Context / Why:** Herkunft und Integrität von Änderungen können verifiziert werden.
- **Admin / Professional Extension:** Commit Signing.
- **Guided Practice:** Signaturprinzip untersuchen.
- **Independent Challenge:** Nutzen und Grenzen erklären.
- **External Practice:** Git security exercise.
- **Verification:** Signed Commit erklären.

## 7 — Docker Security Scan

- **Theory:** Image Vulnerabilities und Supply Chain Security.
- **Context / Why:** Container Images können verwundbare Komponenten enthalten.
- **Admin / Professional Extension:** Image Scanning und Minimal Images.
- **Guided Practice:** Security-Scan konzeptionell durchführen.
- **Independent Challenge:** Findings priorisieren.
- **External Practice:** Container security lab.
- **Verification:** Vulnerability und Misconfiguration unterscheiden.

## 8 — Kubernetes RBAC Deep

- **Theory:** Roles, ClusterRoles, Bindings und ServiceAccounts.
- **Context / Why:** Clusterzugriff benötigt fein granularen Schutz.
- **Admin / Professional Extension:** Least Privilege.
- **Guided Practice:** RBAC-Regeln analysieren.
- **Independent Challenge:** Rechte für einen ServiceAccount minimieren.
- **External Practice:** Kubernetes RBAC challenge.
- **Verification:** Role, ClusterRole und Binding unterscheiden.

## 9 — AI Secure Prompts

- **Theory:** Prompt Injection, Datenabfluss und sichere Anweisungen.
- **Context / Why:** AI-Systeme können durch manipulierte Eingaben beeinflusst werden.
- **Admin / Professional Extension:** Input Isolation und Privilege Boundaries.
- **Guided Practice:** Unsichere Prompt-Szenarien analysieren.
- **Independent Challenge:** Gegenmaßnahmen formulieren.
- **External Practice:** AI security exercise.
- **Verification:** Prompt Injection und normale Prompting-Probleme unterscheiden.

---

# 🔥 DAY 26 — NETWORKING TOOLS DAY

## 1 — ping

- **Theory:** ICMP Echo und Erreichbarkeit.
- **Context / Why:** ping ist ein einfacher erster Netzwerkdiagnoseschritt.
- **Admin / Professional Extension:** ICMP und Timeouts.
- **Guided Practice:** Hosts testen.
- **Independent Challenge:** Netzwerkproblem mit ping eingrenzen.
- **External Practice:** Network troubleshooting lab.
- **Verification:** Aussagekraft und Grenzen von ping erklären.

## 2 — curl

- **Theory:** HTTP und allgemeine Netzwerkrequests.
- **Context / Why:** curl ist ein universelles Tool für API- und Webdiagnose.
- **Admin / Professional Extension:** Header, Status Codes und Verbose Mode.
- **Guided Practice:** Webserver mit curl untersuchen.
- **Independent Challenge:** HTTP-Fehler diagnostizieren.
- **External Practice:** curl exercise.
- **Verification:** HTTP Request/Response erklären.

## 3 — ss

- **Theory:** Sockets, Listening Ports und Verbindungen.
- **Context / Why:** Administratoren müssen wissen, welche Dienste Netzwerkports öffnen.
- **Admin / Professional Extension:** `ss -tulpn`.
- **Guided Practice:** Listening Ports untersuchen.
- **Independent Challenge:** Service und Port zuordnen.
- **External Practice:** Linux socket lab.
- **Verification:** Listening Socket erklären.

## 4 — netstat

- **Theory:** Netzwerkstatistiken und Verbindungen.
- **Context / Why:** Ältere Systeme verwenden weiterhin netstat.
- **Admin / Professional Extension:** Vergleich mit `ss`.
- **Guided Practice:** Netzwerkstatus untersuchen.
- **Independent Challenge:** `netstat`- und `ss`-Output vergleichen.
- **External Practice:** Network tools exercise.
- **Verification:** Zweck von netstat erklären.

## 5 — Python: Sockets

- **Theory:** Sockets und Client/Server-Kommunikation.
- **Context / Why:** Netzwerkautomation benötigt grundlegendes Verständnis der Kommunikationsschicht.
- **Admin / Professional Extension:** TCP Socket Basics.
- **Guided Practice:** Einfachen Socket Client nachvollziehen.
- **Independent Challenge:** Client/Server-Kommunikation modellieren.
- **External Practice:** Python socket lab.
- **Verification:** Socket und Port unterscheiden.

## 6 — Git: Remote Management

- **Theory:** Remote Repositories und Remote URLs.
- **Context / Why:** Projekte benötigen kontrollierte externe Repositories.
- **Admin / Professional Extension:** `git remote`, add/remove/set-url.
- **Guided Practice:** Remote-Konfiguration untersuchen.
- **Independent Challenge:** Remote-Verbindung selbstständig konfigurieren.
- **External Practice:** Git remote management exercise.
- **Verification:** Remote Management erklären.

## 7 — Docker: Networking Deep

- **Theory:** Bridge, DNS und Container Network Interfaces.
- **Context / Why:** Multi-Container-Anwendungen benötigen kontrollierte Kommunikation.
- **Admin / Professional Extension:** Custom Networks und Isolation.
- **Guided Practice:** Container-Netzwerk untersuchen.
- **Independent Challenge:** Netzwerkdesign für mehrere Services entwerfen.
- **External Practice:** Docker networking lab.
- **Verification:** Docker-Netzwerkarchitektur erklären.

## 8 — Kubernetes: Service Discovery

- **Theory:** DNS-basierte Service Discovery.
- **Context / Why:** Pods ändern sich, Services bleiben logisch stabil.
- **Admin / Professional Extension:** Cluster DNS.
- **Guided Practice:** Service Discovery nachvollziehen.
- **Independent Challenge:** Kommunikation über Service Name erklären.
- **External Practice:** Kubernetes service discovery lab.
- **Verification:** Service Discovery erklären.

## 9 — AI: API Chaining

- **Theory:** Mehrere API-/Modellschritte als Pipeline.
- **Context / Why:** Komplexe AI-Anwendungen bestehen häufig aus mehreren Services.
- **Admin / Professional Extension:** Fehlerweitergabe und Logging.
- **Guided Practice:** Mehrstufigen Workflow modellieren.
- **Independent Challenge:** Pipeline mit mehreren Verarbeitungsschritten entwerfen.
- **External Practice:** AI API pipeline exercise.
- **Verification:** API Chain erklären.

---

# 🔥 DAY 27 — UBUNTU HARDENING DAY

## 1 — Disable Root Login

- **Theory:** Root Account und Remote Privilege Risk.
- **Context / Why:** Direkter Root-Zugriff erhöht das Risiko bei kompromittierten Zugangsdaten.
- **Admin / Professional Extension:** SSH-Hardening und sudo.
- **Guided Practice:** Root-Login-Konfiguration analysieren.
- **Independent Challenge:** Sicheren Admin-Zugriff planen.
- **External Practice:** Linux hardening lab.
- **Verification:** Warum Root-Login eingeschränkt werden kann, erklären.

## 2 — Firewall Rules

- **Theory:** Allow/Deny Rules und Default Policy.
- **Context / Why:** Nur notwendige Netzwerkdienste sollen erreichbar sein.
- **Admin / Professional Extension:** UFW-Regelkonzept.
- **Guided Practice:** Firewall-Konfiguration analysieren.
- **Independent Challenge:** Minimalen Serverzugriff modellieren.
- **External Practice:** Firewall hardening exercise.
- **Verification:** Least-Exposure-Prinzip erklären.

## 3 — fail2ban

- **Theory:** Log-basierte automatische Sperrung.
- **Context / Why:** Wiederholte Authentifizierungsversuche können automatisiert begrenzt werden.
- **Admin / Professional Extension:** Jail und Ban-Konzept.
- **Guided Practice:** Funktionsweise untersuchen.
- **Independent Challenge:** Schutzszenario modellieren.
- **External Practice:** fail2ban lab.
- **Verification:** Zweck von fail2ban erklären.

## 4 — auditd

- **Theory:** System Auditing und Audit Events.
- **Context / Why:** Sicherheitsrelevante Aktionen müssen nachvollziehbar sein.
- **Admin / Professional Extension:** Audit Rules.
- **Guided Practice:** Audit-Konzept untersuchen.
- **Independent Challenge:** Audit-Anforderung für sensible Datei formulieren.
- **External Practice:** Linux auditing exercise.
- **Verification:** Logging und Auditing unterscheiden.

## 5 — Python Encryption Basics

- **Theory:** Verschlüsselung, Hashing und Schlüssel.
- **Context / Why:** Automation kann sensible Daten verarbeiten.
- **Admin / Professional Extension:** Keine eigenen Kryptosysteme entwickeln.
- **Guided Practice:** Hashing und Verschlüsselung konzeptionell vergleichen.
- **Independent Challenge:** Geeigneten Mechanismus für verschiedene Szenarien bestimmen.
- **External Practice:** Python security exercise.
- **Verification:** Hashing und Encryption unterscheiden.

## 6 — Git Secure Workflow

- **Theory:** Secrets, Branch Protection und sichere Änderungen.
- **Context / Why:** Source Repositories können sensible Informationen enthalten.
- **Admin / Professional Extension:** Secret Scanning und Signing.
- **Guided Practice:** Unsicheren Workflow analysieren.
- **Independent Challenge:** Secure Git Workflow entwerfen.
- **External Practice:** Git security lab.
- **Verification:** Drei Sicherheitsmaßnahmen erklären.

## 7 — Docker Security Context Deep

- **Theory:** User, Capabilities und Privilegien.
- **Context / Why:** Container benötigen möglichst minimale Rechte.
- **Admin / Professional Extension:** Non-root und Capability Reduction.
- **Guided Practice:** Container-Sicherheitskonfiguration analysieren.
- **Independent Challenge:** Unsicheren Container härten.
- **External Practice:** Container hardening lab.
- **Verification:** Privilege Reduction erklären.

## 8 — Kubernetes Network Policies

- **Theory:** Pod-to-Pod Traffic Control.
- **Context / Why:** Netzwerkzugriff muss innerhalb eines Clusters begrenzt werden.
- **Admin / Professional Extension:** Ingress/Egress Policies.
- **Guided Practice:** NetworkPolicy analysieren.
- **Independent Challenge:** Zugriff zwischen zwei Services minimal erlauben.
- **External Practice:** Kubernetes network-policy lab.
- **Verification:** Zweck einer NetworkPolicy erklären.

## 9 — AI Secure Inference

- **Theory:** Sichere Modellinferenz und Datenminimierung.
- **Context / Why:** AI-Systeme können sensible Eingaben verarbeiten.
- **Admin / Professional Extension:** Access Control, Logging und Input Isolation.
- **Guided Practice:** AI-Sicherheitsrisiko analysieren.
- **Independent Challenge:** Secure Inference Architecture entwerfen.
- **External Practice:** AI security exercise.
- **Verification:** Mindestens drei AI-Sicherheitsmaßnahmen erklären.

---

# 🔥 DAY 28 — LINUX TROUBLESHOOTING DAY

## 1 — dmesg

- **Theory:** Kernel Messages.
- **Context / Why:** Hardware- und Kernelprobleme hinterlassen häufig Hinweise in Kernel Logs.
- **Admin / Professional Extension:** `dmesg`.
- **Guided Practice:** Kernelmeldungen untersuchen.
- **Independent Challenge:** Hardware-/Treiberhinweise identifizieren.
- **External Practice:** Linux troubleshooting lab.
- **Verification:** dmesg sinnvoll einsetzen.

## 2 — journalctl Deep

- **Theory:** Systemweite Logdiagnose.
- **Context / Why:** Moderne Linux-Systeme zentralisieren viele Diagnoseinformationen im Journal.
- **Admin / Professional Extension:** Boot-, Service- und Zeitfilter.
- **Guided Practice:** Boot- und Servicefehler suchen.
- **Independent Challenge:** Fehlerursache aus mehreren Journalabschnitten rekonstruieren.
- **External Practice:** journal troubleshooting challenge.
- **Verification:** Journal gezielt durchsuchen.

## 3 — systemctl Debug

- **Theory:** Servicezustand, Dependencies und Unit Definition.
- **Context / Why:** Servicefehler müssen systematisch untersucht werden.
- **Admin / Professional Extension:** `status`, `cat`, `list-dependencies`.
- **Guided Practice:** Fehlerhaften Service untersuchen.
- **Independent Challenge:** Ursache selbstständig bestimmen.
- **External Practice:** systemd troubleshooting lab.
- **Verification:** Systematisches Vorgehen erklären.

## 4 — Network Debugging

- **Theory:** Layer-basierte Netzwerkdiagnose.
- **Context / Why:** Netzwerkprobleme können Interface, Routing, DNS oder Application Layer betreffen.
- **Admin / Professional Extension:** `ip`, `ping`, `ss`, `curl`, `host`.
- **Guided Practice:** Simuliertes Netzwerkproblem analysieren.
- **Independent Challenge:** Fehler von Layer zu Layer eingrenzen.
- **External Practice:** Linux network troubleshooting lab.
- **Verification:** Diagnose-Reihenfolge erklären.

## 5 — Python Debugging

- **Theory:** Exceptions, Tracebacks und Debugging.
- **Context / Why:** Automation muss nachvollziehbar korrigiert werden können.
- **Admin / Professional Extension:** Logging und reproduzierbare Fehler.
- **Guided Practice:** Fehlerhaftes Script analysieren.
- **Independent Challenge:** Ursache ohne direkte Korrekturhinweise finden.
- **External Practice:** Python debugging exercise.
- **Verification:** Traceback interpretieren.

## 6 — Git Troubleshooting

- **Theory:** Status, log, diff, reflog und recovery.
- **Context / Why:** Versionskontrolle muss auch bei Fehlern beherrscht werden.
- **Admin / Professional Extension:** Konflikte und verlorene Änderungen.
- **Guided Practice:** Simuliertes Git-Problem lösen.
- **Independent Challenge:** Geeignetes Git-Diagnosewerkzeug auswählen.
- **External Practice:** Git troubleshooting lab.
- **Verification:** Diagnoseworkflow erklären.

## 7 — Docker Debug Mode

- **Theory:** Containerzustand, Logs, Inspect und Runtime.
- **Context / Why:** Containerprobleme müssen auf Prozess-, Netzwerk- und Imageebene analysiert werden.
- **Admin / Professional Extension:** `docker inspect`, `logs`, `exec`.
- **Guided Practice:** Fehlerhaften Container untersuchen.
- **Independent Challenge:** Ursache ohne Neustart-Raten finden.
- **External Practice:** Docker troubleshooting lab.
- **Verification:** Containerdiagnose durchführen.

## 8 — Kubernetes Debug Pods

- **Theory:** Pod Status, Events, Logs und Exec.
- **Context / Why:** Kubernetes Troubleshooting erfordert mehrere Informationsquellen.
- **Admin / Professional Extension:** `kubectl describe`, `logs`, `exec`.
- **Guided Practice:** Fehlerhaften Pod analysieren.
- **Independent Challenge:** Root Cause selbstständig finden.
- **External Practice:** Kubernetes debugging lab.
- **Verification:** Pod-Diagnose systematisch durchführen.

## 9 — AI Debugging Prompts

- **Theory:** Reproduzierbarkeit und kontrollierte Promptänderung.
- **Context / Why:** AI-Fehler müssen nachvollziehbar analysiert werden.
- **Admin / Professional Extension:** Prompt Test Cases.
- **Guided Practice:** Fehlerhafte Prompts vergleichen.
- **Independent Challenge:** Ursache einer inkonsistenten Antwort eingrenzen.
- **External Practice:** AI debugging exercise.
- **Verification:** Promptdebugging methodisch erklären.

---

# 🔥 DAY 29 — LINUX REVIEW DAY

## 1 — Commands Review

- **Theory:** Navigation, Files, Search, Text Processing und Help.
- **Context / Why:** CLI-Kompetenz muss automatisiert abrufbar sein.
- **Admin / Professional Extension:** Kombination mehrerer Commands.
- **Guided Practice:** Gemischte CLI-Aufgaben lösen.
- **Independent Challenge:** Unbekannte CLI-Aufgabe ohne Anleitung lösen.
- **External Practice:** Linux command challenge.
- **Verification:** Zentrale Commands selbstständig verwenden.

## 2 — Processes Review

- **Theory:** PID, Signals, Scheduling und Resources.
- **Context / Why:** Prozessverständnis ist Kern der Linux-Administration.
- **Admin / Professional Extension:** `ps`, `top`, `kill`, `nice`.
- **Guided Practice:** Prozessdiagnose durchführen.
- **Independent Challenge:** Ressourcenproblem analysieren.
- **External Practice:** Process challenge.
- **Verification:** Prozessdiagnose durchführen.

## 3 — Services Review

- **Theory:** systemd, Services, Logs und Timers.
- **Context / Why:** Services bilden einen zentralen Teil von Serverbetrieb.
- **Admin / Professional Extension:** `systemctl`, `journalctl`.
- **Guided Practice:** Serviceproblem lösen.
- **Independent Challenge:** Service von Status bis Root Cause analysieren.
- **External Practice:** systemd challenge.
- **Verification:** Service-Troubleshooting durchführen.

## 4 — Filesystem Review

- **Theory:** FHS, Storage, Mounts und Permissions.
- **Context / Why:** Dateien, Geräte und Berechtigungen gehören zusammen.
- **Admin / Professional Extension:** `/etc`, `/var`, `/usr`, `/dev`, `/proc`, `/sys`.
- **Guided Practice:** Filesystem eines Systems analysieren.
- **Independent Challenge:** Speicherort und Zugriff einer unbekannten Datei bestimmen.
- **External Practice:** Linux filesystem challenge.
- **Verification:** Filesystemstruktur erklären.

## 5 — Python Review

- **Theory:** Variables, Functions, Files, OOP, Exceptions und Modules.
- **Context / Why:** Python bildet die Grundlage späterer Automation.
- **Admin / Professional Extension:** Systemautomation.
- **Guided Practice:** Kleines Admin-Script erstellen.
- **Independent Challenge:** Script modularisieren und Fehlerbehandlung hinzufügen.
- **External Practice:** Python practice challenge.
- **Verification:** Script ohne Vorlage erklären.

## 6 — Git Review

- **Theory:** Repository, Branches, Commits, Remotes und Recovery.
- **Context / Why:** Versionskontrolle ist Teil professioneller technischer Arbeit.
- **Admin / Professional Extension:** Rebase, Revert, Reflog und Conflict Resolution.
- **Guided Practice:** Vollständigen Workflow durchführen.
- **Independent Challenge:** Mehrere Git-Probleme selbstständig lösen.
- **External Practice:** Git challenge.
- **Verification:** Git-Workflow sicher beherrschen.

## 7 — Docker Review

- **Theory:** Images, Containers, Networks, Volumes und Resources.
- **Context / Why:** Containertechnologien verbinden Linux und moderne Infrastruktur.
- **Admin / Professional Extension:** Debugging und Security.
- **Guided Practice:** Container-Anwendung betreiben.
- **Independent Challenge:** Fehlerhafte Containerumgebung diagnostizieren.
- **External Practice:** Docker challenge.
- **Verification:** Containerbetrieb erklären.

## 8 — Kubernetes Review

- **Theory:** Pods, Deployments, Services, Storage, RBAC und Troubleshooting.
- **Context / Why:** Kubernetes bündelt zentrale Konzepte moderner Infrastruktur.
- **Admin / Professional Extension:** `kubectl`, Rollouts und Debugging.
- **Guided Practice:** Kleine Workload bereitstellen.
- **Independent Challenge:** Deploymentproblem diagnostizieren.
- **External Practice:** Kubernetes challenge.
- **Verification:** Grundlegenden Kubernetes-Ablauf erklären.

## 9 — AI Review

- **Theory:** LLMs, Tokens, Prompts, Embeddings, RAG und APIs.
- **Context / Why:** AI bildet eine ergänzende technische Kompetenz.
- **Admin / Professional Extension:** Sichere und reproduzierbare AI-Nutzung.
- **Guided Practice:** Mehrere AI-Konzepte miteinander verbinden.
- **Independent Challenge:** Einfachen AI-Workflow entwerfen.
- **External Practice:** AI fundamentals challenge.
- **Verification:** Training, Inference, Prompt, Embedding und RAG unterscheiden.

---

# 🔥 DAY 30 — LINUX ESSENTIALS EXAM DAY

## 1 — Exam Simulation

- **Theory:** Prüfungsstruktur und Linux-Essentials-Kernbereiche.
- **Context / Why:** Wissen muss unter Zeitdruck abrufbar sein.
- **Admin / Professional Extension:** Prüfungssimulation mit praktischer Linux-Anwendung verbinden.
- **Guided Practice:** 40 Fragen in einem 60-Minuten-Szenario bearbeiten.
- **Independent Challenge:** Simulation vollständig ohne Hilfsmittel durchführen.
- **External Practice:** Externe Linux-Essentials-Prüfungssimulation.
- **Verification:** Ergebnisse analysieren und Fehler kategorisieren.

## 2 — Weak Areas

- **Theory:** Wiederholung der individuell schwächsten Themen.
- **Context / Why:** Gezielte Wiederholung ist effektiver als gleichmäßige Wiederholung aller Themen.
- **Admin / Professional Extension:** Schwächen nach Linux-Administration-Relevanz priorisieren.
- **Guided Practice:** Fehlerliste aus der Simulation erstellen.
- **Independent Challenge:** Schwachstellen ohne Lernmaterial erneut lösen.
- **External Practice:** Passende Übungen zu den Schwächen.
- **Verification:** Jede Schwachstelle mindestens einmal erfolgreich lösen.

## 3 — Final Linux Essentials Review

- **Theory:** Linux Community/Open Source, CLI, Files, Archives, Scripts, OS, Hardware, Networking, Users, Groups und Permissions.
- **Context / Why:** Die Prüfung prüft mehrere Linux-Grundlagenbereiche als zusammenhängendes Wissen.
- **Admin / Professional Extension:** Verknüpfung der Grundlagen mit realer Administration.
- **Guided Practice:** Themen systematisch wiederholen.
- **Independent Challenge:** Unbekannte Linux-Aufgabe ohne Anleitung lösen.
- **External Practice:** Final Linux-Essentials review.
- **Verification:** Alle zentralen Themenbereiche selbstständig erklären.

## 4 — Exam Mindset

- **Theory:** Zeitmanagement, Fragenanalyse und Fehlervermeidung.
- **Context / Why:** Fachwissen allein reicht unter Prüfungsbedingungen nicht immer aus.
- **Admin / Professional Extension:** Präzise technische Begriffe verwenden.
- **Guided Practice:** Beispielhafte Fragen unter Zeitlimit bearbeiten.
- **Independent Challenge:** Unsichere Fragen systematisch bearbeiten, ohne vorschnell zu raten.
- **External Practice:** Timed exam practice.
- **Verification:** Eigene Prüfungsstrategie formulieren.

## 5 — Python Practice

- **Theory:** Variables, Functions, Files, Exceptions und grundlegende Automation.
- **Context / Why:** Python unterstützt spätere Linux-Administration.
- **Admin / Professional Extension:** Systeminformationen automatisiert verarbeiten.
- **Guided Practice:** Kleines System-Info-Programm erstellen.
- **Independent Challenge:** Ein kleines Admin-Script vollständig selbstständig entwickeln.
- **External Practice:** Python practice challenge.
- **Verification:** Script erklären und Fehler selbstständig beheben.

## 6 — Git Practice

- **Theory:** Repository, Commit, Branch, Merge und Remote.
- **Context / Why:** Versionierung gehört zum professionellen Entwicklungsworkflow.
- **Admin / Professional Extension:** Technische Dokumentation und Scripts versionieren.
- **Guided Practice:** Repository mit mehreren Commits erstellen.
- **Independent Challenge:** Branch, Merge und Remote-Synchronisierung selbstständig durchführen.
- **External Practice:** Git practical challenge.
- **Verification:** Git-Workflow ohne Vorlage durchführen.

## 7 — Docker Practice

- **Theory:** Image, Container, Build, Network und Volume.
- **Context / Why:** Container bilden eine wichtige Brücke zwischen Linux und moderner Infrastruktur.
- **Admin / Professional Extension:** Ressourcen und Security berücksichtigen.
- **Guided Practice:** Anwendung bauen und als Container starten.
- **Independent Challenge:** Containerproblem selbstständig diagnostizieren.
- **External Practice:** Docker practical challenge.
- **Verification:** Image → Container → Network → Storage erklären.

## 8 — Kubernetes Practice

- **Theory:** Pod, Deployment, Service, ConfigMap und Ressourcen.
- **Context / Why:** Kubernetes bündelt moderne Infrastrukturkonzepte.
- **Admin / Professional Extension:** Rollout, Logs und Troubleshooting.
- **Guided Practice:** Kleine Anwendung deployen.
- **Independent Challenge:** Deployment aktualisieren und Fehler diagnostizieren.
- **External Practice:** Kubernetes practical challenge.
- **Verification:** Deployment → Pod → Service Ablauf erklären.

## 9 — AI Practice

- **Theory:** LLM, Prompt, Token, Embedding, RAG und API.
- **Context / Why:** AI-Kompetenz ergänzt Linux-, Cloud- und Automation-Kenntnisse.
- **Admin / Professional Extension:** Sichere API- und Prompt-Nutzung.
- **Guided Practice:** Einen einfachen AI-Workflow durchführen.
- **Independent Challenge:** Einen kleinen technischen AI-Anwendungsfall entwerfen.
- **External Practice:** AI practical exercise.
- **Verification:** AI-Komponenten und ihren technischen Zusammenhang erklären.

---
