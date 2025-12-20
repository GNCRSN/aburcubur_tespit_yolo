🍫 YOLO11 ile Gerçek Zamanlı Abur Cubur Tespiti
Bu proje, YOLO11n mimarisi kullanılarak geliştirilmiş, gerçek zamanlı bir nesne tespiti (object detection) uygulamasıdır. Proje, kamera görüntüsü üzerinden çeşitli abur cubur ve atıştırmalık ürünlerini yüksek doğrulukla tespit etmek ve sınıflandırmak amacıyla yapılmıştır.

🚀 Proje Hakkında
Bu çalışmanın temel amacı, hazır veri setleri yerine tamamen özgün ve gerçek hayat senaryolarına uygun bir veri seti ile bir yapay zeka modeli eğitmektir. Model, düşük donanımlarda bile hızlı çalışabilmesi için YOLO11n versiyonu tercih edilerek optimize edilmiştir.

Öne Çıkan Özellikler
Özgün Veri Seti: İnternetten hazır alınan görseller değil, bizzat çekilen fotoğraflar kullanılmıştır.

Manuel Etiketleme: Veri setindeki tüm nesneler (atıştırmalıklar) tarafımdan manuel olarak etiketlenmiştir (Labeling).

En Güncel Teknoloji: Ultralytics'in en yeni modellerinden YOLO11n kullanılmıştır.

Gerçek Zamanlı Tespit: OpenCV entegrasyonu ile webcam üzerinden anlık tespit yapar.

🛠️ Kullanılan Teknolojiler
Python: Ana programlama dili.

Ultralytics YOLO11n: Nesne tespiti modeli

OpenCV: Görüntü işleme ve kamera akışı için.

LabelStudio: Etiketleme işlemi için kullanıldı.

Veri Seti ve Eğitim Süreci
Modelin başarısı büyük oranda veri setinin kalitesine dayanmaktadır:

Veri Toplama: Farklı açılardan ve ışık koşullarında abur cubur paketlerinin fotoğrafları çekildi.

Etiketleme (Labeling): Çekilen fotoğraflardaki nesneler tek tek işaretlenerek sınıflara ayrıldı.

Eğitim (Training): Hazırlanan veri seti YOLO11n modeline beslendi ve model eğitildi (best.pt ağırlıkları elde edildi).

PREVIEW:

<img width="480" height="640" alt="readme" src="https://github.com/user-attachments/assets/9d370d5a-f87f-42dc-9268-016d87c22ca4" />

