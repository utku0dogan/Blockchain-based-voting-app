# Votin App

Blockchain based voting application. User information and votes are kept in blocks.

## Used Technologies

- MVC design pattern was used in the project.
- Bootstrap, JavaScript and ejs are used in front end design.
- REST and SOAP web services are used.
- MySQL database is used.

## Installation

install with npm

```bash
npm init
npm start
```

## Projenin amacı 

Günümüzde bir konunun araştırılması, toplumun görüşünün alınması ya da tutumunun tespit edilebilmesi için araştırma anketleri, yüz yüze danışma, telefon görüşmeleri, web anketleri gibi çeşitli yöntemler kullanılmaktadır. Bu yöntemlerden en hızlı ve düşük maliyetli olan yöntem web anketleridir. Web anketi tercih edildiğinde sunucu tabanlı çalışan web uygulamaları kullanılmaktadır. İstemci düğümlerinden sunucuya gönderilen oylama bilgileri, merkezi bir sunucu üzerindeki veri tabanına kaydedilmektedir. Bu çalışmada farklı fikir ya da görüşlerin oylanması, oylama sonuçların gösterilmesi için blok zincir temelli güvenli bir elektronik oylama modeli önerilmiştir. Çalışmada javascript dilinde blok zincir yapısı oluşturularak düğümlerden kullanılan oy verilerinin bir blok olarak şifrelenmesi ve bloğun zincire eklenmesi sağlanmıştır. Blok zincir tabanlı geliştirilen sistemin güvenli ve güvenilir olmasını, seçimde bulunan insanların güvenini artırmaya yardımcı olmasını bekliyoruz.


## Projenin kullanımı 

![image](https://user-images.githubusercontent.com/59983461/168316737-528951bb-ea3e-4a7c-b5e4-baee1f56c683.png)

-Login ekranı ile sisteme giriş yapılır. Kullanıcı giriş yapmadan oy kullan butonuna tıklasa bile sistem buna izin vermez. Sisteme kayıtlı değilse kayıt ol butonu ile kayıt olabilir. 


**-Register Ekranı**
![image](https://user-images.githubusercontent.com/59983461/168317019-6c4cc9ff-c081-4903-867f-c786e3fbd9b5.png)

Kullanıcı gerekli bilgilerini vererek oy kullanmak için kaydolur. Blockchain yapısı ile her kaydolan kullanıcıya özel bir anahtar oluşturulur.




**-Ana Sayfa Ekranı**

![image](https://user-images.githubusercontent.com/59983461/168317173-dd73cec9-acce-46c7-9176-3242cc649c3a.png)

Giriş yapan kullanıcıyı sistem ana sayfaya gönderir. Ana sayfa ekranında istediği ankete girip oy verebilir. 

**-Survey Ekranı**

![image](https://user-images.githubusercontent.com/59983461/168317305-fa0e4746-58da-4e80-a249-6652f2224f2c.png)

Uygulamada bulunan mevcut anketler bu ekranda bulunur. Kullanıcı buradan istediği bir anketi seçebilir ve oyunu verebilir.


**-Polling Ekranı**
![image](https://user-images.githubusercontent.com/59983461/168317416-de88ca05-5687-4cf0-a127-2a9e99eba29f.png)

Kullanıcı oy vermek istediği ankete girdikten sonra sistem oy vereceği ekranı açar. Buradaki seçeneklerden istediği seçimi hür iradesiyle oy verebilir. Sistem kullanıcının daha önce oy kullanıp kullanmadığını kontrol eder. Kullanmadıysa seçimi sisteme kaydeder ve anket güncellenmiş olur. Bu da uygulamamızın güvenli bir seçim yapmasını sağlar.

**-Oy Sonuç Ekranı**

![image](https://user-images.githubusercontent.com/59983461/168317584-176f83d5-f8ea-4a11-9f4b-90b5deb18901.png)

**-Hakkında Ekranı**

![image](https://user-images.githubusercontent.com/59983461/168317675-657cfee2-76c6-4b57-9834-ea989c516653.png)
Hakkında ekranı ile uygulamamızı tanıtmaktayız. Uygulamamızın sahip olduğu özellikler, avantajlar ve bu uygulamayla neyi amaçladığımızı açıklıyoruz!


## ALTI KATMANLI MİMARİ TASARIMI!

![image](https://user-images.githubusercontent.com/59983461/168317844-91763764-a930-40d0-9430-8e94b235dbad.png)
![image](https://user-images.githubusercontent.com/59983461/168317863-7cf0aef2-349b-4c22-9d3d-35ba42efa90c.png)

## VERİ TABANI DİAGRAMI 

![image](https://user-images.githubusercontent.com/59983461/168317947-9fc0a383-9fea-4834-94e7-2e13a95def9e.png)



blockchain hackathon'u için yapılmış bir projedir. 

## Ekip

**Ferhat Eroğlu
Utku Doğan**
