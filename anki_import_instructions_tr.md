# Anki Kartları İçe Aktarma Talimatları

Bu doküman, `bash_boilerplate_anki_tr.md` ve `bash_boilerplate_anki_en.md` dosyalarındaki Anki kartlarını Anki uygulamasına nasıl aktaracağınızı açıklar. Kartlar, **Learn Bash by Building a Boilerplate** dersinden oluşturulmuştur ve **Dr. Piotr Wozniak’ın Twenty Rules of Formulating Knowledge** kurallarına uygundur.

## Kart Tipi Oluşturma
1. Anki’yi açın ve **Araçlar > Kart Tiplerini Yönet**’e gidin.
2. Yeni bir kart tipi oluşturun:
   - İsim: “Bash Kart Tipi”.
3. **Alanlar** sekmesinde aşağıdaki alanları ekleyin (sırayla):
   - Question
   - Answer
   - Example
   - Source
4. **Kartlar** sekmesinde şablonu düzenleyin:
   - **Ön**:
     ```
     {{Question}}
     ```
   - **Arka**:
     ```
     {{Answer}}
     <hr>
     Örnek: {{Example}}
     <hr>
     Kaynak: {{Source}}
     ```

## Dosya Hazırlığı
1. **Dosya Seçimi**:
   - Türkçe kartlar için: `bash_boilerplate_anki_tr.md`
   - İngilizce kartlar için: `bash_boilerplate_anki_en.md`
2. Markdown dosyasındaki içeriği kopyalayın (```text ile başlayan ve biten kod bloğu içindeki metni).
3. Bir metin editöründe (Notepad, VS Code) dosyayı `.txt` uzantısıyla kaydedin:
   - Türkçe: `bash_boilerplate_anki_tr.txt`
   - İngilizce: `bash_boilerplate_anki_en.txt`
   - **Not**: UTF-8 kodlamasını seçin.

## İçe Aktarma
1. Anki’de **İçe Aktar Dosyası**’nı seçin ve `.txt` dosyasını yükleyin.
2. Ayarları yapılandırın:
   - **Deste**: Örneğin, “Bash Dersleri”.
   - **Tür**: “Bash Kart Tipi”.
   - **Alan Eşleme**:
     - Sütun 1: Question
     - Sütun 2: Answer
     - Sütun 3: Example
     - Sütun 4: Source
   - **Ayırıcı**: Tab
   - “İlk alanı benzersiz olarak işaretle” seçeneğini açık tutun.
3. “İçe Aktar”a tıklayın ve kartları kontrol edin.

## Hata Giderme
- **UTF-8 Sorunları**: Dosyanın UTF-8 kodlamasıyla kaydedildiğinden emin olun.
- **Ayırıcı Hatası**: Anki’nin ayırıcı ayarını “Tab” olarak kontrol edin.
- **Eksik Alanlar**: Alan eşlemesinin doğru olduğundan emin olun.

## Notlar
- Kartlar, tab-separated formatta ve 30 kart içerir (27 soru-cevap, 3 cloze deletion).
- Türkçe ve İngilizce kartlar, aynı bilgileri farklı dillerde sunar.
- Sorular veya sorunlar için GitHub üzerinden bir issue açabilirsiniz.