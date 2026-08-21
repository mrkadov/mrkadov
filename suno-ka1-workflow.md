# Suno’yu Profesyonel Kullanmak: 15 Prompt Hilesi ve KA-1 Workflow

Bu rehberin amacı tek promptla şansını denemek değil; Suno’yu aşamalı bir prodüksiyon sistemi gibi kullanmak. Suno’da en büyük farkı genellikle promptun uzunluğu değil, **bilgiyi doğru aşamalara bölmek** yaratır.

> **Ana prensip:** Önce fikir ve kimlik → sonra düzenleme → sonra ses tasarımı → en son mix/master.

**KA-1**, bu prensibin uygulama adıdır:

- **K** — Kimlik
- **A** — Aranjman
- **1** — Birinci kilit (nakarat) ve ondan sonraki cerrahi iterasyon

---

## 15 Prompt Hilesi

### 1. “Etiket yığını” yerine müzikal hikâye yaz

Zayıf prompt:

```
dark rap, emotional, violin, piano, 90 bpm, sad
```

Daha güçlü yaklaşım:

```
Cinematic emotional hip-hop at 90 BPM. Begin with lonely piano and distant atmospheric violin. Gradually introduce deep warm bass and restrained boom bap drums. Keep the verses intimate and spacious, then expand into a powerful memorable chorus with wider drums and emotional strings. Dark, nocturnal, melancholic, cinematic, professional arrangement.
```

Suno’nun detaylı ve daha doğal stil açıklamalarını anlayabilen model yapısından yararlanmış olursun.

**Prompt formülün:**

Genre + BPM + başlangıç + enerji gelişimi + enstrümanlar + vokal + mix karakteri

---

### 2. Aynı promptta 20 enstrüman isteme

Suno’ya:

```
piano, violin, clarinet, oud, guitar, synth, flute, trumpet...
```

yazarsan istediğin şeylerin çoğunu görmezden gelebilir.

Bunun yerine:

**Ana enstrüman + destek enstrümanı + atmosfer** mantığını kullan.

Örnek:

```
Melancholic piano as the main melodic element, expressive solo violin as emotional support, subtle distant clarinet textures in the background.
```

**Kural:** Bir şarkının müzikal kimliğini 2–4 temel unsurla kur.

---

### 3. “Negative prompt” yerine pozitif yönlendirme kullan

Suno’da çoğu zaman:

```
no trap, no pop, no happy music, no EDM
```

yazmak yerine şunu yap:

```
Strictly organic 90s-inspired boom bap drum programming with dusty samples, restrained swing, no modern hyperactive hi-hat patterns.
```

Yani istemediğini söylemek yerine, **istediğin sonucu teknik olarak tarif et**.

---

### 4. Style ve Lyrics alanlarını farklı amaçla kullan

Bu normal kullanıcıların en sık yaptığı hata.

**Style of Music:**

- Genre
- BPM
- Enstrüman
- Aranjman
- Mix karakteri
- Vokal tarzı

**Lyrics:**

- Sözler
- Bölüm yapısı
- Performans yönlendirmeleri
- Ad-lib
- Atmosfer notları

Suno, Lyrics alanındaki ek bağlam ve yönlendirmeleri de kullanabiliyor.

Örnek:

```
[Verse 1]
[Male rap vocal, intimate and close to the microphone]
...

[Pre-Chorus]
[The drums briefly disappear, tension increases]
...

[Chorus]
[More emotional, wider vocal performance]
...
```

---

### 5. Sözlerde “nefes alan boşluklar” oluştur

Özellikle Türkçe rapte her satırı kelimeyle doldurma.

Zayıf:

```
Kafamın içinde bin tane düşünce dolaşıyor
Her gece geçmişim önümde tekrar canlanıyor
```

Daha performatif:

```
Kafamda bin düşünce...
Her biri farklı bir yara

Her gece geçmişim...
Geliyor kapıma
```

Bu yaklaşım Suno’ya **yorumlayacak alan** bırakır.

---

### 6. Nakaratı ilk üretimde değil, ayrı optimize et

Profesyonel workflow:

1. Verse + chorus içeren demo üret.
2. En iyi nakarat melodisini bul.
3. O nakaratı temel kimlik haline getir.
4. Kalan bölümleri sonra düzenle.

Bir şarkının ticari gücünün önemli kısmı nakarattadır. Bu nedenle 10 kötü verse üretmek yerine **en iyi nakaratı 10 farklı varyasyonla aramak** daha verimli olabilir.

---

### 7. “Enerji eğrisi” yaz

Sadece “duygusal şarkı” yazmak yeterli değildir.

Şöyle yönlendir:

```
Energy progression:
0:00–0:15 minimal and atmospheric
Verse: restrained and intimate
Pre-chorus: increasing tension
Chorus: emotional peak
Verse 2: return to controlled energy
Final chorus: biggest and widest section
Outro: gradually strip away instruments
```

v5, uzun yapılar ve bölümler arasındaki müzikal akışı daha iyi yönetmeye yönelik bir kompozisyon sistemi sunuyor.

---

### 8. Promptun en önemli kelimelerini başa koy

Öncelik sıralaman şu olsun:

1. Tür
2. Duygu
3. BPM
4. Ana enstrüman
5. Aranjman
6. Vokal
7. Mix

Örnek:

```
Emotional cinematic boom bap, 90 BPM, melancholic piano...
```

Bunu şu şekilde bitirmekten daha kontrollüdür:

```
...and maybe somewhere there can also be an emotional cinematic boom bap feeling.
```

---

### 9. Weirdness ve Style Influence’ı bilinçli kullan

Custom Mode’daki iki önemli slider:

- **Weirdness:** Güvenli sonuçtan kaotik/deneysel sonuca
- **Style Influence:** Promptuna gevşek veya güçlü bağlılık

Genellikle:

**Ticari şarkı**

- Weirdness: düşük–orta
- Style Influence: yüksek

**Yeni sound arayışı**

- Weirdness: orta–yüksek
- Style Influence: orta

Audio upload kullanıyorsan ayrıca **Audio Influence** da kontrol edilebilir.

**Hile:** İyi bir sonuç alamıyorsan hemen promptu tamamen değiştirme. Önce slider kombinasyonlarını değiştir.

---

### 10. “Reuse Prompt” ile mikro varyasyon üret

En iyi şarkını bulduğunda sıfırdan başlamamalısın.

Reuse Prompt ile:

- Aynı söz
- Aynı yapı
- Aynı temel sound

korunurken yalnızca tek değişkeni değiştir:

- Versiyon A: Daha karanlık
- Versiyon B: Daha melodik
- Versiyon C: Daha güçlü bas
- Versiyon D: Daha sakin vokal
- Versiyon E: Daha sinematik nakarat

Reuse Prompt, aynı başlangıç detaylarını yeniden kullanıp Lyrics, Style ve Title üzerinde değişiklik yapmaya imkân verir.

---

### 11. Beğenmediğin şarkıyı çöpe atma: Replace Section kullan

Örnek:

```
Verse mükemmel
Nakarat kötü
İkinci verse iyi
Outro kötü
```

Şarkıyı baştan üretmek yerine yalnızca sorunlu kısmı değiştir.

Replace Section, orta bölümdeki sözleri veya müzikal kısmı değiştirmek için kullanılabilir ve yeni varyasyonlar oluşturur.

Bu, profesyonel workflow’un en önemli mantığı:

> Generate → Select → Fix → Select → Continue

---

### 12. Bir soundu başka enstrümana dönüştür

Suno Studio’daki **Stem Cover** ile:

- Mırıldandığın melodi → keman
- Parmak ritmi → davul
- Basit vokal melodi → gitar veya synth

dönüşümü yapabilirsin.

Daha önemli ayrıntı:

- **Cover:** İlk/orijinal kaynak sese referans verir.
- **Recreate:** Mevcut seçili versiyondan yeni varyasyon üretir.

Bu ikisini karıştırmamak, iteratif sound design sırasında ciddi avantaj sağlar.

---

### 13. “Mükemmel şarkı” yerine mükemmel parçalar üret

Profesyonel yaklaşım:

- Davul iyi mi? → Davulu ayır.
- Bas iyi mi? → Bası ayır.
- Keman iyi mi? → Kemanı ayır.
- Vokal iyi mi? → Vokali ayır.

Sonra bunları Studio veya FL Studio’da yeniden birleştir.

Advanced Stem Separation; **Auto Split**, **Split from Mix** ve **Advanced Split** gibi modlarla daha ayrıntılı ayırma imkânı sunuyor.

---

### 14. “My Taste” özelliğini prompt laboratuvarı olarak kullan

My Taste sadece öneri sistemi değil; **senin sound DNA’nı biriktiren bir prompt laboratuvarı**.

Avatarına tıkla → **My Taste**. Profil alanı yaklaşık 2000 karaktere kadar düzenlenebilir. Style kutusundaki Magic Wand (değnek), bu profili kullanarak kişiselleştirilmiş stil taslağı üretir.

Pasif öğrenmeyi bekleme. Kimliğini **elle yaz**.

Laboratuvar kullanımı:

1. 2–4 temel unsurla lane’ini yaz.
2. Magic Wand ile taslak al.
3. Şarkıya özel son yüzde otuzu sen düzenle.
4. İşe yarayan cümleleri kütüphanene kaydet.
5. Farklı bir türe çıkıyorsan My Taste’i kapat. Aksi halde değnek seni sürekli kendi lane’ine çeker.

Örnek My Taste profili:

```
Emotional cinematic boom bap, 85–95 BPM. Melancholic piano as the main melodic identity, distant atmospheric violin as emotional support, dusty organic drums with restrained swing. Intimate male rap vocal, close to the microphone in verses, wider and more emotional in choruses. Dark, nocturnal, melancholic, spacious arrangement. Professional mix, warm low end, no hyperactive modern hi-hat patterns.
```

**Kural:** My Taste, promptun yerine geçmez. Sana %70’lik bir başlangıç verir. Kalan %30 hâlâ senin yönetmenliğin.

---

### 15. Kimliği kilitle: Voices, Persona ve Custom Model

Her şarkıda sıfırdan “ben kimim?” diye sorma. Profesyonel katalog, rastgele güzel parçalar yığını değil; **tanınabilir bir kimlik sistemidir**.

Üç katmanı ayrı ayrı kur:

| Katman | Ne kilitler | Ne zaman |
| --- | --- | --- |
| **My Taste** | Stil önerileri ve Magic Wand taslakları | Her gün, ücretsiz dahil |
| **Persona / Style Persona** | Beğendiğin bir şarkının özü ve vokal karakteri | Aynı lane’de yeni parça üretirken |
| **Voices** | Senin sesin / doğrulanmış vokal kimliğin | Vokal tutarlılığı istediğinde |
| **Custom Model** | Katalog sound’un (mix, aranjman, tını) | Pro/Premier; en az 6 kendi parçan |

Hile: Önce 8–12 şarkılık dar bir lane üret. İşe yarayan 1 Persona + 1 Custom Model yeter. Üç ayrı kimliği aynı anda eğitmek, sound’u bulanıklaştırır.

v5.5’in asıl gücü tek özellik değil; **Voices + Custom Model + My Taste’i aynı kimliğe bağlamaktır**.

---

## KA-1 Workflow

Tek oturumda şarkı “ummak” yerine, her oturumu bir aşamaya bağla. Promptu değiştirmeden önce aşamayı bitir.

```
K  Kimlik        fikir, lane, My Taste, Persona/Voice
A  Aranjman      Style hikâyesi + Lyrics mimarisi + enerji eğrisi
1  Birinci kilit nakaratı kilitle, sonra cerrahi iterasyon
```

### Aşama K — Kimlik (üretim yok)

Bu aşamada Generate’e basma.

1. Şarkının tek cümlelik fikrini yaz.
2. Müzikal kimliği 2–4 unsurla kilitle.
3. Vokal karakterini tek cümlede sabitle.
4. My Taste profilinin bu parçayla uyumlu olup olmadığına bak. Değilse kapat veya güncelle.

Kimlik kartı örneği:

```
Fikir: Gece yarısı, kapıya gelen geçmiş.
Lane: cinematic emotional boom bap, 90 BPM.
Ana unsur: melancholic piano.
Destek: distant violin.
Atmosfer: dusty restrained drums, warm bass.
Vokal: intimate male rap, close mic, wider chorus.
```

### Aşama A — Aranjman (hâlâ üretim yok)

Style ve Lyrics’i ayrı yaz.

**Style** = tür + duygu + BPM + ana enstrüman + enerji gelişimi + vokal + mix  
**Lyrics** = bölüm etiketleri + performans notları + nefes alan sözler + ad-lib

Style taslağı:

```
Emotional cinematic boom bap, 90 BPM, melancholic piano, distant atmospheric violin, dusty organic drums, intimate male rap vocal. Begin lonely and spacious, grow into a wide emotional chorus, then return to controlled energy. Dark, nocturnal, melancholic, professional arrangement, warm low end.
```

Lyrics iskeleti:

```
[Intro]
[Sparse piano, distant violin, no drums yet]

[Verse 1]
[Male rap vocal, intimate and close to the microphone]
...

[Pre-Chorus]
[The drums briefly disappear, tension increases]
...

[Chorus]
[More emotional, wider vocal performance, bigger drums and strings]
...

[Verse 2]
[Return to restrained energy, closer vocal]
...

[Final Chorus]
[Biggest and widest section]
...

[Outro]
[Gradually strip away instruments]
```

### Aşama 1 — Birinci kilit

Şimdi üret. Ama hâlâ “mükemmel şarkı” arama. **Nakaratı** ara.

1. Verse + chorus içeren 4–8 demo al.
2. En iyi nakarat melodisini seç. Verse kötü olsa bile nakarat iyiyse o take omurgadır.
3. Weirdness düşük–orta, Style Influence yüksek ile aynı promptu bir kez daha dene. Sonuç kötüyse önce slider’ı, sonra tek değişkeni değiştir.
4. Kazanan nakaratı kimlik haline getir. Bundan sonra her müdahale bu kancayı korumak içindir.

### Cerrahi iterasyon

Nakarat kilitlendikten sonra şarkıyı çöpe atma.

| Sorun | Araç | Kural |
| --- | --- | --- |
| Tek bölüm kötü | Replace Section | Yalnızca o bölümü değiştir |
| Sound doğru, tek katman eksik | Reuse Prompt | Tek değişken: daha karanlık / daha bas / daha sakin vokal |
| Melodi doğru, tını yanlış | Stem Cover | Cover = orijinal kaynak; Recreate = mevcut versiyon |
| Parça iyi, şarkı ortalama | Stem Separation | Davul / bas / keman / vokal ayır, Studio veya FL’de birleştir |
| Katalog dağılmaya başladı | Persona + Voices + Custom Model | Yeni şarkıyı kimlik sistemine bağla |

Profesyonel döngü:

> Generate → Select → Fix → Select → Continue

Mix ve master en son gelir. Önce fikir, sonra düzen, sonra ses, en son parlaklık.

---

## KA-1 Oturum Kontrol Listesi

- [ ] Tek cümlelik fikir yazıldı
- [ ] 2–4 temel unsur kilitlendi
- [ ] Style hikâye gibi yazıldı, etiket yığını değil
- [ ] Lyrics’te bölüm + performans + nefes boşluğu var
- [ ] Enerji eğrisi Style veya Lyrics’te duruyor
- [ ] En önemli kelimeler Style’ın başında
- [ ] İlk hedef nakarat; verse sonraya bırakıldı
- [ ] Kötü sonuçta önce slider, sonra tek değişken
- [ ] Sorunlu bölüm Replace Section ile alındı
- [ ] İyi parçalar stem olarak ayrıldı
- [ ] Beğenilen take Persona / Voice / Custom Model’e bağlandı

---

## Kopyala-yapıştır laboratuvarı

### Ticari şarkı slider’ı

- Weirdness: düşük–orta
- Style Influence: yüksek

### Arama slider’ı

- Weirdness: orta–yüksek
- Style Influence: orta

### Reuse Prompt mikro seti

Aynı söz, aynı yapı. Yalnızca bir satırı değiştir:

```
A: darker, more nocturnal, heavier low end
B: more melodic piano, wider emotional chorus
C: stronger warm bass, tighter boom bap pocket
D: calmer, more intimate vocal, closer to the microphone
E: more cinematic chorus, bigger strings, widest drums
```

---

Tek prompt bir piyangodur. KA-1 bir sistemdir.

Önce kimlik. Sonra aranjman. Sonra nakarat kilidi. Sonra cerrahi. Mix en son.
