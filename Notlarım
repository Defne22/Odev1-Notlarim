Git(version kontrol sitemi(bir check ya da safe point sistemi gibi) VS GitHub
git: arayüz tasarla- (safe point yani arayüz noktası), sonra giriş ekranı, veritabanı bağlantısı ve çıkış fonksiyonu yazılır
Linus Torvalds - git (şuan bir endüstri standardı)
git proje,portal ve interktif.
Git çok yaygın.
rm -rf GitKursu: dosyayı siler
ls : içinde bulunan klasörleri görmek,list gibi,dosyayı görmek için
mkdir GitDersi : klasör ekler
clear : komutu ile her şey temizle
cd Desktop :  masaüstüne kalsör oluşruma için,masaüstüne gitme
git : yardım dökümantasyonu gösterir.
git --version: hangi versiona sahipsin
pwd : güncel olarak nerdesin görmek için
cd Documents: dokumana gitmek için
cd .. : desktop, masaüstüne gir
cd Users : users girer
cd feryat/(tersi)
cd Desktop
touch not.txt: not defteri, metin dosyası oluşturma
rm not.txt: remove yani kaldırma
rm : klasör silmez tek dosya
rm -rf: klasör siler
git config --global user.name "Defne Ozer"
git config user.name :ile kontrol et
git config --global user.email defneozer124@gmail.com
git config user.email:kontrol etme mail

GIT: Versiyon kontrol sistemi, save point (kaydetme)
git hub: bir potral, bir web uygulaması,  websitesi. içerisindeki projeleri saklamamıza izin veren uygulama.

git versiyon sistemi her yerde kullanılabilir ve yazılım endüstrisinde kullanılmadığı yer yok. git dışında başka şeyler de var ama epey kişi git kullanır genellikle
Örn proje: arayüz tasarlandı (kaydettim), giriş ekranı yapıldı (kaydettim), veritabanı bağlantısı yapıldı (kaydettim), çıkış fonk yazıldı (kaydettim)(çıkış fonk ikiye ayrıldı resim paylaşma fonk ve mesajlaşma yazıdı ikisi aynı anda yapılabilir bir arkadaşın varsa bu ikiye ayrılmaya branch denir. resim paylaşma yapan resim indirme fonk yapar. mesajlaşma yazan ise mesajlaşma tasarımı yapar sonra.) Belli bir yerde projeyi birleştirebilirsin ve istediğin noktaya ileri geri gidebilirsin bcs hep kayıtlı. Branch olayı başka kişilerle de tek başına da yapılabilir.

Commit: Burda yapılan kaydetmelere denir ve ing'de adamak denir.

Çalışma Klasörü: Proje klasörü gibi örn arayüz tasarlandı yazdın yazdın yazdın daha commitlemedin git add dedin.
 Index-Staging : arayüz tasarlandı örneği hala sahnede ama
Local Repository : arayüz tasarlandı (git commit en son)

git status: git in güncel durumunu gösterir.
not a git repository : bu klasörün git ile herhangi bir bağlantısı yok diyor.

git init: bu klasörü git bağlantısı ekler. (master olarak görünüyor, inital yani ana branchin ismi) Git başlatılmış yani initiate edilmiş

git innit çalıştırmadan önce git status ile durumunu kontrol et.
ls -la :ile gizli klasör gör
cd .git: ile içerisine gir
cd .. , ls, rm -rf .git (ile yanlışlıkla eklediğin git silinir)

touch ilkdefter.txt : not defteri eklemek
touch ornek.py : python dosyası ekler ve ls ile görürsün.

git add ilkdefter.txt : ile eklersin eklenmeyenleri yani kırmızı olanları
sonra git status ile kontrol edersin
Eğer eklenmişlerse yeşil renkte new file yazar.

git commit dersen: senin için default neyse o açılır.
(git commit -m : ile o mesajı yazabilirsin )
git commit -m "ornek ve ilkdefter oluşturuldu"
git log : ile yaptığın commitleri gör
Master branch içindeyiz zaten bir tane branch var şuan.
Sublime text
git add demek yerine : "git commit -a" yaz ekleyip commit etmek için
git commit -m "ilk satır kodlarımızı yazdık"
her şeyi tek tek eklemek: git add
git status
git log
cd Desktop
touch ornek.html
eklemek için : git add ornek.html
gizli dosya oluştur: touch gizli.txt
git repository'ı git'e koyup herkesin görmesini sağlayabilirsin. 
git add . :her şeyi ekler, gizli txt dahil

git commit -m "html paragraf ekledi"
git log
gitignore : görmezden gelmek

pwd: güncel dosya teyit
touch .gitignore : ile gitignore oluşturulur. git status ile kontrol et.
git commit -m "gitignore dosyası oluşturuldu"
git log : gitignore dosyası oluşturuldu gördün
Q tuşu: qut ordan çıkmak için
git commit -m "gitignore konusunu bitirdik"

gitignore template python bak
HEAD güncel olarak nerde, hangi branch'de olduğunu gösterir.
git branch komutuyla branch açıyorsun.
git branch feat (yeni bir özellik yani feature)
git commit : yeni branch, güncel olduğun yer
git switch master: master'a geri döndün
git merge feat: git commit'leri birleştirme

mkdir Kitap
ls
cd Kitap
git staus
touch ilkbolum.txt
git status yapınca ilkbolum adında bir dosya oluştu bunu staging'e alalım sonra commitlersin diyor.
git add ilkbolum.txt
git commit -m "ilk bolum başlığı yazıldı"
git branch: Tek bir branch olduğunu nerden anladık. Master yazdı çünkü.
 
git add . : hepsini ekler
git commit -m "ilk satırlar yazıldı"
git log: commit 151f02cae451c05944c961bc8c66ade814b7e553 (HEAD -> master)
Author: Defne Ozer 
Date:   Thu Apr 3 13:35:47 2025 +0300
ilk satırlar yazıldı
commit f72587c5993f3e6ee851cceb02e80fadd5866b16
Author: Defne Ozer 
Date:   Thu Apr 3 13:08:45 2025 +0300
ilk bolum başlığı yazıldı

git branch feature
git status
git branch : master yeşil olarak gözüküyor
git switch feature : diyince yine feature'a geçtik.
git branch :master yeşil ve yıldızlı görünüyor
git log

touch deneysel.txt
git add .
git commit -m "ilk satır deneyseller yazıldı"
git log

git add . 
git commit -m "ikinci deneysel satır"
git log: yalnızca master'daki commitleri gördük
git switch feature
git branch: master/feature
git switch master : master'a döndük
deneysel.txt: git switch feature içinde

git status
git commit -m "bugün öğrenilenler yazıldı"
üst ve alt ilerleme ok tuşuna tıklarsan ve  daha önceden yazdığın komutlara geri dönebilirsin.
git add .
git commit -m "bugün öğrenilenler yazıldı"
git add .
git commit -m "son commit satırı eklendi"
git log
git switch feature: yapınca deneysel geri geldi
feat. ve master birleştirecez ve bunun için git merge feat yapıcaz.

git merge feature: merge branch feature

Fast forwarding:
Hem feat'de hem master'da bir şey yaparsan çakışma yani collide olur.

Daha kolayı yeni bir branch açabilirdik feat ve orda commit atarak master'da bir şey yapmayabilirdik.Ve yeni branch'i içeri alırdık. İşte buna da fast forwarding denilir.
git status
git log
git branch arkapak
git branch
git switch arkapak
touch kapakyazısı.txt
git add .
git commit -m "arka kapak ilk satır yazıldı": [master 2c9a878] arka kapak ilk satır yazıldı
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 "kapakyaz\304\261s\304\261.txt"

git add .
git commit -m "arka kapak yazısı güçlendirildi"
git log: commit 2c9a8780799f5609c79538f16ae04ecbc283c2c9 (HEAD -> master)
Author: Defne Ozer 
Date:   Mon Apr 7 17:14:41 2025 +0300

    arka kapak ilk satır yazıldı

commit 68d33b693afea18a408eaa42f56c991a2ea6ce0c (arkakapak)
Author: Defne Ozer 
Date:   Mon Apr 7 16:10:29 2025 +0300

    ilk satır deneyseller yazıldı

git switch master
git log
git branch: çalıştırdığında master'da olduğunu görüyorsun:   arkakapak
* master
git merge arkapak : fast-forward: kapakyazisi.txt  yazdı. 
git log: (HEAD büyüktür master, arkapak)

Merge Conflict:
cd ..
mkdir JavaKitabı
cd JavaKitabı
git status
git init
touch ilkbolum.txt
git status
git add .
git commit -m "giriş cümlesi yazıldı."
git branch arkapak
git switch arkapak
git add .
git commit -m "arka kapak yazıldı."
git switch master
rm ilkbolum.txt
touch bolum1.txt
git add .
git commit -m "ilk bolum tekrar yazıldı"
git branch : çakışma var mı bak
git merge arkapak : birleştirlmiyor bcs çakışmalar var. 
git merge arkapak: hala olmadı bcs dosya eklenmedi.
git add .
git commit -m "merge conflict çözüldü"
git merge arkapak
git status
git branch 
git log
git branch
touch ornek.java
email string oluşturdum sublime'da : String email = "defneozer124@gmail.com";

git add .
git commit -m "email eklendi"
git branch feat
git switch feat
