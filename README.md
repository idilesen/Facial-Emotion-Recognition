# Facial-Emotion-Recognition | VGG19 - FER2013

Bu repo, Global AI Hub bootcamplerinde template olarak kullanmanız amacıyla hazırlanmıştır.
Benim çalışmamda FER2013 veri seti kullanılarak VGG19 tabanlı derin öğrenme modeli ile yüz ifadelerinden duyguların sınıflandırılması yapılmıştır.

Repo görünürlüğü Public olarak ayarlanmalıdır.

📌 Giriş

Bu projede, yüz ifadelerinden duyguların otomatik olarak sınıflandırılması hedeflenmiştir.

Kullanılan veri seti: FER2013

Kullanılan model: VGG19 (transfer learning)

Amaç: Görsellerden 7 temel duygunun sınıflandırılması (Mutlu, Üzgün, Öfkeli, Korkmuş, Şaşırmış, Nötr, İğrenmiş).

Notebook içerisinde, markdown hücrelerinde projenin teknik detayları açıklanmıştır.

📊 Metrikler

Modelin eğitimi sonucunda elde edilen metrikler:

Epoch 15 Sonuçları

F1 Score (Train): 0.5125

F1 Score (Validation): 0.5194

Sonuçlara göre, modelin doğruluk oranı temel seviyede olup, farklı duygular arasında ayrım yapabilme performansı kısıtlıdır. Daha ileri geliştirmelerle performans artırılabilir.

➕ Ekler

Projeye şu aşamalarda geliştirmeler eklenebilir:

Data Augmentation yöntemleri ile veri çeşitliliğinin artırılması

Farklı mimariler (ResNet, EfficientNet) ile karşılaştırma yapılması

Deployment: Streamlit veya benzeri bir araçla arayüz oluşturularak görsellerin yüklenip tahmin yapılabilmesi

🚀 Sonuç ve Gelecek Çalışmalar

Bu çalışma, FER2013 veri seti üzerinde VGG19 kullanılarak yapılan temel bir yüz ifadesi tanıma uygulamasıdır.
Gelecekte:

Daha geniş veri setleri ile modelin genelleme yeteneği artırılabilir.

Gerçek zamanlı kamera entegrasyonu eklenebilir.

Mobil cihazlarda çalışabilecek daha hafif modeller tasarlanabilir.

Bu repo, bootcamp sonrasında da geliştirilmeye devam edilebilecek bir temel sunmaktadır.

🔗 Linkler

Çalışmaya ait Kaggle linkleri:
