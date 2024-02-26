Bu proje, asp.net core ve signalr teknolojilerini kullanarak bir restoran yönetim sistemi geliştirmeyi amaçlamaktadır. Bu sistem sayesinde, restoran çalışanları ve müşteriler arasında gerçek zamanlı iletişim sağlanabilir, siparişler kolayca alınabilir ve takip edilebilir, menü ve fiyatlar güncellenebilir, stok ve gelir raporları oluşturulabilir.
Kullanıcılar, restorandan online olarak sipariş verebilir veya restorana rezervasyon oluşturabilirler. Online sipariş vermek için kullanıcıların giriş yapması gerekmektedir. Daha sonra, menüdeki istedikleri yiyeceği veya içeceği sepetlerine ekleyebilirler.

Siparişler ve rezervasyonlar, admin panelinde SignalR teknolojisi kullanılarak sayfa yenilemeden canlı olarak görüntülenir. Adminler, bu canlı görüntü üzerinden siparişleri ve rezervasyonları inceleyerek onaylama veya iptal etme yetkisine sahiptir. Herhangi bir durum değişikliği, ilgili kullanıcının gerçek e-posta adresine otomatik olarak gönderilir.Bu sayede, kullanıcılar ve adminler işlemleri anlık olarak takip edebilirler ve herhangi bir değişiklik olduğunda hızlı bir şekilde bilgilendirilirler.

Özellikler
-Restoran çalışanları için bir web paneli
-Müşteriler için bir mobil uygulama
-Signalr ile gerçek zamanlı bildirim ve mesajlaşma
-SQL Server ile veritabanı yönetimi
-Entity Framework Core ile ORM
-Razor Pages ile MVC mimarisi
-Bootstrap ile responsive tasarım
-Identity ile kullanıcı yetkilendirme ve kimlik doğrulama

Katmanlar
-UI Layer
-Entity Layer
-DataAccess Layer
-Business Layer
-Dto Layer
-Web Api Layer
