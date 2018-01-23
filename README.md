[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  [![Python](https://img.shields.io/badge/Python-2.7-blue.svg)](https://img.shields.io/badge/Python-2.7-blue.svg) [![Platform](https://img.shields.io/badge/Platform-Linux-orange.svg)](https://img.shields.io/badge/Platform-Linux-orange.svg)  [![Progress](https://img.shields.io/badge/Progress-%2536-brightgreen.svg)](https://img.shields.io/badge/Progress-%2536-brightgreen.svg)


# Makine Öğrenmesi Türkçe Kaynak


Makine Öğrenmesi alanında Türkçe kaynak oluşturmak amacıyla oluşturduğum bir repo'dur.

İçerisinde uygulamalı makine öğrenmesi programları ve anlatımlar yer almaktadır. Yazılara blog'umdan erişebilirsiniz.
*    https://veribilimcisi.com/

## İçerik

1. Bölüm:  Makine Öğrenmesine Giriş [![Progress](https://img.shields.io/badge/Progress-%25100-brightgreen.svg)](https://img.shields.io/badge/Progress-%25100-brightgreen.svg)
2. Bölüm:  Baştan Sona Makine Öğrenmesinin Temelleri [![Progress](https://img.shields.io/badge/Progress-%25100-brightgreen.svg)](https://img.shields.io/badge/Progress-%25100-brightgreen.svg)
3. Bölüm:  Regresyon [![Progress](https://img.shields.io/badge/Progress-%2550-yellow.svg)](https://img.shields.io/badge/Progress-%2550-yellow.svg)
4. Bölüm:  Sınıflandırma [![Progress](https://img.shields.io/badge/Progress-%250-red.svg)](https://img.shields.io/badge/Progress-%250-red.svg)
5. Bölüm:  Kümeleme [![Progress](https://img.shields.io/badge/Progress-%250-red.svg)](https://img.shields.io/badge/Progress-%250-red.svg)
6. Bölüm:  Boyut Azaltma [![Progress](https://img.shields.io/badge/Progress-%250-red.svg)](https://img.shields.io/badge/Progress-%250-red.svg)
7. Bölüm:  Yapay Sinir Ağları [![Progress](https://img.shields.io/badge/Progress-%250-red.svg)](https://img.shields.io/badge/Progress-%250-red.svg)

[![Next](https://img.shields.io/badge/next-derin%20%C3%B6%C4%9Frenme-ff69b4.svg)](https://img.shields.io/badge/next-derin%20%C3%B6%C4%9Frenme-ff69b4.svg)

## Başlarken

Programların çalıştırılabilmesi için gerekli paketleri makinenize yüklemeniz gerekiyor. 
*   Python 2.7 kullanılmaktadır.

Paketlerin kurulumunu sanal ortam içerisine yapabilirsiniz veya [anaconda](https://anaconda.org/) kullanabilirsiniz.

### Gereksinimler

Programların çalıştırılabilmesi için gerekli olan paketlere setup altından erişebilirsiniz.

### Kurulum

Linux makine için kurulum:

* [setup.py](https://github.com/SerayBeser/machine-learning/blob/master/setup/setup.py) çalıştırın.

veya

```sh
$ sudo pip install -r requirements.txt
```

## İçindekiler

###	1.	Bölüm  : Makine Öğrenmesine Giriş
[1.Bölüm  : Makine Öğrenmesine Giriş](https://github.com/SerayBeser/makine-ogrenmesi/tree/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F)

1.1	[Ne Yapmak İstiyoruz?](https://github.com/SerayBeser/machine-learning/blob/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F/1.1%20Ne%20Yapmak%20%C4%B0stiyoruz%3F.pdf)

1.2	[Makine Öğrenmesi Nedir?](https://github.com/SerayBeser/machine-learning/blob/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F/1.2%20Makine%20%C3%96%C4%9Frenmesi%20Nedir%3F.pdf)
        
- 1.2.1	Arthur Samuel: Makine Öğrenmesinin Öncüsü

1.3	[Neden Makine Öğrenmesi Kullanıyoruz?](https://github.com/SerayBeser/machine-learning/blob/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F/1.3%20Neden%20Makine%20%C3%96%C4%9Frenmesi%20Kullan%C4%B1yoruz%3F.pdf)

1.4	[Makine Öğrenmesi Sistemleri](https://github.com/SerayBeser/machine-learning/blob/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F/1.4%20Makine%20%C3%96%C4%9Frenmesi%20Sistemleri.pdf)
- 1.4.1	Denetimli - Denetimsiz Öğrenme
- 1.4.2	Toplu - Çevrimiçi Öğrenme
- 1.4.3	Örnek-Tabanlı - Model-Tabanlı Öğrenme 

1.5	[Makine Öğrenmesinde Karşılaşılan Zorluklar](https://github.com/SerayBeser/machine-learning/blob/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F/1.5%20Makine%20%C3%96%C4%9Frenmesinde%20Kar%C5%9F%C4%B1la%C5%9F%C4%B1lan%20Zorluklar.pdf)
- 1.5.1	Yetersiz Eğitim Verisi Miktarı
- 1.5.2	Temsili Olmayan Eğitim Verileri
- 1.5.3	Düşük Kaliteli Veriler
- 1.5.4	Alakasız Özellikler
- 1.5.5	Eğitim Verilerinin Aşırı Uyumu - Yetersiz Uyumu
    		
1.6	[Test Etme ve Tahminlerin Doğruluğunu Ölçme](https://github.com/SerayBeser/machine-learning/blob/master/B%C3%B6l%C3%BCm%201%20%20:%20Makine%20%C3%96%C4%9Frenmesine%20Giri%C5%9F/1.6%20Test%20Etme%20ve%20Tahminlerin%20Do%C4%9Frulu%C4%9Funu%20%C3%96l%C3%A7me.pdf)
- 1.6.1	Doğruluk, Hassasiyet, Hata
- 1.6.2	Çapraz Doğrulama
- 1.6.3	Karışıklık Matrisi ve Performans Ölçütleri
- 1.6.4	Metrikler


###	2.	Bölüm   : Baştan Sona Makine Öğrenmesinin Temelleri

[2.	Bölüm   : Baştan Sona Makine Öğrenmesinin Temelleri](https://github.com/SerayBeser/makine-ogrenmesi/tree/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri)

2.1	[Veriyi Bulmak](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.1.%20Veriyi%20Bulmak.pdf)

2.2	[Büyük Resmi Görmek](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.2%20B%C3%BCy%C3%BCk%20Resmi%20G%C3%B6rmek.pdf)
- 2.2.1	Sorunun Hatlarını Çizmek
- 2.2.2	Performans Ölçütünü Seçmek
    		
2.3	[Veriyi Almak](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.3%20Veriyi%20Almak.pdf)
- 2.3.1	Çalışma Alanı Oluşturmak
- 2.3.2	Veriyi Yüklemek
- 2.3.3	Veriyi Hızlıca Gözden Geçirmek
- 2.3.4	Veriyi Bölmek

2.4	[Veriyi Anlamak](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.4%20Veriyi%20Anlamak.pdf)
- 2.4.1   Veriyi Görselleştirmek
- 2.4.2   Veriler Arasındaki İlişkiyi İncelemek
    		
2.5	[Veriyi Hazırlamak](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.5%20Veriyi%20Haz%C4%B1rlamak.pdf)
- 2.5.1   Veriyi Temizlemek
- 2.5.2   Metin ve Kategorik Öznitelikleri İşlemek
- 2.5.3   Özellikleri Ölçeklendirmek
        	
2.6	[Modeli Seçmek ve Eğitmek](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.6%20Modeli%20Se%C3%A7mek%20ve%20E%C4%9Fitmek.pdf)

2.7	[Modeli Test Etmek](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.7%20Modeli%20Test%20Etmek.pdf)

2.8	[Sonuçları Sunmak](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.8%20Sonu%C3%A7lar%C4%B1%20Sunmak.pdf)

2.9	[Sistemin Takibini ve Bakımını Yapmak](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%202%20%20:%20%20Ba%C5%9Ftan%20Sona%20Makine%20%C3%96%C4%9Frenmesinin%20Temelleri/2.9%20Sistemin%20Takibini%20ve%20Bak%C4%B1m%C4%B1n%C4%B1%20Yapmak.pdf)


### 3. Bölüm  : Regresyon

[3. Bölüm  : Regresyon](https://github.com/SerayBeser/makine-ogrenmesi/tree/master/B%C3%B6l%C3%BCm%203%20:%20Regresyon)

3.1 [İlk Minik Makine Öğrenmesi Uygulaması](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%203%20:%20Regresyon/3.1.%20%C4%B0lk%20Minik%20Makine%20%C3%96%C4%9Frenmesi%20Uygulamas%C4%B1.pdf)

3.2 [Basit Lineer Regresyon](https://github.com/SerayBeser/makine-ogrenmesi/blob/master/B%C3%B6l%C3%BCm%203%20:%20Regresyon/3.2%20Basit%20Lineer%20Regresyon.pdf)

- 3.2.1   İlişki Türleri
- 3.2.2   İlişkinin Gücü ve Yönü
- 3.2.3   En Küçük Kareler Yöntemi

3.3 Tek Değişkenli Lineer Regresyon

- 3.3.1   Maliyet Fonksiyonu
- 3.3.2   Dereceli Azalma
- 3.3.3   Öğrenme Oranı
- 3.3.4   Kesme Terimi

3.4 Çok Değişkenli Lineer Regresyon [eksik]

- 3.4.1   Özellik Ölçeklendirme ve Normalleştirme
- 3.4.2   Dereceli Azalma Çeşitleri

        - 3.4.2.1   Batch Gradient
        - 3.4.2.2   Stochastic Gradient
        - 3.4.2.3   Mini - Batch Gradient
        
- 3.4.3   Dereceli Azalma Optimizasyon Algoritmaları  

        - 3.4.3.1   Momentum, ….
        
- 3.4.4   Normal Denklemler

3.5 Polinomsal Regresyon 


## Yazar

* **Seray Beşer** -Makine Öğrenmesi Türkçe Kaynak- [machine-learning](https://github.com/SerayBeser/machine-learning)
* **Kaynak** : -Blog'um- https://veribilimcisi.com/

## Lisans


This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/SerayBeser/machine-learning/blob/master/LICENSE.md) file for details





