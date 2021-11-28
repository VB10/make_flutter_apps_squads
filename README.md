# Ozel Tesekkurler Haluk (dokumanin tamamen onun tarafindan hazirlandi)🌟

# Flutter ile Proje Geliştirme: PM, UI, Backend, Flutter

1.  [PM-Project Manager](#pm-project_manager)
2.  [Tasarım-UI](#tasar%C4%B1m-ui)
3.  [Back-End](#back-end)
4.  [Flutter-Coding](#flutter)

> ## 💡Önemli 💡
>
> Local proje yapmak çok verimli değil, mümkün olduğunca local proje yapmamaya çalış.
> Temiz başlangıç için coding(flutter) kısmına özen göster.

* * *

## PM-Project_Manager

- Projeye başlarken bir PM'in neler bilmesi gerektiğini öğren.
- Elimde neler var? Bunları bil.
    - Theme "**dark and light**" kolaylığı.
    - UI KIT kolaylığı.
- Neler yapılmış? Araştır.
    - https://itsallwidgets.com sitesinden neler yapılmış, hangi uygulamalar ne şekilde oluşturulmuş, widget'lar nasıl yapılmış gör.
    - UI tasarımlarını iyi düşünerek projeye başla.

* * *

## Tasarım-UI

- Uygulamanın '**component**' setinin önceden hazırlanması çok önemli. Hazırda dursun.
- Tasarım işinin önceden bitirilmesi faydalı olur.
- *Zeplin* öğren ;
    - Flutter plugin'inini Zepline ekle!
        - **Styleguide**:
            **a.** Color palette
            **b**. Text Style Catalog
            **c.** Spacing and Layout
            **d.** Component
- Tasarımcı olarak çalışmalarını Iphone_8'e göre hazırla. Çentiksiz ekranlar tasarım açısından daha uyumlu.
- Ekran ve Widget'lar için en-boy oranlarının nasıl ayarlanması gerektiğini [HardwareAndro](https://www.youtube.com/channel/UCdUaAKTLJrPZFStzEJnpQAg) kanalından öğren.
- Elle en-boy-boşluk vs değerleri verme. Bunun için en kötü yüzdesel mantık kullan ya da MediaQuery ya da [pub.dev](https://pub.dev/)'den [flutter_screenutil](https://pub.dev/packages/flutter_screenutil) paketini kullan.
- Figma'da flowlar kullan. Hangi ekran-buton nereye gidecek belli olsun.

* * *

## Back-End

- Database işlerini nasıl yapacağız önce buna karar ver?

### Database için iki farklı bakış açısı var:

1️⃣ `FireBase Kullan`

- Sunucu maliyeti düşük 📉

- Security derdi yok ✅

- No-Sql yapısı var 🚩

- Search embeded olarak gelmiyor. (Elasticsearch ile search işlerini yapabilirsin.) ⚠️


2️⃣ `Kendi Backend'ini Yaz`
(*Node.js - Go - **Django** \- Spring - .Net vb* kullan...)

- Sunucu maliyeti ilk zamanlar yüksek 💲

- Daha uzun zaman alabilir ⏳

- Güvenlik işleri zor 🚨

- Devops tutmak gerekebilir ❌

- Sunucu - Publishing - Security işlerine biraz hakim olmak gerekli ❌

- Her şey senin elinde, daha özgür hareket edebilirsin. ✅

- Seraching embeded değil, doğrudan query yap kullan ✅

- Firebase'e göre daha zor ama daha işlevsel ✅

- Büyük projeler için ve kendini geliştirmek için daha faydalı✅

- Zaman içinde maliyet avantakı oluşuyor 📉


* * *

## Flutter

- [HardwareAndro](https://www.youtube.com/channel/UCdUaAKTLJrPZFStzEJnpQAg) kanalındaki videoları izle ve [vb10.dev](https://vb10.dev) sitesinden "**Ana Kısım**" bölümünü iyice oku.
- [pub.dev](https://pub.dev/) sitesindeki önmeli paketleri kullan.
    - Localization için: [easy_localization](https://pub.dev/packages/easy_localization) kullan.
    - State Managment için: [mobx](https://pub.dev/packages/mobx) kullan
    - Kendini geliştir ve bunların üzerine [bloc](https://pub.dev/packages/bloc) ekle/öğren.
    - Animasyonlar için: [animations](https://pub.dev/packages/animations) kullan
    - Ekran boyutlandırma için: [flutter_screenutil](https://pub.dev/packages/flutter_screenutil) kullan
    - Routing içi: Veli Hoca'yı bekle, paket yazıyor. 🔥🐍
- Projeyi temiz tut;
    - [vb10.dev](https://vb10.dev)'den projeyi temiz tutmakla alakalı yazıları oku:
        - Tema kullanımı, 🎨
        - Saklama(cache), 💾
        - Çoklu dil(multi language) 🇹🇷🇺🇸
        - [Hive](https://pub.dev/packages/hive) kullan ✅
- Unit testleri yaz. (⁉️ ne olduğunu bilmiyorum )
- Service testleri yaz. (⁉️ ne olduğunu bilmiyorum )
- Tema yönetimi yap. (Custom tema yaz) 🎨
- Widget'ları modüler ve atomic yap. Widget catalog oluştur. 🧩
- Bir sayfada max. 200 satır kod olsun. Fazlaysa parçala, widget'ları dışarı çıkar. 🔪
- Dart Lang Tutorial'ı mutlaka oku. 📑
- '**Flutter Apperantive**' kitabını oku. 📘
- [dart.dev](https://dart.dev/guides/language/effective-dart/usage)'den ***Effective Dart*** bölümünü oku.  📄

[![Flutter ile Proje Gelistirme](https://img.youtube.com/vi/o_peRYib6vE/0.jpg)](hhttps://youtu.be/o_peRYib6vE "Flutter ile Proje Gelistirme")
