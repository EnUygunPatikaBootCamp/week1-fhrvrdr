
### OOP nedir? Ne amaçlı kullanılır?
- Nesne Yönelimli Programlama, işlevlerin nesne olarak soyutlandığı bir yaklaşımdır.
- Kod tekrarını önlemek, bilgi gizliliği sağlamak, kod bakımını kolaylaştırmak gibi amaçları vardır.
### Polymorphism ne amaçlı kullanılır?
- Polymorphism, farklı işlemler yapan fakat aynı isme sahip olan metodların kullanılması durumudur.
- Örneğin "Hayvan" isminde bir ana sınıf mevcut. Sınıf içerisinde ses isimli metodumuz mevcut. Hayvan sınıfından Kedi ve Köpek isimli iki sınıf türettik. Kedi ve Köpek farklı sesler çıkarır. Türettiğimiz sınıflarda "ses" isimli metodu tekrar tanımlayarak kullanırız. Aynı isimde iki adet metodumuz olur. Bu durum ise Polymorphism(Çok biçimlilik) olarak adlandırılır.
### Bir metodun private, protected ya da public olması kavramlarını açıklayınız.
- Private: Bir metodun sadece tanımlandığı sınıf içerisinden erişilmesini sağlar.
- Protected: Bir metodun tanımlandığı ve kalıtım ile aktarıldığı sınıflardan erişilmesini sağlar.
- Public: Bir metodun sınıf içi, kalıtım aracılığı ve sınıf dışından erişilmesini sağlar.
### (Abstraction) Soyutlama nedir?
-  İç detayların gizlenerek sadece işlevlerin gösterilmesidir. Nesne tabanlı programlamada sınıfların soyutlanmasını Abstract Class ve Interface ikilisi sağlamaktadır.