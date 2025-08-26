# MusicGen Restoration 🎵 
Questo progetto ha come obiettivo il **restauro audio** di clip generate con [MusicGen](https://github.com/facebookresearch/audiocraft),
con particolare attenzione alla riduzione del fruscio in alta frequenza e al mantenimento della musicalità originale.
Ho sperimentato tre modelli principali:
- **M1-Noise Reduction (alte frequenze)**
- **M2-High-Band Spectral Subtraction (HBSS)**
- **M3-MCRA+filtro High Frequency**

## 📂 Contenuto del repository
- `Progetto_ml_ID2_Giorgia_Cecchi_2068959.ipynb` → notebook con il codice  
- `outputs/raw/` → tracce originali  
- `outputs/processed/` → tracce restaurate con i tre metodi  
- `outputs/results/` → metriche numeriche (CSV)
