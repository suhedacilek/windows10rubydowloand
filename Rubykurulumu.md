## Merhaba arkadaşlar , bugün sizlere Windows 10 kullanan arkadaşlarımız için **Ruby** kurulumunu anlatacağım:
>1.İlk olarak bilgisayarınızın **"Başlat"** menüsünden **"Geliştirici ayarları"** nı aratınız.

![Geliştirici Ayarları](https://pbs.twimg.com/media/DtmjHIrWoAA2PZA.jpg:large)

* Geliştirici ayarlarından karşınıza gelen 3 seçenekli kısımdan **"Geliştirici Modu"** nu aktif hale getiriniz.

![Geliştirici Modu](https://pbs.twimg.com/media/DtmkW86XcAATK8x.jpg:large)
+ Bilgisayarınızın ayarlarında gerekli değişiklikleri yaptıktan sonra 2.adımı uygulayabiliriz..

> 2.adımımızda tekrar başlat menüsüne gelip **"Windows özelliklerini açma ve kapama"** yazıp aratıyoruz , karşınıza gelen ekranda aşağıda verilenleri aktif hale getiriyoruz.

![açmakapama](https://pbs.twimg.com/media/DtmqCjWXcAAmxxL.jpg:large)

Bu özellikleri aktif hale getirip **"OK"** butonuna bastıktan sonra bilgisayarınız yeniden başlatılacaktır. 

* Bilgisayarınız yeniden başlayıp açıldıktan sonra 3.adımımızı uygulayabiliriz.. 



>3.adımımızda ilk olarak ---> [Microsof Store](https://aka.ms/wslstore) linkine tıklayınız veya browserdan --->  https://aka.ms/wslstore aratınız..


![Microsoft Store Link](https://pbs.twimg.com/media/DtmgAgVW0AA1RYZ.jpg:large)



Tıkladığınız link sizi *Microsoft Store* mağazasına yönlendirecektir.



![Microsoft Store Mağaaza](https://pbs.twimg.com/media/Dtmf76-WwAAP7sJ.jpg:large)

* Karşınıza gelen ekranda **"Ubuntu"** uygulamasını install ediniz.
* Ubuntu'yu bilgisayarınıza indirdikten sonra **"Launch"** butonundan Ubuntu'yu çalıştırınız.

![Ubuntu](https://pbs.twimg.com/media/Dtmf9lkWsAADYn3.jpg:large)

* Ubuntuyu çalıştırdıktan sonra karşınıza şu şekilde bir ekran gelecektir;

![ubuntu](https://pbs.twimg.com/media/DtmgKGpXQAIl-Fg.jpg:large)


* Söylenilen şekilde yaklaşık birkaç dakika bekleyiniz ...

  * Bekleme sonucunda sistem sizden bir kullanıcı adı oluşturmanızı isteyecektir *Örneğin ; suhedacilek gibi* 

  ![kullanıcıadı](https://pbs.twimg.com/media/DtmgLv_WkAANQmh.jpg:large)

  * Kendinize uygun kullanıcı adını seçip sisteme kabul ettirdikten sonra bir sonraki adımınız kendinize uygun parolayı seçmeniz. 

 > ## UYARI: GELEN ŞİFRE OLUŞTURMA SATIRINDA OLUŞTURDUĞUNUZ ŞİFRENİN KARAKTERLERİ GÖRÜNMEYECEK.YAZDIĞINIZ ŞİFREYİ DİKKATLİ VE EMİN OLDUĞUNUZ BİR ŞEKİLDE OLUŞTURUNUZ.

* Şuan şifrenizi oluşturdunuz , şimdi bir sonraki adıma geçelim..

>4. adım ise Ubuntu konsolunu kullanmaya devam ederek gerekli komutları girip kurulumumuza devam etmek..


> *  ***sudo apt-get update***
> * ***sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev software-properties-common libffi-dev***



- Her komut tamamlandığında yeni bir komut yazmanız için sistem sizi şu şekilde bekleyecek:

![komutbekleme](https://pbs.twimg.com/media/DtmgHJQXQAUAmWo.jpg:large)

>Sudo komutlarını yazdıktan sonra kurulum için önerilen **"rbenv"** methodunu uygulayalım.

> * ***cd***
> * ***git clone https://github.com/rbenv/rbenv.git ~/.rbenv***
> * ***echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc***
> * ***echo 'eval "$(rbenv init -)"' >> ~/.bashrc***
> * ***exec $SHELL***

> * ***git clone https://github.com/rbenv/ruby-build.git~/.rbenv/plugins/ruby-build***
> * ***echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc***
> * ***exec $SHELL***

> * ***rbenv install 2.5.3***
> * ***rbenv global 2.5.3***
> * ***ruby -v***

* Her komutu tek satır halinde yazıp "Enter" tuşuna basacağız , bilgisayar işlem yapıyorsa- önceden de belirttiğim gibi- yeşil yazılı kullanıcı adınız gelene kadar başka birşey yapmayın ve sadece bekleyin.Ek olarak **"rbenv install 2.5.3"** komutunu yazdıktan sonra bilgisayar 5 dakikaya yakın bekleyebilir endişelenip başka birşey yazmaya kalkışmayınız :)

 > Son adım Bundler'i yüklemek ;

 > *  ***"gem install bundler"*** 
 
 komutunu yazdıktan sonra işleminiz tamamlanmış olacaktır. 

>Ubuntu da Ruby'i çalıştırmak için **"irb"** komutunu girip çalışmalarınıza başlayabilirsiniz.

             *Tebrikler :)





