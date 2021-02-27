# Müzik-bot
Bir müzik Botu için indirmek için tam bir bot. Bir modül kullanarak (discord-oynatıcı) ↑

Bir müzik Botu için bir kod mu arıyorsunuz ? Bu tamamen açık kaynak kodlu proje sizin projeniz için !

Bu proje ile ilgili yardıma ihtiyacınız varsa, daha hızlı destek almak için yardım sunucusuna sadece [buraya] tıklayarak katılabilirsiniz(https://discord.gg/5cGSYV8ZZj).

### ⚡ Kurulum

Kodu indirerek başlayalım.
`Config` klasörüne ve ardından `bot ' dosyasına gidin.js'.
Botun başlatılabilmesi için lütfen dosyayı aşağıdaki gibi kimlik bilgilerinizle doldurun :

- Emojiler için

"'js
emojiler: {
off:': x:',
hata:': uyarı:',
queue:': bar_chart:',
music:': musical_note:',
success:': white_check_mark:',
}
```

- Yapılandırma için

"'js
anlaşmazlık: {
token:'TOKEN',
prefix:'PREFİX',
etkinlik:'etkinlik',
}
```

- 'token', [Discord Developers] ' da bulunan botun belirteci(https://discordapp.com/developers/applications) bölüm.
- 'prefix', bot kullanmak için ayarlanacak prefix.
- 'etkinlik', botun etkinliği.

Konsolda, tüm bağımlılıkları yüklemek için `npm ınstall` yazın.

- Botu başlatmak için :

```
# Düğüm İle
düğüm dizini.js
npm start # pakette belirtilmiştir.json

# Pm2 ile
pm2 başlangıç Endeksi.js-adı " MusicBot"
```

Tek yapman gereken botunu açmak !

### Commands müzik komutları

```
<name/URL> oynatın, bir ses kanalında müzik çalın.
<name > ' i arayın, bir müzik seçmek için bir panel açın ve ardından oynatın.
Duraklat, mevcut müziği Duraklat.
devam et, mevcut müziği tekrar aç.
sıra, bir sonraki şarkılara bakın.
clear-queue, kuyruktaki müziği kaldırın.
kuyruğu karıştırmak için karıştırın.
nowplaying, devam eden müziği görün.
tekrarlama işlevini etkinleştirmek veya devre dışı bırakmak için döngü.
volume 1 < - > 100, ses seviyesini değiştirmek.
atla, bir sonraki müziğe atla.
dur, tüm müziği Durdur.
filtre <filtre>, filtre Ekle / Kaldır.
W-filtreler, bkz. filtreler.
```

### General genel komutlar

```
ping, bot gecikmesine bakın.
yardım, mevcut komutların listesine bakın.
hata ayıklama, bkz. ses bağlantılarının sayısı.
```

### Utilities yardımcı programları (kodu değiştirmek için)

Resmi kodda bulunan tüm özellikleri bulun [burada] (https://github.com/Androz2091/discord-player).

Bu [ile kullanılır discord.js](https://www.npmjs.com/package/discord.js) ve [discord-player](https://www.npmjs.com/package/discord-player).