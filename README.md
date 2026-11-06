# Nöbet Puantaj Asistanı · Sürümler

Bu depo yalnızca **Nöbet Puantaj Asistanı** uygulamasının derlenmiş sürümlerini dağıtmak için kullanılır. Kaynak kod bu depoda yer almaz.

## İndirme

**[En son sürümü indirin →](https://github.com/timurmert/nobet-puantaj-surumler/releases/latest)**

1. Sürüm sayfasındaki `NobetPuantaj.exe` dosyasını indirin.
2. İstediğiniz bir klasöre (masaüstü, USB bellek) koyun ve çift tıklayın. Kurulum gerekmez.
3. "Windows bilgisayarınızı korudu" uyarısı çıkarsa **Ek bilgi → Yine de çalıştır**'a basın. Uygulama dijital olarak imzalı olmadığı için bu uyarı görünür.

Uygulama yeni sürümleri kendisi bildirir; **Şimdi Güncelle** düğmesiyle tek tıkla güncellenir. Ayarlarınız korunur.

## Dosyalar

| Dosya | Açıklama |
|---|---|
| `NobetPuantaj.exe` | Uygulama |
| `NobetPuantaj.exe.sha256` | Elle doğrulama için SHA-256 özeti |
| `tatil-verisi.json` | Güncel resmi tatil verisi (uygulama otomatik indirir) |
| `latest.json` | Uygulamanın güncelleme denetiminde okuduğu sürüm bilgisi |

İndirdiğiniz dosyayı PowerShell ile doğrulamak için:

```powershell
(Get-FileHash .\NobetPuantaj.exe -Algorithm SHA256).Hash.ToLower()
```

Çıkan değer, `NobetPuantaj.exe.sha256` dosyasındaki değerle aynı olmalıdır.

## Lisans

Tescilli yazılımdır; tüm hakları saklıdır. Bu deponun herkese açık olması kullanım, kopyalama veya dağıtım hakkı vermez. Yazılım yalnızca telif hakkı sahibinin yazılı izniyle kullanılabilir.

İzin talepleri için: timurmertusta@gmail.com

Copyright (c) 2026 Timur Mert USTA. All rights reserved.
