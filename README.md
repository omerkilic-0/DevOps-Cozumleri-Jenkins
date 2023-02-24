# DevOps Çözümleri (Jenkins)

Bu eğitim kavram haritası mantığında kısa kelime ve cümleler ile devam edecektir.

# Agile Metodolijisi CI,CD

2' ye ayrılır:
  1. Scrum
  2. Kanban
# Agile
Farklı sektördeki bir çok iş insanının bir araya gelmesiyle oluşmuştur.

# 4 Temel Esastan Oluşur

1. Bireyler ve Etkileşimler(Süreçler ve Araçlar)
2. Çalışan yazılım(Dokümantasyon)
3. Müşteri işbirliği(Sözleşme ve pazarlıklardan)
4. Değişime adapte olmak(Plana bağlı kalmak)

# Agile Manifesto 12 Temel Prensibi

1. Ürünün erken, devamlı teslimi
2. Değişimin benimsenmesi
3. sürekli teslimat(2, 3 hafta içerisinde teslim)
4. İş birimi ve yazılımcı iş birliği
5. Motive breyler
6. Yüz yüze iletişim
7. Çalışan yazılım
8. Sabit tempo ile üretim
9. Teknik mükellik
10. Sadelik
11. Otonom organizasyon
12. Düzenli verim kontrolleri

# Agile’ nin 4 Temeli

1. Ürünün erken, devamlı teslimi
2. Değişimin benimsenmesi
3. sürekli teslimat(2, 3 hafta içerisinde teslim)
4. Çalışan yazılım

# Agile DevOps

Ekip iş birliği esas alınır.
Ürün teslimatının sorumluluk ve hesap hızlandırmak için verebilirliğe dikkat çeker.
Değişime odaklanır "Hızlı başarısız ol ve öğren" tutumunu benimser.

# CI/CD

Sürekli iyileştirme esas alınır.
Otomasyon kolaylaştırır araçlara odaklanır.

# (CI) Continuous İntegration

Yapılan değişiklikten sonra sistemin çalıştığını sorun olmadığını kontrol etmek için kullanılan yöntemdir.

# (CD) Continuous Delivery 

CI’ nın devamıdır sorunsuz çalışan yapıyı bireylere atmak için kullanılır. 

# (CD) Continuous Depleyment

Delivery’ nin otomatik gerçekleşmesidir.

# CI/CD’  nin İlkeleri

1. Tekrar eden sürümlerin desteklenmesi
2. Kodun test odaklı geliştirilmesi
3. Küçük yinelemelerle çalışma
4. Build ve Run

# CI/CD’ nin Faydaları

1. Verimliliği artırır
2. Riskleri azaltır
3. Servisleri çevikleştirir.

# Derleme Araçları(Build Tools)

Çalıştıra bilen uygulamaların otomatikleştiren programlardır.

# Amacı:

- Bağımlılıkların(Dependecy) indirilmesi.
- Kaynak kodun Binary koda derlenmesi ve paketlenmesi.
- Testlerin çalıştırılması.
- kodun üretim sistemlerine dağıtım için hazırlanması.

# Maven Pom Dosyası

- Project metadata
- Dependencies
- Maven Plugins

# Maven Kodları

1. Dosyaları temizlemek için(mvn clean)
2. Birim testleri çalıştırmak için(mvn test)
3. Projeyi derlemek için(mvn compile)
4. Paketlemek için(mvn package)
5. Dokümantasyon oluşturmak için(mvn site)

# Docker

Uygulamayı test eder ve dağıtır.
- Hızlı uygulama sunmamızı sağlar
- Sorunu bulup düzeltmeyi kolaylaştırır.

# Docker Hangi Durumlarda Tercih Edilir

1. Mikro hizmetler
2. Sürekli entegrasyon ve teslim
3. Veri işleme
4. Hizmet olarak Container’ lar

# Dockerfile Komutları

From
From image: tag
From Ubuntu: 18,04, latest

Cmd
From Ubuntu
Cmd[”/bin/echo”]

Run 
Run Komut
Run apt-get update&&apt-get upgrade&&apt-get install-y vim

Volume 
Volume <mountpoint>
  
User
User <user>
  
# Jenkins
  
 Açık kaynak kodlu bir otomasyon programıdır.

# Jenkins Kavramı
  
Job
Node
Plugin(eklenti)
Pipeline
  
# Pipeline
 
Jenkins yükleyince otomatik gelir.
  
# Pipeline Özellikleri

- Kod
- Dayanıklılık
- Duraklatılabilirlik
- Çok yönlü
- Genişletilebilirlik

# Pipeline Tanımları
  
1. Pipeline
2. Node
3. Stage
4. Step
  
# Yazar:
  
  Ömer Kılıç
 
# Yayınlanma Tarihi:
  
  24.02.2023
  
# Yazar İletişim/Bilgi/Özgeçmiş:
  
  http://omerkilic.rf.gd/
