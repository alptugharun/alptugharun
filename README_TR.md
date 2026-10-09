<div align="center">

<a href="./README.md">English</a> · <a href="./README_TR.md">Türkçe</a>

# ALPTUĞ HARUN
### Yapay zekâ iş akışı geliştiricisi · Açık kaynak araçlar · İçerik üretim sistemleri

**Yapay zekâ fikirlerini insanların kurabildiği, inceleyebildiği ve gerçekten kullanabildiği araçlara dönüştürüyorum.**

[Projeleri keşfet](#nereden-başlamalı) · [2 dakikalık kontrol](#iki-dakikada-dene) · [Doğrulama yaklaşımı](#vaat-değil-kanıt) · [İş birliği](#birlikte-çalışalım)

[![Web sitesi](https://img.shields.io/badge/Web_sitesi-alptugharun.com-0B1220?style=for-the-badge)](https://alptugharun.com)
[![Yazılar](https://img.shields.io/badge/Practical_AI-Workflows-365CF5?style=for-the-badge)](https://alptugharun.hashnode.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bağlantı-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/alptugharun/)

</div>

---

## Rozet koleksiyonu değil, çalışan ürün vitrini

**İyi bir GitHub profili ürün sayfası gibi çalışmalı:** açık bir fayda, hemen denenebilen araçlar, yeniden üretilebilir kanıt ve dürüst sınırlar.

```text
İHTİYAÇ                         GELİŞTİRME AKIŞI                  KANIT
"İşimi çözsün"             →     prompt → skill → MCP → otomasyon  → demo + test
"Ne içerik üretmeliyim?"    →     veri → puanlama → insan kontrolü   → açıklanabilir sonuç
"Kurulum güvenli mi?"       →     izinler → statik denetim          → bulgu + inceleme
```

## Nereden başlamalı?

| İhtiyacın | Buradan başla | Ne sağlıyor? |
| :--- | :--- | :--- |
| **API anahtarı olmadan AI aracı denemek** | [AI Social Media Toolkit](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/START-HERE.md) | Yerel kontrol, prompt, asistan taslakları, Agent Skills ve içerik akışları |
| **Üç salt okunur MCP aracı kullanmak** | [AI Workbench MCP](https://github.com/alptugharun/ai-workbench-mcp) | Prompt listesi, prompt oluşturma ve asistan taslağı |
| **Skill kurmadan riskleri incelemek** | [Agent Skill Safety Auditor](https://github.com/alptugharun/agent-skill-safety-auditor) | Çevrimdışı statik kontrol ve anlaşılır risk bulguları |
| **Kendi verilerinle içerik fırsatı sıralamak** | [Creator Signal Lab](https://github.com/alptugharun/creator-signal-lab) | Şeffaf CSV tabanlı fırsat ve aykırı gönderi analizi |
| **Görselleri farklı formatlarda hazırlamak** | [Creator Frame Studio beta](https://github.com/alptugharun/ai-social-media-toolkit/tree/main/tools/creator-frame-studio) | Yerel kadrajlama ve dışa aktarma; AI veya otomatik paylaşım değil |

> **Yayın sınırı:** Beta sürümler ve açık PR'lar, kullanıma sunulmuş ve üretim ortamında doğrulanmış özellik gibi gösterilmez. Güncel durum için ilgili depoya bak.

## İki dakikada dene

Ana toolkit'in ücretsiz ve API anahtarı gerektirmeyen yerel kontrolü:

```bash
git clone https://github.com/alptugharun/ai-social-media-toolkit.git
cd ai-social-media-toolkit
python tools/first_run_check.py
```

Başarılı sonuç **yerel dosyaları** denetler; harici AI sağlayıcılarını, gerçek hesapları veya bütün uygulama ortamlarını doğrulamaz. [Kurulum ve hata giderme rehberi →](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/START-HERE.md)

## Projeler ve doğrulama bağlantıları

| Ürün | Kontrol et |
| :--- | :--- |
| [AI Social Media Toolkit](https://github.com/alptugharun/ai-social-media-toolkit) | [CI](https://github.com/alptugharun/ai-social-media-toolkit/actions/workflows/validate-skills.yml) · [Güvenlik](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/SECURITY.md) · [Katkı rehberi](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/CONTRIBUTING.md) |
| [AI Workbench MCP](https://github.com/alptugharun/ai-workbench-mcp) | [CI](https://github.com/alptugharun/ai-workbench-mcp/actions/workflows/ci.yml) · [Bağımsız ortam testi çağrısı](https://github.com/alptugharun/ai-workbench-mcp/issues/5) |
| [Agent Skill Safety Auditor](https://github.com/alptugharun/agent-skill-safety-auditor) | [CI](https://github.com/alptugharun/agent-skill-safety-auditor/actions/workflows/ci.yml) · Statik tarama; güvenlik sertifikası değil |
| [Creator Signal Lab](https://github.com/alptugharun/creator-signal-lab) | [CI](https://github.com/alptugharun/creator-signal-lab/actions/workflows/ci.yml) · Scraping veya virallik tahmini yok |

## Vaat değil, kanıt

**Taslak → çevrimdışı test → gerçek uygulama ortamında test → gerçek kullanıcı kanıtı** aşamalarını birbirinden ayırıyorum. Yeşil yerel test, bağımsız kullanıcı doğrulaması değildir. Güvenlik uyarısı tek başına zararlı yazılım teşhisi değildir.

Önceliklerim: en az yetki · açıklanabilir sonuç · test edilebilir kurulum · anlaşılır hata mesajları · erişilebilir dokümantasyon · paylaşım öncesinde insan onayı.

## Profesyonel GitHub profili nasıl hazırlanır?

**GitHub profil README fikirleri** arayanlar için bu sayfada uyguladığım altı kural:

1. Teknolojileri saymadan önce kullanıcının hangi işini çözdüğünü anlat.
2. Gösterişli sayılardan önce gerçekten çalıştırılabilen bir örnek sun.
3. Testlerin neyi kanıtladığını ve neyi kanıtlamadığını açıkça yaz.
4. Harici görseller yüklenmese bile sayfa anlaşılır kalsın.
5. Mobil okunabilirliğe, erişilebilirliğe ve iki dil arasında geçişe önem ver.
6. Yıldız istemek kadar yeniden üretilebilir hata bildirimini de önemse.

Bu sayfa bir uygulama örneğidir; Google sıralaması veya dünyada birincilik garantisi değildir.

## Birlikte çalışalım

AI destekli içerik sistemleri, Agent Skill/MCP uygulamaları, araştırma araçları ve onay kontrollü otomasyonlar geliştiriyorum. Açık kaynak depolarım teknik vitrinim; uygulama ve danışmanlık çalışmalarım için [alptugharun.com](https://alptugharun.com).

Markalar: **ADYA Creative** · **Yeşil Dijital Akademi**. Yazılar: [Practical AI Workflows](https://alptugharun.hashnode.dev). Portfolyo: [Behance](https://www.behance.net/alptugharun/). Sosyal: [Instagram](https://www.instagram.com/alptug.harun/).

<div align="center">

**DAHA AZ GÜRÜLTÜ. DAHA FAYDALI ÜRÜN. DAHA SAĞLAM KANIT.**

</div>
