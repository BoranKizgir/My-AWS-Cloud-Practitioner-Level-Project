
# AWS S3 Statik Web Sitesi Barındırma

Bu proje, AWS bulut altyapısını kullanarak bir web sitesinin nasıl barındırılacağını göstermektedir.

##  Kullanılan Teknolojiler
- **Amazon S3:** Web sitesi dosyalarını (HTML) depolamak ve sunmak için kullanıldı.
- **S3 Static Website Hosting:** S3 bucket'ı bir web sunucusu gibi yapılandırıldı.
- **Bucket Policy:** Dış dünyanın web sitesine erişebilmesi için gerekli JSON izinleri tanımlandı.

##  Uygulanan Adımlar
1. Bir S3 Bucket oluşturuldu ve "Public Access" izinleri düzenlendi.
2. `index.html` dosyası bucket'a yüklendi.
3. "Static Website Hosting" özelliği aktif edilerek bir uç nokta (endpoint) oluşturuldu.
4. Bucket Policy eklenerek nesnelere (objects) okuma izni verildi.

##  Ekran Görüntüsü
![Web Sitemin S3 Üzerindeki Hali](WebSite Screenshot.png)
