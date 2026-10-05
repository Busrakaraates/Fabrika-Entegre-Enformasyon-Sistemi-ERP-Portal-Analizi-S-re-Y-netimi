Fabrika ERP Portal – Süreç Yönetimi ve İş Analizi

Bu proje, Inspimo Bilişim Teknolojileri bünyesindeki stajım süresince yürüttüğüm iş analizi ve süreç yönetimi çalışmalarını içeriyor.

Sanayi tarafında işlerin çoğu zaman kâğıt üzerinde, WhatsApp gruplarında veya dağınık Excel tablolarında yürüdüğünü; bunun da malzeme kaybına, takip edilemeyen firelere ve iletişim kopukluklarına yol açtığını gördük. Bu projede amacım, fabrikanın gerçek sahadaki işleyişini bozmadan tüm operasyonu tek bir dijital çatı altında toplayacak süreci modellemekti.

📌 Problem ve Yaklaşımım

Bir fabrikada herkes aynı masada oturmuyor, herkesin iş yapış şekli ve teknolojiye bakışı farklı. Bu yüzden projeyi "herkes için tek tip bir ekran" mantığıyla değil, sahadaki rollerin gerçek ihtiyaçlarına göre kurguladım:

Mavi Yaka (Depo / Mal Kabul): Sahada hareket halinde, bazen iş eldiveniyle işlem yapıyor. Bu ekranda uzun formlar veya karmaşık filtreler olamazdı. Arayüzü yalnızca barkod/QR okutma ve tek tıkla malzeme giriş-çıkışı yapabilecekleri devasa butonlarla kurguladım (3 Tık Kuralı & Hick Kanunu).

Gri Yaka (Üretim & Vardiya Şefi): Günün telaşında veri girmekle vakit kaybetmek istemiyor. Depodan ham madde talebini ve vardiya sonundaki sağlam/fire miktarını minimum adımla sisteme girmesini sağlayan onay odaklı form akışları modelledim.

Beyaz Yaka (Satın Alma & Muhasebe): Detay görmek, listelemek, filtrelemek ve dışa aktarmak zorunda. Bu kitle için detaylı veri tabloları, Excel/PDF export araçları ve e-Fatura entegrasyon ekranlarını planladım.

Fabrika Müdürü (Executive): Sisteme kesinlikle veri girmemeli. Karar vericinin ihtiyacı olan tek şey; fire oranları, anlık ciro ve üretim kapasitesini tek ekranda özetleyen KPI kartları ve grafiklerdi.

🔄 Kurduğum Süreç Zinciri

Sistemin arkasındaki veri akışını şu 6 adımlık operasyonel zincir üzerinden yapılandırdım:

Satın Alma: Kritik stok seviyesine inen hammadde için tedarikçi siparişinin açılması.

Depo (Mal Kabul): Sahaya gelen malzemenin QR/Barkod ile sisteme işlenmesi.

Üretim: İhtiyaç duyulan malzemenin hatta çekilmesi, gün sonu sağlam ürün ve fire verilerinin girilmesi.

Depo / Sevkiyat: Üretimi biten nihai ürünün çıkış kaydı.

Finans: Sevkiyat teyidiyle birlikte faturanın kesilmesi ve siparişin kapatılması.

Yönetim İzleme: Tüm bu adımlardan gelen verinin anlık olarak müdür paneline KPI olarak yansıması.

⏱️ Proje Yaşam Döngüsü ve Zaman Planı (8 Hafta)

Bir portal projesinin ilk müşteri temasından canlıya geçişine kadar olan süreci adım adım çıkardım ve 8 haftalık bir takvime oturttum:

1 - 2. Hafta: Sahadaki aksaklıkların tespiti, mevcut durum mülakatları ve bütçe/fizibilite planlaması.

3. Hafta: Gereksinim analizi ve İş Gereksinim Dokümanı'nın (BRD) yazılması.

4 - 5. Hafta: UI/UX wireframe ve prototip süreçleri.

5 - 6. Hafta: Ekip içi geliştirme planlaması ve veritabanı şemalarının netleştirilmesi.

7. Hafta: Test senaryoları (QA) ve güvenlik kontrolleri.

8. Hafta: Kullanıcı eğitimleri ve sistemin sahada devreye alınması.

🎯 Bu Stajdan Ne Öğrendim?

İyi bir yazılımın sadece iyi kod yazmaktan ibaret olmadığını; sahanın derdini anlamayan bir sistemin çalışanlar tarafından terk edildiğini gördüm.

Kullanıcı deneyiminin (UX) ofis çalışanından fabrika işçisine kadar nasıl değiştiğini birebir sahada deneyimledim.

Bir projenin analizinden bütçelendirmesine, rol yetkilendirmelerinden (RBAC) devreye alma planına kadar tüm süreç yönetim adımlarını uçtan uca tecrübe ettim.
