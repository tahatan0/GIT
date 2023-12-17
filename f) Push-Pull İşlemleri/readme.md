- **Sırasıyla Push-Pull Etmek. (Düzenleniyor...)**
  ![Untitled](../!img/Untitled%2020.png)
  ![Untitled](../!img/Untitled%2021.png)
  ![Untitled](../!img/Untitled%2022.png)
  ### Projeyi Push Etmek
  1. **git init** **→** Local Repository oluşturur. (Proje Klasörünün içinde .git klasörü)
  2. **git add \*** **→** Değişikliklerin hepsini, working dir’ den stage’ e atar.
  3. **git commit -m "_commit yorumu_”** **→** staged’ den *HEAD*’e gönderir.
  4. **git remote add origin** [https://github.com/tahatan0/tahatan0.git](https://github.com/tahatan0/tahatan0.git) **: Eğer** bir remote repository bağlantısı **yoksa** ssh ile (reponun url’si) bağlıyoruz.
  5. **git push -u origin master** **→** Burada bahsi geçen `origin` remote repository’nin kök dizinini belirtir ve sabit bir isimdir. `master` ise sizin çalıştığınız branch (dal)’ı belirtir. Branch’larınıza istediğiniz gibi isim verebilirsiniz.
  ***
  ### Projeyi Pull Etmek (Düzenleniyor…….)
  1.
  2. **git remote add origin** [https://github.com/tahatan0/tahatan0.git](https://github.com/tahatan0/tahatan0.git)
  3. **git pull origin master** veya **git pull**
  4.
  ### GIT Stash
  Çalışmalarımza devam ederken güncel dosyaları çekmek isteyebiliriz. Bu tarz durumlarda çakışma olmaması için`git stash` komutunu kullanarak çalışmakta olduğumuz dosyaları saklayabiliriz. Bu işlem *pull*’dan önce yapılmalıdır.
  Pull işlemi tamamlandıktan sonra tekrar çalışmalarımızı stash’den almak için ise  `git stash apply` komutu ile kaydedilmemiş çalışmalarımızı geri alabiliriz.
  ### GIT Merge
  Farklı bir branch’da çalışmamızı tamamladık ve artık bu branch’i projemize Dahil etmek istiyoruz. Bunun için `git merge branch_ismi` komutunu kullanabilirsiniz.
  ***
