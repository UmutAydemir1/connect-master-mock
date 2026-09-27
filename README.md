# Connect Master · Kübra Catering Mock

Kübra Catering için geliştirilen, tamamen mock verilerle çalışan Connect Master operasyon prototipi.

🔗 **Canlı Demo:** [https://umutaydemir1.github.io/connect-master-mock/](https://umutaydemir1.github.io/connect-master-mock/)

## Demo Kapsamı

- Ana yönetici, şube sorumlusu, bölge mühendisi, şoför, satın alma, finans ve evrak sorumlusu rol görünümleri
- Otomatik/manüel fatura yönlendirme, şube kontrolü ve aylık maliyete yansıma
- Malzeme giriş–çıkış–transfer ve eksik/fazla/hatalı teslimat takibi
- Personel harcamaları ile fiş/fatura tutar farkı alarmları
- Satın alma–mal kabul–fatura üçlü karşılaştırması
- Evrak teslim zinciri, cari/vade takibi ve banka hareketi eşleştirme
- Teklif, katalog, video/QR ve web sitesi AI denetim ekranları

Kayıtlar tarayıcı `localStorage` alanında tutulur; canlı Mikro, banka veya veritabanı bağlantısı yoktur.

## Yerel Ortamda Başlatma

Projeyi yerel ortamda çalıştırmak için:

```bash
python3 -m http.server 4173 --directory dist
```

Tarayıcınızda açın:
```
http://127.0.0.1:4173/
```
