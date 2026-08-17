# Mali Müşavir Programı — Kurulum ve Güncellemeler

Bu depo yalnızca müşterilere dağıtılacak **imzalı kurulum ve otomatik güncelleme paketlerini** içerir. Kaynak kodu, müşteri verileri ve özel imzalama anahtarı burada tutulmaz.

## Güncel sürüm: M300

- [Müşteri kurulumunu indir](https://github.com/dsradonda/MaliMusavirProgrami-Guncellemeler/releases/download/M300/MaliMusavirProgrami_Musteri_Setup.exe)
- [M300 güncelleme paketini indir](https://github.com/dsradonda/MaliMusavirProgrami-Guncellemeler/releases/download/M300/MaliMusavirProgrami_Update_M300.zip)
- [M300 sürüm notları](https://github.com/dsradonda/MaliMusavirProgrami-Guncellemeler/releases/tag/M300)

Program açıldığında `latest.json` dosyasını kontrol eder. Yeni sürüm varsa müşteriye bildirim gösterir; paket Ed25519 imzası ve SHA-256 özeti doğrulandıktan sonra kurulur.

> Yönetici kurulumu özel imzalama anahtarı içerdiği için bu açık depoda yayımlanmaz.
