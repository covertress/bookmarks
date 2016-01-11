
bookmarks (awesome links / malware analysis / re)


- [Malware Analysis](#awesome-malware-analysis)
    - [Malware Collection](#malware-collection)
        - [Anonymizers](#anonymizers)
        - [Honeypots](#honeypots)
        - [Malware Corpora](#malware-corpora)
    - [Open Source Threat Intelligence](#open-source-threat-intelligence)
        - [Tools](#tools)
        - [Other Resources](#other-resources)
    - [Detection and Classification](#detection-and-classification)
    - [Online Scanners and Sandboxes](#online-scanners-and-sandboxes)
    - [Domain Analysis](#domain-analysis)
    - [Browser Malware](#browser-malware)
    - [Documents and Shellcode](#documents-and-shellcode)
    - [File Carving](#file-carving)
    - [Deobfuscation](#deobfuscation)
    - [Debugging and Reverse Engineering](#debugging-and-reverse-engineering)
    - [Network](#network)
    - [Memory Forensics](#memory-forensics)
    - [Windows Artifacts](#windows-artifacts)
    - [Storage and Workflow](#storage-and-workflow)
    - [Miscellaneous](#miscellaneous)
- [Resources](#resources)
    - [Books](#books)
    - [Twitter](#twitter)
    - [Other](#other)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [Thanks](#thanks)

---

## Malware Collection

### Anonymizers

*Web traffic anonymizers for analysts.*

* [Anonymouse.org](http://anonymouse.org/) - A free, web based anonymizer.
* [OpenVPN](https://openvpn.net/) - VPN software and hosting solutions.
* [Privoxy](http://www.privoxy.org/) - An open source proxy server with some
  privacy features.
* [Tor](https://www.torproject.org/) - The Onion Router, for browsing the web
  without leaving traces of the client IP.

### Honeypots

*Trap and collect your own samples.*

* [Conpot](https://github.com/mushorg/conpot) - ICS/SCADA honeypot.
* [Dionaea](http://dionaea.carnivore.it/) - Honeypot designed to trap
  malware.
* [Glastopf](http://glastopf.org/) - Web application honeypot.
* [Honeyd](http://www.honeyd.org/) - Create a virtual honeynet.
* [HoneyDrive](http://bruteforce.gr/honeydrive) - Honeypot bundle Linux distro.
* [Kippo](https://github.com/desaster/kippo) - Medium interaction SSH honeypot.
* [Mnemosyne](https://github.com/johnnykv/mnemosyne) - A normalizer for
  honeypot data; supports Dionaea.
* [Thug](https://github.com/buffer/thug) - Low interaction honeyclient, for
  investigating malicious websites.

### Malware Corpora

*Malware samples collected for analysis.*

* [Clean MX](http://support.clean-mx.de/clean-mx/viruses.php) - Realtime
  database of malware and malicious domains.
* [Contagio](http://contagiodump.blogspot.com/) - A collection of recent
  malware samples and analyses.
* [Exploit Database](https://www.exploit-db.com/) - Exploit and shellcode
  samples.
* [Malshare](http://malshare.com) - Large repository of malware actively
  scrapped from malicious sites.
* [maltrieve](https://github.com/krmaxwell/maltrieve) - Retrieve malware
  samples directly from a number of online sources.
* [MalwareDB](http://malwaredb.malekal.com/) - Malware samples repository.
* [theZoo](https://github.com/ytisf/theZoo) - Live malware samples for
  analysts.
* [ViruSign](http://www.virusign.com/) - Malware database that detected by
  many anti malware programs except ClamAV.
* [VirusShare](http://virusshare.com/) - Malware repository, registration
* [Zeltser's Sources](https://zeltser.com/malware-sample-sources/) - A list
  of malware sample sources put together by Lenny Zeltser.
* [Zeus Source Code](https://github.com/Visgean/Zeus) - Source for the Zeus
  trojan leaked in 2011.
  required.

## Open Source Threat Intelligence

### Tools

*Harvest and analyze IOCs.*

* [Combine](https://github.com/mlsecproject/combine) - Tool to gather Threat
  Intelligence indicators from publicly available sources.
* [IntelMQ](https://www.enisa.europa.eu/activities/cert/support/incident-handling-automation) -
  A tool for CERTs for processing incident data using a message queue.
* [IOC Editor](https://www.fireeye.com/services/freeware/ioc-editor.html) -
  A free editor for XML IOC files.
* [ioc_writer](https://github.com/mandiant/ioc_writer) - Python library for
  working with OpenIOC objects, from Mandiant.
* [Massive Octo Spice](https://github.com/csirtgadgets/massive-octo-spice) -
  Previously known as CIF (Collective Intelligence Framework). Aggregates IOCs
  from various lists. Curated by the [CSIRT Gadgets Foundation](http://csirtgadgets.org/collective-intelligence-framework).
* [MISP](https://github.com/MISP/MISP) - Malware Information Sharing
  Platform curated by [The MISP Project](http://www.misp-project.org/).
* [PassiveTotal](https://www.passivetotal.org/) - Research, connect, tag and
  share IPs and domains.
* [PyIOCe](https://github.com/pidydx/PyIOCe) - A Python OpenIOC editor.
* [threataggregator](https://github.com/jpsenior/threataggregator) -
  Aggregates security threats from a number of sources, including some of
  those listed below in [other resources](#other-resources).
* [ThreatCrowd](https://www.threatcrowd.org/) - A search engine for threats,
  with graphical visualization.
* [ThreatTracker](https://github.com/jiachongzhi/ThreatTracker) - A Python
  script to monitor and generate alerts based on IOCs indexed by a set of
  Google Custom Search Engines.
* [TIQ-test](https://github.com/mlsecproject/tiq-test) - Data visualization
  and statistical analysis of Threat Intelligence feeds.

### Other Resources

*Threat intelligence and IOC resources.*

* [Autoshun](http://autoshun.org/) ([list](http://autoshun.org/files/shunlist.csv)) -
  Snort plugin and blocklist.
* [CI Army](http://cinsscore.com/) ([list](http://cinsscore.com/list/ci-badguys.txt)) -
  Network security blocklists.
* [Critical Stack- Free Intel Market](https://intel.CriticalStack.com) - Free
  intel aggregator with deduplication featuring 90+ feeds and over 1.2M indicators.
* [CRDF ThreatCenter](http://threatcenter.crdf.fr/) - List of new threats detected
  by CRDF anti-malware.
* [Emerging Threats](http://www.emergingthreats.net/) - Rulesets and more.
* [FireEye IOCs](https://github.com/fireeye/iocs) - Indicators of Compromise
  shared publicly by FireEye.
* [hpfeeds](https://github.com/rep/hpfeeds) - Honeypot feed protocol.
* [Internet Storm Center (DShield)](https://isc.sans.edu/) - Diary and
  searchable incident database, with a web [API](https://dshield.org/api/)
  ([unofficial Python library](https://github.com/rshipp/python-dshield)).
* [malc0de](http://malc0de.com/database/) - Searchable incident database.
* [Malware Domain List](http://www.malwaredomainlist.com/) - Search and share
  malicious URLs.
* [OpenIOC](http://openioc.org/) - Framework for sharing threat intelligence.
* [Palevo Blocklists](https://palevotracker.abuse.ch/blocklists.php) - Botnet
  C&C blocklists.
* [STIX - Structured Threat Information eXpression](http://stixproject.github.io) -
  Standardized language to represent and share cyber threat information.
  Related efforts from [MITRE](http://www.mitre.org/):
  - [CAPEC - Common Attack Pattern Enumeration and Classification](http://capec.mitre.org/)
  - [CybOX - Cyber Observables eXpression](http://cyboxproject.github.io)
  - [MAEC - Malware Attribute Enumeration and Characterization](http://maec.mitre.org/)
  - [TAXII - Trusted Automated eXchange of Indicator Information](http://taxiiproject.github.io)
* [threatRECON](https://threatrecon.co/) - Search for indicators, up to 1000
  free per month.
* [Yara rules](https://github.com/Yara-Rules/rules) - Yara rules repository.
* [ZeuS Tracker](https://zeustracker.abuse.ch/blocklist.php) - ZeuS
  blocklists.

## Detection and Classification

*Antivirus and other malware identification tools*

* [AnalyzePE](https://github.com/hiddenillusion/AnalyzePE) - Wrapper for a
  variety of tools for reporting on Windows PE files.
* [chkrootkit](http://www.chkrootkit.org/) - Local Linux rootkit detection.
* [ClamAV](http://www.clamav.net/) - Open source antivirus engine.
* [ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - Read, write and
  edit file metadata.
* [hashdeep](https://github.com/jessek/hashdeep) - Compute digest hashes with
  a variety of algorithms.
* [Loki](https://github.com/Neo23x0/Loki) - Host based scanner for IOCs.
* [Malfunction](https://github.com/Dynetics/Malfunction) - Catalog and
  compare malware at a function level.
* [MASTIFF](https://github.com/KoreLogicSecurity/mastiff) - Static analysis
  framework.
* [MultiScanner](https://github.com/MITRECND/multiscanner) - Modular file
  scanning/analysis framework
* [nsrllookup](https://github.com/rjhansen/nsrllookup) - A tool for looking
  up hashes in NIST's National Software Reference Library database.
* [packerid](http://handlers.sans.org/jclausing/packerid.py) - A cross-platform
  Python alternative to PEiD.
* [PEiD](http://woodmann.com/BobSoft/Pages/Programs/PEiD) - Packer identifier
  for Windows binaries.
* [PEV](http://pev.sourceforge.net/) - A multiplatform toolkit to work with PE
  files, providing feature-rich tools for proper analysis of suspicious binaries.
* [Rootkit Hunter](http://rkhunter.sourceforge.net/) - Detect Linux rootkits.
* [ssdeep](http://ssdeep.sourceforge.net/) - Compute fuzzy hashes.
* [totalhash.py](https://gist.github.com/malc0de/10270150) - Python script
  for easy searching of the [TotalHash.com](https://totalhash.cymru.com/) database.
* [TrID](http://mark0.net/soft-trid-e.html) - File identifier.
* [YARA](https://plusvic.github.io/yara/) - Pattern matching tool for
  analysts.
* [Yara rules generator](https://github.com/Neo23x0/yarGen) - Generate
  yara rules based on a set of malware samples. Also contains a good
  strings DB to avoid false positives.

## Online Scanners and Sandboxes

*Web-based multi-AV scanners, and malware sandboxes for automated analysis.*

* [AndroTotal](https://andrototal.org/) - free online analysis of APKs
  against multiple mobile antivirus apps.
* [Anubis](https://anubis.iseclab.org/) - Malware Analysis for Unknown Binaries
  and Site Check.
* [AVCaesar](https://avcaesar.malware.lu/) - Malware.lu online scanner and
  malware repository.
* [Cryptam](http://www.cryptam.com/) - Analyze suspicious office documents.
* [Cuckoo Sandbox](http://cuckoosandbox.org/) - Open source, self hosted
  sandbox and automated analysis system.
* [cuckoo-modified](https://github.com/brad-accuvant/cuckoo-modified) - Modified
  version of Cuckoo Sandbox released under the GPL. Not merged upstream due to
  legal concerns by the author.
* [DeepViz](https://www.deepviz.com/) - Multi-format file analyzer with
  machine-learning classification.
* [DRAKVUF](https://github.com/tklengyel/drakvuf) - Dynamic malware analysis
  system.
* [Hybrid Analysis](https://www.hybrid-analysis.com/) - Online malware
  analysis tool, powered by VxSandbox.
* [IRMA](http://irma.quarkslab.com/) - An asynchronous and customizable
  analysis platform for suspicious files.
* [Jotti](https://virusscan.jotti.org/en) - Free online multi-AV scanner.
* [Malheur](https://github.com/rieck/malheur) - Automatic sandboxed analysis
  of malware behavior.
* [Malwr](https://malwr.com/) - Free analysis with an online Cuckoo Sandbox
  instance.
* [MASTIFF Online](https://mastiff-online.korelogic.com/) - Online static
  analysis of malware.
* [Metascan Online](https://live.metascan-online.com/) - Free file scanning
  with multiple antivirus engines.
* [Noriben](https://github.com/Rurik/Noriben) - Uses Sysinternals Procmon to
  collect information about malware in a sandboxed environment.
* [PDF Examiner](http://www.pdfexaminer.com/) - Analyse suspicious PDF files.
* [Recomposer](https://github.com/secretsquirrel/recomposer) - A helper
  script for safely uploading binaries to sandbox sites.
* [SEE](https://github.com/F-Secure/see) - Sandboxed Execution Environment (SEE) 
  is a framework for building test automation in secured Environments.
* [VirusTotal](https://www.virustotal.com/) - Free online analysis of malware
  samples and URLs
* [Zeltser's List](https://zeltser.com/automated-malware-analysis/) - Free
  automated sandboxes and services, compiled by Lenny Zeltser.

## Domain Analysis

*Inspect domains and IP addresses.*

* [Desenmascara.me](http://desenmascara.me) - One click tool to retrieve as
  much metadata as possible for a website and to assess its good standing.
* [Dig](http://networking.ringofsaturn.com/) - Free online dig and other
  network tools.
* [IPinfo](https://github.com/hiddenillusion/IPinfo) - Gather information
  about an IP or domain by searching online resources.
* [MaltegoVT](https://github.com/jiachongzhi/MaltegoVT) - Maltego
  transform for the VirusTotal API. Allows domain/IP research, and searching
  for file hashes and scan reports.
* [SenderBase](http://www.senderbase.org/) - Search for IP, domain or network
  owner.
* [SpamCop](https://www.spamcop.net/bl.shtml) - IP based spam block list.
* [SpamHaus](http://www.spamhaus.org/lookup/) - Block list based on
  domains and IPs.
* [Sucuri SiteCheck](https://sitecheck.sucuri.net/) - Free Website Malware
  and Security Scanner.
* [TekDefense Automator](http://www.tekdefense.com/automater/) - OSINT tool
  for gatherig information about URLs, IPs, or hashes.
* [URLQuery](https://urlquery.net/) - Free URL Scanner.
* [Whois](http://whois.domaintools.com/) - DomainTools free online whois
  search.
* [Zeltser's List](https://zeltser.com/lookup-malicious-websites/) - Free
  online tools for researching malicious websites, compiled by Lenny Zeltser.
* [ZScalar Zulu](http://zulu.zscaler.com/#) - Zulu URL Risk Analyzer.

## Browser Malware

*Analyze malicious URLs. See also the [domain analysis](#domain-analysis) and
[documents and shellcode](#documents-and-shellcode) sections.*

* [Firebug](http://getfirebug.com/) - Firefox extension for web development.
* [Java Decompiler](http://jd.benow.ca/) - Decompile and inspect Java apps.
* [Java IDX Parser](https://github.com/Rurik/Java_IDX_Parser/) - Parses Java
  IDX cache files.
* [JSDetox](http://www.relentless-coding.com/projects/jsdetox/) - JavaScript
  malware analysis tool.
* [jsunpack-n](https://github.com/urule99/jsunpack-n) - A javascript
  unpacker that emulates browser functionality.
* [Malzilla](http://malzilla.sourceforge.net/) - Analyze malicious web pages.
* [RABCDAsm](https://github.com/CyberShadow/RABCDAsm) - A "Robust
  ActionScript Bytecode Disassembler."
* [swftools](http://www.swftools.org/) - Tools for working with Adobe Flash
  files.
* [xxxswf](http://hooked-on-mnemonics.blogspot.com/2011/12/xxxswfpy.html) - A
  Python script for analyzing Flash files.

## Documents and Shellcode

*Analyze malicious JS and shellcode from PDFs and Office documents. See also
the [browser malware](#browser-malware) section.*

* [AnalyzePDF](https://github.com/hiddenillusion/AnalyzePDF) - A tool for
  analyzing PDFs and attempting to determine whether they are malicious.
* [diStorm](http://www.ragestorm.net/distorm/) - Disassembler for analyzing
  malicious shellcode.
* [JS Beautifier](http://jsbeautifier.org/) - JavaScript unpacking and deobfuscation.
* [JS Deobfuscator](http://www.kahusecurity.com/2015/new-javascript-deobfuscator-tool/) -
  Deobfuscate simple Javascript that use eval or document.write to conceal
  its code.
* [libemu](http://libemu.carnivore.it/) - Library and tools for x86 shellcode
  emulation.
* [malpdfobj](https://github.com/9b/malpdfobj) - Deconstruct malicious PDFs
  into a JSON representation.
* [OfficeMalScanner](http://www.reconstructer.org/code.html) - Scan for
  malicious traces in MS Office documents.
* [olevba](http://www.decalage.info/python/olevba) - A script for parsing OLE
  and OpenXML documents and extracting useful information.
* [Origami PDF](https://code.google.com/p/origami-pdf/) - A tool for
  analyzing malicious PDFs, and more.
* [PDF Tools](http://blog.didierstevens.com/programs/pdf-tools/) - pdfid,
  pdf-parser, and more from Didier Stevens.
* [PDF X-Ray Lite](https://github.com/9b/pdfxray_lite) - A PDF analysis tool,
  the backend-free version of PDF X-RAY.
* [peepdf](http://eternal-todo.com/tools/peepdf-pdf-analysis-tool) - Python
  tool for exploring possibly malicious PDFs.
* [Spidermonkey](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey) -
  Mozilla's JavaScript engine, for debugging malicious JS.

## File Carving

*For extracting files from inside disk and memory images.*

* [bulk_extractor](https://github.com/simsong/bulk_extractor) - Fast file
  carving tool.
* [EVTXtract](https://github.com/williballenthin/EVTXtract) - Carve Windows
  Event Log files from raw binary data.
* [Foremost](http://foremost.sourceforge.net/) - File carving tool designed
  by the US Air Force.
* [Hachoir](https://bitbucket.org/haypo/hachoir) - A collection of Python
  libraries for dealing with binary files.
* [Scalpel](https://github.com/sleuthkit/scalpel) - Another data carving
  tool.

## Deobfuscation

*Reverse XOR and other code obfuscation methods.*

* [Balbuzard](https://bitbucket.org/decalage/balbuzard/wiki/Home) - A malware
  analysis tool for reversing obfuscation (XOR, ROL, etc) and more.
* [de4dot](https://github.com/0xd4d/de4dot) - .NET deobfuscator and
  unpacker.
* [ex_pe_xor](http://hooked-on-mnemonics.blogspot.com/2014/04/expexorpy.html)
  & [iheartxor](http://hooked-on-mnemonics.blogspot.com/p/iheartxor.html) -
  Two tools from Alexander Hanel for working with single-byte XOR encoded
  files.
* [NoMoreXOR](https://github.com/hiddenillusion/NoMoreXOR) - Guess a 256 byte
  XOR key using frequency analysis.
* [PackerAttacker](https://github.com/BromiumLabs/PackerAttacker) - A generic
  hidden code extractor for Windows malware.
* [unxor](https://github.com/tomchop/unxor/) - Guess XOR keys using
  known-plaintext attacks.
* [VirtualDeobfuscator](https://github.com/jnraber/VirtualDeobfuscator) -
  Reverse engineering tool for virtualization wrappers.
* [XORBruteForcer](http://eternal-todo.com/var/scripts/xorbruteforcer) -
  A Python script for brute forcing single-byte XOR keys.
* [XORSearch & XORStrings](http://blog.didierstevens.com/programs/xorsearch/) -
  A couple programs from Didier Stevens for finding XORed data.
* [xortool](https://github.com/hellman/xortool) - Guess XOR key length, as
  well as the key itself.

## Debugging and Reverse Engineering

*Disassemblers, debuggers, and other static and dynamic analysis tools.*

* [angr](https://github.com/angr/angr) - Platform-agnostic binary analysis
  framework developed at UCSB's Seclab.
* [BARF](https://github.com/programa-stic/barf-project) - Multiplatform, open
  source Binary Analysis and Reverse engineering Framework.
* [binnavi](https://github.com/google/binnavi) - Binary analysis IDE for
  reverse engineering based on graph visualization.
* [Bokken](https://inguma.eu/projects/bokken) - GUI for Pyew and Radare.
* [Capstone](https://github.com/aquynh/capstone) - Disassembly framework for
  binary analysis and reversing, with support for many architectures and
  bindings in several languages.
* [codebro](https://github.com/hugsy/codebro) - Web based code browser using
  clang to provide basic code analysis.
* [dnSpy](https://github.com/0xd4d/dnSpy) - .NET assembly editor, decompiler
  and debugger.
* [Evan's Debugger (EDB)](http://codef00.com/projects#debugger) - A
  modular debugger with a Qt GUI.
* [GDB](http://www.sourceware.org/gdb/) - The GNU debugger.
* [GEF](https://github.com/hugsy/gef) - GDB Enhanced Features, for exploiters
  and reverse engineers.
* [hackers-grep](https://github.com/codypierce/hackers-grep) - A utility to
  search for strings in PE executables including imports, exports, and debug
  symbols.
* [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml) - Windows
  disassembler and debugger, with a free evaluation version.
* [Immunity Debugger](http://debugger.immunityinc.com/) - Debugger for
  malware analysis and more, with a Python API.
* [ltrace](http://ltrace.org/) - Dynamic analysis for Linux executables.
* [objdump](https://en.wikipedia.org/wiki/Objdump) - Part of GNU binutils,
  for static analysis of Linux binaries.
* [OllyDbg](http://www.ollydbg.de/) - An assembly-level debugger for Windows
  executables.
* [PANDA](https://github.com/moyix/panda) - Platform for Architecture-Neutral Dynamic Analysis
* [PEDA](https://github.com/longld/peda) - Python Exploit Development
  Assistance for GDB, an enhanced display with added commands.
* [pestudio](https://winitor.com/) - Perform static analysis of Windows
  executables.
* [Process Monitor](https://technet.microsoft.com/en-us/sysinternals/bb896645.aspx) -
  Advanced monitoring tool for Windows programs.
* [Pyew](https://github.com/joxeankoret/pyew) - Python tool for malware
  analysis.
* [Radare2](http://www.radare.org/r/) - Reverse engineering framework, with
  debugger support.
* [SMRT](https://github.com/pidydx/SMRT) - Sublime Malware Research Tool, a
  plugin for Sublime 3 to aid with malware analyis.
* [strace](http://sourceforge.net/projects/strace/) - Dynamic analysis for
  Linux executables.
* [Udis86](https://github.com/vmt/udis86) - Disassembler library and tool
  for x86 and x86_64.
* [Vivisect](https://github.com/vivisect/vivisect) - Python tool for
  malware analysis.
* [X64dbg](https://github.com/x64dbg/) - An open-source x64/x32 debugger for windows.

## Network

*Analyze network interactions.*

* [Bro](https://www.bro.org) - Protocol analyzer that operates at incredible
  scale; both file and network protocols.
* [BroYara](https://github.com/hempnall/broyara) - Use Yara rules from Bro.
* [CapTipper](https://github.com/omriher/CapTipper) -  Malicious HTTP traffic
  explorer.
* [chopshop](https://github.com/MITRECND/chopshop) - Protocol analysis and
  decoding framework.
* [Fiddler](http://www.telerik.com/fiddler) - Intercepting web proxy designed
  for "web debugging."
* [Hale](https://github.com/pjlantz/Hale) - Botnet C&C monitor.
* [INetSim](http://www.inetsim.org/) - Network service emulation, useful when
  building a malware lab.
* [Malcom](https://github.com/tomchop/malcom) - Malware Communications
  Analyzer.
* [Maltrail](https://github.com/stamparm/maltrail) - A malicious traffic 
  detection system, utilizing publicly available (black)lists containing 
  malicious and/or generally suspicious trails and featuring an reporting
  and analysis interface.
* [mitmproxy](https://mitmproxy.org/) - Intercept network traffic on the fly.
* [Moloch](https://github.com/aol/moloch) - IPv4 traffic capturing, indexing
  and database system.
* [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - Network
  forensic analysis tool, with a free version.
* [ngrep](http://ngrep.sourceforge.net/) - Search through network traffic
  like grep.
* [PcapViz](https://github.com/mateuszk87/PcapViz) - Network topology and traffic visualizer.
* [Tcpdump](http://www.tcpdump.org/) - Collect network traffic.
* [tcpick](http://tcpick.sourceforge.net/) - Trach and reassemble TCP streams
  from network traffic.
* [tcpxtract](http://tcpxtract.sourceforge.net/) - Extract files from network
  traffic.
* [Wireshark](https://www.wireshark.org/) - The network traffic analysis
  tool.

## Memory Forensics

*Tools for dissecting malware in memory images or running systems.*

* [DAMM](https://github.com/504ensicsLabs/DAMM) - Differential Analysis of
  Malware in Memory, built on Volatility
* [FindAES](http://jessekornblum.livejournal.com/269749.html) - Find AES
  encryption keys in memory.
* [Muninn](https://github.com/ytisf/muninn) - A script to automate portions
  of analysis using Volatility, and create a readable report.
* [Rekall](http://www.rekall-forensic.com/) - Memory analysis framework,
  forked from Volatility in 2013.
* [TotalRecall](https://github.com/sketchymoose/TotalRecall) - Script based
  on Volatility for automating various malware analysis tasks.
* [VolDiff](https://github.com/aim4r/VolDiff) - Run Volatility on memory
  images before and after malware execution, and report changes.
* [Volatility](https://github.com/volatilityfoundation/volatility) - Advanced
  memory forensics framework.
* [WinDbg](https://msdn.microsoft.com/en-us/windows/hardware/hh852365) - Live
  memory inspection and kernel debugging for Windows systems.

## Windows Artifacts

* [AChoir](https://github.com/OMENScan/AChoir) - A live incident response
  script for gathering Windows artifacts.
* [python-evt](https://github.com/williballenthin/python-evt) - Python
  library for parsing Windows Event Logs.
* [python-registry](http://www.williballenthin.com/registry/) - Python
  library for parsing registry files.
* [RegRipper](http://brettshavers.cc/index.php/brettsblog/tags/tag/regripper/)
  ([GitHub](https://github.com/keydet89/RegRipper2.8)) -
  Plugin-based registry analysis tool.

## Storage and Workflow

* [Aleph](https://github.com/trendmicro/aleph) - OpenSource Malware Analysis
  Pipeline System.
* [CRITs](https://crits.github.io/) - Collaborative Research Into Threats, a
  malware and threat repository.
* [Malwarehouse](https://github.com/sroberts/malwarehouse) - Store, tag, and
  search malware.
* [Viper](http://viper.li/) - A binary management and analysis framework for
  analysts and researchers.

## Miscellaneous

* [DC3-MWCP](https://github.com/Defense-Cyber-Crime-Center/DC3-MWCP) -
  The Defense Cyber Crime Center's Malware Configuration Parser framework.
* [Pafish](https://github.com/a0rtega/pafish) - Paranoid Fish, a demonstration
  tool that employs several techniques to detect sandboxes and analysis
  environments in the same way as malware families do.
* [REMnux](https://remnux.org/) - Linux distribution and docker images for
  malware reverse engineering and analysis.
* [Santoku Linux](https://santoku-linux.com/) - Linux distribution for mobile
  forensics, malware analysis, and security.

# Resources

## Books

*Essential malware analysis reading material.*

* [Malware Analyst's Cookbook and DVD](https://amzn.com/dp/0470613033) -
  Tools and Techniques for Fighting Malicious Code.
* [Practical Malware Analysis](https://amzn.com/dp/1593272901) - The Hands-On Guide
  to Dissecting Malicious Software.
* [The Art of Memory Forensics](https://amzn.com/dp/1118825098) - Detecting
  Malware and Threats in Windows, Linux, and Mac Memory.
* [The IDA Pro Book](https://amzn.com/dp/1593272898) - The Unofficial Guide
  to the World's Most Popular Disassembler.

## Twitter

*Some relevant Twitter accounts.*

* Adamb [@Hexacorn](https://twitter.com/Hexacorn)
* Andrew Case [@attrc](https://twitter.com/attrc)
* Claudio [@botherder](https://twitter.com/botherder)
* Dustin Webber [@mephux](https://twitter.com/mephux)
* Glenn [@hiddenillusion](https://twitter.com/hiddenillusion)
* jekil [@jekil](https://twitter.com/jekil)
* Jurriaan Bremer [@skier_t](https://twitter.com/skier_t)
* Lenny Zeltser [@lennyzeltser](https://twitter.com/lennyzeltser)
* Liam Randall [@hectaman](https://twitter.com/hectaman)
* Mark Schloesser [@repmovsb](https://twitter.com/repmovsb)
* Michael Ligh (MHL) [@iMHLv2](https://twitter.com/iMHLv2)
* Open Malware [@OpenMalware](https://twitter.com/OpenMalware)
* Richard Bejtlich [@taosecurity](https://twitter.com/taosecurity)
* Volatility [@volatility](https://twitter.com/volatility)

## Other

* [APT Notes](https://github.com/kbandla/APTnotes) - A collection of papers
  and notes related to Advanced Persistent Threats.
* [Honeynet Project](http://honeynet.org/) - Honeypot tools, papers, and
  other resources.
* [Malicious Software](https://zeltser.com/malicious-software/) - Malware
  blog and resources by Lenny Zeltser.
* [Malware Analysis Search](https://cse.google.com/cse/home?cx=011750002002865445766%3Apc60zx1rliu) -
  Custom Google search engine from [Corey Harrell](journeyintoir.blogspot.com/).
* [WindowsIR: Malware](http://windowsir.blogspot.com/p/malware.html) - Harlan
  Carvey's page on Malware.
* [/r/csirt_tools](https://www.reddit.com/r/csirt_tools/) - Subreddit for CSIRT
  tools and resources, with a
  [malware analysis](https://www.reddit.com/r/csirt_tools/search?q=flair%3A%22Malware%20analysis%22&sort=new&restrict_sr=on) flair.
* [/r/Malware](https://www.reddit.com/r/Malware) - The malware subreddit.
* [/r/ReverseEngineering](https://www.reddit.com/r/ReverseEngineering) -
  Reverse engineering subreddit, not limited to just malware.
* [Malware Samples and Traffic](http://malware-traffic-analysis.net/) - This
  blog focuses on network traffic related to malware infections.

# Related Awesome Lists

* [Android Security](https://github.com/ashishb/android-security-awesome)
* [AppSec](https://github.com/paragonie/awesome-appsec)
* [CTFs](https://github.com/apsdehal/awesome-ctf)
* ["Hacking"](https://github.com/carpedm20/awesome-hacking)
* [Honeypots](https://github.com/paralax/awesome-honeypots)
* [Infosec](https://github.com/onlurking/awesome-infosec)
* [PCAP Tools](https://github.com/caesar0301/awesome-pcaptools)
* [Pentesting](https://github.com/enaqx/awesome-pentest)
* [Security](https://github.com/sbilly/awesome-security)
