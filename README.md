Hava Durumu Tahmin Uygulaması
Bu uygulama, kullanıcıların dünya genelindeki şehirlerin anlık hava durumu verilerini kolayca sorgulamasını sağlayan basit ama güçlü bir Python konsol programıdır. Açık kaynaklı bir hava durumu API'si aracılığıyla gerçek zamanlı verileri çeker ve kullanıcı dostu bir arayüzde sunar.

Ana Özellikler
Gerçek Zamanlı Veri: OpenWeatherMap API'si ile anlık sıcaklık, nem ve rüzgar bilgileri.

Küresel Kapsam: Dünya genelindeki herhangi bir şehrin hava durumunu sorgulama yeteneği.

Kullanıcı Dostu Konsol Arayüzü: Basit ve anlaşılır komut satırı arayüzü ile hızlı erişim.

Döngüsel Sorgulama: Kullanıcı "q" tuşuna basana kadar sürekli sorgu yapabilme imkanı.

Kullanılan Teknolojiler
Dil: Python 3.x

Harici Kütüphaneler: requests (API çağrıları için)

Hava Durumu API'si: OpenWeatherMap API

Kurulum
Bu projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

Depoyu Klonlayın:

Bash

git clone https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git
Proje Dizinine Gidin:

Bash

cd REPO_ADINIZ
Gerekli Kütüphaneleri Kurun:

Bash

pip install requests
API Anahtarınızı Ayarlayın:

API_ANAHTARI değişkenini kendi API anahtarınızla güncelleyin.

Python

API_ANAHTARI = "SİZİN_API_ANAHTARINIZ"
Uygulamayı Çalıştırın:

Bash

python hava_durumu.py
