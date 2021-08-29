# Regresyon-Modelleri
Lineer Regresyon Modelleri (Ridge-Lasso-ElasticNet)
## Ridge Regresyon
Bir veri sınıfındaki çok değişkenli verileri analiz etmek için bu yönteme başvurulur. Verilerdeki en küçük kareler tahmincilerinin varyanslarından daha küçük varyanslı tahminler verdiğinden tercih edilebilir. Aşırı öğrenmeye (over-fitting) karşı dirençlidir. Tüm değişkenlere modelde yer verme imkânı sağlar, ilgisiz olan değişkenleri çıkarmaz ancak katsayılarını sıfıra yaklaştırır. Ridge regresonda L2 Düzenliliği kullanılır.

## Lasso Regresyon
Çıktı olarak düzenlediği modelin tahmin doğruluğunu ve yorumluluğunu arttırmak için kullanılır. Ridge regresyondan en temel farkı L2 düzenliliği yerine L1 düzenliliği kullanmasıdır. Yine aynı ridge regresyonu gibi tüm değişkenlere modelde yer verme imkânı sağlar ancak ridge regresyonundan farklı olarak ilgisiz değişkenlerin katsayılarını sıfıra eşitler.

## ElasticNet (ENet) Regresyon

Bu regresyonun yaptığı işlem kısaca ridge ve lasso regresyonlarını birleştirmektir. Yani hem L1 hem de L2 düzenliliğini kullanmaktadır.ElasticNetCV, birden çok alfa değerini arayabilen ve en iyisini uygulayabilen bir çapraz doğrulama sınıfıdır. Yani özetle bu yöntem tek alfa değeriyle model oluşturup işlemi bitirmek yerine tanımlanılan tüm alfa değerlerini inceleyip karar verir.

Detaylı çalışmam : https://burakzdd.medium.com/regresyon-analizi-3afd045e42be 
