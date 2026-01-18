
Yazılım
* İşletim Sistemi:Windows 11
* Dil:** Python 3.10+
* Versiyon Kontrol:Git

 2. Bağımlılıklar (Dependencies)
Projenin çalışması için gereken Python kütüphaneleri:
* `openai`: API bağlantıları için.
* `transformers`: HuggingFace modellerini yerelde test etmek için.
* `torch`: PyTorch (Model işlemleri için).
* `colorama`: Terminal çıktılarını renklendirmek için.

 3. Fonksiyonel Gereksinimler
1.  **Saldırı Simülasyonu:** Sistem, belirlenen "jailbreak" promptlarını hedef modele gönderebilmelidir.
2.  **Başarı Analizi:** Modelin verdiği cevapta "Üzgünüm, yapamam" gibi reddetme ifadeleri olup olmadığını kontrol etmelidir.
3.  **Raporlama:** Başarılı olan (modelin korumasını aşan) promptları `logs/success.txt` dosyasına kaydetmelidir.

 4. Proje Takvimi (Roadmap)
* **Hafta 1:** Literatür taraması ve GitHub reposunun kurulumu. (Tamamlandı)
* **Hafta 2:** Test ortamının hazırlanması ve temel saldırı scriptinin (main.py) yazılması.
* **Hafta 3:** Farklı Prompt Injection tekniklerinin (DAN, Base64) denenmesi.
* **Hafta 4:** Sonuçların analizi ve final raporunun yazılması.
