<p align="center">
  <a href="README.md">English</a> | <b>Deutsch</b>
</p>

<h1 align="center">
  <code>Awesome TUIs</code>
</h1>

Dies ist eine von der Community gepflegte Liste von TUI-Anwendungen. Eine TUI-Anwendung läuft in Ihrem Terminal und verfügt über ein gewisses Maß an Interaktivität. In dieser Liste enthaltene Befehle sollten keine anderen interaktiven Befehle umschließen (z. B. `fzf`) und sollten gewartet werden.

Ich habe ein Video von meinen Lieblings-TUIs aus dieser Liste erstellt (eines aus jeder Sektion). Klicken Sie auf das Bild, um es sich anzusehen. 👇

[![](https://i.ytimg.com/vi/_fLmA4fjiAE/maxresdefault.jpg)](https://youtu.be/_fLmA4fjiAE?si=IgXuo)

Hier gibt es viele coole Projekte, mit denen ich in keiner Verbindung stehe. Die Benutzung erfolgt auf eigene Gefahr. Wenn Sie ein cooles Tool haben, das Sie teilen möchten, [öffnen Sie bitte einen PR](https://github.com/rothgar/awesome-tuis/pulls).

## Inhaltsverzeichnis

- [Dashboards](#dashboards)
- [Entwicklung](#entwicklung)
- [Docker/LXC/K8s](#dockerlxck8s)
- [Editoren](#editoren)
- [Dateimanager](#dateimanager)
- [Spiele](#spiele)
- [Bibliotheken](#bibliotheken)
- [Messaging](#messaging)
- [Sonstiges](#sonstiges)
- [Multimedia](#multimedia)
- [Produktivität](#produktivität)
- [Bildschirmschoner](#bildschirmschoner)
- [Web](#web)

<details open><summary><h2>Dashboards</h2></summary>

- [AdGuardian-Term](https://github.com/lissy93/AdGuardian-Term) Ein TUI-Dashboard zur Überwachung des Echtzeitverkehrs von einer AdGuard Home-Instanz
- [apachetop](https://github.com/tessus/apachetop) Zeigt Informationen einer laufenden Kopie von Apache an.
- [atop](https://github.com/Atoptool/atop/) System- und Prozessmonitor auf Root-Ebene für Linux
- [Backlog.md](https://github.com/MrLesk/Backlog.md) Ein Werkzeug zur Verwaltung der Projektzusammenarbeit zwischen Menschen und KI-Agenten in einem Git-Ökosystem
- [bandwhich](https://github.com/imsnif/bandwhich) Terminal-Bandbreitenauslastungs-Tool
- [bashtop](https://github.com/aristocratos/bashtop) Ressourcen-Manager geschrieben in Bash
- [below](https://github.com/facebookincubator/below) Ein zeitreisender Ressourcen-Monitor für moderne Linux-Systeme
- [binsider](https://github.com/orhun/binsider) Eine TUI zur Analyse von Linux-Binärdateien.
- [bmon](https://github.com/tgraf/bmon) Ein Monitoring- und Debugging-Tool zum Erfassen netzwerkbezogener Statistiken und deren visueller Aufbereitung.
- [bottom](https://github.com/ClementTsang/bottom) Ein anpassbarer grafischer Prozess-/Systemmonitor für das Terminal.
- [bpytop](https://github.com/aristocratos/bpytop) Ein Python-basierter Systemmonitor mit vielen Informationen.
- [btop++](https://github.com/aristocratos/btop) Ressourcen-Monitor mit Extras
- [cgdb](https://github.com/cgdb/cgdb) Konsolen-Frontend für den GNU-Debugger
- [chdig](https://github.com/azat/chdig) Mit TUI-Interface in ClickHouse eintauchen
- [cheatshh](https://github.com/AnirudhG07/cheatshh) Eine fzf-TUI zur Verwaltung selbstgemachter Kommandozeilen-Cheatsheets für Unix.
- [claws](https://github.com/clawscli/claws) Ein Terminal-UI für das AWS-Ressourcenmanagement mit Vim-Style-Keybindings, Kommandozeilen-Navigation und optionalem Nur-Lese-Modus.
- [cointop](https://github.com/miguelmota/cointop) Die schnellste und interaktivste terminalbasierte UI-Anwendung zur Verfolgung von Kryptowährungen
- [CoreFreq](https://github.com/cyring/CoreFreq) CPU-Monitoring-Software für 64-Bit-Prozessoren
- [csysdig](https://github.com/draios/sysdig) Ncurses-Interface auf Root-Ebene für sysdig, ein Werkzeug zur Erkundung und Fehlerbehebung von Linux-Systemen mit erstklassiger Unterstützung für Container
- [damon](https://github.com/hashicorp/damon) TUI-Interface für Hashicorp Nomad
- [dashbrew](https://github.com/rasjonell/dashbrew) TUI-Dashboard-Builder, mit dem Sie Daten von Skripten und APIs visualisieren können.
- [dolphie](https://github.com/charles-001/dolphie) Ein zentrales Fenster für Echtzeitanalysen von MySQL/MariaDB & ProxySQL
- [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) TUI zur Steuerung und Überwachung von Framework-Computer-Hardware, gebaut in Rust
- [fubar](https://github.com/irishmaestro/fubar) Formidable Unix Binary Arsenal & Repository. TUI gebaut für gtfobins-Poweruser.
- [gh-dash](https://github.com/dlvhdr/gh-dash) Eine funktionsreiche Terminal-UI für GitHub PRs und Issues
- [Glances](https://github.com/nicolargo/glances) Glances behält Ihr System im Auge. Eine Alternative zu top/htop.
- [Goaccess](https://github.com/allinurl/goaccess) GoAccess ist ein Echtzeit-Weblog-Analysator und interaktiver Betrachter, der im Terminal in nix-Systemen oder über Ihren Browser läuft.
- [gobang](https://github.com/TaKO8Ki/gobang) Ein plattformübergreifendes TUI-Datenbankmanagement-Tool geschrieben in Rust
- [gonzo](https://github.com/control-theory/gonzo) Eine leistungsstarke Echtzeit-Log-Analyse-Terminal-UI inspiriert von k9s.
- [gotop](https://github.com/xxxserxxx/gotop) Ein terminalbasierter grafischer Aktivitätsmonitor inspiriert von gtop und vtop
- [gping](https://github.com/orf/gping) Ping, aber mit einem Graphen
- [Grafterm](https://github.com/slok/grafterm) Metrik-Dashboards auf dem Terminal, eine von Grafana inspirierte Terminal-Version
- [htop](https://github.com/htop-dev/htop) Interaktiver Textmodus-Prozessbetrachter für Unix-Systeme. Er zielt darauf ab, ein besseres 'top' zu sein.
- [htui](https://github.com/PierreKieffer/htui) Heroku Terminal-Benutzeroberfläche
- [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui) Ein von gping inspiriertes Terminal-Visualisierungstool zur Überwachung von Echtzeit-Hardwaresensordaten von HWInfo
- [ID-Spoofer](https://github.com/NubleX/ID-Spoofer) Ein plattformübergreifendes Cybersicherheits-Toolkit für Fingerabdruck- und Traffic-Verschleierung.
- [kaskade](https://github.com/sauljabin/kaskade) TUI für Kafka, die es Ihnen ermöglicht, mit Stil in Ihrem Terminal mit Topics zu interagieren und diese zu konsumieren!
- [kmon](https://github.com/orhun/kmon) Linux Kernel Manager und Aktivitätsmonitor
- [Kyanos](https://github.com/hengyoush/kyanos) Linux-Netzwerkanalyse-Tool basierend auf eBPF
- [ls-horizons](https://github.com/litescript/ls-horizons) Terminal-UI zur Echtzeit-Visualisierung von NASAs Deep Space Network
- [macmon](https://github.com/vladkens/macmon) Leistungsüberwachung ohne sudo für Apple Silicon-Prozessoren, geschrieben in Rust
- [nerdlog](https://github.com/dimonomid/nerdlog) Schneller, remote-first, Multi-Host-TUI-Log-Viewer
- [nethogs](https://github.com/raboof/nethogs) Ein 'net top' Werkzeug
- [netscanner](https://github.com/Chleba/netscanner) Netzwerk-Scanner
- [nvtop](https://github.com/Syllo/nvtop) Überwachung von GPU-Prozessen für AMD, Intel und NVIDIA
- [oryx](https://github.com/pythops/oryx) Eine TUI zum Sniffen von Netzwerkverkehr mittels eBPF
- [otel-tui](https://github.com/ymtdzzz/otel-tui) Ein Terminal-OpenTelemetry-Viewer
- [Planor](https://github.com/mrusme/planor) The Cloud Aviator, Dashboard für AWS, Vultr, Heroku, ...
- [process-compose](https://github.com/F1bonacc1/process-compose) TUI zum Ausführen von Apps und Prozessen
- [psmux](https://github.com/marlocarlo/psmux) tmux-kompatibler Terminal-Multiplexer für Windows, gebaut in Rust mit ratatui.
- [psnet](https://github.com/marlocarlo/psnet) Echtzeit-TUI-Netzwerkmonitor für Windows mit Geschwindigkeitsgraphen, DNS-Auflösung und Paketinspektion.
- [pstop](https://github.com/marlocarlo/pstop) htop-ähnlicher Systemmonitor für Windows mit CPU-Balken pro Kern, Baumansicht und 7 Farbschemata.
- [Puffin](https://github.com/siddhantac/puffin) Ein schönes Terminal-Dashboard für hledger
- [Raijin](https://github.com/MasonStooksbury/Raijin) Eine kostenlose, einfache Wetter-TUI, die Daten ohne API-Schlüssel, Konto oder Abonnement abruft
- [rustnet](https://github.com/domcyrus/rustnet) Ein plattformübergreifendes Netzwerk-Monitoring-Tool mit tiefer Paketinspektion
- [s-tui](https://github.com/amanusk/s-tui) Dienstprogramm zur CPU-Belastung und -Überwachung
- [sacha](https://github.com/Sachamama/sacha) Eine zweispaltige AWS-TUI zum Durchsuchen, Suchen und Verwalten von Ressourcen über sieben Dienste hinweg, einschließlich CloudWatch Logs, S3, DynamoDB, Lambda, SSM, SQS und EC2.
- [sockttop](https://github.com/jasonwitty/socktop) socktop ist ein Remote-Systemmonitor mit einer funktionsreichen TUI, inspiriert von top/btop, der über WebSockets mit einem leichtgewichtigen Agenten kommuniziert.
- [ServerHub](https://github.com/nickprotop/ServerHub) Ein TUI-Serverüberwachungs-Dashboard für Linux mit Echtzeit-Metriken, skriptfähigen Widgets und Fernverwaltung
- [sysz](https://github.com/joehillen/sysz) Eine fzf-Terminal-UI für systemctl
- [talos linux](https://github.com/siderolabs/talos) Eine Linux-Distro mit einem TUI-Dashboard für lokale und Remote-Nutzung
- [tdash](https://github.com/jessfraz/tdash) Ein Terminal-Dashboard mit Statistiken von Google Analytics, GitHub, Travis CI und Jenkins. Sehr speziell für mich gebaut
- [tegratop](https://github.com/pythops/tegratop) Monitoring-Tool (ähnlich top) für Nvidia Jetson-Boards
- [TermUI](https://github.com/gizak/termui) Golang-Terminal-Dashboard
- [ticker](https://github.com/achannarasappa/ticker) Verfolgen Sie Aktien-, Krypto- und Derivatepreise sowie Positionen in Echtzeit von Ihrem Terminal aus
- [trek](https://github.com/franckverrot/trek) ncurses-Explorer für Hashicorp Nomad-Cluster
- [trippy](https://github.com/fujiapple852/trippy) Ein Netzwerkdiagnose-Tool, das Funktionen wie mtr und mehr enthält
- [ttop](https://github.com/inv2004/ttop) Systemmonitoring-Tool mit historischem Datenservice, Triggern und top-ähnlicher TUI
- [tufw](https://github.com/peltho/tufw) Terminal-UI für ufw
- [tuicamp](https://github.com/AbeEstrada/tuicamp) Inoffizielle TimeCamp-TUI
- [updo](https://github.com/Owloops/updo) Website-Monitoring-Tool mit Uptime-Tracking, Antwortzeit-Metriken und SSL-Zertifikatsüberwachung.
- [tmd-top](https://github.com/CDWEN0526/tmd-top) Dient zur Überwachung des TCP-Verkehrs von Prozessen auf Linux-Systemen, detailliert aufgeschlüsselt für jede IP-Verbindung
- [wander](https://github.com/robinovitch61/wander) HashiCorp Nomad Terminal-Client
- [WTF](https://github.com/senorprogrammer/wtf) Das Dashboard für persönliche Informationen in Ihrem Terminal.
- [Yozefu](https://github.com/MAIF/yozefu) Eine TUI zur Untersuchung der Daten eines Kafka-Clusters.
- [zenith](https://github.com/bvaisvil/zenith) Grafische Metriken im Terminal für Ihr *nix-System, geschrieben in Rust

---

</details>

<details open><summary><h2>Entwicklung</h2></summary>

- [act3](https://github.com/dhth/act3) Kurzer Blick auf die letzten 3 Durchläufe Ihrer GitHub-Actions
- [amtui](https://github.com/pehlicd/amtui/) Alertmanager TUI - Ihr Terminal-Begleiter für Alertmanager
- [amux](https://github.com/andyrewlee/amux) Einfaches Ausführen paralleler Coding-Agenten
- [ATAC](https://github.com/Julien-cpsn/ATAC) Ein funktionsreicher TUI API-Client geschrieben in Rust. ATAC ist kostenlos, quelloffen, offline und kontofrei.
- [austin-tui](https://github.com/P403n1x87/austin-tui) Das top-ähnliche textbasierte User-Interface für Austin
- [blinkenlights](https://github.com/jart/blink) TUI, die zum Debuggen von x86_64-Linux oder i8086-Programmen über verschiedene Plattformen hinweg verwendet werden kann
- [brows](https://github.com/rubysolo/brows) CLI GitHub Release Browser
- [burf](https://github.com/razeghi71/burf) TUI für Google Cloud Storage (GCS)
- [cargo-seek](https://github.com/tareqimbasher/cargo-seek) Eine TUI zum Suchen, Hinzufügen und Installieren von Cargo Crates
- [catalyst](https://github.com/PraveenGongada/catalyst) Elegante TUI zum Auslösen von GitHub Actions-Workflows mit Matrix-Konfigurationen.
- [cnTUI](https://github.com/fipso/cntui) Chrome-Requests von Ihrem Terminal mittels curl wiederholen
- [chiko](https://github.com/felangga/chiko) Der ultimative TUI gRPC-Client
- [Claude Code Bridge](https://github.com/bfly123/claude_code_bridge) Echtzeit-Multi-KI-Zusammenarbeit zwischen Claude, Codex und Gemini im Terminal
- [Close Mongo Ops Manager](https://github.com/closeio/close-mongo-ops-manager) MongoDB-Operationen überwachen und beenden
- [Cloud Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) Claude Token-Verbrauch überwachen
- [codex](https://github.com/openai/codex) Leichtgewichtiger Coding-Agent, der in Ihrem Terminal läuft
- [csope](https://github.com/agvxov/csope) C Quellcode-Browser basierend auf cscope
- [CuTE](https://github.com/PThorpe92/CuTE) TUI zum Erstellen, Ausführen und Speichern von curl-Befehlen, rekursiven Download von entfernten Quellen, Testen Ihrer API-Endpunkte und Verwalten Ihrer Schlüssel
- [crush](https://github.com/charmbracelet/crush) Der glanzvolle KI-Coding-Agent
- [dbee](https://github.com/murat-cileli/dbee) Schneller & minimalistischer Datenbank-Browser
- [dblab](https://github.com/danvergara/dblab) Der Datenbank-Client, den jeder Kommandozeilen-Junkie verdient
- [ddqa](https://github.com/DataDog/ddqa) Jira TUI zur Unterstützung bei Software-Releases
- [ddv](https://github.com/lusingander/ddv) Terminal-DynamoDB-Viewer
- [delta](https://github.com/dandavison/delta) Ein Pager mit Syntax-Hervorhebung für git, diff und grep Ausgaben
- [deputui](https://github.com/twiddler/deputui) NPM-Paket-Updates überprüfen und installieren
- [differ](https://github.com/JanSmrcka/differ) Ein TUI git diff Betrachter
- [euporie](https://github.com/joouha/euporie) Jupyter Notebooks im Terminal
- [fast-resume](https://github.com/angristan/fast-resume) Indexierung und Fuzzy-Suche für Coding-Agent-Sessions
- [Feluda](https://github.com/anistark/feluda) Erkennung restriktiver und inkompatibler Lizenzen in allen Abhängigkeiten Ihres Projekts.
- [Froggit](https://github.com/thewizardshell/froggit) Minimalistische Git TUI mit GitHub CLI Integration
- [fx](https://github.com/antonmedv/fx) Terminal JSON Betrachter & Prozessor
- [ggc](https://github.com/bmf-san/ggc) Ein terminalbasiertes Git CLI Werkzeug geschrieben in Go
- [gitui](https://github.com/extrawurst/gitui) Razend schnelle Terminal-UI für Git geschrieben in Rust
- [gitv](https://github.com/jayanaxhf/gitv): Ein schöner, funktionsreicher und leistungsstarker Terminal-Client für GitHub Issues.
- [git-crecord](https://github.com/andrewshadura/git-crecord) Interaktives Werkzeug für selektive Commits
- [git-scope](https://github.com/Bharath-code/git-scope) Terminal-UI-Dashboard zur Inspektion mehrerer lokaler Git-Repositories.
- [grv](https://github.com/rgburke/grv) Terminal-Interface zum Betrachten von Git-Repositories
- [harlequin](https://github.com/tconbeer/harlequin) Die SQL-IDE für Ihr Terminal
- [heretek](https://github.com/wcampbell0x2a/heretek) GDB TUI Dashboard
- [jqp](https://github.com/noahgorstein/jqp) Ein TUI-Spielplatz zum Experimentieren mit jq
- [kagan](https://github.com/kagan-sh/kagan) KI-gestütztes Kanban-TUI für autonome Entwicklungs-Workflows
- [lazygit](https://github.com/jesseduffield/lazygit) Einfache Terminal-UI für Git-Befehle
- [lazymake](https://github.com/rshelekhov/lazymake) Moderne TUI für Makefiles mit interaktiver Target-Auswahl, Abhängigkeitsvisualisierung und Sicherheitsanalyse für Befehle.
- [lazysql](https://github.com/jorgerojas26/lazysql) Ein plattformübergreifendes TUI-Datenbankmanagement-Tool geschrieben in Go.
- [lazyjournal](https://github.com/Lifailon/lazyjournal) TUI für journalctl, Dateisystem-Logs sowie Docker- und Podman-Container zum schnellen Betrachten und Filtern
- [lean-tui](https://codeberg.org/wvhulle/lean-tui) Interaktive Visualisierung von Beweisen und Programmen, die im Lean4-Beweisassistenten geschrieben wurden
- [logradar](https://github.com/nanook72/logradar) Eine schnelle Rust TUI zur interaktiven Log-Filterung und Hervorhebung.
- [LogLens](https://github.com/Caelrith/loglens-core) Ein strukturierter Log-Viewer und Abfrage-Engine für das Terminal.
- [logshark](https://github.com/ugosan/logshark) Ein Debugger-CLI für JSON-Logs geschrieben in Go
- [mitmproxy](https://www.mitmproxy.org) Ein freier und quelloffener interaktiver HTTPS-Proxy
- [models](https://github.com/arimxyer/models) TUI zum Durchsuchen von KI-Modellen und Coding-Agenten
- [nap](https://github.com/maaslalani/nap) Code-Schnipsel in Ihrem Terminal
- [nodebro](https://github.com/jonaburg/nodebro) Einfaches Betrachten der aktuellsten GitHub-Releases/Tags und Release-Notes vom Terminal aus
- [opencode](https://github.com/sst/opencode) KI-Coding-Agent, gebaut für das Terminal
- [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) OPC UA-Client TUI mit Echtzeit-Oszilloskop-Ansicht für die industrielle Automatisierung
- [Quorum](https://github.com/Detrol/quorum-cli) Multi-Agenten KI-Diskussionssystem für strukturierte Debatten zwischen LLMs
- [play](https://github.com/paololazzari/play) Ein TUI-Spielplatz zum Experimentieren mit Ihren Lieblingsprogrammen wie grep, sed, awk, jq und yq
- [posting](https://github.com/darrenburns/posting) Ein leistungsstarker HTTP-Client, der in Ihrem Terminal lebt
- [pproftui](https://github.com/Oloruntobi1/pproftui) Eine terminalbasierte Benutzeroberfläche für Go's pprof, die Profiling interaktiv macht
- [proxymock](https://proxymock.io) Ein Netzwerkrekorder, der API-Payloads in einer TUI anzeigt und automatisch Tests und Mocks aus den Beobachtungen generiert.
- [prs](https://github.com/dhth/prs) Bleiben Sie über PRs auf dem Laufenden, ohne das Terminal zu verlassen
- [pudb](https://github.com/inducer/pudb) Ein konsolenbasierter visueller Debugger für Python
- [pyautogit](https://github.com/jwlodek/pyautogit) Eine Terminal-UI zur Verwaltung von Git-Repositories, geschrieben mit py_cui
- [qo](https://github.com/kiki-ki/go-qo) Interaktiver SQL-Filter für JSON, CSV, TSV und andere Streams.
- [rainfrog](https://github.com/achristmascarl/rainfrog) Eine Datenbankmanagement-TUI für Postgres, MySQL und SQLite, geschrieben in Rust
- [regex-tui](https://github.com/vitor-mariano/regex-tui) Eine einfache TUI zur Visualisierung und zum Testen regulärer Ausdrücke
- [resterm](https://github.com/unkn0wn-root/resterm) Ein Terminal-Client für HTTP/GraphQL/gRPC mit Unterstützung für WebSockets, SSE, Workflows, Profiling, OpenAPI und Response-Diffs.
- [runme](https://github.com/stateful/runme) Code-Schnipsel direkt aus Ihrer README.md oder anderen Markdowns entdecken und ausführen
- [sls-dev-tools](https://github.com/Theodo-UK/sls-dev-tools) Entwickler-Tools für die Serverless-Welt
- [snips.sh](https://github.com/robherley/snips.sh) ✂️ passwortlose, anonyme SSH-gestützte Pastebin mit einer benutzerfreundlichen TUI und Web-UI
- [stu](https://github.com/lusingander/stu) Eine TUI für Amazon S3
- [termdbms](https://github.com/mathaou/termdbms) Eine TUI zum Betrachten und Bearbeiten von Datenbankdateien.
- [terraform-tui](https://github.com/idoavrah/terraform-tui) Terraform-Zustand betrachten und damit interagieren
- [Toad](https://github.com/batrachianai/toad) Eine vereinheitlichte Schnittstelle für KI
- [toolui](https://github.com/jinek/ToolUI) Dotnet Core Anwendung zur Verwaltung installierter Nuget-Tools
- [tokui](https://github.com/zdyxry/tokui) Eine interaktive TUI zur Visualisierung von Codestatistiken von tokei.
- [Twig](https://github.com/workdone0/twig) Terminal-UI zum interaktiven Durchsuchen von JSON- und YAML-Dateien.
- [serie](https://github.com/lusingander/serie) Ein reichhaltiger Git-Commit-Graph
- [soft-serve](https://github.com/charmbracelet/soft-serve) Ein schmackhafter, selbsthostbarer Git-Server für die Kommandozeile
- [sot](https://github.com/anistark/sot) Ein top-ähnliches System-Observability-Tool geschrieben in Python
- [sqlit](https://github.com/Maxteabag/sqlit) Eine leichtgewichtige TUI für SQL-Datenbanken inspiriert von lazygit
- [sq](https://github.com/sheenazien8/sq) Ein Datenbank-Client, der speziell für Vim-Nutzer entwickelt wurde
- [tig](https://github.com/jonas/tig) Textmodus-Interface für Git
- [turbostream](https://github.com/turboline-ai/turbostream) Werkzeug zum Extrahieren wichtiger Signale aus hochfrequenten Streaming-Daten mittels KI-Agenten
- [vctui](https://github.com/thebsdbox/vctui) Konsolenschnittstelle für vCenter
- [violet](https://github.com/braheezy/violet) Farbenfrohes TUI-Frontend zum Ausführen von Vagrant-Befehlen
- [VT Code](https://github.com/vinhnx/vtcode) VT Code - Semantischer Coding-Agent
- [Wikit](https://github.com/BryanCE/wikit) TUI zur Verwaltung von Wiki.js Instanzen
- [ec](https://github.com/chojs23/ec) Ein nativ in TUI eingebettetes Git Mergetool mit 3 Spalten
---

</details>

<details open><summary><h2>Docker/LXC/K8s</h2></summary>

- [Argonaut](https://github.com/darksworm/argonaut) ArgoCD TUI
- [cruise](https://github.com/cruise-org/cruise) Eine Container-Management TUI
- [ctop](https://github.com/bcicen/ctop) Top-ähnliche Schnittstelle für Container-Metriken
- [d4s](https://github.com/jr-k/d4s) Eine schnelle, tastaturgesteuerte Terminal-UI zur Verwaltung von Docker-Containern, Compose-Stacks und Swarm-Services mit der Ergonomie von K9s
- [dtop](https://github.com/amir20/dtop) Terminal-Dashboard zur Docker-Überwachung über mehrere Hosts hinweg
- [dive](https://github.com/wagoodman/dive) Ein Werkzeug zur Untersuchung jeder Ebene in einem Docker-Image
- [dockly](https://github.com/lirantal/dockly) Immersives Terminal-Interface zur Verwaltung von Docker-Containern und Services
- [DockMate](https://github.com/shubh-io/dockmate) Ein leichtgewichtiger TUI-Manager für Docker und Podman
- [docker-dash](https://github.com/GustavoCaso/docker-dash) Ein vollständiges TUI-Management-Tool für Docker
- [dprs](https://github.com/durableprogramming/dprs) Eine TUI zur Verwaltung von Docker-Containern mit Echtzeitüberwachung und Log-Streaming
- [dry](https://github.com/moncho/dry) Ein Docker-Manager für das Terminal
- [ducker](https://github.com/robertpsoane/ducker) Eine etwas "verrückte" Docker TUI basierend auf k9s
- [e1s](https://github.com/keidarcy/e1s) TUI zur Verwaltung von AWS ECS Ressourcen
- [eks-node-viewer](https://github.com/awslabs/eks-node-viewer/) Visualisierung der dynamischen Node-Auslastung innerhalb eines Kubernetes-Clusters
- [etcd-walker](https://github.com/nexusriot/etcd-walker/) Open-Source TUI Werkzeug zur Verwaltung von etcd Schlüsseln
- [k9s](https://github.com/derailed/k9s) TUI zur Verwaltung eines Kubernetes-Clusters
- [k8s-tui](https://github.com/otavioCosta2110/k8s-tui) TUI Kubernetes Ressourcenmanager mit Multi-Cluster Unterstützung
- [kdash](https://github.com/kdash-rs/kdash) Ein einfaches und schnelles Dashboard für Kubernetes
- [kftui](https://github.com/hcavarsan/kftray) Eine TUI zur Verwaltung mehrerer kubectl port-forward Befehle, mit Unterstützung für UDP und K8s Proxy.
- [ktop](https://github.com/vladimirvivien/ktop) Ein top-ähnliches Werkzeug für Ihre Kubernetes-Cluster
- [kubetui](https://github.com/sarub0b0/kubetui) Ein TUI Werkzeug konzipiert für das Monitoring von Kubernetes Ressourcen.
- [lazycontainer](https://github.com/andreybleme/lazycontainer) TUI zur Verwaltung von Apple-Containern
- [lazydocker](https://github.com/jesseduffield/lazydocker) Der einfachere Weg, alles rund um Docker zu verwalten
- [lazytrivy](https://github.com/owenrumney/lazytrivy) Der einfachere Weg, Images, k8s und das Dateisystem mit Trivy zu scannen
- [oxker](https://github.com/mrjackwills/oxker) Eine einfache TUI zum Betrachten und Steuern von Docker-Containern
- [Pocker](https://github.com/pommee/Pocker) TUI-basierte Anwendung für Docker-bezogene Aufgaben.
- [Podman-tui](https://github.com/containers/podman-tui) TUI für Podman Container
- [sen](https://github.com/TomasTomecek/sen) Terminal Benutzeroberfläche für die Docker Engine
- [talos-pilot](https://github.com/handfish/talos-pilot) TUI für Talos Linux bietet Echtzeit-Node-Monitoring, Log-Streaming und verschiedene Diagnosen
---

</details>

<details open><summary><h2>Editoren</h2></summary>

- [amp](https://github.com/jmacdonald/amp) Ein kompletter Texteditor für Ihr Terminal
- [C-Edit](https://github.com/velorek1/c-edit) Ein Texteditor mit Dropdown-Menüs im Stil des MS-DOS Editors
- [Durdraw](https://github.com/cmang/durdraw) Ein Editor für ASCII-, Unicode- und ANSI-Kunst
- [Edit](https://github.com/microsoft/edit) Ein einfacher Texteditor. Hommage an den klassischen MS-DOS Editor.
- [Fresh](https://github.com/sinelaw/fresh) Ein einfach zu bedienender, leistungsstarker und schneller terminalbasierter Texteditor.
- [helix](https://helix-editor.com/) Ein postmoderner Texteditor.
- [frogmouth](https://github.com/Textualize/frogmouth) Ein Markdown-Browser für Ihr Terminal
- [kakoune](http://kakoune.org/) Ein moderner, modaler Texteditor mit Fokus auf Interaktivität und Effizienz
- [kilo](https://github.com/antirez/kilo) Ein minimaler, aber kompletter Editor in etwa 1000 Zeilen C-Code.
- [maki](https://sr.ht/~bscit/maki/) Ein einfacher tabulator-basierter Texteditor mit Dateinavigation und Schwerpunkt auf Akku-Schonung
- [markln](https://github.com/xqtr/markln) Ein terminalbasierter Markdown-Editor, gebaut mit Textual.
- [micro](https://github.com/zyedidia/micro) Ein moderner und intuitiver terminalbasierter Texteditor
- [nino](https://github.com/evanlin96069/nino) Ein kleiner terminalbasierter Texteditor, geschrieben in C.
- [orbiton](https://github.com/xyproto/orbiton) Durch VT100 begrenzter Texteditor, geeignet für Programmierung, Git-Commit-Nachrichten und Markdown-Bearbeitung
- [slap](https://github.com/slap-editor/slap) Sublime-ähnlicher terminalbasierter Texteditor
- [tilde](https://github.com/gphalkes/tilde) Intuitiver Texteditor für das Terminal
- [thymus](https://github.com/blademd/thymus) Ein interaktiver Browser & Editor für Netzwerkkonfigurationsdateien.
- [treemd](https://github.com/Epistates/treemd) Ein Markdown-Navigator mit baumbasierter struktureller Navigation
- [turbo](https://github.com/magiblot/turbo) Ein experimenteller Texteditor für das Terminal, basierend auf Scintilla und Turbo Vision
- [vis](https://github.com/martanne/vis) Ein vi-ähnlicher Editor basierend auf den strukturellen regulären Ausdrücken von Plan 9
- [zee](https://github.com/zee-editor/zee) Ein moderner Texteditor für das Terminal geschrieben in Rust
---

</details>

<details open><summary><h2>Dateimanager</h2></summary>

- [adbtuifm](https://github.com/darkhz/adbtuifm) Eine TUI Dateimanager für Android, basierend auf der Android Debug Bridge (ADB).
- [broot](https://github.com/Canop/broot) Ein neuer Weg, Verzeichnisbäume zu sehen und darin zu navigieren
- [deletor](https://github.com/pashkov256/deletor) Dateien effizient verwalten und löschen mit einer interaktiven TUI und skriptfähigem CLI.
- [far2l](https://github.com/elfmz/far2l) Linux-Portierung des Far v2 Dateimanagers
- [fml](https://github.com/wick3dr0se/fml) :file_folder: Ein verblüffend einfacher, schneller Dateimanager geschrieben in BASH v4.2+.
- [goful](https://github.com/anmitsu/goful) ein leistungsstarker TUI Dateimanager geschrieben in Go.
- [lf](https://github.com/gokcehan/lf) Ein in Go geschriebener Terminal-Dateimanager, stark inspiriert vom ranger Dateimanager.
- [mc](https://github.com/MidnightCommander/mc) GNU Midnight Commander. Ein freier, plattformübergreifender orthodoxer Dateimanager.
- [nnn](https://github.com/jarun/nnn) n³ Der unorthoxe Terminal-Dateimanager.
- [ntc](https://codeberg.org/ItsZariep/ntc) Ncurses tabulator-basierter Dateiauswähler.
- [ranger](https://github.com/ranger/ranger) Ein VIM-inspirierter Dateimanager für die Konsole.
- [rovr](https://github.com/NSPC911/rovr) Ein postmoderner Terminal-Dateimanager.
- [s3duck-tui](https://github.com/nexusriot/s3duck-tui) Eine TUI für S3-Clients.
- [sfm](https://github.com/afify/sfm) Einfacher Dateimanager.
- [superfile](https://github.com/MHNightCat/superfile) Ziemlich schicker und moderner Terminal-Dateimanager.
- [TUIFIManager](https://github.com/GiorgosXou/TUIFIManager) Ein plattformübergreifender terminalbasierter Dateimanager _(unterstützt termux)_.
- [Vifm](https://github.com/vifm/vifm) Ein TUI Dateimanager mit vi-Keybindings und anderem vim-ähnlichen Verhalten.
- [yazi](https://github.com/sxyazi/yazi) Razend schneller Terminal-Dateimanager geschrieben in Rust, basierend auf async I/O.
---

</details>

<details open><summary><h2>Spiele</h2></summary>

- [tui-2048](https://github.com/ps06756/tui-2048) Das Spiel 2048 für Ihr Terminal
- [awkaster](https://github.com/TheMozg/awk-raycaster) Pseudo-3D Shooter komplett in gawk geschrieben unter Verwendung der Raycasting-Technik
- [balatrotui](https://github.com/Passeriform/BalatroTUI) Ein TUI Klon von Balatro
- [bastet](https://github.com/fph/bastet) Bösartiges Tetris-ähnliches Spiel
- [botany](https://github.com/jifunks/botany/) Virtueller Pflanzen-Freund
- [brickgame-4bit](https://github.com/ilyakurdyukov/brickgame-4bit) Brick Game Emulator (4-Bit Holtek Chip)
- [BrogueCE](https://github.com/tmewett/BrogueCE) Wunderschöner Roguelike Dungeon Crawler
- [cbonsai](https://gitlab.com/jallbrit/cbonsai) Ein Bonsai-Baum Generator
- [chess-tui](https://github.com/thomas-mauran/chess-tui) Spielen Sie Schach in Ihrem Terminal, gebaut in Rust
- [clidle](https://github.com/ajeetdsouza/clidle) Spielen Sie Wordle in Ihrem Terminal. Funktioniert auch über SSH!
- [csol](https://github.com/nielssp/csol) Sammlung von Solitär/Patience-Spielen wie Klondike, FreeCell, Spider und Yukon
- [DOOM-ASCII](https://github.com/wojciech-graj/doom-ascii) Textbasiertes DOOM im Terminal.
- [Gameboy Emulator](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) Ein PHP Terminal GameBoy Emulator
- [GitType](https://github.com/unhappychoice/gittype) Ein CLI-Code-Tippspiel, das Ihren Quellcode in Tipp-Herausforderungen verwandelt
- [go-life](https://github.com/sachaos/go-life) Terminalbasiertes Conway's Spiel des Lebens
- [gokemon](https://github.com/nathanieltooley/gokemon) Ein terminalbasierter Pokemon-Kampfsimulator
- [Greed](https://gitlab.com/esr/greed) Ein Spiel des Konsums. Essen Sie so viel Sie können, bevor Sie sich in eine Ecke fressen!
- [Maze](https://github.com/itchyny/maze) Einfaches Labyrinth-Spiel geschrieben in Go.
- [Maze TUI](https://github.com/agl-alexglopez/maze-tui) Labyrinthe bauen und mit verschiedenen Algorithmen lösen.
- [Micro Snake](https://github.com/troglobit/snake) Ein kleines Snake-Spiel, das ANSI-Escape-Sequenzen zum Zeichnen des Spielfelds nutzt.
- [Micro Tetris](https://github.com/troglobit/tetris) Eine der kleinsten Tetris-Implementierungen der Welt, nutzt nur ANSI-Escape-Sequenzen zum Zeichnen.
- [minesweep-rs](https://github.com/cpcloud/minesweep-rs) Ein Minesweeper-Spiel geschrieben in Rust unter Verwendung von tui-rs.
- [minesweeper_4d_rs](https://github.com/itabesamesa/minesweeper_4d_rs) 4D Minesweeper geschrieben in Rust unter Verwendung von Ratatui (kann auch für klassisches Minesweeper genutzt werden)
- [moon-buggy](https://github.com/seehuhn/moon-buggy) Fahren Sie mit einem Auto über den Mond
- [MyMan](https://sourceforge.net/projects/myman/) MyMan ist ein Videospiel für Farb- und Monochrom-Textterminals im Genre von Namcos Pac-Man
- [nchess](https://github.com/billyvinning/nchess) Schach im Terminal, geschrieben in C.
- [NetHack](https://github.com/NetHack/NetHack) Dungeon-Erkundungsspiel
- [nInvaders](http://ninvaders.sourceforge.net/) Space Invaders
- [nSnake](https://github.com/alexdantas/nSnake) Das klassische Snake-Spiel mit Text-Interface
- [nudoku](https://github.com/jubalh/nudoku) ncurses-basiertes Sudoku-Spiel
- [onx](https://github.com/vyalovvldmr/onx) Tic-Tac-Toe Client-Server-Spiel für Partner. Basiert auf textual und python.
- [pokete](https://github.com/lxgr-linux/pokete) Ein terminalbasiertes Spiel ähnlich wie Pokemon
- [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) P2P Terminal-Spiel über Weltraumpiraten, die Basketball in der Galaxie spielen.
- [snake](https://github.com/wick3dr0se/snake) :video_game: Ein minimales TUI Snake-Spiel geschrieben in purem BASH v5.1+
- [Square Tic Tac Toe](https://github.com/learnbyexample/TUI-apps/tree/main/SquareTicTacToe) Wie Tic-Tac-Toe, aber bilden Sie ein Quadrat mit 4 Ecken statt einer Linie
- [ssHattrick](https://github.com/ricott1/sshattrick) Spielen Sie Hattrick in Ihrem Terminal über SSH.
- [sshtron](https://github.com/zachlatta/sshtron) Mehrspieler-Lightcycle-Spiel, das über SSH läuft
- [sssnake](https://github.com/AngelJumbo/sssnake) Das klassische Snake-Spiel für das Terminal, das sich selbst spielen kann und als Bildschirmschoner genutzt werden kann.
- [steam-tui](https://github.com/dmadisetti/steam-tui) Einfacher TUI-Client für steamcmd. Ermöglicht grafisches Starten, Aktualisieren und Herunterladen von Steam-Spielen.
- [sudoku-rs](https://github.com/MitchelPaulin/sudoku-rs) Sudoku gebaut mit tui-rs
- [sweeper](https://github.com/igor47/sweeper) Minesweeper unter Verwendung von curtsies
- [terminal-phase](https://gitlab.com/dustyweb/terminal-phase) Space-Shooter für das Terminal!
- [terminal-pong](https://github.com/IshmamR/terminal.pong) Ein einfaches, unterhaltsames Ping-Pong-Spiel für das Terminal.
- [termrex](https://github.com/SATYADAHAL/termrex) Ein terminalbasierter Endless-Runner inspiriert vom Chrome Dino-Spiel.
- [tetro-tui](https://github.com/Strophox/tetro-tui) Ein sehr konfigurierbares Tetris-ähnliches Spiel mit ASCII-Partikeln, Replays und mehr.
- [tinytetris](https://github.com/taylorconor/tinytetris) 80x23 Terminal-Tetris!
- [tty-solitaire](https://github.com/mpereira/tty-solitaire) Solitär läuft in Ihrem Terminal!
- [typeinc](https://github.com/AnirudhG07/Typeinc) ncurses-basierter Tippgeschwindigkeitstest mit verschiedenen Schwierigkeitsstufen.
- [typing-game-cli](https://github.com/akgondber/typing-game-cli) Kommandozeilen-Spiel zum Üben der Tippgeschwindigkeit gegen einen Roboter oder das eigene beste Ergebnis
- [UniPac](https://github.com/jesper-olsen/UniPac) Unicode-gestütztes Pac-Man für das Terminal, geschrieben in Rust.
- [wocogo](https://codeberg.org/kedlubnowski/wocogo) Worte aus einer Liste gegebener Segmente bilden. Einfaches TUI-Spiel in Python, ähnlich wie NY Times Combinations.
- [Wordle](https://github.com/m-dango/raku-wordle/) Skript und Bibliothek für Wordle, geschrieben in Raku
- [Zigtris](https://github.com/ringtailsoftware/zigtris) Noch ein Terminal-Tetris
- [Zoridor](https://github.com/ringtailsoftware/zoridor) Quoridor im Terminal spielen
---

</details>

<details open><summary><h2>Bibliotheken</h2></summary>

<h3>Python</h3>

- [Argenta](https://github.com/koloideal/Argenta) Bibliothek zum Erstellen modularer Anwendungen **Python**
- [blessed](https://github.com/jquast/blessed) Blessed ist eine einfache, praktische Bibliothek zur Erstellung von **Python** Terminal-Apps
- [blessings](https://github.com/erikrose/blessings) Ein **Python** Wrapper für ncurses, der Ihren Code ansehnlich macht
- [notcurses](https://github.com/dankamongmen/notcurses) Funkelnde Zeichengrafik-/TUI-Bibliothek für **C** und **Python**. Definitiv kein curses.
- [py_cui](https://github.com/jwlodek/py_cui) **Python** Bibliothek mit dem Ziel, widgetbasierte TUI/CUI-Schnittstellen so einfach wie möglich zu gestalten.
- [pytermgui](https://github.com/bczsalba/pytermgui) Ein einfaches, aber leistungsstarkes TUI-Framework für Ihre **Python** (3.7+) Anwendungen.
- [Python Prompt Toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) Bibliothek zum Erstellen leistungsstarker interaktiver Kommandozeilenanwendungen in **Python**
- [pyTermTk](https://github.com/ceccopierangiolieugenio/pyTermTk) Eigenständige TUI-Bibliothek für **Python** mit QT-ähnlicher API-Semantik
- [Rich](https://github.com/willmcgugan/rich) Eine **Python** Bibliothek für Rich-Text und schöne Formatierung im Terminal.
- [textual](https://github.com/willmcgugan/textual) Ein TUI (Text User Interface) Framework für **Python**, inspiriert von moderner Webentwicklung.
- [UniCurses](https://github.com/unicurses/unicurses) Ein **Python** Modul, das Curses-Funktionalität auf allen Betriebssystemen bereitstellen will.
- [urwid](https://github.com/urwid/urwid) Eine Konsolen-Benutzeroberflächenbibliothek für **Python** unter Linux, OSX, Cygwin oder anderen unixoiden OS.
- [Vindauga](https://github.com/gabbpuy/vindauga) Eine **Python** Implementierung der unter BSD lizenzierten C++ Turbo Vision Bibliothek.

<h3>GO</h3>

- [bubbletea](https://github.com/charmbracelet/bubbletea) Ein **Go** Framework basierend auf Elm, um funktionale und spaßige Terminal-Apps zu bauen
- [gocui](https://github.com/jroimartin/gocui) Minimalistisches **Go** Paket zur Erstellung von Console User Interfaces
- [pterm](https://github.com/pterm/pterm/) Ein modernes **Go** Modul zur Verschönerung von Konsolenausgaben. Mit Diagrammen, Fortschrittsbalken, Tabellen, Bäumen und vielem mehr!
- [stickers](https://github.com/76creates/stickers) Bausteine für charmbracelet/lipgloss in **Go**
- [tui-go](https://github.com/marcusolsson/tui-go) Eine **Go** UI-Bibliothek für Terminalanwendungen (veraltet)
- [tview](https://github.com/rivo/tview/) Terminal-UI-Bibliothek mit reichhaltigen, interaktiven Widgets — geschrieben in **Go**
- [tcell](https://github.com/gdamore/tcell) Tcell ist ein alternatives **Go** Terminal-Paket, ähnlich wie termbox, aber in einigen Punkten besser.

<h3>C</h3>

- [AnbUI](https://github.com/oerg866/anbui) Eine minimale Text-UI Bibliothek in **C**
- [libuv](https://github.com/libuv/libuv) Plattformübergreifende asynchrone I/O Bibliothek - geschrieben in **C**
- [ncurses](https://invisible-island.net/ncurses/announce.html) Eine klassische **C** Bibliothek mit Bindings für viele Sprachen
- [tuibox](https://github.com/Cubified/tuibox) Eine Single-Header **C** Terminal-UI-Bibliothek, fähig zur Erstellung mausgesteuerter, interaktiver Anwendungen.

<h3>C++</h3>

- [ASCII_Board_Game_Engine](https://github.com/tjunruh/ASCII_Board_Game_Engine) Eine Grafik-Engine zur Erstellung von Brettspielen in **C++**
- [ConsoleCraftEngine](https://github.com/ural89/ConsoleCraftEngine) Eine terminalbasierte 2D-Game-Engine geschrieben in **C++**.
- [FINAL CUT](https://github.com/gansm/finalcut) **C++** Bibliothek zur Erstellung von Terminalanwendungen mit textbasierten Widgets
- [FTXUI](https://github.com/ArthurSonzogni/FTXUI) 💻 **C++** Funktionale Terminal-Benutzeroberfläche. ❤️
- [GGUI](https://github.com/Gabidal/GGUI) **C++17** Strukturierte Terminal-Benutzeroberfläche. 🐧/🪟
- [imtui](https://github.com/ggerganov/imtui) Eine Immediate-Mode-Text-UI Bibliothek für **C++**, unterstützt 256 ANSI Farben und Maus-/Tastatureingaben.
- [rang](https://github.com/agauniyal/rang) Eine minimale Modern-C++-Bibliothek nur aus Headern für Terminal-Annehmlichkeiten.
- [termdb](https://github.com/agauniyal/termdb) Terminfo Parser für modernes **C++**
- [Tui Widgets](https://github.com/tuiwidgets/tuiwidgets) Ein High-Level widgetbasiertes Toolkit für Terminalanwendungen in **C++**
- [tvision](https://github.com/magiblot/tvision) Eine moderne Portierung von **C++** Turbo Vision 2.0, plattformübergreifend mit Unicode-Unterstützung.
- [uvw](https://github.com/skypjack/uvw) Header-only, eventbasierter libuv Wrapper in modernem **C++**
- [xtd](https://github.com/gammasoft71/xtd) Freies Modern-C++-Framework zur Erstellung von Konsolen- (CLI), Formular- (GUI wie WinForms) und Unit-Test-Anwendungen.

<h3>Java</h3>

- [casciian](https://github.com/crramirez/casciian) Eine Text-UI Bibliothek für **Java** basierend auf "Jexer" ohne AWT/Swing-Abhängigkeiten.
- [Jexer](https://gitlab.com/AutumnMeowMeow/jexer) Eine **Java** Bibliothek, die ein textbasiertes Fenstersystem implementiert, das vage an Turbo Vision erinnert.
- [Lanterna](https://github.com/mabe02/lanterna) Eine **Java** Bibliothek zur Erstellung textbasierter UIs, sehr ähnlich zur C-Bibliothek curses.
- [TUI4J](https://github.com/WilliamAGH/tui4j) Ein **Java** Terminal-UI-Framework mit Bubble Tea (Go) Portierung.

<h3>.NET</h3>

- [Consolonia](https://github.com/jinek/Consolonia) Ein **.NET** terminalbasiertes GUI-Framework mit XAML-Unterstützung
- [Hex1b](https://github.com/mitchdenny/hex1b) Eine **.NET** Bibliothek zum Bauen interaktiver TUIs mit einer von React inspirierten deklarativen API
- [SharpConsoleUI](https://github.com/nickprotop/ConsoleEx) Multi-Window-TUI-Framework für **.NET** mit überlappenden Fenstern.
- [Spectre.Console](https://github.com/spectreconsole/spectre.console) Eine **.NET** Bibliothek zur Erstellung schöner Konsolenanwendungen
- [Terminal.Gui](https://github.com/gui-cs/Terminal.Gui) Plattformübergreifendes Terminal-UI Toolkit für **.NET**

<h3>Rust</h3>

- [iocraft](https://github.com/ccbrown/iocraft) **Rust** Crate für wunderschöne TUIs mit deklarativer, React-ähnlicher API.
- [Ratatui](https://github.com/tui-rs-revival/ratatui) Ein **Rust** Crate zum Bauen von Terminal-UIs (aktiv gewarteter Fork von tui-rs).
- [tui-input](https://github.com/sayanarijit/tui-input) TUI Input-Bibliothek für mehrere Backends wie tui-rs und ratatui in **Rust**
- [tui-rs](https://github.com/fdehau/tui-rs) Terminal-Benutzeroberflächen und Dashboards mit **Rust** (nicht mehr gewartet, nutzen Sie Ratatui).
- [Zaz](https://github.com/raphamorim/zaz) Eine **Rust** TUI-Bibliothek für effizientes Terminal-Rendering.

<h3>Andere</h3>

- [Ashen](https://github.com/colinta/Ashen) Ein Elm-inspiriertes Framework geschrieben in **Swift**
- [blessed](https://github.com/chjj/blessed) High-Level Terminal-Schnittstelle für **Node.js**
- [gum](https://github.com/charmbracelet/gum) Ein Werkzeug für glanzvolle **Shell** Skripte
- [ink](https://github.com/vadimdemedes/ink) React für interaktive **Node.js** Kommandozeilen-Apps
- [ink-web](https://github.com/cjroth/ink-web) Browserbasierte Runtime für Ink, die React TUI Apps mittels xterm.js rendert.
- [Melker](https://melker.sh) HTML-ähnliches TUI-Framework für **TypeScript/Deno** mit Flexbox-Layout.
- [moulti](https://moulti.run/) Ein CLI-gesteuertes TUI zur Anzeige beliebiger Ausgaben in einklappbaren Blöcken. Konzipiert für **Shell** Skripte.
- [nimwave](https://github.com/ansiwave/nimwave) Text-Schnittstellen für Terminal oder Browser in **Nim** bauen
- [nocterm](https://github.com/Norbert515/nocterm) Ein Flutter-ähnliches TUI-Framework für **Dart** mit Hot-Reload.
- [OpenTUI](https://github.com/sst/opentui) Eine **TypeScript** Bibliothek zum Bauen von Terminal-Benutzeroberflächen
- [php-tui](https://github.com/php-tui/php-tui) Umfangreiche TUI-Bibliothek für **PHP** basierend auf Ratatui.
- [termbox2](https://github.com/termbox/termbox2) Eine Terminal-Rendering Bibliothek zur Erstellung von TUIs.
- [TermGL](https://github.com/wojciech-graj/TermGL) Eine terminalbasierte Grafikbibliothek für 2D und 3D Grafik.
- [Thermage](https://github.com/thermage/thermage) Thermage ist eine **PHP** Bibliothek für die Anpassung von CLI-Farben, Formatierungen und Themes.
---

</details>

<details open><summary><h2>Messaging</h2></summary>

- [aerc](https://aerc-mail.org/) E-Mail-Client
- [alpine](https://alpineapp.email/) E-Mail-Client
- [basalt](https://github.com/erikjuhani/basalt) TUI Anwendung zur Verwaltung von Obsidian Vaults und Notizen direkt vom Terminal.
- [blitzdenk](https://github.com/Lommix/blitzdenk) Minimaler Multi-API Auto-Kontext Projekt-Chatbot als TUI
- [Devzat](https://github.com/quackduck/devzat) Chat über SSH, geschrieben in Golang, selbsthostbar.
- [discordo](https://github.com/ayntgl/discordo) Ein leichtgewichtiger, sicherer und funktionsreicher Discord-Terminal-Client
- [endcord](https://github.com/mzivic7/endcord) Funktionsreicher Discord TUI-Client.
- [Gomphotherium](https://github.com/mrusme/gomphotherium) Ein Kommandozeilen-Client für Mastodon.
- [gomuks](https://github.com/tulir/gomuks) Matrix-Client
- [gurk-rs](https://github.com/boxdot/gurk-rs) Signal Messenger Client für das Terminal
- [iamb](https://iamb.chat) Ein Matrix-Client für Vim-Süchtige, geschrieben in Rust
- [instagram-cli](https://github.com/supreme-gg-gg/instagram-cli) Nutzen Sie Instagram vom Terminal aus
- [irssi](https://irssi.org/) Ein IRC-Terminal-Client
- [mastui](https://github.com/kimusan/mastui) Mastodon TUI
- [matcha](https://github.com/floatpane/matcha) E-Mail-Client
- [matterhorn](https://github.com/matterhorn-chat/matterhorn) Ein Mattermost-Terminal-Client.
- [mcabber](https://mcabber.com/) XMPP (Jabber) Client
- [meli](https://meli.delivery/) E-Mail-Client
- [Mutt](https://gitlab.com/muttmua/mutt) E-Mail-Client
- [nchat](https://github.com/d99kris/nchat) Telegram/WhatsApp Client
- [nomadnet](https://github.com/markqvist/NomadNet) Sicheres Nachrichten-Netzwerk basierend auf Reticulum
- [nostui](https://github.com/akiomik/nostui) Nostr-Client
- [nostratui](https://github.com/adamm-xyz/nostratui) Eine Terminal-Benutzeroberfläche zum Durchsuchen von Nostr-Posts, geschrieben in Rust.
- [Profanity](https://profanity-im.github.io) XMPP (Jabber) Client
- [sclack](https://github.com/haskellcamargo/sclack) Slack-Terminal-Client
- [scli](https://github.com/isamert/scli/) Einfache Terminal-Benutzeroberfläche für Signal Messenger
- [siggo](https://github.com/derricw/siggo) Terminal-UI für signal-cli, geschrieben in Go
- [Slack-term](https://github.com/erroneousboat/slack-term) Slack-Client für Ihr Terminal
- [sup](https://github.com/sup-heliotrope/sup) Ein curses-basierter E-Mail-Client im "Thread-mit-Tags" Stil
- [SuperChat](https://github.com/serialexp/superchat) Terminalbasierte Chat-Anwendung mit Thread-Unterstützung und eigenem Binärprotokoll.
- [Superhighway84](https://github.com/mrusme/superhighway84) Von USENET inspiriertes dezentrales Diskussionssystem
- [tgt](https://github.com/FedericoBruzzone/tgt) Eine TUI für Telegram, geschrieben in Rust
- [toot](https://github.com/ihabunek/toot) Mastodon CLI & TUI
- [tuisky](https://github.com/sugyan/tuisky) TUI-Client für BlueSky
- [tuix](https://github.com/pythops/tuix) TUI zur Verwaltung von Bildschirmen
- [tut](https://github.com/RasmusLindroth/tut) Mastodon TUI-Client
- [twitch-tui](https://github.com/Xithrius/twitch-tui) Twitch-Chat im Terminal
- [Weechat](https://weechat.org/) Erweiterbarer Chat-Client
- [zulip-terminal](https://github.com/zulip/zulip-terminal) Offizieller Zulip-Terminal-Client
---

</details>

<details open><summary><h2>Sonstiges</h2></summary>

- [arttime](https://github.com/reportaman/arttime) Bringt die Schönheit von Text-Art mit der Funktionalität von Uhr, Timer und Zeitmanager zusammen.
- [asciiMol](https://github.com/dewberryants/asciiMol) Curses-basierter ASCII-Molekül-Viewer für Linux-Terminals.
- [bluetuith](https://github.com/darkhz/bluetuith) TUI-basierter Bluetooth-Verbindungsmanager.
- [bluetui](https://github.com/pythops/bluetui) Eine TUI zur Verwaltung von Bluetooth-Geräten.
- [Caligula](https://github.com/ifd3f/caligula) Benutzerfreundliche, leichtgewichtige TUI zum Schreiben von Disk-Images.
- [Captain's log](https://github.com/NikolaDucak/caps-log) Ein kleines TUI Journaling-Werkzeug
- [cava](https://github.com/karlstav/cava) Plattformübergreifender Audio-Visualisierer
- [cfdisk](https://github.com/util-linux/util-linux) TUI Partitions-Editor, enthalten in util-linux
- [cgdisk](https://www.rodsbooks.com/gdisk/cgdisk-walkthrough.html) TUI Partitions-Editor für GUID-Partitionstabellen, nach dem Vorbild von cfdisk
- [csvlens](https://github.com/YS-L/csvlens) TUI CSV-Viewer. Wie 'less', aber für CSV gemacht.
- [CrunchyCleaner](https://github.com/knuspii/crunchycleaner) Ein leichtgewichtiges Cache-Cleanup-Tool für Windows & Linux.
- [diary](https://github.com/actuday6418/Diary) Eine Tagebuch-App geschrieben in Rust, die Texte und Daten verschlüsselt.
- [DigiSurf](https://github.com/SeanMcLoughlin/digisurf) Ein TUI Signalwellen-Viewer
- [diskonaut](https://github.com/imsnif/diskonaut) Terminal-Festplattenplatz-Navigator
- [distrobox-tui](https://github.com/phanirithvij/distrobox-tui) TUI zur Verwaltung von Distrobox-Containern
- [ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector) Ein CLI-Werkzeug und Go-Bibliothek, die Instanztypen basierend auf Kriterien wie VCPUs und Speicher empfiehlt
- [emu2](https://github.com/dmsc/emu2) Ein einfacher DOS-Emulator für die Linux-Textkonsole.
- [flawz](https://github.com/orhun/flawz) Eine Terminal-UI zum Durchsuchen von Sicherheitslücken (CVEs)
- [fnf](https://github.com/leo-arch/fnf) Ein interaktiver Fuzzy-Finder für das Terminal
- [fzf](https://github.com/junegunn/fzf) Ein universeller Kommandozeilen-Fuzzy-Finder
- [gdu](https://github.com/dundee/gdu) Schneller Festplattenplatz-Analysator mit Konsolenschnittstelle, geschrieben in Go
- [gif-for-cli](https://github.com/google/gif-for-cli) Konvertiert ein GIF in ASCII
- [godap](https://github.com/Macmod/godap) Eine komplette TUI für LDAP, geschrieben in Golang
- [golazo](https://github.com/0xjuanma/golazo) Erhalten Sie Fußball-Live-Updates und Spielstatistiken in Ihrem Terminal
- [gpg-tui](https://github.com/orhun/gpg-tui) Eine Terminal-Benutzeroberfläche für GnuPG
- [HumBLE Explorer](https://github.com/koenvervloesem/humble-explorer) Ein plattformübergreifender Bluetooth Low Energy Scanner
- [IconicFonts](https://github.com/iconicFonts/iconic-fonts) Eine Sammlung angepasster Schriftarten mit über 60.000 Icons, speziell für TUIs.
- [impala](https://github.com/pythops/impala) TUI zur Verwaltung von WLAN
- [isw](https://gitlab.com/thom-cameron/isw) Einfache Stoppuhr-Anwendung für Pomodoro etc.
- [jrnl](https://jrnl.sh/) Notizen sammeln, ohne die Kommandozeile zu verlassen. Benutzerfreundlich, zukunftssicher, sicher.
- [keydex](https://github.com/shikaan/keydex) TUI Passwortmanager für KeePass-Datenbanken.
- [lazynginx](https://github.com/giacomomasseron/lazynginx) Einfache TUI zur Nginx-Verwaltung.
- [LearnByExample](https://github.com/learnbyexample/TUI-apps) Eine TUI mit Tutorials und über 300 Übungen zu Python, grep, awk, sed & Terminal-Nutzung.
- [lnav](https://lnav.org/) Ein fortschrittlicher Log-Viewer für kleinere Umgebungen
- [mac-cleanup-go](https://github.com/2ykwang/mac-cleanup-go) macOS Festplattenreinigung: Cache/Dev-Artefakte scannen, Vorschau und Löschen.
- [mapscii](https://github.com/rastapasta/mapscii) Braille- & ASCII-Weltkarten-Renderer für Ihre Konsole
- [mqttui](https://github.com/EdJoPaTo/mqttui) MQTT-Client geschrieben in Rust
- [moc](https://moc.daper.net/download) Konsolen-Audio-Player
- [moribito](https://github.com/ericschmar/moribito) Durchsuchen von LDAP-Verzeichnisbäumen und Ausführen von Abfragen.
- [NanoCore](https://github.com/AfaanBilal/NanoCore) Ein 8-Bit CPU Emulator TUI geschrieben in Rust.
- [neoss](https://github.com/PabloLec/neoss) Visualisierung von Socket-Statistiken für Unix-Systeme.
- [nmtui](https://developer.gnome.org/NetworkManager/stable/nmtui.html) ncurses Netzwerkmanager
- [oha](https://github.com/hatoo/oha) HTTP-Lastgenerator
- [packemon](https://github.com/ddddddO/packemon) Paketgenerator und Monitor.
- [pass-cli](https://github.com/arimxyer/pass-cli) Eine TUI und CLI für die Passwortverwaltung mit rclone-Cloud-Synchronisierung
- [PesterExplorer](https://github.com/HeyItsGilbert/PesterExplorer) Eine TUI zur Untersuchung von Pester-Ergebnissen.
- [pug](https://github.com/leg100/pug) Modul- und Infrastrukturmanagement für Terraform und Tofu.
- [physics-TUI](https://github.com/ClaudioRMalvino/physics_TUI) Physik-Anwendung für das Studium
- [ncdu](https://dev.yorhel.nl/ncdu) Festplattenplatz-Analysator mit ncurses-Interface
- [redu](https://github.com/drdo/redu) ncdu für Ihr restic-Repository.
- [nemu](https://github.com/nemuTUI/nemu) Eine TUI für QEMU
- [recoverpy](https://github.com/PabloLec/recoverpy) Eine TUI zur Wiederherstellung überschriebener oder gelöschter Daten.
- [rocket.term](https://github.com/gerstner-hub/rocket.term) Textbasierter Chat-Client für Rocket.chat.
- [smassh](https://github.com/kraanzu/smassh) Tippgeschwindigkeitstest-Anwendung inspiriert von MonkeyType.
- [steam_friends_list_tui](https://github.com/AdamWHY2K/steam_friends_list_tui) Die Steam-Freundesliste in der Kommandozeile
- [Systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) Programm zur Verwaltung von systemd Services via TUI.
- [tcpterm](https://github.com/sachaos/tcpterm) Paketvisualisierer in TUI.
- [tab-pal](https://github.com/ben-n93/tab-pal) Farbmuster in Tableau über die Kommandozeile bearbeiten.
- [term.everything](https://github.com/mmulet/term.everything) Jede GUI-App im Terminal ausführen
- [terminalperiodictable](https://github.com/velorek1/terminalperiodictable) Ein schönes TUI-Periodensystem für Unix-Systeme, in C geschrieben.
- [termshark](https://github.com/gcla/termshark) Terminal-UI für tshark
- [thokr](https://github.com/coloradocolby/thokr) Eine elegante Tipp-TUI geschrieben in Rust
- [tlock](https://github.com/eklairs/tlock) Manager für Zwei-Faktor-Authentifizierungs-Token im Terminal
- [tray-tui](https://github.com/Levizor/tray-tui) System-Tray in Ihrem Terminal
- [tttui](https://github.com/reidoboss/tttui) Von Monkeytype inspirierter Tipptest direkt im Terminal
- [ttyper](https://github.com/max-niederman/ttyper) Terminalbasierter Tipptest
- [tui-shop](https://github.com/Gcat101/tui-shop) Download-Werkzeug für TUIs/CLIs.
- [tweakcc](https://github.com/Piebald-AI/tweakcc) TUI zum Anpassen Ihrer Claude-Code-Themes und mehr.
- [typtea](https://github.com/ashish0kumar/typtea) Minimaler Tippgeschwindigkeitstest mit Unterstützung für Dutzende Programmiersprachen.
- [try-rs](https://github.com/tassiovirginio/try-rs/) Razend schnelle TUI zur Verwaltung temporärer Projekte.
- [vortix](https://github.com/Harry-kp/vortix) Terminal-UI für WireGuard und OpenVPN mit Echtzeit-Telemetrie.
- [wb](https://github.com/MertGunduz/wb) Eine TUI-Vokabelheft-App für Linux.
- [wego](https://github.com/schachmat/wego) Wetter-App
- [wavemon](https://github.com/uoaerg/wavemon) Überwachung drahtloser Geräte
- [wifitui](https://github.com/shazow/wifitui) Schnelle und freundliche WLAN-Terminal-UI.
- [WG Commander](https://github.com/andrianbdn/wg-cmd) TUI für einfaches WireGuard-VPN-Setup.
- [WireGuard Monitor](https://codeberg.org/anthonymills/Wireguard_Monitor) Einfache TUI in Rust zur Anzeige des Status von WireGuard-Verbindungen.
- [wttr.in](https://github.com/chubin/wttr.in) Der richtige Weg, das Wetter zu prüfen
- [WifUI](https://github.com/sohamw03/wifui) TUI zur Verwaltung von WLAN-Verbindungen unter Windows (Rust)
- [xplr](https://github.com/sayanarijit/xplr) Ein hackbarer, minimaler, schneller TUI Dateimanager.
- [x-cmd](https://github.com/x-cmd/x-cmd) Eine große Sammlung von Werkzeugen.
---

</details>

<details open><summary><h2>Multimedia</h2></summary>

- [ani-l](https://github.com/komposer-aml/ani-l) Rust-basiertes Anime-Browsing und Streaming ohne das Terminal zu verlassen
- [asak](https://github.com/chaosprint/asak) Plattformübergreifende TUI für Audioaufnahme/-wiedergabe
- [bookokrat](https://github.com/bugzmanov/bookokrat) EPUB-Reader mit vollem Funktionsumfang und Vim-Keybindings.
- [chafa](https://hpjansson.org/chafa/) Werkzeug zur Konvertierung von Bildern (auch animierte GIFs) in ANSI/Unicode Zeichenkunst.
- [cmdpxl](https://github.com/knosmos/cmdpxl) Praktischer Kommandozeilen-Bildeditor
- [cmus](https://cmus.github.io/) Ein kleiner, schneller und leistungsstarker Konsolen-Musikplayer für Unix-ähnliche Systeme.
- [ctune](https://github.com/An7ar35/ctune) ncurses-basierter Internetradio-Player für Linux.
- [draw](https://github.com/maaslalani/draw) Einfaches Zeichenwerkzeug im Terminal.
- [fancy-cat](https://github.com/freref/fancy-cat) Leichtgewichtiger PDF-Reader mit Vim-Keybindings
- [favicon-editor](https://github.com/xyproto/favicon-editor) Spartanischer Graustufen-Favicon-Editor
- [gadacz](https://github.com/rareitems/gadacz) Hörbuch-Player
- [GopherTube](https://github.com/krishnassh/gophertube) Terminalbasierter YouTube-Client, nutzt mpv zur Wiedergabe
- [Gorae](https://github.com/Han8931/gorae) Bibliothekar für PDFs und EPUBs mit Vim-Navigation.
- [image-sorter](https://github.com/jgalat/image-sorter) TUI zum Sortieren von Bildern unter Verwendung von Keybindings, in Rust geschrieben.
- [invidtui](https://github.com/darkhz/invidtui) TUI Invidious-Client für Windows, Linux und macOS.
- [jellyfin-tui](https://github.com/dhonus/jellyfin-tui) Jellyfin-Client
- [kew](https://github.com/ravachol/kew) Musikplayer für das Terminal unter Linux
- [line](https://github.com/pd3v/line) Kleiner Midi-Sequenzer und Sprache für Live-Coding
- [MAL-Cli](https://github.com/L4z3x/mal-tui) Terminal-Interface für die offizielle MyAnimeList API, in Rust geschrieben.
- [managarr](https://github.com/Dark-Alex-17/managarr) TUI und CLI zur Verwaltung Ihrer *arr-Server
- [manga-tui](https://github.com/josueBarretogit/manga-tui) Terminalbasierter Manga-Reader und Downloader mit Bild-Rendering.
- [marstui-audio](https://github.com/schooldanlp6/marstui-rustio) Audio-Management-Interface, ähnlich wie pavucontrol.
- [mps-youtube](https://github.com/mps-youtube/mps-youtube) Terminalbasierter YouTube-Player und Downloader
- [mpvc](https://github.com/gmt4/mpvc) mpc-ähnliche Steuerschnittstelle für mpv
- [nap](https://nap.sourceforge.net/) Napster-Client für Linux
- [ncspot](https://github.com/hrkfdn/ncspot) Plattformübergreifender ncurses Spotify-Client in Rust.
- [pipe-viewer](https://github.com/trizen/pipe-viewer) Leichtgewichtiger YouTube-Client für Linux, benötigt keinen API-Key.
- [ostui](https://git.sr.ht/~ser/ostui) CLI-Client für Subsonic-API Server wie gonic und Navidrome
- [pyradio](https://github.com/coderholic/pyradio) Web-Radio Player mit Tausenden Stationen.
- [RadioGoGo](https://github.com/Zi0P4tch0/RadioGoGo) Surfen auf globalen Radiowellen via TUI.
- [Relax-player](https://github.com/ebithril/relax-player) Leichtgewichtige, ablenkungsfreie Alternative zu webbasierten Umgebungsgeräusch-Playern.
- [roku-cli](https://github.com/winsbe01/roku-cli) Fernbedienung für Roku in der Kommandozeile
- [rmpc](https://mierak.github.io/rmpc/) Konfigurierbarer MPD-Client inspiriert von ncmpcpp und ranger.
- [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) MIDI-gesteuerte virtuelle Pfeifenorgel.
- [sonicradio](https://github.com/dancnb/sonicradio) Eleganter Radio-Player unter Verwendung der Radio-Browser API.
- [soundcloud2000](https://github.com/grobie/soundcloud2000) Ein Terminal-Client für SoundCloud
- [spotatui](https://github.com/LargeModGames/spotatui) Spotify-Client mit nativem Streaming und Lyrik-Synchronisation.
- [spotify-player](https://github.com/aome510/spotify-player) Spotify-Player im Terminal mit vollem Funktionsumfang.
- [spotui](https://github.com/ceuk/spotui) Spotify-Client geschrieben in Python
- [tdf](https://github.com/itsjunetime/tdf) Ein TUI-basierter PDF-Viewer
- [terminal-yt](https://github.com/jooooscha/terminal-yt) Kleiner, von newsboat inspirierter YouTube-Manager
- [termusic](https://github.com/tramhao/termusic) Musikplayer TUI in Rust geschrieben
- [textual-paint](https://github.com/1j01/textual-paint) MS Paint in Ihrem Terminal
- [timg](https://github.com/hzeller/timg) Ein Terminal-Bildbetrachter
- [tizonia-openmax-il](https://github.com/tizonia/tizonia-openmax-il) Cloud-Musikplayer für Linux (Spotify, YouTube, SoundCloud, etc.)
- [tortuise](https://github.com/buildoak/tortuise) Gaussian Splatting 3D-Viewer im Terminal.
- [Toutui](https://github.com/AlbanDAVID/Toutui) Audiobookshelf-Client für Linux
- [Trophy](https://github.com/taigrr/trophy) 3D-Modell-Viewer für OBJ- und GLB-Dateien
- [upiano](https://github.com/eliasdorneles/upiano) Ein Klavier im Terminal
- [valveFM](https://github.com/zorig/valvefm) Vintage FM-Radio TUI.
- [vlc](https://github.com/videolan/vlc) VLC enthält ein ncurses Interface, `vlc --intf ncurses`
- [waves](https://github.com/llehouerou/waves) Musikplayer mit Vim-Navigation und Radio-Modus.
- [wiremix](https://github.com/tsowell/wiremix) TUI Audio-Mixer für PipeWire.
- [xytz](https://github.com/xdagiz/xytz) Schöne TUI zum Herunterladen von YouTube-Videos/Playlists.
- [ytui-music](https://github.com/sudipghimire533/ytui-music) Musik von YouTube hören. Konfigurierbar, privat und schön.
- [ytdl-tui](https://github.com/darky/ytdl-tui) TUI zum Herunterladen von YouTube-Videos
- [ytfzf](https://github.com/pystardust/ytfzf) Finden und Abspielen von YouTube/Peertube Videos ohne API.
- [viu](https://github.com/viu-media/viu) Ihr Anime-Erlebnis im Terminal
- [vv](https://github.com/wolfpld/vv) Ein Terminal-Bildbetrachter mit Unterstützung für viele Formate.
---

</details>

<details open><summary><h2>Produktivität</h2></summary>

- [abook](https://abook.sourceforge.io/) TUI Adressbuch mit mutt-Integration
- [agent-deck](https://github.com/asheshgoplani/agent-deck) Terminal-Dashboard zur Verwaltung mehrerer KI-Coding-Agent Sessions
- [awsui](https://github.com/junminhong/awsui) Leistungsstarkes Interface für AWS Profil- und SSO-Management.
- [Bagels](https://github.com/EnhancedJax/Bagels) TUI Ausgaben-Tracker
- [Brief](https://github.com/WilliamAGH/brief) OpenAI Chat-Client mit Slash-Befehlen und lokaler Werkzeug-Ausführung.
- [calcure](https://github.com/anufrievroman/calcure) Moderner Kalender und Aufgabenmanager.
- [calcurse](https://calcurse.org/) Kalender und Terminplanungsanwendung für die Kommandozeile
- [clipse](https://github.com/savedra1/clipse) TUI-basierte Zwischenablage-Verwaltung
- [Chronos](https://github.com/samuelstranges/chronos) Ein vim-ähnlicher Kalender
- [Desktop-TUI](https://github.com/Julien-cpsn/desktop-tui) Eine Desktop-Umgebung ohne Grafik
- [doxx](https://github.com/bgreenwell/doxx) Dokumentenbetrachter für Microsoft Word-Dateien
- [drako](https://github.com/lucky7xz/drako) Rasterbasierter, anpassbarer Kommando- und TUI-Deck-Launcher
- [dvtm](https://github.com/martanne/dvtm) Terminal-Multiplexer mit Fensterverwaltung wie dwm
- [ekphos](https://github.com/hanebox/ekphos) Schnelles Forschungs-Werkzeug für Markdown in Rust.
- [elia](https://github.com/darrenburns/elia) ChatGPT-Client fürs Terminal, gebaut mit Textual
- [fjira](https://github.com/mk-5/fjira) TUI Anwendung für Atlassian Jira
- [GeekCalendar](https://github.com/fearlessgeekmedia/GeekCalendar) Kalender mit Vim-Keybindings.
- [Glow](https://github.com/charmbracelet/glow) Markdown-Reader, konzipiert, um die Eleganz von TUIs zu zeigen.
- [gocheat](https://github.com/Achno/gocheat) Schöne TUI Cheatsheet für Keybindings und Aliase
- [helm](https://github.com/0xjuanma/helm) Minimalistischer Pomodoro-Timer
- [hledger-ui](https://github.com/simonmichael/hledger) TUI zum Durchsuchen von Buchhaltungsdaten
- [h-m-m](https://github.com/nadrad/h-m-m) Hackers Mind Map
- [hnjobs](https://github.com/mwinters0/hnjobs) Finden Sie Ihren nächsten Job auf "Who's Hiring"
- [hygg](https://github.com/kruserr/hygg) 📚 Vereinfacht das Lesen. Minimalistischer Dokumenten-Reader.
- [HydroToDo](https://github.com/Henriquehnnm/hydrotodo) Einfache und schöne To-Do-Liste
- [HydroFetch](https://github.com/Henriquehnnm/hydrofetch) Werkzeug für Systeminformationen, für Fish Shell geschrieben.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) Befehlsvorlagen mit KI-Integration verwalten
- [jiratui](https://github.com/whyisdifficult/jiratui) Interaktion mit Atlassian Jira direkt aus der Shell
- [Judo](https://github.com/giacomopiccinini/judo) Multi-Datenbank TUI für To-Do-Listen (Rust + SQLite)
- [kabmat](https://github.com/PlankCipher/kabmat) Programm zur Verwaltung von Kanban-Boards mit Vim-Keybindings
- [kanban](https://github.com/fulsomenko/kanban) TUI Kanban-Board für Projektmanagement mit Sprint-Tracking.
- [kanban-python](https://github.com/Zaloog/kanban-python) Kanban-App geschrieben in Python
- [khal](https://github.com/pimutils/khal) Standardbasierter Kalender, synchronisierbar mit CalDAV-Servern
- [LazySSH](https://github.com/adembc/lazyssh) SSH-Manager zum Durchsuchen und Verbinden basierend auf SSH-Konfigurationen.
- [levite](https://github.com/RauliL/levite) Tabellenkalkulation mit RPN-Formeln und Vi-Schnittstelle
- [mcfly](https://github.com/cantino/mcfly) Intelligente Suche in der Shell-Historie
- [mynav](https://github.com/GianlucaP106/mynav) Workspace- und Session-Management für Terminal-Umgebungen
- [multranslate](https://github.com/Lifailon/multranslate) TUI zum gleichzeitigen Übersetzen in mehreren Übersetzern.
- [nless](https://github.com/mpryor/nothing-less) Terminal-Pager zum Durchsuchen tabellarischer Daten mit Vi-Keybindings.
- [numr](https://github.com/nasedkinpv/numr) Taschenrechner mit natürlicher Sprache und Einheitenumrechnung.
- [openmux](https://github.com/monotykamary/openmux) Terminal-Multiplexer im Zellij-Stil
- [pagerduty-tui](https://github.com/Mk555/pagerduty-tui) Minimalistische UI zur Verwaltung von Incidents
- [patat](https://github.com/jaspervdj/patat) Präsentationen unter Verwendung von Pandoc
- [pdiary](https://github.com/manipuladordedados/pdiary) Einfache Tagebuch-Anwendung in Python mit Verschlüsselung.
- [pkm](https://github.com/wick3dr0se/pkm) Minimaler Paketmanager-Wrapper in Bash.
- [pomo](https://github.com/Bahaaio/pomo) Anpassbarer Pomodoro-Timer mit ASCII-Kunst und Produktivitätsstatistiken.
- [portfolio_rs](https://github.com/MarkusZoppelt/portfolio_rs) Werkzeug zur Verwaltung von Finanzportfolios.
- [pream-team](https://github.com/nikoladucak/pream-team/) Behalten Sie GitHub PRs Ihres Teams über mehrere Repositories hinweg im Auge.
- [presenterm](https://github.com/mfontanini/presenterm) Slideshow-Werkzeug für Markdown im Terminal
- [procmux](https://github.com/napisani/procmux) TUI zum parallelen Ausführen mehrerer Befehle.
- [productivity-timer](https://github.com/h-sifat/productivity-timer) Zeit-Tracker für die Kommandozeile.
- [sc-im](https://github.com/andmarti1424/sc-im) Tabellenkalkulation für das Terminal. Fortführung von sc
- [SheetsUI](https://github.com/zaphar/sheetsui) Eine konsolenbasierte Tabellenkalkulation
- [slides](https://github.com/maaslalani/slides) Präsentationswerkzeug mit Unterstützung für Markdown-Syntax.
- [sshm](https://github.com/gu1llaum-3/sshm) SSH-Verbindungen einfach verwalten.
- [ssh-slides](https://github.com/ivantsepp/ssh-slides) Präsentationen über SSH halten
- [Tabiew](https://github.com/shshemi/tabiew) Leichtgewichtige App zum Betrachten tabellarischer Daten (CSV, Parquet, etc.).
- [taskline](https://github.com/perryrh0dan/taskline) Aufgaben, Boards & Notizen für die Kommandozeile
- [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) Eine Terminal-Benutzeroberfläche für Taskwarrior
- [television](https://github.com/alexpasmantier/television) Vielseitiger Fuzzy-Finder TUI
- [tenere](https://github.com/pythops/tenere) ChatGPT TUI in Rust geschrieben.
- [termscp](https://github.com/veeso/termscp) Dateitransfer und Explorer (SCP/SFTP/S3, etc.).
- [tiki](https://github.com/boolean-maybe/tiki) Git-versionierter Projekt- und Issue-Manager auf Markdown-Basis.
- [tmux](https://github.com/tmux/tmux) Terminal-Multiplexer
- [tododo](https://github.com/bmarse/tododo) Schöner TODO.md Manager.
- [todoman](https://github.com/pimutils/todoman) Einfacher, standardbasierter Task-Manager
- [topydo](https://github.com/topydo/topydo) Mächtige To-Do-Liste im todo.txt Format
- [ttyplot](https://github.com/tenox7/ttyplot) Echtzeit-Plotting für das Terminal.
- [TUI_ProjectManager](https://github.com/NicoDblc/TUI_ProjectManager) Projektbasierte To-Do-Liste in Rust.
- [tuidict](https://github.com/404Simon/tuidict) Schnelles Offline-Wörterbuch mit Multi-Language Support.
- [tui-deck](https://github.com/mebitek/tui-deck) TUI für Nextcloud Deck in Go.
- [TUIOS](https://github.com/Gaurav-Gosain/tuios) Window-Manager für Terminal-Sessions.
- [tui-slides](https://github.com/Chleba/tui-slides) Präsentationswerkzeug, das Bilder und Widgets rendern kann.
- [tuihub](https://github.com/ashis0013/tuihub) Ein Dashboard für den persönlichen Gebrauch.
- [tvterm](https://github.com/magiblot/tvterm) Ein Terminal-Emulator, der in Ihrem Terminal läuft
- [Visidata](https://github.com/saulpw/visidata) Multitool für tabellarische Daten.
- [zellij](https://github.com/zellij-org/zellij) Ein Terminal-Arbeitsplatz mit allem Drum und Dran
- [zeit](https://github.com/mrusme/zeit) Werkzeug zur Zeiterfassung von Aktivitäten.
- [Toney](https://github.com/SourcewareLab/Toney) Schnelle Notizen-App für moderne Entwickler.
- [Tock](https://github.com/kriuchkov/tock) Zeiterfassungstool mit interaktiver TUI.
---

</details>

<details open><summary><h2>Bildschirmschoner</h2></summary>

- [astroterm](https://github.com/da-luce/astroterm) Ein Planetarium für das Terminal! Erkunden Sie Sterne und Sternbilder.
- [gitlogue](https://github.com/unhappychoice/gitlogue) Visualisiert die Git-Commit-Historie als Bildschirmschoner.
- [neo](https://github.com/st3w/neo) Simuliert den "digitalen Regen" aus Matrix.
- [rxpipes](https://github.com/inunix3/rxpipes) 2D-Rekonstruktion des klassischen Pipes-Bildschirmschoners.
- [pond](https://gitlab.com/alice-lefebvre/pond) Ein beruhigender Bildschirmschoner, der einen kleinen Teich simuliert.
- [weathr](https://github.com/veirt/weathr) Wetter-App mit ASCII-Animationen.
---

</details>

<details open><summary><h2>Web</h2></summary>

- [bombadillo](https://bombadillo.colorfield.space/) TUI Browser für Gopher, Gemini und Finger.
- [browsh](https://github.com/browsh-org/browsh) Ein moderner textbasierter Browser.
- [bulletty](https://github.com/CrociDB/bulletty) Schöner Feed-Reader (ATOM/RSS).
- [Canard](https://github.com/mrusme/canard) TUI Client für den Journalist RSS Aggregator.
- [carbonyl](https://github.com/fathyb/carbonyl) Chromium im Terminal ausführen.
- [castero](https://github.com/xgi/castero) Eine TUI zum Hören von Podcasts.
- [CatenaVetus](https://github.com/jimbob88/CatenaVetus) TUI zum Lesen der Kirchenväter.
- [Chawan](https://chawan.net) Browser für Web, FTP, Gopher und Gemini mit JavaScript-Unterstützung.
- [cloudflare-speed-cli](https://github.com/kavehtehrani/cloudflare-speed-cli) Internet-Geschwindigkeitstest via Cloudflare.
- [eilmeldung](https://github.com/christo-auer/eilmeldung) RSS-Reader mit vielen Konfigurationsmöglichkeiten.
- [elinks](https://github.com/rkd77/elinks) Browser mit JavaScript-Unterstützung.
- [hackernews-TUI](https://github.com/aome510/hackernews-TUI) Eine Terminal-UI zum Durchsuchen von Hacker News.
- [haxor-news](https://github.com/donnemartin/haxor-news) Hacker News über die Kommandozeile lesen.
- [Lagrange](https://gmi.skyjake.fi/lagrange) Client zum Durchsuchen des Geminispace.
- [LYNX](https://lynx.invisible-island.net/) Ein klassischer textbasierter Terminal-Browser.
- [podliner](https://github.com/timkicker/podliner) Plattformübergreifender Podcast-Client.
- [newsboat](https://github.com/newsboat/newsboat) Ein RSS/Atom Feed-Reader für die Textkonsole.
- [nyaa](https://github.com/Beastwick18/nyaa) Durchsuchen und Herunterladen von nyaa.si Torrents.
- [omaro](https://github.com/Rolv-Apneseth/omaro) TUI zum Durchsuchen von lobste.rs Posts.
- [rfc_reader](https://github.com/ozan2003/rfc_reader) Werkzeug zum Lesen von RFC-Dokumenten.
- [rtorrent](https://github.com/rakshasa/rtorrent) Textbasierter BitTorrent-Client in C++.
- [rttt](https://gitlab.com/BlackEdder/rttt) Reader für Hacker News, RSS und Reddit.
- [searxngr](https://github.com/scross01/searxngr) Web-Suche via SearXNG.
- [Slumber](https://github.com/LucasPickering/slumber) Terminalbasierter HTTP/REST Client.
- [stegodon](https://github.com/deemkeen/stegodon) Föderiertes Mikroblogging mit ActivityPub-Unterstützung.
- [surge](https://github.com/surge-downloader/surge) Schneller Download-Manager in Go.
- [tblogs](https://github.com/ezeoleaf/tblogs) Entwickler-Blogs vom Terminal aus lesen.
- [textual-web](https://github.com/Textualize/textual-web) TUIs und Terminals im Browser ausführen.
- [twterm](https://github.com/ryota-ka/twterm) TUI Twitter-Client mit vollem Funktionsumfang.
- [w3m](https://github.com/tats/w3m) Ein textbasierter WWW-Browser.
---

</details>
