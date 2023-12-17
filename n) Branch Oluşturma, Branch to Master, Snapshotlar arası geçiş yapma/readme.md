# Branch Oluşturma, Timeline…vs

![Untitled](../!img/Untitled%2035.png)

![Untitled](../!img/Untitled%2036.png)

![Untitled](../!img/Untitled%2037.png)

- Timeline’ı açarak bu şekilde daha önceki commitlere yani snapshotlara bakabiliriz.

## Branch Oluşturma

![Untitled](../!img/Untitled%2038.png)

![Untitled](../!img/Untitled%2039.png)

- Sol altta daha önce master yazıyordu, şimdi loginForm adlı oluşturduğumuz dizindeyiz yani branchteyiz (loginForm Workspace’i)

![Untitled](../!img/Untitled%2040.png)

- üstüne tıklarsak yine master’a geçiş yapabiliriz.
- **git checkout _branch_ismi : branchler arası geçiş yapar_**

### Branch’imizi, Master’la birleştirme

- **git checkout _master : Master’a geçiyoruz_**
- **git merge _branch_ismi : alt branchimizin adını yazıyoruz_**
- Master branchindeyken, xxx branchinde yapılan değişiklikleri görmek istiyorsak, ilgili dosyada **git merge _branch_ismi yazmamız gerekiyor_**
