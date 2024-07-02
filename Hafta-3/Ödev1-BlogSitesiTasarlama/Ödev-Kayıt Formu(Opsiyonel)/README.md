# Kayıt Formu

Bu proje, kullanıcıların ad, email, yaş, cinsiyet seçimi, sosyal medya hesapları, üyelik onayı ve ek yorumlar gibi bilgileri girebilecekleri bir web formunu içermektedir.

## Özellikler

1. **Sayfa Başlığı ve Açıklama**: Form, bir `h1` başlık elementi içinde "Kayıt Formu" başlığıyla başlamakta ve bir `p` elementi içinde "Öğrenci Kayıt Formu" açıklamasıyla devam etmektedir.

2. **Form Elementi**: Form, bir `form` elementi içinde `survey-form` id'siyle tanımlanmıştır.

3. **İsim Giriş Alanı**: Kullanıcıların adlarını girebilecekleri bir `input` elementi bulunmaktadır. Bu elementin `id` özelliği `name` ve `type` özelliği `text` olarak tanımlanmıştır.

4. **E-posta Giriş Alanı**: Kullanıcıların e-posta adreslerini girebilecekleri bir `input` elementi bulunmaktadır. Bu elementin `id` özelliği `email` ve `type` özelliği `email` olarak tanımlanmıştır. Geçersiz e-posta adresleri için HTML5 doğrulama hatası görülmektedir.

5. **Sayı Giriş Alanı**: Kullanıcıların yaşlarını girebilecekleri bir `input` elementi bulunmaktadır. Bu elementin `id` özelliği `number`, `type` özelliği `number` olarak tanımlanmıştır. Bu alan sadece rakamları kabul etmekte ve belirtilen min-max aralığında olması gerekmektedir. Geçersiz girişlerde HTML5 doğrulama hatası görülmektedir.

6. **Etiketler ve Placeholder Metinleri**: İsim, e-posta ve sayı giriş alanları için uygun etiketler bulunmaktadır (`name-label`, `email-label`, `number-label`). İlgili input alanları placeholder textleri ile açıklama veya talimat içermektedir.

7. **Seçim Kutusu**: Kullanıcıların cinsiyet seçimlerini yapabilecekleri bir `select` dropdown elementi bulunmaktadır. Bu elementin `id` özelliği `gender` ve en az iki seçenek içermektedir.

8. **Radyo Düğmeleri**: Kullanıcıların üyelik onaylarını seçebilecekleri en az iki radyo düğmesi bulunmaktadır.

9. **Onay Kutuları**: Kullanıcıların hangi sosyal medya hesaplarını kullandıklarını seçebilecekleri en az iki onay kutusu bulunmaktadır.

10. **Metin Alanı**: Kullanıcıların ek yorumlarını girebilecekleri bir `textarea` elementi bulunmaktadır.

11. **Gönder Butonu**: Tüm bilgileri göndermek için bir `input` elementi bulunmaktadır. Bu elementin `id` özelliği `submit` olarak tanımlanmıştır.

## Kullanım

Form, tarayıcıda doğru şekilde çalışabilmesi için HTML5 doğrulama özelliklerini kullanmaktadır. Kullanıcılar formu doldurduktan sonra "Gönder" butonuna tıklayarak bilgileri gönderebilirler.
