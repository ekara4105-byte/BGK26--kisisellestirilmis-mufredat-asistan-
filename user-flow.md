 Flying Focus: User Flow 
​Bu dosyayı projenin içine ekleyerek AI'nın sayfalar arası geçişi hatasız kodlamasını sağlayabilirsin:
​1. Giriş ve Karşılama (Onboarding)
​Adım 1: Kullanıcı uygulamayı açar (Ana Dashboard).
​Adım 2: AI sorar: "Bugün enerji seviyen nasıl?" (Düşük / Orta / Yüksek).
​Adım 3: Kullanıcı seçimini yapar.
​2. Müfredat ve Veri Girişi (Input Phase)
​Adım 4: Eğer ilk kullanımsa, kullanıcı "Müfredat Yükle" butonuna tıklar.
​Adım 5: Ders adlarını, konuları ve Deadline (Son Teslim Tarihi) bilgilerini girer.
​Adım 6: "Kaydet"e basar (Veriler SQLite veritabanına kalıcı olarak yazılır).
​3. Dinamik Planlama (AI Processing)
​Adım 7: AI, girilen müfredatı ve seçilen enerji seviyesini analiz eder.
​Adım 8: Ekrana o an için en uygun 3 görev çıkarır (Örn: "Enerjin düşük, şu 10 dakikalık özeti izle").
​4. Çalışma ve Geri Bildirim (Action Phase)
​Adım 9: Kullanıcı görevi tamamladığında "Bitirdim" işaretlemesi yapar.
​Adım 10: Eğer bir deadline yaklaşıyorsa, sistem uyarı verir: "Sınava 2 gün kaldı, rota güncelleniyor!"
