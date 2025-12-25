
🏦 Banka Otomasyonu – C# & PostgreSQL

Bu proje, C# Console Application kullanılarak geliştirilmiş ve PostgreSQL veritabanı ile çalışan basit bir banka otomasyon sistemidir.

🔧 Kullanılan Teknolojiler

C# (.NET Console App)

ADO.NET mimarisi

PostgreSQL

Npgsql (.NET Data Provider for PostgreSQL)

SQL (CRUD + parametreli sorgular)

NpgsqlConnection, NpgsqlCommand, NpgsqlDataReader

ExecuteScalar / ExecuteNonQuery / ExecuteReader kullanımı

Temel hata yönetimi (try–catch)

🎯 Amaç

Veritabanı işlemlerini ADO.NET mantığıyla gerçek bir senaryo üzerinde pratik etmek.leyicisi
- PostgreSQL veritabanı

### Kurulum

1. GitHub reposunun ana sayfasında sağ üst köşede bulunan "Code" butonuna tıklayarak projeyi bilgisayarınıza indirin veya klonlayın.

    ```bash
    git clone https://github.com/kullaniciadi/banka-otomasyon-projesi.git
    ```

2. `BankaOtomasyonProjesi.sln` dosyasını Visual Studio veya tercih ettiğiniz C# geliştirme ortamında açın.

3. PostgreSQL veritabanınızı oluşturun ve bağlantı ayarlarınızı `appsettings.json` dosyasında güncelleyin.

    ```json
    {
      "ConnectionStrings": {
        "DefaultConnection": "Host=localhost;Port=5432;Database=dburun;Username=postgres;Password=sifre"
      }
    }
    ```

4. Proje dosyalarınızı derleyin ve çalıştırın.

## Kullanım

Proje başlatıldığında, basit bir kullanıcı arayüzü ile karşılaşacaksınız. Müşteri hesaplarını ekleyebilir, para transferi yapabilir, bakiye sorgulayabilirsiniz.

## Katkıda Bulunma

Eğer projeye katkıda bulunmak istiyorsanız, lütfen bir çekme isteği oluşturun. Yeni özellikler ekleyebilir veya hataları düzeltebilirsiniz.


