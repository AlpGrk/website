## 1. Projenin amacı

Kullanıcının basit şekilde yapılacak işler listesi oluşturabildiği, düzenleyebildiği ve tamamlandı olarak işaretleyebildiği bir web sitesi yapılacak.

## 2. Temel özellikler

İlk versiyonda sadece şu özellikler olsun:

* Yeni görev ekleme
* Görevi listeleme
* Görevi tamamlandı / tamamlanmadı olarak işaretleme
* Görevi silme
* Görevi düzenleme
* Tamamlanan ve tamamlanmayan görevleri ayırma
* Basit ve mobil uyumlu tasarım

## 3. İlk versiyon kapsamı

Yazılımcıya şu şekilde net verebilirsin:

### MVP kapsamı

* Tek sayfalık bir TODO uygulaması
* Kullanıcı bir input alanına görev yazıp ekleyebilmeli
* Eklenen görevler liste halinde görünmeli
* Her görevde şu aksiyonlar olmalı:

  * Tamamlandı olarak işaretle
  * Düzenle
  * Sil
* Sayfa yenilense bile görevler kaybolmamalı

### Veri saklama

İlk aşamada backend gerekmeden şu yöntem yeterli:

* Görevler tarayıcıda Local Storage içinde saklansın

Bu sayede daha hızlı ve daha ucuz geliştirme olur.

## 4. Ekran yapısı

### Ana sayfa

Sayfada şu alanlar olsun:

* Üstte başlık: “My Todo List”
* Altında görev ekleme alanı

  * Text input
  * “Ekle” butonu
* Altında filtre alanı

  * Tümü
  * Aktif
  * Tamamlandı
* Altında görev listesi

### Her görev kartında

* Görev adı
* Durum checkbox’ı
* Düzenle butonu
* Sil butonu

## 5. Kullanıcı akışları

### Görev ekleme

* Kullanıcı input’a görev adını yazar
* Ekle butonuna basar
* Görev listeye eklenir
* Input temizlenir

### Görev tamamlama

* Kullanıcı checkbox’a tıklar
* Görev tamamlandı olarak işaretlenir
* Görsel olarak üstü çizili veya farklı renkte görünür

### Görev düzenleme

* Kullanıcı düzenle butonuna tıklar
* Görev adı düzenlenebilir hale gelir
* Kaydet ile güncellenir

### Görev silme

* Kullanıcı sil butonuna tıklar
* Görev listeden kaldırılır

### Filtreleme

* Tümü: tüm görevler görünür
* Aktif: sadece tamamlanmamış görevler
* Tamamlandı: sadece tamamlanan görevler

## 6. Teknik beklenti

Yazılımcıya şu beklentiyi iletebilirsin:

### Önerilen teknoloji

Basit bir proje olduğu için:

* Frontend: HTML, CSS, JavaScript
  veya
* React ile tek sayfa uygulama

### Tavsiyem

Eğer geliştirici modern frontend biliyorsa:

* React kullanılsın

Eğer en hızlı ve en ucuz çözüm isteniyorsa:

* Sade HTML/CSS/JavaScript ile yapılsın

## 7. Veri modeli

Görev objesi şu şekilde olabilir:

* id
* title
* completed
* createdAt

Örnek:

* id: unique değer
* title: görev adı
* completed: true/false
* createdAt: oluşturulma tarihi

## 8. Tasarım beklentisi

* Temiz ve sade görünüm
* Beyaz arka plan
* Yumuşak gri tonlar
* Tamamlanan görevler soluk/çizili görünsün
* Mobil uyumlu olsun
* Gereksiz animasyon olmasın

## 9. Kabul kriterleri

İş bitti denebilmesi için:

* Görev eklenebiliyor olmalı
* Görev düzenlenebiliyor olmalı
* Görev silinebiliyor olmalı
* Görev tamamlandı olarak işaretlenebiliyor olmalı
* Filtreleme çalışıyor olmalı
* Sayfa yenilendiğinde görevler kaybolmamalı
* Mobilde düzgün görünmeli

## 10. İkinci faz için opsiyonel geliştirmeler

İlk versiyona dahil değil ama sonra eklenebilir:

* Kullanıcı girişi
* Görevlere tarih ekleme
* Öncelik seviyesi
* Kategori ekleme
* Dark mode
* Sürükle bırak sıralama
* Backend ve veritabanı entegrasyonu
* Çoklu kullanıcı desteği

İstersen bunu bir sonraki mesajda sana daha profesyonel bir “yazılımcı iş dokümanı” formatında da hazırlayayım.
