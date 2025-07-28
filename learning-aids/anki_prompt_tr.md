Grok Talimat (Türkçe)
Amaç
Verilen ders notlarını, Dr. Piotr Wozniak'ın Twenty Rules of Formulating Knowledge kurallarının tamamına uygun şekilde Anki kartlarına dönüştürmek. Kartlar, tab-separated formatta, Türkçe, Anki’ye doğrudan aktarılabilir ve Question, Answer, Example, Source alanlarıyla hazırlanacak. Cloze deletion kartları uygun şekilde seçilecek.
Talimatlar

Ders Notları:
Gönderilen ders notlarını (metin, bağlantı veya kopyala-yapıştır) al.
Notları küçük, anlamlı parçalara ayır (kavramlar, hatalar, örnekler).


Anki Kart Formatı:
Alanlar ve Sıralama:
Question: Soru metni (kısa, net, tek bir bilgiyi hedefler).
Answer: Kavramın açıklaması (örneksiz, kısa ve net).
Example: Kod örneği veya pratik uygulama (varsa; yoksa boş).
Source: Notun alındığı modül/kurs (örneğin, “Free Foundational C# with Microsoft Certification - [Modül Adı]”).


Yapı: Her satır, Question [TAB] Answer [TAB] Example [TAB] Source formatında.
Dosya: Kartları .txt formatında, UTF-8 kodlamasıyla sun. Dosya adı: [konu]_anki.txt (örneğin, csharp_first_code_anki.txt).


Cloze Deletion:
Cloze deletion kartları uygun şekilde seçilir. Kısa, net ve kritik bilgileri (tanımlar, karşılaştırmalar, hata kodları, kurallar) cloze formatına dönüştür.
Cloze kartlar, toplam kartların %10-20’sini oluşturur ve tek bir eksik bilgiyi hedefler.
Örnek: “C# ... harf duyarlıdır” → “C# büyük-küçük harf duyarlıdır”.


20 Kural Uygulamaları:
Kural 1 (Anlamadan Öğrenme): Kavramlar açık, örnekler ayrı.
Kural 2 (Kendi Bağlamında Öğren): Bilgi, ders bağlamında sunulur (örneğin, C#’ta Console.WriteLine’ın kullanımı programlama bağlamında).
Kural 3, 4 (Basitlik): Her kart tek bir bilgiyi hedefler, gereksiz detaylardan kaçınılır.
Kural 5 (Cloze Deletion): Uygun yerlerde cloze kartlar eklenir (seçim Grok’a ait).
Kural 6 (Resim ve Görsel Kullanımı): Kod örnekleri veya diyagramlar Example alanına eklenir, ancak görseller metin tabanlı kalır.
Kural 7 (Mnemonic): Hatırlatıcı benzetmeler kullanılır (örneğin, “Console.WriteLine, mektup gibi satır sonu ekler”).
Kural 8 (Geniş Kapsamlılık): Notların tüm önemli noktaları kapsanır.
Kural 9 (Tekrarlama): Kartlar, öğrenmeyi pekiştirmek için tekrarlanabilir yapıda tasarlanır.
Kural 10 (Önceliklendirme): Daha kritik bilgiler (örneğin, sık yapılan hatalar) önceliklendirilir.
Kural 11 (Karışıklık Önleme): Benzer kavramlar netleştirilir (örneğin, Console.Write vs. Console.WriteLine).
Kural 12 (Kendi Bilgine Güven): Kartlar, öğrencinin kendi notlarına dayalı olarak doğru ve güvenilir olur.
Kural 13 (Doğrudanlık): Sorular ve cevaplar doğrudan, dolaylı ifadelerden kaçınılır.
Kural 14 (Yeniden Formüle Etme): Aynı bilgi farklı açılardan sorulabilir (örneğin, “Console.WriteLine ne yapar?” ve “Satır sonu ekleyen C# komutu nedir?”).
Kural 15 (Tekrarlama Aralığı Optimizasyonu): Kartlar, Anki’nin aralıklı tekrar algoritmasına uygun şekilde kısa ve net tasarlanır.
Kural 16 (Bağlam İpuçları): Source ve Example bağlam sağlar.
Kural 17 (Kişiselleştirme): Kartlar, notların içeriğine göre özelleştirilir.
Kural 18 (Kaynak Sağlama): Source alanı her karta eklenir.
Kural 19 (Örnekler): Example alanı, kod örneklerini ayrı tutar.
Kural 20 (Gözden Geçirme): Kartlar doğruluk için kontrol edilir.


Kart Oluşturma Süreci:
Notları analiz et, her önemli noktayı (kavram, hata, örnek) bir karta dönüştür.
Soru-cevap ve cloze deletion formatlarını kullan (cloze için seçim Grok’a ait).
Örnekleri Example alanına taşı, açıklamaları Answer’da tut.
Source alanını notun modül/kurs bilgisiyle doldur.
Kartları tab-separated formatta, .txt dosyası olarak sun.


Anki’ye Aktarma Talimatları:
Kart Tipi Ayarlama:
Anki’de Araçlar > Kart Tiplerini Yönet’e git.
Yeni kart tipi oluştur (örneğin, “C# Kart Tipi”).
Alanlar (sırayla): Question, Answer, Example, Source.
Şablon:
Ön: {{Question}}
Arka: {{Answer}} <hr> Örnek: {{Example}} <hr> Kaynak: {{Source}}




İçe Aktarma:
.txt dosyasını kopyala, metin editöründe (Notepad, VS Code) konu_anki.txt adıyla kaydet (UTF-8 kodlaması).
Anki’de İçe Aktar Dosyası’nı seç, dosyayı yükle.
Ayarlar:
Deste: Örneğin, “C# Certification”.
Tür: “C# Kart Tipi”.
Alan eşleme:
Sütun 1: Question
Sütun 2: Answer
Sütun 3: Example
Sütun 4: Source


Ayırıcı: Tab.
“İlk alanı benzersiz olarak işaretle” açık.


“İçe Aktar”a tıkla, kartları kontrol et.




Örnek Uygulama:
Not: Write Your First Code modülü.
Kart Örneği:C#'ta `Console.WriteLine` ne yapar?    Mesajı yazdırır ve satır sonu ekler.    `Console.WriteLine("Hello");` → "Hello" ve yeni satır    Free Foundational C# with Microsoft Certification - Write Your First Code
C# ... harf duyarlıdır.    Büyük-küçük.    `int x` ve `int X` farklı değişkenlerdir.    Free Foundational C# with Microsoft Certification - Write Your First Code


Kartlar, kavramlar, hatalar ve cloze kartlar (Grok’un seçimi) içerir.


Ek Notlar:
Yeni notlar gönderilirse, modül adını belirt (örneğin, “Data Types”), Source alanını buna göre doldur.
Farklı alanlar, format (örneğin, CSV) veya ek cloze kartlar istenirse, talimatta belirt.
Hata durumunda (örneğin, eşleşme sorunu), sorun bildirilirse, spesifik çözüm önerilir.



Talimat Sonu
Yeni notlar ve modül adı paylaşılırsa, bu mantıkla Anki kartlarına dönüştürülecek.