# Web Teknolojileri ve Programlama Ödevi

Bu proje, Dockerize edilmiş basit ve modern bir kişisel web sayfasıdır. Proje kapsamında HTML, CSS ve Docker teknolojileri kullanılmıştır.

## Proje İçeriği
* **index.html**: Kişisel bilgilerin, iletişim kanallarının ve sosyal medya hesaplarının yer aldığı ana sayfa.
* **style.css**: Sayfanın modern ve duyarlı (responsive) tasarımını sağlayan stil dosyası.
* **Dockerfile**: Projenin Nginx sunucusu üzerinde Dockerize edilmesini sağlayan yapılandırma dosyası.

---

## Kurulum ve Çalıştırma Adımları

Projeyi yerel bilgisayarınızda Docker container üzerinde çalıştırmak için aşağıdaki komutları sırasıyla terminal veya PowerShell üzerinden uygulayabilirsiniz:

### 1. Docker Image Oluşturma
Proje dizininin içerisindeyken projenin Docker imajını derlemek için şu komutu çalıştırın:
```bash
docker build -t webproje .
