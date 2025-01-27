- Çerçeveye aktif filtreleme/enjeksiyon eklendi

- Windows işletim sistemlerinde çalışmasını engelleyen DHCP zehirleyici hatası düzeltildi

- ARP spoofing zehirleyicisinde bazı performans iyileştirmeleri yapıldı

- Appcachepoison, BrowserSniper eklentileri yeniden düzenlendi

- Proxy eklentisi API'si yeniden düzenlendi

- Enjekte eklentisi artık HTML/JS ayrıştırmak ve enjekte etmek için BeautifulSoup4 kullanıyor

- HTA Drive by eklentisi eklendi

- SMBTrap eklentisi eklendi

- Yapılandırma dosyası artık anında güncelleniyor!

- SessionHijacker, Ferret-NG ile değiştirildi, çerezleri yakalar ve bağlı istemcilere besleyecek bir proxy başlatır

- JavaPwn eklentisi, artık Java, Flash ve tarayıcı açıklarını destekleyen BrowserSniper ile değiştirildi

- Düzenli aralıklarla bir istemcinin tarayıcısının ekran görüntülerini oluşturma yeteneğine sahip 

- Screenshotter eklentisinin eklenmesi

- Impacket kitaplığı kullanılarak tamamen işlevsel bir SMB sunucusu eklendi

- DNSChef eklendi, çerçeve artık bir IPv4/IPv6 (TCP & UDP) DNS sunucusudur! Desteklenen sorgular: 'A',     'AAAA', 'MX', 'PTR', 'NS', 'CNAME', 'TXT', 'SOA', 'NAPTR', 'SRV', 'DNSKEY' ve 'RRSIG'

- Net-Creds entegre edildi, şu anda desteklenen protokoller: FTP, IRC, POP, IMAP, Telnet, SMTP, SNMP (community dizeleri), NTLMv1/v2 (HTTP, SMB, LDAP vb. tüm desteklenen protokoller) ve Kerberos
LLMNR, NBT-NS ve MDNS'i zehirlemek ve sahte bir WPAD sunucusu olarak hareket etmek için Responder entegre 
edildi

- SSLstrip+ by Leonardo Nve, BlackHat Asia 2014'te gösterildiği gibi HSTS'yi kısmen atlamak için entegre edildi

- Sahte eklenti artık DHCP spoofing yaparken 'ShellShock' hatasını kullanabilir

- Sahte eklenti artık ICMP, ARP ve DHCP spoofing'i destekliyor

- Üçüncü taraf araçlarının kullanımı tamamen kaldırıldı (örneğin Ettercap)

- FilePwn eklentisi, the-backdoor-factory ve BDFProxy kodunu kullanarak yürütülebilir zip ve tar dosyalarına arka kapı açacak şekilde yeniden yazıldı

- Metasploit'in RPC sunucusu ile arayüz oluşturmak için msfrpc.py eklendi

- BeEF'in RESTfulAPI'si ile arayüz oluşturmak için beefapi.py eklendi

- Krzysztof Kotowicz tarafından uygulama önbellek zehirleme saldırısının eklenmesi (saldiriyi açiklayan blog yazisi burada: http://blog.kotowicz.net/2010/12/squid-imposter-phishing-websites.html)