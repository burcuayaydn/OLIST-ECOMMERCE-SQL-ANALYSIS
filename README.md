# 🛒 Olist E-Commerce SQL Analysis

Bu projede, Brezilya merkezli Olist e-ticaret veri seti kullanılarak uçtan uca veri analizi gerçekleştirilmiştir.  
Amaç; müşteri davranışlarını, sipariş trendlerini, satıcı performansını ve ödeme alışkanlıklarını incelemektir.

---

## 📊 Proje Kapsamı

### 1. Sipariş Analizi

- Aylık sipariş dağılımı
- Sipariş durumlarına göre kırılım
- Kategori bazlı satış analizi
- Özel günlerde (Sevgililer Günü vb.) öne çıkan kategoriler
- Haftanın günlerine ve ayın günlerine göre sipariş davranışı

### 2. Müşteri Analizi

- En çok alışveriş yapan şehirler
- Müşteri lokasyon bazlı davranış analizi

### 3. Satıcı Analizi

- En hızlı teslimat yapan satıcılar (Top 5)
- Satıcı performansı (yorum, puan, sipariş sayısı)
- Satıcıların ürün çeşitliliği ve satış ilişkisi

### 4. Ödeme Analizi

- Ödeme tiplerine göre sipariş dağılımı
- Taksitli vs tek çekim ödeme analizi
- Ödeme alışkanlıklarının kategori bazlı incelenmesi

---

## 🛠 Kullanılan Teknolojiler

- SQL (PostgreSQL)
- Veri Manipülasyonu (JOIN, CTE, Window Functions)
- Veri Analizi

---

## 🔍 Öne Çıkan İçgörüler

- Hafta içi sipariş sayısı hafta sonuna göre daha yüksektir
- Belirli kategoriler (örneğin: bed_bath_table, furniture_decor) kampanya dönemlerinde öne çıkmaktadır
- Taksitli ödeme bazı kategorilerde daha yaygındır
- Satıcı performansı sadece hızla değil, müşteri yorumlarıyla birlikte değerlendirilmelidir

---

## 📁 Dosyalar

- `olist_analysis.sql` → Tüm SQL sorgularını içerir

---

## 🚀 Amaç

Bu proje, SQL kullanarak gerçek bir veri seti üzerinde analiz yapma, veri içgörüsü çıkarma ve iş problemlerine çözüm üretme yetkinliğini göstermeyi amaçlamaktadır.
