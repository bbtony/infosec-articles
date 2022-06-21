# is-articles
# Go-malwares-history

Репозиторий содержит ссылки на статьи и переводы, интересных материалов по и malware-reverse/development. Преимущественно 
написанных на Golang. Может быть полезна исследователям, различным сотрудникам по ИБ, пентестерам.

**Malwares (переводы):**
* ```noname``` - malware без имени 
* ```-``` - отсутствие перевода


| Name           | Publication date | Original | Translation                               | Description                |
|:---------------|:-----------------| :------- |:------------------------------------------| :------------------------- |
| r2r2 			 | -       			| [ENG](https://www.guardicore.com/labs/operation-prowli-traffic-manipulation-cryptocurrency-mining/) | -                                         ||
| Analog Zebrocy | 30.01.2019       | [ENG](https://blog.malwarebytes.com/threat-analysis/2019/01/analyzing-new-stealer-written-golang/) | -                                         ||
| GoBrut 		 | 06.03.2019       | [ENG](https://www.fortinet.com/blog/threat-research/new-stealth-worker-campaign-creates-a-multi-platform-army-of-bru) | -                                         ||
| Rocke 		 | 15.03.2019       | [ENG](https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang) | - ||
| Zebrocy        | 03.06.2019       | [ENG](https://securelist.com/zebrocys-multilanguage-malware-salad/90680/) | -                                         ||
| <b>noname</b>  | 02.07.2019       | [ENG](https://www.f5.com/labs/articles/threat-intelligence/new-golang-malware-is-spreading-via-multiple-exploits-to-mine-mo) | -                                         ||
| GoBotKR		 | 08.07.2019       | [ENG](https://www.welivesecurity.com/2019/07/08/south-korean-users-backdoor-torrents/) | -                                         ||
| Kaiji   		 | 04.05.2020       | [ENG](https://www.intezer.com/blog/research/kaiji-new-chinese-linux-malware-turning-to-golang/) | -                                         |ботнет, брут ssh, ddos|
| Golang PlugX   | 23.11.2020       | [ENG](https://www.proofpoint.com/us/blog/threat-insight/ta416-goes-ground-and-returns-golang-plugx-malware-loader) | -                                         ||
| Blackrota      | 24.11.2020       | [ENG](https://blog.netlab.360.com/blackrota-a-heavily-obfuscated-backdoor-written-in-go/) | [RU](./translations/malware/blackrota.md) |бэкдор, эксплуатация ошибки конфигурации Docker, написан на Go. |
| <b>noname</b>  | 29.12.2020       | [ENG](https://www.intezer.com/blog/research/new-golang-worm-drops-xmrig-miner-on-servers/) | - |"червь", майнер, постэксплуатация. |
| ElectroRAT     | 05.01.2021       | [ENG](https://www.intezer.com/blog/research/operation-electrorat-attacker-creates-fake-companies-to-drain-your-crypto-wallets/) | -                                         ||
| Ezuri          | 07.01.2021       | [ENG](https://www.bleepingcomputer.com/news/security/linux-malware-authors-use-ezuri-golang-crypter-for-zero-detection/) | -                                         ||
| Kinsing        | 03.09.2021       | [ENG](https://www.cyberark.com/resources/threat-research-blog/kinsing-the-malware-with-two-faces) | -                                         ||
| Capoae         | 16.09.2021       | [ENG](https://www.akamai.com/blog/security/capoae-malware-ramps-up-uses-multiple-vulnerabilities-and-tactics-to-spread) | -                                         ||
| DECAF          | 28.10.2021       | [ENG](https://blog.morphisec.com/decaf-ransomware-a-new-golang-threat-makes-its-appearance)      | -                                         ||
| BotenaGo       | 11.11.2021       | [ENG](https://cybersecurity.att.com/blogs/labs-research/att-alien-labs-finds-new-golang-malwarebotenago-targeting-millions-of-routers-and-iot-devices-with-more-than-30-exploits) | [RU](./translations/malware/botenago.md)  | ботнет, VT распознается как вариант Mirai, большой вектор атак на устройства. |
| Linux_AVP      | 18.11.2021       | [ENG](https://sansec.io/research/ecommerce-malware-linux-avp) | -                                         ||
| TellYouThePass | 11.01.2022       | [ENG](https://www.crowdstrike.com/blog/tellyouthepass-ransomware-analysis-reveals-modern-reinterpretation-using-golang/) | -                                         | |
| DoNot Go       | 18.01.2022       | [ENG](https://www.welivesecurity.com/2022/01/18/donot-go-do-not-respawn/) | -                                         | |
| Next BotenaGo  | 26.01.2022       | [ENG](https://cybersecurity.att.com/blogs/labs-research/botenago-strike-again-malware-source-code-uploaded-to-github) | -                                         | |
| Kraken         | 16.02.2022       | [ENG](https://www.zerofox.com/blog/meet-kraken-a-new-golang-botnet-in-development/) | -                                         | |
| PartyTicket    | 25.02.2022       | [ENG](https://www.zscaler.com/blogs/security-research/technical-analysis-partyticket-ransomware) |-||
| Go Elephant    | 01.04.2022       | [ENG](https://blog.malwarebytes.com/threat-intelligence/2022/04/new-uac-0056-activity-theres-a-go-elephant-in-the-room/) | -                                         | |
| Denonia        | 06.04.2022       | [ENG](https://www.cadosecurity.com/cado-discovers-denonia-the-first-malware-specifically-targeting-lambda/) | [RU](./translations/malware/denonia.md)                                         | |
| BlackByte      | 03.05.2022       | [ENG](https://www.zscaler.com/blogs/security-research/analysis-blackbyte-ransomwares-go-based-variants) |-| RaaS  |
| Panchan        | 15.06.2022       | [ENG](https://www.akamai.com/blog/security/new-p2p-botnet-panchan) |-| Botnet  |

Не являются Go-malwares, но интересные примеры и техники:

| Name | Publication date | Original | Translation                               | Description                |
|:-----|:-----------------| :------- |:------------------------------------------| :------------------------- |
| Pink | 29.10.2021       | [ENG](https://blog.netlab.360.com/pink-en/) | [RU](./translations/malware/pink.md)      |ботнет, гибридное управление, обновляемая конфигурация. |
| CronRAT        | 24.11.2021       | [ENG](https://sansec.io/research/cronrat) | -                                         ||
