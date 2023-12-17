- **GIT Bash** ve **Git Temel Komutları**
  ![Untitled](../!img/Untitled%205.png)
  ![Untitled](../!img/Untitled%206.png)
  `git add -A .txt` komutunu çalıştırsaydık tüm .txt uzantılı dosyaları **staged** ortamına eklerdi.
  # **Değişiklikleri Commit’lemek**
  _Commit_, **staged** ortamına alınan dosyaların *HEAD*’e gönderilmesidir. Yapılan değişiklikler ***commit* sonucu hala sizin local’inizdedir** ve **uzak sunucuya gönderilmesi için push edilmesi gerekir.**
  - **Eğer İlk defa bir projeyi versiyon kontrol sistemine yani Git SCM e initialize ediceksek,
    git init komutunu kullanmalıyız.**
    ![Untitled](../!img/Untitled%207.png)
    ![Untitled](../!img/Untitled%208.png)
  - Proje klasörünün dosya yolunda yani içinde git bash açıldı
    ![Untitled](../!img/Untitled%209.png)
  - git init yazdık ve proje klasörümüzün içinde görünmeyen ‘’ .git ‘’ adında bir klasör açıldı, bu klasörün içerisindeki yapı GIT tarafından yönetiliyor. pek bi işimiz yok bu klasörle
    ![Untitled](../!img/Untitled%2010.png)
    ![Untitled](../!img/Untitled%2011.png)
  - Burada **git add index.html** diyerek bu dosyayı takibe (tracking) aldık.
    ![Untitled](../!img/Untitled%2012.png)
  - Eğer yanlış dosyayı takibe aldıysak **git rm —cached index.html** yazarak bunu takipten çıkartabiliriz.
    veya **git reset** **index.html**
    `git reset` komutu dosyayı silmez. Sadece commit’lenmeye hazır durumda olma statüsünden çıkartır!
    ![Untitled](../!img/Untitled%2013.png)
    ![Untitled](../!img/Untitled%2014.png)
  - Eğer yaptığımız değişikliklerin snapshot’unu almak yani kaydetmek commit atmak istiyorsak;
    git commit -m ‘_Commit Hakkinda Yorum…vb_’
    ![Untitled](../!img/Untitled%2015.png)
    **git diff** ile en son aldığımız snaphot’a kıyasla şuanki snapshot arasındakı değişiklikleri görüyoruz.
    a ile b arasındaki fark buna tekabül ediyor.
    **Not**
    ![Untitled](../!img/Untitled%2016.png)
  - **M** : Modified
  - **U** : Untracked
    ![Untitled](../!img/Untitled%2017.png)
  - git log : projede hangi kullanıcı hangi saate ne commitlemiş loglarını gösterir
    ![Untitled](../!img/Untitled%2018.png)
    ![Untitled](../!img/Untitled%2019.png)
