**pwd :** nerde olduğumuzu gösteren komut  <br>
**cd Desktop** : cd buraya git demek yani masaüstü klasörüne girer.<br>
**cd .. :** yapar isek bir önceki klasöre geri gel demek<br>
**mkdir :** klasör oluştur demek.<br>
**touch not.txt :** metin dosyayı oluşturur.<br>
**rm not.txt :** nottxt silinir.<br>
- *rm sadece dosya siler klasör silmek için "rm -rf" klasöradi yazılır.*

- kullanıcı adını ve email git e kaydetme:<br>
$ git config --global user.name "username"<br>
sorgulama : git config --global user.name<br>


- e mail girme<br>
$ git config --global user.email emailname<br>
sorgulama : $ git config --global user.email<br>

**commit :** yaptığımız değişikliklere denir.(değişiklik kaydetme gibi o noktalar)<br>
**Branch: **Dallanma denir(version gibi) aynı anda bir projede çalışılabilir, farklı kısımlarda ikiye ayrılma branch ile yaparız. <br>

**git status : **güncel git durumunu gösterir. <br>

**git init :** klasörü git e bağlamak için
<br>

**ls -la : **gizli dosyalarıda gösterir.<br>

**dosyayı git e ekleme:
git add ilkdefter.txt**<br>

**commit yapma:** git commit -m "ornek ilkdefter"<br>

**git add .** : tüm işlemleri kayıt edecektir.<br>


**git add .** : tüm işlemleri kayıt edecektir.<br>

** git log** : tüm kayıtları görebiliriz (mesajları log)
<br>
*git add diyince commitlenmiş olmuyor ayrı olarak commit etmek gerekiyor.*<br>

git'e eklemek istemediğimiz dosyaları nasıl yapabiliriz:<br>
- touch .gitignore ile bir gitignore dosyayı oluşturulur. <br>
- <br>


**HEAD** : git içerisinde hangi konumda olduğumuzu gösteriyor. Genelde son commiti gösterir.<br>

**git merge** yapmak demek iki işi birbiri ile birleştirmek demek.<br>

güncel branch leri görmek için : **git branch** <br>

yeni bir branch oluşturmak istersek; **git branch feature(isim)** <br>

branch değiştirmek istersek : **git switch feature **<br>


iki brach'i birleştirmek istersek; **git merge feature **<br>

**Fast-Forward Merge**: Feature branch’iniz master’a merge olacağı anda eğer master üzerinde bir değişiklik (commit) olmamışsa, git varsayılan olarak master hattının son commit hash’i olarak, feature branch’in hash’ini alır. Bu duruma Fast-Forward Merging denir.<br>



