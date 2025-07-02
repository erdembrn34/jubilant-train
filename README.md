# Hisse Senedi Fiyatlarının Keşifsel Analizi ve Backtesting

Bu proje, SAP 500 endeksine ait hisse senedi fiyat verisi üzerinde keşifsel veri analizi, teknik gösterge hesaplama ve basit backtesting stratejileri uygulanmasını içermektedir.

## İçerik

- Veri ön işleme ve temel istatistiksel analizler  
- Teknik göstergeler: MACD, RSI, Bollinger Bands, Stochastic Oscillator  
- Basit al-sat stratejileri ve performans değerlendirmesi  
- Parametre optimizasyonu ve grafiklerle sonuç görselleştirme  

## Dosya Yapısı

- `data/` : Veri dosyaları  
- `notebooks/` : Jupyter notebook ile interaktif analizler  
- `src/` : Python modülleri (gösterge ve backtesting fonksiyonları)  
- `results/figures/` : Üretilen grafik ve görseller  

## Kurulum

```bash
git clone <repo-url>
cd stock-analysis-project
python -m venv venv
source venv/bin/activate      # Windows için: venv\Scripts\activate
pip install -r requirements.txt

