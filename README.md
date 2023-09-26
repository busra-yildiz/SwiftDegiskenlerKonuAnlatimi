# SwiftDegiskenlerKonuAnlatimi
Eğer Swift programlama dilinde değişkenler nasıl tanımlanır ve ekrana nasıl yazdırılır konusunda bilgi edinmek istiyorsanız, işte adım adım bir rehber:

Swift'te Değişken Tanımlama:

Swift'te değişkenler veya sabitler tanımlamak için var veya let anahtar kelimelerini kullanabilirsiniz. İşte bu iki anahtar kelimenin kullanımı:

[Değişken Tanımlama (Var)
var degiskenAdi = deger
Bu şekilde bir değişken tanımlanabilir. degiskenAdi değişkenin adını temsil eder ve deger ise değişkenin başlangıç değerini ifade eder. Swift, genellikle türleri otomatik olarak çıkarabildiği için tür belirtmeniz gerekmez. Örneğin:
var sayi = 10
var metin = "Merhaba, Swift!"
Sabit Tanımlama (Let):
Sabitler, bir kez tanımlandıktan sonra değeri değiştirilemeyen değişkenlerdir. Sabitler için let anahtar kelimesini kullanabilirsiniz:
let sabitAdi = deger
Ekrana Yazdırma:

Swift'te ekrana yazdırmak için print() fonksiyonunu kullanabilirsiniz. Bu fonksiyon, belirtilen metni veya değeri konsola yazdırır. İşte örnek kullanımı:
let mesaj = "Merhaba, dünya!"
print(mesaj)
Yukarıdaki örnekte, mesaj sabiti oluşturuldu ve bu mesaj print() fonksiyonuyla ekrana yazdırıldı. Çıktı olarak "Merhaba, dünya!" görüntülenir.

Ayrıca, değişkenlerin veya ifadelerin değerlerini ekrana yazdırmak için dize içindeki özel yer tutucuları (placeholders) da kullanabilirsiniz. Örneğin:
let ad = "John"
let yas = 30
print("Benim adım \(ad) ve ben \(yas) yaşındayım.")
Yukarıdaki örnekte, \() içindeki ifadeler değerlerine dönüştürülerek metin içine yerleştirilir ve ekrana yazdırılır. Çıktı olarak "Benim adım John ve ben 30 yaşındayım." görüntülenir.

Bu şekilde Swift'te değişken tanımlama ve ekrana yazdırma işlemlerini gerçekleştirebilirsiniz.
