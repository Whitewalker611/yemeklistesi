[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7364968&assignment_repo_type=AssignmentRepo)
# BİL 3106: HW1
Bu ödevde, HTML ve CSS'yi kullanacaksınız. 

Benzerini yapmanız için ekran görüntüleri, web sayfasının açıklaması ve resimler size verilecektir. Bu web sayfasını, verilen ekran görüntülerinde gösterildiği gibi yeniden oluşturmanız beklenmektedir.

# Yemek Listesi: *food-list.html*

[Listicle](https://en.wikipedia.org/wiki/Listicle), tematik yapısı olarak bir
liste kullanan, oldukça popüler bir makale türüdür.

Sivas’ta “yenilmesi önerilen 4 yiyecek/içeçek” ile ilgili bir
**listicle** web sayfası oluşturacaksınız. Web sayfasını `food-list-style.css`'de
tanımlanan stiller ile `food-list.html` olarak oluşturmalısınız.

## 1. Genel Görünüm

Tüm sayfanın (1903 piksel ekran genişliğine sahip) tam boyutlu ekran görüntüsü
Teams’deki `HW1` ve Github'daki `images` klasöründe verilmiştir:

![Tam sayfa ekran görüntüsü](https://github.com/Bil3106/hw1/blob/main/full-page.png)

-   Makalenin metni, HW1 başlangıç ​​kodunuzda bulunan `food-list-content.txt`
    dosyasında bulunmaktadır.

-   `food-list-content.txt` metnini kopyalayıp `food-list.html` dosyanıza
    yapıştırın, ardından sayfaya stil vermek için gerekli HTML etiketlerini
    ekleyin.

-   Resimler, HW1 başlangıç ​​kodunun `images/` dizinindedir.

## 2. Bölüm (Section) Ölçümleri

![Bölümlerin piksel ölçümleri](https://github.com/Bil3106/hw1/blob/main/section-measurement-with-px.jpg)

Piksel ölçümlerinin yazılmadığı hali için [tıklayınız](https://github.com/Bil3106/hw1/blob/main/section-measurement.png).

## 3. Font tipi, büyüklüğü ve rengi

**Sayfa başlığı**:

-   Yazı karakteri: `Roboto Slab` ve yedek yazı karakteri `serif`.

-   Yazı karakteri büyüklüğü: `36px`.

-   Yazı karakteri weight `normal` (kalın değil)

-   Başlık dikey ve başlık resmine ortalanacak şekildedir.

**Yazar Profil Yazısı**

-   Yazı karakteri `Source Sans Pro` ve yedek yazı karakteri `sans-serif`.

-   Yazı karakteri büyüklüğü: `18px`.

-   Yazar ismi (“Saliha Yeşilyurt”) için `font weight: bold`

-   Son güncelleme yazısının stili `italic`

-   Yazı karakteri rengi `rgb(51, 51, 51)`

-   Satır yüksekliği (line height) `24px`

-   "Son güncelleme" satırının altındaki gri çizgi, metnin altından `10px`, `2px`
    genişliğinde ve rengi `#e6e6e6`

**İçerik (Body) Yazısı**

-   **Başlık**

    -   Yazı karakteri: `Roboto Slab` ve yedek yazı karakteri `serif`.

    -   Yazı karakteri büyüklüğü: `36px`.

    -   Yazı karakteri weight `bold`

    -   Numara rengi `rgba(0, 0, 0, 0.25)`

    -   Başlık rengi: `rgb(51, 51, 51)`

-   **Adres**

    -   Başlığın altındaki adres bir linktir ve `Bağlantılar (Links)` bölümünde
        bahsedilecektir.

-   **Paragraflar**

    -   Yazı karakteri `Source Sans Pro` ve yedek yazı karakteri `sans-serif`

    -   Yazı karakteri büyüklüğü: `18px`.

    -   Satır yüksekliği (line height) `32px`

    -   Yazı karakteri rengi `rgb(51, 51, 51)`

-   **Öneri Bölümü**

    -   “Öneri” ifadesi kalındır (`bold`)

## 4. Bağlantılar (Links)

Bağlantıların sayfanızda nasıl çalışması gerektiğine dair açıklamalar:

-   Sayfadaki her adres (Google maps) bir bağlantıdır. Her bağlantının URL'si
    `food-list-content.txt` dosyasında listelenmiştir.

-   Bağlantı rengi: `#42b4d6`

-   Bağlantı kalın değildir ve fareyle bağlantının üzerine gelmedikçe
    bağlantının altı çizili değildir.

-   Bağlantının üzerine geldiğinizde bağlantının altı çizilir.

-   İpucu:

    -   Bir alt çizgiyi kaldırmak için kullanılan CSS özelliği: `text-decoration:
        none;`

    -   Alt çizgi eklemek için kullanılan CSS özelliği: `text-decoration:
        underline;`

## Resimler (Images)

-   **Başlık resmi**

    -   Başlık bir arka plan resmidir (`images/header.jpg`)

        -   **Not**: Resme css/ klasöründen referans vermek için yolun şu
            şekilde olması gerekir : `../images/header.jpg`

    -   Arka plan tekrar etmez.

    -   Arka planın boyutu kapsayacak (`cover`) şekilde ayarlandı.

    -   Arka planın konumu üste(`top`) sabitlenmiştir.

    -   Yüksekliği `500px`’dir.

    -   Başlık resminin üzerinde `rgba(0, 0, 0, .3)` olan yarı saydam bir renk
        katmanı vardır.

        -   **Not**: Aşağıdaki CSS kuralını kullanarak bunu yapabilirsiniz:

        -   `background-image: linear-gradient(rgba(0, 0, 0, .3), rgba(0, 0, 0,
            .3)), url(../images/header.jpg)`;

-   **Profil resmi**

    -   Profil resmi `images/profile.jpg`'dir.

        -   **Not**: Görüntüye css/ klasöründen referans vermek için yolun
            `../images/profile.jpg` olması gerekir.

    -   Genişliği `100px`’dir.

    -   Yarıçapı `%100` olan yuvarlatılmış köşelere sahiptir.

    -   `1px` kalınlığında `beyaz` bir kenarlığı vardır.

# Gereksinimler

-   **Derste öğrendiğimiz HTML ve CSS'yi kullanın**. Bu ödevi derste
    öğrendiğimiz HTML ve CSS'yi kullanarak yapabilirsiniz. Derste anlatılmayan
    HTML/CSS kullanmanız yasak değilse de, yanlış kullanırsanız ya da stil
    açısından zayıf seçimler yaparsanız notunuz kırılabilir.

-   **Javascript kullanmayın**. Bu ödevde JavaScript kullanmaya gerek yoktur.

-   **Liste düzenini oluşturmak için sıralı bir liste öğesi (`ol`) kullanmaya
    gerek yok**. HTML'de `ol` yerine "1.", "2." vb. sayıları yazmanızı öneririz.

-   **Verilen görünüme mümkün olduğunca benzetmeye çalışın**. Web sayfanızdaki
    birkaç piksel farklılık sorun değil, ancak gözle görülür farklılıklar ödev puanınızın
    düşmesine neden olur.

-   **Açıklayıcı adlar kullanın** ve mümkün mertebe `temiz kod` olarak yazmaya
    çalışın.

-   

# Ödevin Gönderilme Şekli

-   **Bitiş Tarihi**: 21 Mart 2022 Pazartesi N.Ö’ler için saat 11:00, İ.Ö’ler
    için saat 16:00’dır.

-   Ödevler, ders arasında ve sonrasında `sınıfta` kontrol edilecektir.

-   Kontrol edilen ödevlerin `Github’a` gönderilmesi istenecektir.
-   HW0’da anlatılan yöntemle ödevi alıp tekrar aynı linke (kendi reponuza) değişikliklerinizi atacaksınız (push). 
-   İkinci yöntem olarak: HW0’da anlatılan şekilde sadece değişen dosyalarınızı **Edit this file** (kalem ikonu) diyerek düzenleyebilir ve daha sonra **Commit changes** yapabilirsiniz.

