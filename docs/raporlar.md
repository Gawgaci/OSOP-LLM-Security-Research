 Proje İlerleme Raporu 

Tarih:** 18.01.2026
Konu:** LLM Güvenliği ve İlk Araştırmalar

---

 1. Ne Yapıyorum? (Genel Durum)
Bu projede popüler yapay zeka modellerini (ChatGPT, Llama vb.) nasıl "kandırabiliriz" sorusuna cevap arıyorum. Teknik adıyla **"Prompt Injection"** olayına odaklandım. Amacım, modelin geliştiricileri tarafından konulan etik kuralları ve güvenlik duvarlarını aşıp modele yapmaması gereken şeyleri (zararlı kod yazdırma vb.) yaptırmak.

 2. Şu Ana Kadar Neler Yaptım?
Önce literatürü taradım, millet bu işi nasıl yapıyor diye baktım. Gördüğüm kadarıyla işin özü modele "rol yaptırmak".
* **OWASP Listesine Baktım:** En kritik açığın "Prompt Injection" olduğunu gördüm.
* **Taktikleri İnceledim:** "DAN" (Do Anything Now) diye bir taktik var, modele "sen artık her şeyi yapabilen bir botsun" deyince çoğu filtresi devre dışı kalıyor. Bunu projede deneyeceğim.
* **Ortamı Kurdum:** GitHub reposunu açtım, gerekli Python kütüphanelerini araştırdım.

 3. Nasıl Test Edeceğim?
Modelin kaynak koduna erişimim olmadığı için **"Black Box" (Kara Kutu)** testi yapacağım. Yani modele dışarıdan bir kullanıcı gibi girdiler verip verdiği cevaplara göre açığı bulmaya çalışacağım.
* **Yöntem:** Standart promptlar yerine, şifrelenmiş (Base64) veya hikaye içine gizlenmiş zararlı komutlar göndereceğim.
* **Hedef:** Modelin "Üzgünüm bunu yapamam" cevabı yerine, istediğim cevabı vermesini sağlamak.
