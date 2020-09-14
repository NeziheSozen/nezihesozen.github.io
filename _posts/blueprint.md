# Unreal Engine 4 Blueprint

## Actor Sınıfı
Level içerisine yerleştirilebilecek herhangi bir nesnedir. 3B dönüşüm işlemlerini (öteleme, döndürme, ölçeklenirme) desteklemektedir. Bir Actor sınıfı meydana getirilebilir(ing. spawn) ya da yok edilebilir (ing. destroy). 

Tüm "AActor" sınıfı, tüm aktörlerin temel sınıfıdır. AActor sınıfından bir örnek oluşturma işlemine "spawning" denilmektedir. Bu işlem, SpawnActor() isimli generic fonksiyonu ile yapılabilmektedir. 

Aktör bir anlamda Component isimli nesne türlerini barındıran Container olarak düşünülebilir.

## Pawn (Piyon) Sınıfı
Oyuncular ve Yapay Zeka tarafından kontrol edilen aktörlerin temel sınıfıdır. Oyun dünyasında yer alan bir oyuncunun ya da Yapay Zekanın fiziksel temsilidir. Bu fiziksel temsil sadece oyun içindeki görünüm anlamına gelmemekte, aynı zamanda çarpışmalar ve diğer fiziksel etkileşimler açısından dünyayla nasıl etkileşime girdiğini de belirlemektedir.

## Character Sınıfı
Oyun dünyası içerisinde hareket edebilme özelliğine sahip olan bir Pawn türüdür.  

## Player Controller Sınıfı
Pawn ile oyuncu (insan) arasındaki yazılım arayüzüdür. Bu sınıf aslında oyuncunun isteklerini temsil eder. Pawn'daki tüm girdileri kullanmak mümkündür. PlayerController oyun boyunca devam ederken Pawn geçici olabilir. Örneğin, bazı oyunlarda, ölebilir ve yeniden doğabilirsiniz. Böylece yeni bir Pawn alırsınız, ancak PlayerController'ınız aynı olacaktır.

## Game Mode Base Sınıfı
Bu sınıf, oynanan oyunu, kurallarını, puanlamasını ve oyun türünün diğer yönlerini tanımlar. 

## Actor Component Sınıfı

## Scene Component Sınıfı


# Kaynaklar
[1. Pawn](https://docs.unrealengine.com/en-US/Gameplay/Framework/Pawn/index.html)

[2. Player Controller](https://docs.unrealengine.com/en-US/Gameplay/Framework/Controller/PlayerController/index.html)

[3. Game Mode](https://docs.unrealengine.com/en-US/Gameplay/Framework/GameMode/index.html)
