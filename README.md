# Kişisel Web Sayfası ve Docker Projesi

## Proje Açıklaması
Bu proje, Bulut Bilişim dersi ödevi kapsamında geliştirilmiş; Docker container mantığını, temel web teknolojilerini ve GitHub sürüm kontrol sistemini uygulamalı olarak anlamayı amaçlayan basit bir kişisel web sayfasıdır.

## Öğrenci Bilgileri
* **Adı Soyadı:** Yusuf Eren Kaya
* **Bölüm / Program:** Bilgisayar Programcılığı

## Kullanılan Teknolojiler
* HTML5 & CSS3
* Docker & Nginx
* GitHub & GitHub Pages

---

## Docker Çalıştırma Komutları

Proje dizininde terminali açarak aşağıdaki komutları sırasıyla çalıştırabilirsiniz:

### 1. Docker Image Oluşturma:

    docker build -t webproje .

### 2. Docker Container Çalıştırma:

    docker run -d -p 8080:80 webproje

### 3. Tarayıcı Erişimi:

    http://localhost:8080
