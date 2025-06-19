# 🎓 2025 Türkiye Üniversiteleri SQL Veritabanı

Bu depo, **YÖK Atlas** verilerinden elde edilen güncel Türkiye'deki üniversitelerin tamamını içeren, kullanıma hazır bir SQL dosyası içermektedir.

## 📦 İçerik

SQL dosyası şunları içerir:

- Tablonun adı: `universities`
- Alanlar:
  - `id`: Benzersiz üniversite kimliği (INT)
  - `logo`: Üniversitenin logosunun URL’si (VARCHAR)
  - `address`: Üniversitenin adres bilgisi (TEXT)
  - `name`: Üniversite adı (VARCHAR)
  - `type`: Üniversitenin türü (Devlet / Vakıf) (VARCHAR)
  - `location`: Şehir bilgisi (VARCHAR)
  - `website`: Üniversitenin resmi web sitesi (VARCHAR)
  - `status`: Üniversitenin sistemdeki durumu (`aktif` / `pasif`) – ENUM

Veri karakter seti: **utf8mb4**  
Hazır SQL komutları ile birlikte gelmektedir: `CREATE TABLE` + `INSERT INTO`.

## 📁 Dosya

- `universities.sql`: SQL veritabanı dosyası
- Toplam üniversite sayısı: **200+**

## 🧩 Kullanım

Bu SQL dosyasını kendi projelerinizde doğrudan kullanabilirsiniz. Örnek:

```sql
SOURCE universities.sql;
