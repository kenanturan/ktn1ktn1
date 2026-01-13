# Uzun Mesafe Atış Simülasyonu - Web Versiyonu

Bu klasör (`web sürümü`), simülasyonu web tarayıcılarında çalıştırmak için hazırlanmıştır.

## Nasıl Çalıştırılır?

Simülasyonun sorunsuz çalışması için bir "yerel sunucu" (local server) kullanılması veya dosyaların bir web sunucusuna yüklenmesi gerekir.

### Yöntem 1: VS Code Live Server (Önerilen)
1. Bu klasörü VS Code ile açın.
2. `index.html` dosyasına sağ tıklayıp **"Open with Live Server"** seçeneğini seçin.

### Yöntem 2: Python (Eğer yüklüyse)
1. Terminali açıp bu klasörün içine gelin.
2. `python3 -m http.server 8000` yazıp Enter'a basın.
3. Tarayıcıda `http://localhost:8000` adresine gidin.

## Önemli Not: Menü Kullanımı
Modern tarayıcı güvenlik önlemleri nedeniyle, simülasyonun **içindeki** bazı menü butonları çalışmayabilir.

Bu sorunu çözmek için ekranın **SOL TARAFINA** özel bir **BÖLÜM LİSTESİ** menüsü eklenmiştir.
- Eğer simülasyon içindeki butonlara bastığınızda bir şey olmuyorsa, **Lütfen soldaki menüyü kullanın.**
- Soldaki menüden istediğiniz bölüme (Örn: Range 1, Urban 2) tıkladığınızda bölüm anında açılacaktır.

## Dosya Yapısı
- `index.html`: Ana giriş ekranı.
- `basic.html`: Temel Seviye simülasyon ve menüsü.
- `advanced.html`: İleri Seviye simülasyon ve menüsü.
- `files/`: Simülasyon dosyalarının yedeği (Dosyalar ayrıca ana dizinde de mevcuttur).
- `ruffle/`: Simülasyonu oynatan emülatör dosyaları.
