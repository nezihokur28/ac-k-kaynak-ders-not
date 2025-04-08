# Özgür Yazılım Felsefesi ve Açık Kaynak Kodlu Yazılım Kavramı
Özgür yazılım, kullanıcıların yazılımı çalıştırma, inceleme, değiştirme ve dağıtma özgürlüğüne sahip olduğu bir felsefedir. Temel olarak dört özgürlük içerir:
1. Yazılımı herhangi bir amaçla çalıştırabilme.
2. Yazılımın nasıl çalıştığını inceleme ve değiştirme.
3. Yazılım kopyalarını dağıtma.
4. Değiştirilen sürümleri topluluğa sunabilme.

Açık kaynak kodlu yazılım, özgür yazılım felsefesini teknik olarak destekleyen bir kavramdır. Ancak her açık kaynak yazılım, özgür yazılım değildir.

---

# İşletim Sistemi Katmanları
1. **Kernal (Çekirdek)**: Donanım yönetimi ve sistem kaynaklarının kontrolünü sağlar.
2. **Hizmet Katmanı**: Çekirdek hizmetleri üzerine kurulu sistem işlevlerini sağlar.
3. **Uygulama Katmanı**: Kullanıcıların doğrudan kullandığı uygulamaları barındırır.
4. **Shell**: Kullanıcı komutlarını çekirdeğe ileten bir arayüzdür.

---

# CPU Zamanlama Algoritmaları
1. **FCFS (First-Come, First-Served)**: İlk gelen işlem öncelikli olarak yürütülür.
2. **SJF (Shortest Job First)**: Kısa işler öncelikli olarak yürütülür.
3. **Priority Scheduling**: İşlemler öncelik seviyelerine göre sıralanır.
4. **Round Robin**: İşlemler zaman dilimlerine bölünerek sırayla yürütülür.

---

# CPU Planlama Algoritması: Round Robin (q=5)
Tablo:
| İşlem | İşlem Süresi (ms) | Öncelik |
|-------|-------------------|---------|
| P1    | 10                | 1       |
| P2    | 12                | 0       |
| P3    | 7                 | 3       |
| P4    | 5                 | 2       |

**Round Robin Algoritması** ile işlem sırası:
1. P1 (5ms çalışır, kalan: 5ms)
2. P2 (5ms çalışır, kalan: 7ms)
3. P3 (5ms çalışır, kalan: 2ms)
4. P4 (5ms çalışır, kalan: 0ms)
5. P1 (5ms çalışır, kalan: 0ms)
6. P2 (5ms çalışır, kalan: 2ms)
7. P3 (2ms çalışır, kalan: 0ms)
8. P2 (2ms çalışır, kalan: 0ms)

---

# Dosya Erişim Hakları
Dosya: `dr-xrw-r-- 2 root root 4096 Kas 5 01:02 bin`
- **d**: Bu bir dizindir.
- **r-x**: Sahibi (root) dizini okuyabilir ve çalıştırabilir, yazamaz.
- **rw-**: Grup, dizini okuyabilir ve yazabilir, çalıştırma yetkisi yoktur.
- **r--**: Diğer kullanıcılar dizini sadece okuyabilir.

---

# Bulut Bilişim Hizmet Modelleri
1. **IaaS (Infrastructure as a Service)**: Fiziksel altyapı hizmetleri sunar. Örnek: AWS EC2.
2. **PaaS (Platform as a Service)**: Uygulama geliştirme platformları sağlar. Örnek: Google App Engine.
3. **SaaS (Software as a Service)**: Yazılım hizmetleri sunar. Örnek: Dropbox.

---

# Sanallaştırma Teknolojileri Grupları
1. **Donanım Sanallaştırması**: Örnek: VMware ESXi.
2. **İşletim Sistemi Seviyesi Sanallaştırma**: Örnek: Docker.
3. **Uygulama Sanallaştırması**: Örnek: Citrix XenApp.

---

# Hypervizör, SELinux, Docker Containers ve Virtualization Kavramları
1. **Hypervizör**: Sanal makineleri çalıştıran yazılım (örnek: Hyper-V).
2. **SELinux**: Linux için güvenlik modülü; erişim kontrolleri sağlar.
3. **Docker Containers**: Uygulamaları konteynerler içinde çalıştıran hafif sanallaştırma teknolojisi.
4. **Virtualization**: Fiziksel kaynakları sanal olarak birden fazla ortama böler.

---

Bu düzenlemeler sorularınıza uygun oldu mu? 😊
