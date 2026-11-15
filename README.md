# Anki — GitHub Pages

1332 Hollandaca kelimelik, Türkçe/İngilizce anlamlı, mobil uyumlu, tamamen statik kelime öğrenme uygulaması.

## Yayınlama

1. GitHub üzerinde **Public** bir repository oluşturun.
2. `index.html` dosyasını repository kök dizinine yükleyin (Add file → Upload files → Commit changes).
3. Repository → **Settings → Pages** → **Build and deployment → Deploy from a branch** seçin.
4. **Branch: main**, **Folder: /(root)** seçin ve **Save** deyin.
5. Birkaç dakika sonra `https://KULLANICI_ADI.github.io/REPO_ADI/` adresini açın.

## Yerelde çalıştırma

`index.html` dosyasını tarayıcıda açabilirsiniz. Sunucu, Python ve kurulum gerekmez.

## Öğrenme ve veri saklama

- SM-2 temelli planlama: öğrenme adımları 1 ve 10 dakika, sonrasında gün bazlı aralıklar. Anki'nin güncel FSRS algoritmasının birebir kopyası değildir.
- Cevaplar: Tekrar, Zor, İyi, Kolay.
- Tarayıcının localStorage alanına kayıt. Aynı tarayıcı/profil kullanılmalı. Gizli modda kalıcılık garanti edilmez.
- Ayarlar bölümünden JSON yedeği indirin ve başka cihazda içe aktarın. Otomatik senkronizasyon yoktur.
- Aynı gün çalışılmış yeni kartlar sonraki günlere devredilir; öğrenme kartları zamanı gelince tekrar görünür.
- GitHub Pages herkese açık bir web sayfasıdır; CSV kelimeleri de herkese açıktır.

## Dosyalar

- `index.html`: uygulamanın tamamı, kelimeler dahil.
- `README.md`: bu açıklama.
