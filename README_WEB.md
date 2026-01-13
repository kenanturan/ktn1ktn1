# Uzun Mesafe Atış Simülasyonu - Web Versiyonu

Bu proje, orijinal Flash (.swf) dosyalarını modern web tarayıcılarında çalıştırmak için [Ruffle](https://ruffle.rs/) emülatörünü kullanır.

## Nasıl Çalıştırılır?

Güvenlik nedeniyle, modern tarayıcılar yerel dosya sisteminden (file:// protokolü) doğrudan Flash dosyalarını yüklemeye izin vermeyebilir. Bu nedenle, simülasyonu çalıştırmak için basit bir yerel web sunucusu kullanmanız önerilir.

### Seçenek 1: Python ile (Eğer Python yüklüyse)
1. Terminali açın.
2. Bu klasörün bulunduğu dizine gidin:
   ```bash
   cd "/Users/kenanturan/Desktop/Uzun Mesafe At   Simülasyonu(rev)/Uzun Mesafe Atış Simülasyonu(rev)"
   ```
3. Aşağıdaki komutu çalıştırın:
   ```bash
   python3 -m http.server 8000
   ```
4. Tarayıcınızda `http://localhost:8000` adresine gidin.

### Seçenek 2: VS Code "Live Server" Eklentisi
Eğer Visual Studio Code kullanıyorsanız:
1. Bu klasörü VS Code ile açın.
2. "Live Server" eklentisini yükleyin.
3. `index.html` dosyasına sağ tıklayıp "Open with Live Server" diyerek çalıştırın.

## Notlar
- `files/` klasörü içindeki tüm `.swf` dosyaları simülasyonun parçasıdır. `main.swf` ana giriş noktasıdır.
- Ruffle, Flash Player'ın tüm özelliklerini %100 desteklemeyebilir, ancak çoğu içerik sorunsuz çalışır.
