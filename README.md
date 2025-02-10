# Instagram Clone with Bootstrap

Bu proje, Bootstrap kullanılarak bir Instagram klonunun oluşturulmasını içerir. Aşağıdaki gereksinimler karşılanarak sayfa tasarımı tamamlanmıştır.

## Özellikler

- **Navbar** 
  - Yukarı sabitlenmiş (fixed-top) ve sayfa aşağı kaydırıldığında yukarıda kalır.
  - İçerik ile birleşmemesi için `body`'ye padding verilmiştir.
  - Yüksekliği 54px olup arka plan rengi beyazdır.
  - Logonun içinde `margin-left: 192px;` uygulanmıştır.
  - Arama çubuğu `d-flex` ile ortalanmış, soldan `ms-5` margin verilmiştir.
  - Arama çubuğunun `::placeholder` stiline `assets` klasöründeki arama simgesi arka plan olarak eklenmiş ve tekrar etmemesi sağlanmıştır.
  - Sağ üstteki menüye `ms-5 mt-2` margin verilmiştir.
  - Menü, `sm` boyutunda kaybolacak şekilde `display: none;` ile düzenlenmiştir.

- **İçerik Alanı**
  - Offset değeri 4 olup, üstten `mt-2` margin verilmiştir.
  - `middlearea` için maksimum yükseklik `200px !important;` ile belirlenmiştir.
  - `col` değeri varsayılan olarak `12`, diğer tüm ölçeklerde `6` olacak şekilde ayarlanmıştır.

- **Hikayeler Alanı**
  - Resimler ve altlarındaki isimler hizalanmıştır (`d-flex flex-column align-items-center`).

- **Gönderiler**
  - Üç nokta simgesi sağa hizalanmıştır (`float-end`).
  - Beğenme, yorum yapma, paylaşma butonlarında `border` kaldırılmıştır.
  - Bookmark ikonu `offset-7` olacak şekilde hizalanmıştır.
  - Card header ve footer’ların arka plan rengi beyaz yapılmıştır.
  - Yorum paylaşma metni sağa alınmıştır (`text-end`).

- **Sağ Panel**
  - Sağ panelin genişliği artırılmıştır.
  - `stickysidebar` class'ı ile panelin sayfa kaydırıldıkça sabit kalması sağlanmıştır (`position: sticky; top: 0;`).
  - `rightpanel` için arka plan rengi beyaz yapılmış, kenarlık kaldırılmıştır.
  - "Tümünü Gör" ve "Takip Et" butonları sağa hizalanmıştır.

- **Genel Stil**
  - Sayfanın arka plan rengi Instagram'dan alınarak uygulanmıştır.


- **Önemli Notlar**
- Bootstrap ızgara sistemini kullanarak responsive tasarım oluşturulmuştur.
- `!important` kullanımı yalnızca zorunlu yerlerde uygulanmıştır.
- CSS'in `position` özelliği ile sağ panel sabitlenmiştir.

🎨🚀
