**☕ Starbucks Menu Analysis: Nutrition & Data Storytelling**

  Bu proje, Starbucks menüsündeki 77 farklı yiyecek ürününün besin değerlerini (kalori, yağ, karbonhidrat, protein, lif) inceleyerek; ürün kategorilerini tahmin eden bir Makine Öğrenmesi modeli ve stratejik Veri Görselleştirme çalışmalarını kapsamaktadır.

**📌 Proje Özeti**

  Analiz, menüdeki ürünlerin "Besin DNA'sını" (Nutritional Fingerprint) ortaya çıkarmayı hedefler. Veri seti üzerinde yapılan incelemeler, markanın ürün kategorizasyonunun tesadüfi olmadığını, belirli besin profili standartlarına dayandığını kanıtlamaktadır.

**🚀 Öne Çıkan Bulgular**

  *Kategori Dağılımı:* Portföyün %53'ü (41 ürün) unlu mamullerden (Bakery) oluşmaktadır.

  *Korelasyon Analizi:* Kalori artışının birincil sorumlusu karbonhidrat değil, 0.76 korelasyon katsayısı ile yağ oranıdır.

  *Tahminleme Başarısı:* Karar Ağacı (Decision Tree) algoritması kullanılarak geliştirilen model, ürünlerin besin değerlerine bakarak kategorilerini %69 doğrulukla tahmin edebilmektedir.

  *Stratejik Fırsat:* Lif oranı ile kalori arasında çok düşük bir ilişki (0.26) saptanmıştır; bu durum, kalori yükünü artırmadan sağlıklı/lifli ürün geliştirme potansiyeline işaret eder.

**🛠️ Kullanılan Teknolojiler**

  *Dil:* Python

  *Veri Manipülasyonu:* Pandas, NumPy

  *Görselleştirme:* Matplotlib, Seaborn

  *Makine Öğrenmesi:* Scikit-learn (Decision Tree Classifier)

**📊 Model Algoritması**

  Algoritma, ürünleri sınıflandırırken şu temel mantığı izler:

  1. **Protein < 12.5g** kontrolü yapar.

  2. Ardından **Kalori < 200** eşiğini değerlendirir.

  3. Bu metrikler sonucunda ürünü "Bakery" veya diğer kategorilere atar.

**💡 İş Stratejisi Önerileri**

  *Pazarlama:* Düşük kalori/Yüksek lif profiline sahip Parfe ve Salatalar sağlık bilinci yüksek kitleye odaklanmalıdır.

  *Ar-Ge:* Unlu mamullerdeki yağ oranı revize edilerek menü geneli ortalama kalori yükü (338.8 kcal) düşürülebilir.

  *Büyüme:* Bistro Box ve Sıcak Kahvaltı çeşitlendirilerek "öğün destinasyonu" konumu güçlendirilmelidir.
