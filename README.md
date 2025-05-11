# Temel Python/Pandas Veri Analizi Raporlama Görevleri

---

## 1. Titanic Yolcu Listesi  
**Kaynak:** [Kaggle: Titanic – Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  
**Açıklama:** Yaş, cinsiyet, sınıf, ücret vb. yolcu bilgileri ile hayatta kalma etiketi.

### Önerilen Raporlama Görevleri  
1. **Grup Bazında Hayatta Kalma Oranları**  
   - Genel hayatta kalma oranını hesaplayın.  
   - `Pclass`, `Sex` ve yaş gruplarına (örn. çocuk vs. yetişkin) göre gruplayın.  
   - Çubuk grafiklerle görselleştirin.  
2. **Ücret Dağılımı Analizi**  
   - Sınıflara göre ücret dağılımının histogramını çizin.  
   - Aykırı değerleri tespit edin ve yönetme stratejinizi açıklayın.  
3. **Eksik Veri Özeti**  
   - Her sütundaki eksik değer sayısını ve yüzdesini raporlayın.  
   - Eksik verileri doldurun veya çıkarın; seçiminizi gerekçelendirin.  

---

## 2. Iris Çiçeği Ölçümleri  
**Kaynak:** [UCI Machine Learning Repository: Iris Data](https://archive.ics.uci.edu/ml/datasets/iris)  
**Açıklama:** Üç iris türüne ait çanak ve taç yaprak ölçümleri.

### Önerilen Raporlama Görevleri  
1. **Tanımlayıcı İstatistikler**  
   - Tür bazında her özellik için ortalama, medyan ve varyans hesaplayın.  
   - Düzenli bir DataFrame içinde sunun.  
2. **Korelasyon Matrisi & Isı Haritası**  
   - Özellikler arasındaki korelasyonu hesaplayın.  
   - Isı haritası (heatmap) ile görselleştirin.  
3. **Basit Dağılım Matrisi**  
   - Türlere göre renklendirilmiş ikili dağılım grafikleri (pairwise scatter) oluşturarak ayrışmayı inceleyin.  

---

## 3. Superstore Satış Verisi (Örnek)  
**Kaynak:** [Kaggle: Sample – Superstore Sales Dataset](https://www.kaggle.com/juhi1994/superstore)  
**Açıklama:** Sipariş tarihleri, kategori, satış, kâr, bölge gibi perakende işlem verisi.

### Önerilen Raporlama Görevleri  
1. **Aylık Satış & Kâr Trendleri**  
   - Satış ve kârı aya göre toplayın.  
   - Zaman serisi çizgi grafikleriyle sezonluk değişimi yorumlayın.  
2. **En İyi Kategori & Alt Kategori**  
   - Ürün kategorilerini toplam satış ve kara göre sıralayın.  
   - Yatay çubuk grafikleriyle görselleştirin.  
3. **Bölgesel Performans Panosu**  
   - Bölge × Kategori bazında satış/kâr pivot tablosu oluşturun.  
   - Isı haritası veya açıklamalı tablo kullanın.  

---

## 4. NYC Taksi Yolculuk Kayıtları (Örnek)  
**Kaynak:** [NYC TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
**Açıklama:** Alış/iniş zamanları, konumları, mesafe, ücret bilgileri.

### Önerilen Raporlama Görevleri  
1. **Yoğun Saat Analizi**  
   - Alış zaman damgalarından günün saatini çıkarın.  
   - En yoğun saatleri belirleyin.  
2. **Ortalama Ücret vs. Mesafe**  
   - Ücret ile yolculuk mesafesini dağılım grafiği (scatter plot) ile gösterin.  
   - Basit bir lineer regresyon modeli kurun ve raporlayın.  
3. **Coğrafi Toplama (Bonus)**  
   - İlçe (borough) bazında yolculuk sayısını toplayın (pickup enlem/boylam eşlemesi gerektirir).  

---

## 5. COVID-19 Küresel Vaka Sayıları  
**Kaynak:** [Our World in Data: COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)  
**Açıklama:** Ülkelere göre günlük vaka, ölüm, test, aşı verileri.

### Önerilen Raporlama Görevleri  
1. **Ülke Düzeyinde Zaman Serisi**  
   - Seçilen 3 ülke için milyonda yeni vaka sayılarını çizin.  
   - Başlangıç ve zirve tarihlerini karşılaştırın.  
2. **Hareketli Ortalama & Büyüme Oranları**  
   - 7 günlük hareketli ortalamayı hesaplayın.  
   - Günlük yüzde değişim oranını hesaplayın.  
3. **Aşılama İlerleme Raporu**  
   - İlk 10 ülke için nüfusun % kaçının tam aşılandığını gösteren çubuk grafik hazırlayın.  

---

## 6. Dünya Kalkınma Göstergeleri  
**Kaynak:** [Dünya Bankası WDI CSV](https://databank.worldbank.org/source/world-development-indicators)  
**Açıklama:** Ülke ve yıl bazında ekonomik ve sosyal göstergeler (GSYH, yaşam beklentisi, okuryazarlık vb.).

### Önerilen Raporlama Görevleri  
1. **Gösterge Karşılaştırması**  
   - Belirli bir yıl için kişi başı GSYH ile yaşam beklentisini karşılaştıran grafik oluşturun.  
   - Aykırı değerler için notlar ekleyin.  
2. **Trend Analizi**  
   - 5 ülke seçin, 2000’den günümüze GSYH zaman serisi grafiği çizin.  
3. **Eksik Veri & Tamamlama**  
   - Anahtar göstergelerdeki boşlukları tespit edin.  
   - Basit tamamlama yöntemleri önerin ve uygulayın (örn. ileri doldurma).  

---

### Kullanım Talimatları
- **Teslimat:** Jupyter Notebook veya Python betiği; `pandas`, `matplotlib` (veya `seaborn`) kullanarak net markdown açıklamalarıyla hazırlanmalı.  
- **Değerlendirme Kriterleri:**  
  - Kodun doğruluğu ve okunabilirliği  
  - Görselleştirmelerin kalitesi (eksen etiketleri, başlıklar)  
  - Yorumların içgörü sağlayıcılığı (“Bu bize ne anlatıyor?”)  
  - Eksik/aykırı veri yönetimi  
