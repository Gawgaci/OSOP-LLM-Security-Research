 Araştırma Kaynakları ve Literatür Taraması

1. Temel Kaynaklar (Core Resources)
* **OWASP Top 10 for LLM Applications (2025):** Büyük Dil Modelleri için en kritik 10 güvenlik riskini tanımlayan standart belge.
    * *Odak Noktası:* LLM01: Prompt Injection, LLM02: Insecure Output Handling.
    * *URL:* [owasp.org/www-project-top-10-for-large-language-model-applications/](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* **Microsoft Security Blog - Jailbreak Attacks:** Microsoft'un LLM'lere yönelik "Dan" ve türevi saldırılar üzerine analizleri.

 2. Akademik Makaleler (Academic Papers)
* **"Universal and Transferable Adversarial Attacks on Aligned Language Models" (Zou et al., 2023):**
    * *Özet:* Otomatikleştirilmiş "suffix" ekleme yöntemi ile neredeyse tüm açık kaynak modellerin (Llama-2, Vicuna) korumasının aşılabileceğini kanıtlayan çalışma.
* **"Jailbroken: How Does LLM Safety Training Fail?" (Wei et al., 2023):**
    * *Özet:* Güvenlik eğitimlerinin (RLHF) neden karmaşık prompt injection saldırılarına karşı yetersiz kaldığını inceleyen araştırma.

 3. Kullanılacak Araçlar ve Kütüphaneler (Tools)
* **Garak (LLM Vulnerability Scanner):** LLM'ler için nmap benzeri güvenlik tarayıcısı.
* **LangChain:** Prompt yönetimi ve zincirleme saldırı senaryolarını test etmek için framework.
* **PyRIT (Python Risk Identification Tool):** Microsoft'un yayınladığı kırmızı takım (red teaming) aracı.

 4. Zafiyet Veritabanları
* **AI Vulnerability Database (AVID):** Yapay zeka sistemlerine özgü güvenlik
