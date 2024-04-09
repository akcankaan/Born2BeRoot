# Sanal Makineler: Modern Bilgisayar Teknolojisinin Temel Taşları

Sanal makineler, günümüzde bilgisayar sistemlerinin temel yapı taşlarından biri haline gelmiştir. Bu teknoloji, fiziksel bilgisayarların veya uzak sunucuların üzerinde çalışan ve özel bir işletim sistemi barındıran yazılımlardır. Sanal makineler, bilgisayar sistemlerinin esnekliğini artırırken, bir dizi avantaj sunarlar.

## Sanal Makinelerin Çalışma Prensibi

Sanal makine yazılımları, fiziksel bilgisayarın donanımını taklit eden sanal bir ortam oluşturur ve bu ortamda işletim sistemi ve uygulamaları çalıştırır. Bu sayede, farklı işletim sistemlerini eşzamanlı olarak kullanmak mümkün hale gelir. Ayrıca, sanal makineler izole edilmiş oldukları için birincil sisteme herhangi bir etki yapmazlar.

## Sanal Makinelerin Kullanım Alanları

Sanal makinelerin kullanımı çok geniş bir yelpazede bulunmaktadır. Bunlar arasında:

- İşletim sistemi ve uygulamaların test edilmesi
- Farklı işletim sistemlerinin eşzamanlı olarak kullanılması
- Geliştirme ortamlarının oluşturulması
- Güvenlik amacıyla kullanılması
- Veri toplama gibi işlemler yer alır.

## Sanal Makinelerin Avantajları

1. **Fiziksel Donanım Gereksinimlerinin Azalması:** Sanal makine yazılımı sayesinde, bir bilgisayar üzerinde birden fazla işletim sistemi ve uygulama çalıştırılabilir. Bu durum, fiziksel donanım gereksinimlerini azaltır ve maliyetleri düşürür.
   
2. **Mobilite:** Sanal makine dosyalarının taşınması, fiziksel bilgisayar taşımaktan daha kolaydır. Bu da işletim sistemi ve uygulamaların farklı bilgisayarlarda kullanılmasını kolaylaştırır.
   
3. **Eski Bilgisayarların Değerlendirilmesi:** Sanal makine yazılımı sayesinde, eski bilgisayarlar üzerinde yeni işletim sistemleri ve uygulamalar çalıştırılabilir. Bu da atık azaltımına ve maliyet düşüşüne katkı sağlar.
   
4. **Güvenlik:** Sanal makineler, host bilgisayarın gerçek donanımından ayrı olarak çalıştığından, güvenlik açısından avantaj sağlar. Bir sanal makinedeki güvenlik açığı, host bilgisayarı etkilemez.

5. **Yüksek Kullanım Verimliliği:** Sanal makine yazılımı, fiziksel bilgisayarın tüm özelliklerini kullanarak birden fazla işletim sistemi ve uygulamayı aynı anda çalıştırabilir, bu da yüksek kullanım verimliliği sağlar.

## Karşılaştırma: CentOS ve Debian

| Özellikler         | CentOS                                 | Debian                              |
|--------------------|----------------------------------------|-------------------------------------|
| Geliştiriciler     | Red Hat topluluğu                      | Debian kullanıcıları               |
| Mimariler          | Çoklu mimari desteği yoktur            | Çoklu mimari desteği vardır        |
| Paket Yönetimi     | YUM paket yöneticisini kullanır        | APT paket yöneticisini kullanır    |
| Kullanım Alanı     | Daha çok sunucular için kullanılır     | Hem sunucular için hem günlük kullanım için kullanılabilir |
| Paket Çeşitliliği | Varsayılan paketler azdır              | Varsayılan paket çeşitliliği fazladır |
| Stabilite          | CentOS kararlı bir dağıtımdır, ancak Debian bir adım önde görülür | Debian, CentOS kadar kararlı bir dağıtımdır |
| Durum              | CentOS 2020'de Red Hat tarafından resmi olarak durdurulmuştur | Debian sürekli olarak geliştirilmektedir |

## Rocky Linux: CentOS'un Yerine Geçen Yeni Bir Alternatif

CentOS'un durdurulmasının ardından ortaya çıkan Rocky Linux, CentOS'un temellerini devam ettirirken daha güçlü bir mimari sunar. Özellikle entegrasyon, veri merkezi, bulut ve sanallaştırma gibi alanlarda kullanılan Rocky Linux, aynı zamanda özel ve kamu sektöründe çeşitli uygulama ve hizmetleri barındırmak için ideal bir seçenektir. Rocky Linux, CentOS'un sunduğu LTS veya ELS desteklerinin yanı sıra ek olarak performans ve hizmet odaklı olarak optimize edilmiştir.

### Neden Debian?

Debian, paket yönetimi kolaylığı ve stabilitesiyle öne çıkar. apt (Advanced Packaging Tool) kullanarak güncel yazılımlara kolayca erişim sağlar. Ayrıca, geniş ve aktif bir topluluğa sahip olması, sorunların hızlı bir şekilde çözülmesini sağlar. Bu nedenle, Debian birçok kullanıcı için tercih edilen bir işletim sistemidir.
# Paket Yöneticileri: APT ve Aptitude

Linux işletim sistemlerinde yazılım yönetimi oldukça önemlidir ve bunu gerçekleştirmek için birçok araç bulunmaktadır. İki yaygın olarak kullanılan araç **APT** ve **Aptitude**'dir.

## APT (Advanced Package Tool)

APT, Debian ve diğer Debian tabanlı Linux dağıtımlarında yaygın olarak kullanılan bir paket yöneticisidir. APT, aşağıdaki gibi temel işlevleri gerçekleştirir:

- Mevcut uygulamaların güncellenmesi ve yeni uygulamaların yüklenmesi.
- Uygulamaların yüklenmesi ve kaldırılması.
- Bağımlılıkların yönetimi.

Bazı temel APT komutları şunlardır:

- `apt-get update`: Mevcut uygulamaların listesini günceller.
- `apt-get upgrade`: Mevcut uygulamaları günceller.
- `apt-get install [paket]`: Belirtilen paketi yükler.
- `apt-get remove [paket]`: Belirtilen paketi kaldırır.
- `apt-get purge [paket]`: Belirtilen paketi kaldırır ve ilişkili tüm dosyaları siler.

## Aptitude

Aptitude da Debian ve Debian tabanlı Linux dağıtımlarında kullanılan bir paket yöneticisidir. APT gibi çalışır ve aşağıdaki işlevleri gerçekleştirir:

- Uygulamaların yüklenmesi, güncellenmesi, kaldırılması ve bağımlılıkların yönetimi.
- APT'ye göre daha gelişmiş bir arayüze sahiptir ve daha fazla özellik sunar.

Bazı temel Aptitude komutları şunlardır:

- `aptitude update`: Mevcut uygulamaların listesini günceller.
- `aptitude upgrade`: Mevcut uygulamaları günceller.
- `aptitude install [paket]`: Belirtilen paketi yükler.
- `aptitude remove [paket]`: Belirtilen paketi kaldırır.
- `aptitude purge [paket]`: Belirtilen paketi kaldırır ve ilişkili tüm dosyaları siler.

## APT ve Aptitude Arasındaki Farklar

- **İşlevsellik:** Aptitude, APT'den daha geniş bir işlevselliğe sahiptir ve diğer APT varyantlarının işlevlerini bütünleştirir.
- **Arayüz:** Aptitude, APT'den farklı olarak salt metin ve etkileşimli bir kullanıcı arayüzüne sahiptir.
- **Paket Yönetimi:** Aptitude, apt-get'den daha gelişmiş bir paket yönetimine sahiptir ve kullanılmayan paketleri otomatik olarak kaldırabilir.

Bu farklılıklar, kullanıcıların tercihlerine ve ihtiyaçlarına göre hangi paket yöneticisini kullanacaklarına karar vermelerine yardımcı olabilir.

# Güvenlik: DAC ve MAC

Güvenlik, bilgisayar sistemlerindeki en önemli konulardan biridir ve erişim denetimi bu konuda kritik bir rol oynar. İki yaygın erişim denetimi mekanizması **İsteğe Bağlı Erişim Denetimi (DAC)** ve **Zorunlu Erişim Denetimi (MAC)** olarak bilinir.

## İsteğe Bağlı Erişim Denetimi (DAC)

İsteğe bağlı erişim denetimi, bir kullanıcının veya sürecin dosyalara, soketlere ve diğer kaynaklara erişip erişemeyeceğini, kullanıcı sahipliğine veya izinlere bakarak belirler. Temelde, kullanıcıların kendi oluşturdukları nesneler üzerinde tam kontrol sahibi olduğu bir yapıdır.

## Zorunlu Erişim Denetimi (MAC)

Zorunlu erişim denetimi ise, kullanıcıların oluşturdukları nesneler üzerindeki denetim düzeyini kısıtlayan bir güvenlik mekanizmasıdır. MAC'te, tüm dosya sistemine ek etiketler veya kategoriler eklenir ve kullanıcılar ve süreçler bu kategorilere uygun erişim haklarına sahip olmalıdır.

### SELinux

**SELinux (Security-Enhanced Linux)**, bir subject'in (örneğin bir uygulama) bir objeye (örneğin bir dosya) erişmeye çalıştığında çekirdek politika sunucusu tarafından izinlerin kontrol edildiği bir güvenlik mekanizmasıdır. SELinux, DAC'ta belirlenen erişim kurallarını es geçmez ve çekirdek politikalarına göre erişimin gerçekleşip gerçekleşmeyeceğini belirler. Üç farklı modu vardır: enforcing, permissive ve disabled.

### AppArmor

**AppArmor**, sisteme verilebilecek zararı sınırlayan veya tamamen durduran bir uygulamadır. Örneğin, Ubuntu'nun varsayılan yapılandırmasında, belirli eylemleri gerçekleştirebilen uygulamaların izinleri sınırlandırılır. AppArmor, dosya yoluna göre erişim kontrolü sağlar ve genellikle SUSE ve Ubuntu'da kullanılır.

# UFW (Uncomplicated Firewall)

**UFW (Uncomplicated Firewall)**, bir güvenlik duvarı yönetim aracıdır ve ağdaki trafiği kontrol etmek için kullanılır. UFW, basit ve anlaşılır bir arayüze sahiptir ve kurallarını komut satırı aracılığıyla belirleyebilirsiniz. Örneğin, belirli IP adreslerinden gelen trafiği izin verebilir veya belirli portları açarak sadece belirli servislerin kullanılmasına izin verebilirsiniz.

# Diskler ve Bellekler

Diskler ve bellekler, bir bilgisayar sisteminin temel yapı taşlarından biridir. Diskler, verilerin kalıcı olarak depolandığı ve bellekler ise geçici olarak saklandığı önemli bileşenlerdir. İşte bu bileşenlerle ilgili bazı temel kavramlar:

## Mantıksal Birim ve Fiziksel Birim Arasındaki Fark

Mantıksal birim ve fiziksel birim, disk alanının iki farklı yönetim şeklidir:

- **Fiziksel birim:** Bir işletim sistemi tarafından fiziksel olarak takılı olan bir disk bölümü olarak görülür.
- **Mantıksal birim:** İşletim sistemi tarafından bir dosya gibi görülür. Bu birimler, esnek bir şekilde yönetilebilir ve birden fazla fiziksel diskin bölümlerini oluşturabilir veya birleştirebilir.
# Diskler ve Bellekler

## LVM (Logical Volume Manager)

**LVM (Logical Volume Manager)**, bir işletim sistemi üzerinde disk alanını yönetmek için kullanılan bir araçtır. LVM, diskler arasında bölümler oluşturarak, bu bölümleri mantıksal birimler olarak adlandırır. Bu sayede, disk alanı daha esnek bir şekilde yönetilebilir.

## lsblk Komutu

`lsblk` komutu, Linux sistemlerinde kullanılan bir komuttur ve sistemde bulunan blok cihazlarını listelemek için kullanılır. Blok cihazları, verileri sabit boyutlu bloklarda saklayan bir depolama cihazı türüdür.

## Disk İsimlendirmeleri

Linux sistemlerinde, diskler genellikle "sd" ile başlayan kısaltmalarla adlandırılır. Örneğin, ilk sabit disk "sda" olarak adlandırılır. Disk isminin sonunda "crypt" varsa, bu disk üzerindeki verilerin şifreli olduğunu gösterir.

## Linux Sistem Bölümleri

Linux sistemlerinde, diskler genellikle birkaç ayrı bölüme ayrılır. Örneğin, `/boot`, `/root`, `/swap`, `/home`, `/var` gibi farklı amaçlar için kullanılan bölümler bulunur. Her bölüm, farklı sistem dosyalarını veya kullanıcı verilerini saklar.

## ROM (Read-Only Memory) ve sr0

**ROM**, bir bilgisayar veya diğer elektronik cihazda sadece okunabilen verileri saklar. `sr0` ise, genellikle bir CD-ROM sürücüsünün veya optik sürücünün sistemde tanımlanmış adıdır.

## MAJ:MIN

`MAJ:MIN`, bir disk bölümünün Major ve Minor numaralarını gösterir. Major numara, bir disk sürücüsünün türünü belirtirken, Minor numara daha ayrıntılı bir tanımlama yapar.

Bu kavramlar, diskler ve belleklerle ilgili temel bilgileri kapsar ve bir bilgisayar sistemini anlamak için önemlidir.

# SSH: Güvenli Kabuk Protokolü

**SSH (Secure Shell)**, bir bilgisayar ağı üzerinde güvenli bir bağlantı oluşturmak için kullanılan bir protokoldür. Bu protokol, bilgisayarlar arasında veri iletişimini şifreleyerek güvenliği sağlar. İşte SSH'nin temel özellikleri:

## Güvenlik

SSH, veri iletişimini şifreleyerek güvenliği sağlar. Bu sayede, bilgisayarlar arasındaki bağlantı sırasında verilerin izinsiz erişimden korunmasını sağlar. Ayrıca, kimlik doğrulama mekanizmalarıyla da güvenliği artırır.

## Bağlantı

SSH, bir bilgisayar veya sunucuya uzaktan erişim sağlamak için kullanılır. Bir bilgisayarın terminaline (komut satırı) bağlanarak komutlar çalıştırılabilir veya dosyalar transfer edilebilir.

## Kullanım Kolaylığı

SSH genellikle bir komut satırı aracılığıyla kullanılır, ancak grafiksel kullanıcı arayüzleri de mevcuttur. Bu da kullanıcıya esneklik sağlar ve farklı platformlarda (Windows, macOS, Linux) kullanılabilir.

## Kimlik Doğrulama

SSH, kullanıcıların kimlik doğrulamasını sağlamak için çeşitli yöntemler sunar. Bunlar arasında parola, anahtar tabanlı kimlik doğrulama (SSH anahtarları), ve zaman zaman iki faktörlü kimlik doğrulama gibi yöntemler bulunur.

## Çok Amaçlı Kullanım

SSH, sunucu yönetimi, dosya transferi, uzak masaüstü bağlantısı gibi birçok farklı amaç için kullanılabilir. Bu, bir bilgisayarın uzaktan yönetimini kolaylaştırır ve güvenli bir şekilde veri alışverişi sağlar.

SSH, bilgisayar ağı üzerinde güvenli bir iletişim sağlayan ve uzaktan erişim kolaylığı sunan bir protokoldür. Güvenliği ve kullanım kolaylığı nedeniyle geniş bir kullanıcı kitlesi tarafından tercih edilmektedir.
# Sudo: Süper Kullanıcı İşlemi

**Sudo** (SuperUser DO), Unix benzeri işletim sistemlerinde kullanılan bir komuttur. Bu komut, kullanıcıların sistem yöneticisi yetkilerine sahip olmadıkları halde, bu yetkilere sahip olan bir kullanıcı adı ve parolası kullanarak sistemde çalıştırılmasına izin verilen komutları çalıştırmak için kullanılır.

## Özellikler:

- **Yetkilendirme:** Sudo, belirli kullanıcıların belirli komutları çalıştırabilmelerini sağlar. Bu sayede, kullanıcıların sadece gerektiğinde yönetici yetkilerine sahip olmaları sağlanır ve güvenlik artırılır.
- **Güvenlik:** Sudo, sistemde kötü amaçlı kullanımları engellemek için gereksiz yetkilere sahip olmayı önler. Bu şekilde, istenmeyen değişikliklerin önlenmesine yardımcı olur.
- **Yapılandırma:** Sudo, `/etc/sudoers` dosyasında yapılandırılır. Bu dosya, hangi kullanıcıların hangi komutları çalıştırabileceğini ve hangi komutların çalıştırılmasına izin verilmeyeceğini belirler. Bu sayede, sistem yöneticisi istenmeyen erişimleri kontrol altında tutabilir.

Sudo, sistem yöneticileri tarafından sıkça kullanılan bir araçtır ve kullanıcıların güvenli ve kontrollü bir şekilde sistemde değişiklik yapmalarını sağlar.
# Crontab: Zamanlanmış Görevler

**Crontab**, Unix benzeri işletim sistemlerinde kullanılan bir servistir. Bu servis, belirli zaman aralıklarında otomatik olarak çalıştırılmasına izin verilen komutları ve görevleri yönetmek için kullanılır. Genellikle sistem yöneticisi tarafından yapılandırılır ve belirli bir zaman aralığında çalışacak görevler ve komutlar belirlemek için kullanılır.

## Özellikler:

- **Zamanlama:** Crontab, belirli zaman aralıklarında çalıştırılacak görevleri tanımlamanızı sağlar. Örneğin, her gün, her hafta veya her ay belirli bir saatte bir görevin çalıştırılmasını planlayabilirsiniz.
- **Yapılandırma:** Crontab, genellikle `/etc/crontab` veya `/etc/cron.d` gibi dizinlerde bulunan dosyalarda yapılandırılır. Bu dosyaları düzenleyerek hangi görevlerin ne zaman çalıştırılacağını belirleyebilirsiniz.
- **Kullanıcı Ayarları:** Crontab, farklı kullanıcılar için ayrı ayrı yapılandırılabilir. Her kullanıcı kendi crontab dosyasını düzenleyerek kendi zamanlanmış görevlerini tanımlayabilir.

## Temel Kullanım:

- `crontab -e`: Kullanıcının crontab dosyasını düzenlemesine izin verir.
- `crontab -l`: Kullanıcının mevcut crontab görevlerini listeler.
- `crontab -r`: Kullanıcının crontab dosyasını siler.

## Örnek Kullanım:

```bash
# Her gün saat 03:00'te bir yedek alma işlemi
0 3 * * * /bin/bash /usr/local/bin/backup.sh

# Her hafta Pazartesi günü saat 02:00'de sistem güncelleme işlemi
0 2 * * 1 /usr/bin/apt-get update && /usr/bin/apt-get upgrade -y
```

## TCP Nedir?

TCP, Transmission Control Protocol (İletişim Kontrol Protokolü) olarak adlandırılır. Bu protokol, internet üzerinde veri gönderimini gerçekleştirmek için kullanılır. TCP, verileri parçalara böler (bunlar "paketler" olarak adlandırılır) ve her bir paketi ayrı ayrı gönderir. Bu sayede, herhangi bir paketin kaybı durumunda sadece o paket yeniden gönderilir, diğer paketler etkilenmez. TCP ayrıca verilerin aynı sırayla ve doğru şekilde alıcıya ulaşmasını sağlar.

TCP, IP (Internet Protocol) protokolü ile birlikte kullanılır. IP, paketleri doğru yere göndermek için kullanılır, ancak gönderilen verilerin doğru şekilde alıcıya ulaşmasını ve verilerin parçalara ayrılmasını sağlamaz. Bu nedenle, TCP ve IP protokolleri birlikte kullanılır. Bağlantı bilgileri (kaç bağlantı olduğu vb.) /proc/net/sockstat adresinde tutulur.

### Komutlar ve Açıklamaları

- `id`: Kullanıcının kimlik bilgilerini gösterir.
- `whoami`: Kullanıcının kim olduğunu gösterir.
- `finger`: Kullanıcı hakkında detaylı bilgi verir.
- `w`: Sistemde çalışan kullanıcıları ve ne yaptıklarını gösterir.
- `last`: Kullanıcıların sisteme son giriş bilgilerini gösterir.
- `users`: Sistemde çalışan kullanıcıların listesini gösterir.
- `getent`: Sistemdeki kullanıcı ve gruplar hakkında bilgi toplamak için kullanılabilir. Bu komut, /etc/passwd, /etc/group ve benzeri dosyalarda bulunan bilgileri kullanarak kullanıcı ve gruplar hakkında bilgi verir.

### Güvenlik Duvarı Yönetimi İçin UFW Komutları

- `ufw enable`: Güvenlik duvarını etkinleştirir.
- `ufw disable`: Güvenlik duvarını devre dışı bırakır.
- `ufw default deny`: Varsayılan olarak tüm bağlantıları reddeder.
- `ufw default allow`: Varsayılan olarak tüm bağlantıları kabul eder.
- `ufw allow [port/service]`: Belirtilen port veya hizmete izin verir.
- `ufw deny [port/service]`: Belirtilen port veya hizmete izin vermez.
- `ufw show`: Güvenlik duvarı kurallarını gösterir.

### Kullanıcı ve Grup Yönetimi İçin Linux Terminali Komutları

- `useradd`: Yeni bir kullanıcı oluşturur.
- `userdel`: Bir kullanıcıyı siler.
- `usermod`: Bir kullanıcının bilgilerini değiştirir.
- `passwd`: Bir kullanıcının parolasını değiştirir.
- `chage`: Bir kullanıcının parola ömrünü değiştirir.
- `groupadd`: Yeni bir grup oluşturur.
- `groupdel`: Bir grubu siler.
- `groupmod`: Bir grubun bilgilerini değiştirir.
- `adduser <username> <groupname>`: Bir kullanıcıyı bir gruba ekler.

### Hizmet Yönetimi İçin Linux Terminali Komutları

- `systemctl`: Systemd hizmetlerini yönetir.
- `service`: Sistemin eski hizmetlerini yönetir.
- `chkconfig`: Sistemin eski hizmetlerini yönetir.
- `systemctl start [hizmet]`: Belirtilen hizmeti başlatır.
- `systemctl stop [hizmet]`: Belirtilen hizmeti durdurur.
- `systemctl restart [hizmet]`: Belirtilen hizmeti yeniden başlatır.
- `systemctl status [hizmet]`: Belirtilen hizmetin durumunu gösterir.

### Diğer İlgili Komutlar

- `dpkg -l`: Sistemde yüklü olan paketlerin listesini gösterir.
- `hostnamectl`: Ana bilgisayarın adını kontrol eder.
- `hostnamectl set-hostname sunucu1`: Ana bilgisayar adını sunucu1 olarak ayarlar.
- `head -n 2 /etc/os-release`: İşletim sisteminin ismini gösterir.
- `/usr/sbin/aa-status`: APPArmor'un yüklü olup olmadığını gösterir.
- `ss -tunlp`: Sanal makinenin portlarını gösterir.
- `uname`: İşletim sistemi bilgilerini gösterir.

### Crontab ile Zamanlanmış Görevler

- `(*/10 * * * * bash /usr/local/sbin/monitoring.sh)`: (*dakikası)(*saati)(*ayın günü)(*yılın ayı)(*haftanın günü)
- `sudo systemctl status cron`: Cron durumunu gösterir.
- `sudo systemctl stop cron`: Cron'u durdurur.
- `sudo systemctl disable cron`: Reboot sonrası çalışmasını engeller.

### Şifre Gereksinimleri

- `minlen=10`: En az 10 karakter uzunluğu istenmektedir.
- `ucredit=-1`: En az 1 büyük karakter istenmektedir. (Pozitif durumda Max içeriği belirler.)
- `lcredit=-1`: En az 1 küçük karakter istenmektedir. (Pozitif durumda Max içeriği belirler.)
- `maxrepeat=3`: 3'ten fazla art arda karakter içermemelidir.
- `user_check=0`: Şifre, kullanıcı adını içermemelidir.
- `difok=7`: Eski şifre kullanılmak isteniyorsa, eski şifreden farklı olarak en az 7 karakter içermelidir.
- `enforce_for_root`: Belirtilen kuralları root yani kök kullanıcı şifresi içinde uygula anlamına gelir.
- `retry=3`: Standart kuraldır. Art arda 3 defa şifre giriş işlemi gerçekleştirilebilir.

