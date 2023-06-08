# GeleceğimAll Bootcamp 

## Git ve GitHub

### Git nedir?
        Bir versiyon kontrol sistemidir.. peki..

### Versiyon Kontrol Sistemi Nedir?

        Bir döküman (yazılım projesi, ofis belgesi vb.) üzerinde yaptığınız değişiklikleri adım adım izleyen, istediğinizde kayıt eden ve isterseniz bunu internet üzerindeki bir bilgisayarda veya yerel bir cihazda (repository / repo / depo) saklamanızı ve yönetmenizi sağlayan bir sistemdir.
### Git init nedir ?

        git init komutu, içinde bulunulan klasöre .git dosyası oluşturarak o klasörü bir git repository haline getirecektir.

	
### Terminalde yeni bir branch oluşturmak için

  git checkout -b feature/my-new-branch  

### ***git checkout branchName*** komutu ile branch değiştirilebiliyor bu noktada geçtiğimiz branch ile başka bir branch birleştirmesi yapılabilir

1. git checkout branchName  

2. git merge otherBranchName  

### ***git rm*** - bir dosyayı bir dosyayı kaldırmak için kullanabiliriz.

1. git rm fileName.js  -

* kaldırma işlemi yapabilmek adına dosyada yapılan ve cache’e kaydedilmiş dosyaların değişikliklerini geri almamız yada bu dosyanın izlenmesini kaldırmamız gerekiyor,
* yada kaldırmaya zorlamak için rm’den sonra -f diyebiliriz
	
	
## Visual Studio Code ile Source Control

1. Yapılan değişiklikleri dosya adının yanında bulunan + işaretine basarak izlenen dosya haline getiriyoruz – değişiklikleri durum haline getiriyoruz

2. Stage edilmiş dosyaları source control’de mesaj yazarak commit ediyoruz

* mesajlar emir kipi ile yazılmalı sen dosyada yaptığın değişiklikleri sanki github’a bunu sende yap dercesine yazılmalı(bu bir adaptır)
“readme.md ekle” yarattığım dosyayı commit et sende ekle dercesine
* Stage edilen dosyada yapılan değişikliklerin stageden geri alınması için izlenen dosyanın yanında eksi işaretine basılır.

### .gitignore

	oluşturulan repository de değişikliklerinin takip edilmemesi istenen dosyalar bu dosya içerisine eklenir.

	eğer * işareti konulup bir dosya uzantısı eklenirse o dosya uzantısına sahip hiçbir dosya commit’e eklenmeyecek git üzerinde takip edilmeyecektir.

ya da rep içerisinde dosya adresi eklenir;

 ***./temp/bilmemNe.java***      

“ ! “ = dosya adının başına konulduğunda .gitignore dosyasında yazılı dosya görmezden gelmesini sağlıyor. “izin verme / hariç tutma” anlamına geliyor.

