# Csharp-Arduino-Kontrollu-Gunes-paneli
 <br>
<h2>Projenin genel tanımı ve amacı</h2><br>
<br> 
C SHARP ekranından arduino seri port iletişimi yapılarak yatay da ve dikeyde hareket edebilen güneş paneli kontrolü gerçekleştirilmiştir.Güneş paneli 4 adet ldr ile gelen ışığa göre hareket etmektedir.
<br>
 <br>
 <br>
<p>
<img align="center" width="500" height="300" src="https://user-images.githubusercontent.com/43750173/55818009-583b8700-5afe-11e9-8baf-22b4d98f1115.PNG">
</p>
<br>
<h2>Kullanılan teknolojiler</h2><br>
C#, Microsoft'un geliştirmiş olduğu yeni nesil programlama dilidir. Yine Microsoft tarafından geliştirilmiş .NET Teknolojisi için geliştirilmiş dillerden biridir. Microsoft tarafından geliştirilmiş olsa da ECMA ve ISO standartları altına alınmıştır.
&nbsp;&nbsp;&nbsp;&nbsp;<p><br>
<img align="left" width="350" height="300" src="https://user-images.githubusercontent.com/43750173/55818087-7c976380-5afe-11e9-8df4-673297902953.png" >
 <img align="center" width="350" height="300" src="https://user-images.githubusercontent.com/43750173/55818153-a6508a80-5afe-11e9-8a5d-b39b79968d20.jpg">
</p>
<br>
<br>
Arduino bir G/Ç kartı ve Processing/Wiring dilinin bir uygulamasını içeren geliştirme ortamından oluşan bir fiziksel programlama platformudur. Arduino tek başına çalışan interaktif nesneler geliştirmek için kullanılabileceği gibi bilgisayar üzerinde çalışan yazılımlara da bağlanabilir. 
<br>

<h2>Projenin Uygulama Aşamaları</h2><br><br>

Sistemde 3 adet form ekranlarımız bulunmaktadır.ilk ekranımız Kullanıcı giriş denetimi için gerekli şifre ve kullanıcı adını istemekdir.Başarılı girişte form2 ekranına hatalı durumda hatalı giriş mesajını vericektir.
<br><p>
<img align="left" width="850" height="400" src="https://user-images.githubusercontent.com/43750173/55818340-0e9f6c00-5aff-11e9-987e-a5c7d04a3a3b.PNG" >

</p><br><br><br><br>
 <br>
 <br>
 <br><br><br><br>
 <br>
 <br>
<h1>Form2 ekranı</h1><br>
Butona bastığımız anda Form2 ekranı karşımıza gelecektir.Burda gerekli Seri Port bağlantısı yapmak için gerekli Port seçilir.
Veri gönderim hızı da seçildikten sonra başarılı bağlantı gerçekleştirilirse kontrol ekranı FORM3 ekranı karşımıza gelecektir.
<br><br>
<br><br><br><br>
 

<img align="left" width="850" height="400" src="https://user-images.githubusercontent.com/43750173/55818457-56be8e80-5aff-11e9-863f-c43858daeb4d.PNG" ><br>
 <br>
 <br><br>
 <br>
 <br>
<br><h1>Form3 ekranı</h1><br> 
Gelen Form 3 Ekranında ise 2 adet kontrol ekranımızı içeren butonlarımız mevcuttur.Otomatik kontrol butonu sistemin ışığa gelen yere göre otomatik hareket etmesini sağlayan yapıdır.
 <img align="center" width="850" height="400" src="https://user-images.githubusercontent.com/43750173/55818907-64c0df00-5b00-11e9-9a77-7fd155da8a08.PNG">
 <br><br>
 <br>
 <br>
<h1>Otomotik Kontrol</h1><br>
Butona bastığımız 4 adet ldr; 2 üst 2 alt olmak üzere alt üslerin toplamı ve birbirinden çıkarımı sağlanır ve solların birbirinden toplanıp gene keza farkı alınarak ikisi arasında büyük olan tarafa hareketi sağlanmıştır.Tekrar Kullanıcı Değiştir denerek geri dönülebilir.<br><br>
<img align="left" width="850" height="400" src="https://user-images.githubusercontent.com/43750173/55818911-668aa280-5b00-11e9-9a85-83886f792f5a.PNG" >

<br><h1>Kullanıcı Kontrol<h1>
  <br>
  Form 3 seçilen veya kullanıcı değiştir ile ekrana gelen kullanıcı kontrolü için butona tıklanır.2 adet SCROLL Barlar lada panele veri yollanarak yatay ve dikey eksende hareketi sağlanır
 <img align="center" width="850" height="400" src="https://user-images.githubusercontent.com/43750173/55819169-db5ddc80-5b00-11e9-82ec-255b73de085b.PNG">


<br>
<br>
