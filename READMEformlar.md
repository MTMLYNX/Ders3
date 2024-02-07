# Formlar

Bu HTML dosyası, basit bir form oluşturmayı amaçlar. Form, kullanıcının ad, soyad, cinsiyet, ilgi alanları ve bir mesaj bırakmasına olanak tanır.

## Form Elemanları

### Ad ve Soyad

Kullanıcının adını ve soyadını girmesi için metin giriş kutuları kullanılmıştır.

```html
<label for="ad">Adınız:</label>
<input type="text" id="ad" name="ad" required>

<label for="soyad">Soyadınız:</label>
<input type="text" id="soyad" name="soyad" required placeholder="Soyadınız">
Cinsiyet
Kullanıcının cinsiyetini seçmesi için radio düğmeleri kullanılmıştır.

html

<p>Erkek</p><input type="radio" id="erkek" name="cinsiyet" value="erkek">
<p>Kadın</p><input type="radio" id="kadin" name="cinsiyet" value="kadin">
İlgi Alanları
Kullanıcının ilgi alanlarını seçmesi için checkbox kullanılmıştır.

html

<label for="basketbol">Basketbol:</label><input type="checkbox" id="basketbol">
<hr>
<label for="futbol">Futbol:</label><input type="checkbox" id="futbol">
<hr>
Mesaj
Kullanıcının bir mesaj bırakması için metin alanı kullanılmıştır.

html

<textarea name="mesaj" id="mesaj" cols="15" rows="5"></textarea>
Konular
Kullanıcının ilgilendiği konuyu seçmesi için bir dropdown (select) menü kullanılmıştır.

html

<select name="konular" id="konular">
    <option value="Web">Web Geliştirme</option>
    <option value="Tasarim">Grafik Tasarım</option>
</select>
Gönder Butonları
Formun gönderilmesini sağlamak için submit ve button düğmeleri kullanılmıştır.

html

<input type="submit" value="ONAYLA">
<input type="button" value="Onayla">
Bu örnek form, temel HTML form elemanlarını kullanarak bir kullanıcıdan bilgi almayı amaçlar. Form elemanları, kullanıcının girmesi gereken bilgi türünü açıklayan etiketler içerir.

css


Bu README.md dosyasını, projenizin ana dizinine ekleyebilir ve GitHub'da proje açıklamanız olarak kullanabilirsiniz.
