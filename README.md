# Virtual ADGV

[English](#english) | [Türkçe](#türkçe)

---

<a name="english"></a>
## English

**Virtual ADGV (Virtual Advanced DataGridView)** is an enhanced fork of the original **[Advanced DataGridView](https://github.com/davidegironi/advanceddatagridview)**. It is a .NET WinForms **DataGridView with advanced Filtering and Sorting** capabilities, now updated with dedicated support for **Virtual Mode** and fixes for modern .NET environments.

### Download

* **[NuGet (VirtualADGV)](https://www.nuget.org/packages/VirtualADGV)**
* **[GitHub Repository](https://github.com/HibrahimBoz/VirtualAdvanceddatagridview)**

### Key Features & Improvements

* **[NEW] Virtual Mode Support (v1.1.0)**: 
    * Specifically optimized to handle large datasets (75M+ rows) efficiently.
    * **Advanced Selection Logic**: Support for Shift-Click, Ctrl-Click, and Range dragging in Virtual Mode.
    * **Selection Promotion**: Automatically promotes native WinForms selection to high-performance Virtual Selection when interacting with large ranges.
* **[FIX] Modern .NET Resource Loading**: Resolved the `MissingManifestResourceException` commonly encountered in .NET 5, 6, 7, and 8 environments.
* **Advanced Filtering & Sorting**: Retains the powerful Excel-like filtering and multi-column sorting from the original ADGV.

---

<a name="türkçe"></a>
## Türkçe

**Virtual ADGV (Virtual Advanced DataGridView)**, orijinal **[Advanced DataGridView](https://github.com/davidegironi/advanceddatagridview)** projesinin geliştirilmiş bir fork'udur. .NET WinForms için **gelişmiş Filtreleme ve Sıralama** yeteneklerine sahip olan bu bileşen, **Virtual Mode (Sanal Mod)** desteği ve modern .NET ortamları için kritik hata düzeltmeleri ile güncellenmiştir.

### İndir

* **[NuGet (VirtualADGV)](https://www.nuget.org/packages/VirtualADGV)**
* **[GitHub Deposu](https://github.com/HibrahimBoz/VirtualAdvanceddatagridview)**

### Temel Özellikler ve İyileştirmeler

* **[YENİ] Virtual Mode Desteği (v1.1.0)**: 
    * Milyonlarca satırlık (75M+) büyük veri setlerini verimli bir şekilde işlemek için optimize edildi.
    * **Gelişmiş Seçim Mantığı**: Sanal Modda Shift-Tıklama, Ctrl-Tıklama ve Sürükleyerek seçim desteği.
    * **Seçim Terfisi (Promotion)**: Büyük aralıklarla etkileşime girildiğinde yerel WinForms seçimini yüksek performanslı Sanal Seçime otomatik olarak aktarır.
* **[DÜZELTME] Modern .NET Kaynak Yükleme**: .NET 5, 6, 7 ve 8 ortamlarında sıkça karşılaşılan `MissingManifestResourceException` hatası çözüldü.
* **Gelişmiş Filtreleme ve Sıralama**: Orijinal ADGV'nin sunduğu güçlü Excel tarzı filtreleme ve çok sütunlu sıralama özelliklerini korur.

---

## License / Lisans

Copyright (c) Davide Gironi, 2015  
Modified work Copyright (c) 2026 Halil İbrahim Bozoğlu  
Virtual ADGV is open source software licensed under the [Microsoft Public License (Ms-PL) license](http://opensource.org/licenses/MS-PL)  
Original work Copyright (c), 2013 Zuby <zuby@me.com> http://adgv.codeplex.com