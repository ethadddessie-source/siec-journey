# Mobil Listeleri Tek Ekrana Sığdırma

## Yapılacaklar
- Hafızlık ve aidat tablolarındaki yatay kaydırmayı kaldırmak.
- Mobil görünümde sütun genişliklerini sabitleyip tabloyu ekran genişliğine oturtmak.
- Profil fotoğrafı, öğrenci adı, sayılar ve durum alanlarını dar ekranda taşmayacak şekilde küçültmek ve kısaltmak.
- Hoca işlem düğmelerini de aynı satırda, taşma yaratmayacak boyutta tutmak.
- Telefon ve masaüstü görünümünde listelerin düzgün göründüğünü doğrulamak.

## Teknik Ayrıntılar
- Her iki tabloya `table-fixed` ve yüzde/sabit sütun genişlikleri uygulanacak.
- İsim hücrelerinde `min-w-0`, `w-full` ve `truncate`; sabit öğelerde `shrink-0` kullanılacak.
- Mobilde gereksiz dış yatay kaydırma kapsayıcıları kaldırılacak; küçük avatar ve kısa ödeme metinleri kullanılacak.
