# Miras Alma ve Kapsülleme Örnek Projesi

## Proje Açıklaması

Bu proje, nesne yönelimli programlamanın (OOP) temel prensiplerinden olan **miras alma** (inheritance) ve **kapsülleme** (encapsulation) kavramlarını içeren örnek bir uygulamadır. Amaç, sınıflar arasında ilişki kurarak kod tekrarını azaltmak ve veriyi güvenli bir şekilde işleyerek korumaktır.

## Kullanılan Kavramlar

### Miras Alma (Inheritance)

Miras alma, alt sınıfların (derived classes) üst sınıflardan (base classes) özellik ve davranışları devralmasını sağlar. Bu projede:
- **Ana sınıf** olarak belirlenen temel bir sınıf oluşturulmuş ve diğer sınıflar, bu sınıfın özelliklerini miras almıştır.
- Bu yapı, tekrar eden kodu ortadan kaldırarak kodun daha düzenli ve okunabilir olmasını sağlar.
- Alt sınıflar, üst sınıflardan miras aldıkları özellikleri özelleştirerek esnek bir yapı sunar.

### Kapsülleme (Encapsulation)

Kapsülleme, verilerin dışarıdan doğrudan erişimini sınırlandırarak güvenli hale getirir. Bu projede:
- **Özel** (private) erişim belirleyicisi ile veriler sınıf dışından erişime kapatılmıştır.
- Veriye yalnızca belirli metotlar (getter ve setter metotları) aracılığıyla erişim sağlanarak, veri bütünlüğü korunmuştur.
- Bu teknik, kodun daha güvenli, düzenli ve sürdürülebilir olmasını sağlar.

## Proje Dosya Yapısı

- `BaseClass.cs`: Ana sınıf ve genel özellikler burada tanımlanmıştır. (Program içinde başka isimler ile tanımlanmış olup belirtilmiştir.)
- `DerivedClass.cs`: Alt sınıf, ana sınıftan miras alarak özellikleri genişletir ve özelleştirir. (Alt sınıflar ve miras alanlar belirtilmiştir, Projede ki isimleri farklıdır.)
- `Program.cs`: Projenin çalıştırılabilir dosyasıdır; sınıflar ve yöntemler burada test edilmiştir.
