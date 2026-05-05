# Чекліст GitHub-профілю (не README)

Цей файл — підказки для налаштувань, які **не** живуть у `README.md` профілю.

## Bio

- Онови біо в **Settings → Profile** (або `gh auth refresh -h github.com -s user` і `gh api user -X PATCH -f bio="..."`).
- Без фраз на кшталт «slow to respond». Краще: спеціалізація (RE, malware analysis, DevSecOps) + стек.

## Закріплені репозиторії (Pinned)

Принцип **«менше — краще»**: залиш **4** репо, які продають вузьку спеціалізацію (DevSecOps + RE), без форків і «шуму».

1. **`APT-SecureOps-Lab`** — GCP/GKE, Falco, Trivy, BigQuery.
2. **`MalKit-Malware-Analysis-Reverse-Engineering-Toolkit`** — RE / malware-analysis tooling.
3. **`Vulnerability-Dashboard`** (або твій Streamlit CVE-дашборд під такою назвою) — коли репо опубліковано; зараз на акаунті може ще не існувати — тоді тимчасово заміни на сильний **Go/C++** флагман.
4. **`Polyglot-Microservices-Benchmark`** (або інший нативний **Go/C++** проєкт з чітким README).

**GitHub:** Profile → **Customize your pins** → зніми зайве (Honeypot, ZenFlare, BOLA, FastLM тощо), залиш саме ці чотири.

### Topics для APT (discoverability)

На **`APT-SecureOps-Lab`** варто тримати серед іншого: `cloud-security`, `gcp`, `kubernetes-security`, `falco`, `blue-teaming`, `trivy`, `bigquery`, `devsecops` (лиміт GitHub — 20 тегів на репо).

## Contribution graph

- **Settings → Profile** → увімкни показ приватних контрибуцій, якщо працюєш у приватних репо (і загалом зроби граф **публічним**, якщо хочеш довіри для портфоліо).

## Social preview («обличчя» репозиторію)

Коли кидаєш лінк у Telegram / Discord / LinkedIn, без прев’ю виглядає «сірим». Це **не** файл у гілці — картинку треба завантажити в налаштуваннях репо.

**Шлях:** репозиторій → **Settings** → **General** → внизу блок **Social preview** → **Edit** → завантаж зображення.

**Розмір:** орієнтир **1280×640** або класичні **1200×630** (OG); головний текст/логотип тримай ближче до центру — краї обрізаються в деяких клієнтах.

**Пріоритетні репо (мінімум):**

| Репозиторій | Ідея для картинки |
|---------------|-------------------|
| **APT-SecureOps-Lab** | Експорт Mermaid / схема GKE → Trivy → BigQuery, або стилізований скрин Terraform/README |
| **MalKit-Malware-Analysis-Reverse-Engineering-Toolkit** | Логотип-напис MalKit, стек RE (Ghidra/x64dbg), або фрагмент структури `docs/` |

Після збереження перевір прев’ю через «Copy link» і встав в чат — має підтягнутися твоя картинка, а не дефолтний GitHub.

## Релізи

- Для інструментів створюй **Releases** (хоча б `v0.1.0` з нотатками + архів сирців). Бінарники додавай, коли з’явиться стабільний build.

## Маркетинг (поза GitHub)

- Діліться лінками в тематичних чатах / r/ReverseEngineering тощо — це окремо від коду.

## Bio (формулювання для 9+)

Приклад позиціонування (без «slow to respond»):

`DevSecOps | Cloud Security (GCP/GKE) | Reverse Engineering & malware-analysis tooling`

Додай **LinkedIn** / блог у полі *Social accounts* профілю GitHub, якщо є.

## Vulnerability Dashboard (Streamlit)

Якщо репозиторій з **Python + Streamlit** ще не на GitHub — опублікуй його окремо й додай у **Pinned**. У README обов’язково:

- 2–3 **скриншоти** UI (звіти, фільтри CVE);
- `pip install -r requirements.txt` + `streamlit run app.py` (або фактичний шлях).

## Релізи (MalKit та інші тули)

- **MalKit:** реліз **`v1.0.0`** створено на GitHub з коротким changelog; наступні ітерації — `v1.0.1`, `v1.1.0` тощо.
- Для інших тулів: **`v0.x`**, поки API не зафіксований; потім **`v1.0.0`** + нотатки «що вміє збірка».
- **Бінарники** в Releases — лише якщо це легальні навчальні артефакти й ти готовий до AV false positives; інакше залишай **джерела + інструкція збірки**.
