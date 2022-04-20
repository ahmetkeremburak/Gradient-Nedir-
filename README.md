# Gradient Nedir?
Bu repo [patika.dev](app.patika.dev)'in matematik dersi projesi için oluşturulmuştur.

##Gradientler birden fazla değişkeni olan fonksiyonların türevleridir.
Tek değişkenli fonksiyonlarda gördüğümüz üzere türev x değişkenimizdeki değişim ve buna bağlı olarak fonksiyonda meydana gelen değişimin oranıdır. peki ya fonksiyon birden fazla değişkene sahipse? Mesela: 
f(x,y) = z olduğu vakit türevini nasıl almalıyız?

Böylesi bir durumda fonksiyonun hem x hem de y değişkenlerine göre iki defa parçalı türeviyle fonksiyondaki değişim oranını ifade edebiliriz. Peki bu iki değişkenli fonksiyonlar size bir şeyi hatırlattı mı? Vektörleri düşünün. İki boyutlu bir düzlemde vektörlerin de x ve y kısımları mevcuttur.

Bunu biraz daha açalım. İki boyutlu bir vektörde x ve y elementleri farklı oranlarda değişerek fonksiyonu farklı şekillerde etkileyebilirler. Bu değişimi hesaplamak için fonksiyonun her iki elementindeki değişim bulunur ve toplam değişim bunların üzerinden hesaplanır. Bu değişime "Gradient" denir.

## Ne işe yarar?

Birden fazla değişkenli bir fonksiyonun(mesela bir vektörün) gradienti bize ne ifade eder? Gradient fonksiyondaki her elemanın türevini alarak bize tüm fonksiyonun en büyük artışı için gereken formülü verir. Burada dikkat edilmesi gereken gradient kendi başına bize bir nokta vermez. Gradiente bir nokta verdiğimiz zaman bize o noktaya ait en yüksek artışı elde etmek için nereye doğru gitmemiz gerektiğini gösterir. Yani bize bir yön verir.

## Formül

![Gradient Formül](https://betterexplained.com/wp-content/plugins/wp-latexrender/pictures/684fd5c5646d584452c708ac16a6dd6f.png)

Bu formül 3 değişkenli bir fonksiyonun gradientini gösteriyor. Ters üçgen gradient anlamına gelir ve "del" olarak telaffuz edilir. Üçgen işaretini deltadan hatırlayın. Gradient da bir nevi değişimi yansıtıyor. 



