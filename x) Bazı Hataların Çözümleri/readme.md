# Bazı Hataların Çözümleri

![Untitled](../!img/mergeEror.png)
## 1) ''Main and Master are entirely different commit histories''
### Commitlediğimiz Master Branch'i, Main Branch'e Taşınmıyorsa (Merge Edilemiyorsa:)
 `git checkout master`

 `git branch main master -f  `

 `git checkout main  `

 `git push origin main -f `

İşlemlerini deneyebilirsiniz.
---