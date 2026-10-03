<div align="center">

<a href="./README.md"><img src="https://img.shields.io/badge/English-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="English"></a>
<a href="./README_TR.md"><img src="https://img.shields.io/badge/Türkçe-E30A17?style=for-the-badge&logo=readme&logoColor=white" alt="Türkçe"></a>

# Alptuğ Harun

### Sosyal Medya Uzmanı · AI Workflow Builder · Dijital İçerik Üreticisi

Belirsiz bir AI fikrini alıp **çalışan, test edilebilen, anlatılabilen ve tekrar kullanılabilen** bir sisteme dönüştürmeyi seviyorum.

[![Website](https://img.shields.io/badge/alptugharun.com-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://alptugharun.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alptugharun/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/alptug.harun/)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/alptugharun/)

</div>

---

## Gerçekte ne geliştiriyorum?

Açık kaynak işlerimde kullandığım akış basit:

**prompt → yeniden kullanılabilir asistan → Agent Skill → MCP/API → otomasyon → doğrulama**

**ChatGPT/OpenAI, Claude/Anthropic, Gemini ve Grok/xAI** tarafında çalışıyorum. Canva, Pinterest, Reels, sosyal medya araştırması ve dijital görünürlük ise bu sistemlerin creator odaklı uygulama alanları.

Benim için en önemli kısım şu: **çalışıyor mu, nerede bozulabilir, hangi izni istiyor ve başka biri aynı sonucu tekrar üretebilir mi?**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/MCP-111827?style=flat-square" alt="MCP">
<img src="https://img.shields.io/badge/Agent_Skills-6D28D9?style=flat-square" alt="Agent Skills">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI">
<img src="https://img.shields.io/badge/Anthropic-D97706?style=flat-square" alt="Anthropic">
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini">
<img src="https://img.shields.io/badge/Grok-000000?style=flat-square&logo=x&logoColor=white" alt="Grok">
<img src="https://img.shields.io/badge/Canva-00C4CC?style=flat-square&logo=canva&logoColor=white" alt="Canva">
<img src="https://img.shields.io/badge/Pinterest-BD081C?style=flat-square&logo=pinterest&logoColor=white" alt="Pinterest">
</p>

## Öne çıkan açık kaynak çalışmam

### 🚀 [AI Social Media Toolkit](https://github.com/alptugharun/ai-social-media-toolkit)

Sadece prompt koleksiyonu olmayan, pratik bir AI workbench.

İçinde:

- yeniden kullanılabilir prompt sistemleri ve asistan blueprint'leri;
- creator operasyonları, araştırma ve dijital görünürlük için **17 Agent Skill**;
- bağımlılıksız, salt-okunur **MCP server**;
- API/bot başlangıç yapıları;
- CI, CodeQL, OpenSSF Scorecard ve M8ven doğrulaması;
- tekrar üretilebilir demolar, runtime kanıt kuralları ve hata senaryoları.

[![CI](https://github.com/alptugharun/ai-social-media-toolkit/actions/workflows/validate-skills.yml/badge.svg)](https://github.com/alptugharun/ai-social-media-toolkit/actions/workflows/validate-skills.yml)
[![M8ven Score](https://m8ven.ai/badge/mcp/alptugharun-ai-social-media-toolkit-adv58l?v=03bebb9d62df5457451770e8ba62ec55)](https://m8ven.ai/mcp/alptugharun-ai-social-media-toolkit-adv58l?s=readme)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/alptugharun/ai-social-media-toolkit/badge)](https://scorecard.dev/viewer/?uri=github.com/alptugharun/ai-social-media-toolkit)

**Buradan başla:** [2 dakikalık doğrulama](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/START-HERE.md) · [10 Quick Wins](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/QUICK-WINS.md) · [AI Ecosystem Hub](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/AI-ECOSYSTEM-HUB.md) · [Standalone MCP](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/packages/ai-workbench-mcp/README.md)

## Bağımsız projeler

Toolkit içindeki üç çalışma artık kendi odaklı public reposuna sahip.

### 🔌 [AI Workbench MCP](https://github.com/alptugharun/ai-workbench-mcp)

[![CI](https://github.com/alptugharun/ai-workbench-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/alptugharun/ai-workbench-mcp/actions/workflows/ci.yml)

Yeniden kullanılabilir prompt ve asistan blueprint'lerini sunan bağımlılıksız, salt-okunur MCP server. Public yüzeyi özellikle küçük tutuldu: `list_prompts`, `render_prompt` ve `get_assistant`. `0.1.0a1` sürümü PyPI'de yayınlandı ve resmi MCP Registry'de aktif; exact-version stdio doğrulaması gerçek host uyumluluğundan ayrı tutuluyor.

### 🛡️ [Agent Skill Safety Auditor](https://github.com/alptugharun/agent-skill-safety-auditor)

[![CI](https://github.com/alptugharun/agent-skill-safety-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/alptugharun/agent-skill-safety-auditor/actions/workflows/ci.yml)

Agent Skill'leri kurmadan önce offline inceler. Remote shell pipe, process erişimi, environment okuma ve install hook gibi sinyalleri görünür hale getirir; son kararı regex'e değil insana bırakır.

### 📈 [Creator Signal Lab](https://github.com/alptugharun/creator-signal-lab)

[![CI](https://github.com/alptugharun/creator-signal-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/alptugharun/creator-signal-lab/actions/workflows/ci.yml)

İki şeffaf creator araştırma aracı: içerik fırsatlarını önceliklendiren scorer ve kendi baseline'ına göre sosyal gönderi outlier'larını bulan scorer. Scraping yok, gizli AI puanı yok, virallik vaadi yok.

Ana toolkit içinde kalan iki güçlü hat: **Creator Research Radars** ve **Human-first Content QA**. Bunları da ancak bağımsız kullanım senaryosu entegre kalmaktan daha güçlü hale gelirse ayıracağım.

**Hâlâ 20 boş repo yerine az sayıda gerçekten kullanılan repo tercih ederim.**

## İki dakikada bir şey dene

Ana toolkit'i klonla ve çalıştır:

```bash
python tools/first_run_check.py
```

Bu kontrol için API key, sosyal medya girişi veya ücretli model çağrısı gerekmez.

Başarılı bir çalıştırma; yerel kataloğu, dry-run provider yolunu, Agent Skill installer akışını ve creator demoyu doğrular.

## Kanıt seviyelerini nasıl ayırıyorum?

Şunları birbirine karıştırmıyorum:

**Blueprint** → **Offline tested** → **Runtime verified** → **Production evidence**

Bir README'de "çalışıyor" yazması, gerçek bir hostun onu çalıştırdığı anlamına gelmez.

Standalone MCP paketini gerçek bir hostta test etmek istersen:

→ [Bağımsız MCP runtime doğrulaması](https://github.com/alptugharun/ai-social-media-toolkit/issues/110)

## Creator ve marka tarafı

GitHub, yaptığım işlerin teknik ve açık kaynak katmanı.

GitHub dışında AI destekli sosyal medya, dijital görünürlük ve creator sistemleri üzerinde **ADYA Creative** ve **Yeşil Dijital Akademi** kapsamında çalışıyorum.

---

<div align="center">

### GitHub görünümü

<img src="https://github-readme-stats.vercel.app/api?username=alptugharun&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" height="165" alt="Alptuğ Harun GitHub stats">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alptugharun&layout=compact&theme=github_dark&hide_border=true" height="165" alt="Top languages">

**Daha az gürültü. Daha fazla kanıt.**

</div>
