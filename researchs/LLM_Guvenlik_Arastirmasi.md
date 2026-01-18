 LLM Güvenliği ve Prompt Injection Araştırması

 1. Prompt Injection Nedir?
Kullanıcı girdileri aracılığıyla Büyük Dil Modellerini (LLM) geliştiricinin belirlediği kuralların dışına çıkmaya zorlama tekniğidir. Tıpkı SQL Injection gibi, modelin girdiyi komut olarak algılaması sağlanır.

 2. OWASP Top 10 for LLM (2025)
OWASP'ın yayınladığı listeye göre en kritik riskler:
1.  **LLM01: Prompt Injection:** Modelin manipüle edilerek izinsiz işlemler yapması.
2.  **LLM02: Insecure Output Handling:** Model çıktılarının güvenlik kontrolünden geçmeden sunulması.

 3. Yaygın Saldırı Teknikleri (Jailbreak)
* **DAN (Do Anything Now):** Modele kısıtlamaları kaldırması için rol yapma komutu verme.
* **Payload Splitting:** Zararlı komutları parçalara bölerek filtreleri atlatma.
* **Translation Attacks:** Zararlı komutu nadir bir dile çevirip modele verme.

 4. Araştırılacak Kaynaklar
* OWASP LLM Security Top 10
* GitHub: `jailbreak_llms` dataset
* Makale: "Universal and Transferable Adversarial Attacks on Aligned Language Models"
