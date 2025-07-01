# Africa-text-Open-Source-Dataset-
## 🇹🇿Maelezo ya Kiswahili

Karibu kwenye **African Text Datasets**! Hapa tunakusanya dataseti zote za maandishi (CSV, JSON, nk.) kwa ajili ya miradi ya NLP.

### 1. Muhtasari & Madhumuni  
- **Nini:** Corpus za maandishi za Afrika (habari, mitandao ya kijamii, mahojiano, n.k.)  
- **Kwa Nini:** Kuleta muundo thabiti wa saraka, metadata na leseni ili kurahisisha matumizi na ushirikiano.

### 2. Mahitaji ya Msingi  
1. Akaunti ya GitHub  
2. Installation ya Git hakikisha imo kwenye Laptop,PC or any device (`git --version`)  
3. (Hiari) Python ≥ 3.7 kwa kuendesha skripti za uhakiki  
4. Umesoma na kukubali **CC BY 4.0** kwa data na **MIT** kwa code

### 3. Muundo wa Saraka  

- `datasets/text/<jina-la-dataset>/data.csv`  
- `datasets/text/<jina-la-dataset>/README.md` — Eleza dataset hii maalum  
- `scripts/validate_text.py` — Uhakiki wa muundo na schema  
- `LICENSE` — CC BY 4.0  
- `CONTRIBUTING.md` — Mwongozo wa michango

### 4. Mwongozo wa Kuchangia

1. **Fork & Clone**  
<pre lang="bash"><code>
git clone https://github.com/AI-Zanzibar/african-text-datasets.git
cd african-text-datasets
</code></pre>

2. **Badilisha Branch ya Main kwenda kwenye contribute**
<pre lang="bash"><code>
git fetch origin
git checkout -b feature/ongeza-text-dataset origin/contribute
</code></pre>

3. **Ukimaliza Kuchangia dataset hakikisha uncommitted changes**
<pre lang="bash"><code>
git add .
git commit -m "feat(text): ongeza dataset <jina-la-dataset>"
git push origin feature/ongeza-text-dataset
</code></pre>

