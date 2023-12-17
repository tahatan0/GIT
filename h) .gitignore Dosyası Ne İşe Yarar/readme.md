# `.gitignore` Dosyası Ne İşe Yarar?

- `.gitignore` dosyasının içerisinde yazmış olduğumuz dosyalar, dosya uzantıları, klasörler artık git tarafından takip edilmez. Untracked

- Versiyon Kontrol Sisteminde Tutmamız Gerek Olmayan, Üstünde Sürekli Değişiklik Yapmadığımız, sabit duran dosya, video, görsel gibi elementleri tanımlar.

- Herangi bir yazılım dili geliştirirken google’a :
  **react/.gitignore Yazarak, versiyonlanmasına gerek olmayan sabit dosyaları öğrenebiliriz.**

![Untitled](../!img/Untitled%2031.png)

- Kullandığımız Kod Editörünün de (IDE) değişmeyen, sürekli versiyonlanmaması gereken dosyaları olabilir :
  **Örneğin : Aşağıdaki Elemanları Versiyonlamak Gereksizdir.**
- Görseller (../!img)
- Videolar
- Logolar
- Paket Yöneticisi İle Kurulmuş Dosyalar (**npm**)
- Logs
- IDE eklentileri
- API anahtarları, kimlik bilgileri
- • Çalışma dizinizdeki **geçici dosyalar**

### Nasıl Yapılır?

- Proje’nin içerisinde bir dosya açıp adını ‘’.gitignore’’ yapıyoruz.

![Untitled](../!img/Untitled%2032.png)

![Untitled](../!img/Untitled%2033.png)

![Untitled](../!img/Untitled%2034.png)
