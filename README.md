# Mushaf Ibn Hashim — Shared Verification Databases

This repository stores the **manually verified** verse metadata databases shared between:
1. **Mushaf Ibn Hashim Studio Editor (macOS Desktop)** (`mushaf-editor-ibn-hashim`)
2. **Qur'an Editor (iOS Mobile Editor)** (`mobile-mushaf-editor`)

## Files

| File | Description |
| :--- | :--- |
| `verified_verses.json` | Map of verified verses (`"surah:verse"`) with verification timestamps (`verifiedAt`, `formattedDate`: `"mm-dd-yyyy xx:yyAM"`) and verified verse-level texts (`text_translation`, `text_arabic`, `text_arabic13`) |
| `quran_word_by_word.json` | Verified word-by-word Arabic (`a`, `a13`), English translation (`t`), and transliteration (`tr`) |
| `quran_roots.json` | Verified trilateral roots (`r`, `r13`), lexicon verbs/nouns (`rv`, `rv13`, `mudaari`, `mudaari13`, `rvt`, `rn`, `rn13`, `rnt`), and morphological breakdown (`comp`) |
| `quran_english_irab_full.json` | Verified word-by-word English grammatical analysis (I‘rab) |
| `arabic-irab-default.json` | Verified summarized Arabic I‘rab per word |
| `darwish_irab.json` | Verified in-depth classical Arabic I‘rab (*I‘rab al-Qur’an al-Karim wa Bayanuhu* by Muhyi al-Din al-Darwish) |
| `quran_english_balagha_full.json` | Verified English rhetorical analysis (Balaghah) |
| `darwish_balagha.json` | Verified classical Arabic rhetorical analysis (Balaghah by al-Darwish) |
