# Odev

## 1. JavaScript nedir ve tarihsel gelişiminden bahsedin

> JavaScript, web tarayıcılarında çalışan ve web sayfalarına dinamik özellikler kazandıran bir programlama dilidir. JavaScript, kullanıcı etkileşimi, sayfa içeriğini değiştirme, asenkron veri iletişimi ve çeşitli diğer görevler için kullanılabilir. 1995 yılında Brendan Eich tarafından Netscape Communications Corporation'da geliştirilmeye başlanan bu dil, günümüzde sadece tarayıcılarda değil, sunucu taraflı geliştirme (Node.js) ve mobil uygulama geliştirme gibi geniş bir yelpazede kullanılmaktadır. JavaScript, ES6 (ECMAScript 2015) ile birlikte bir dizi yenilik ve güncelleme almış, geliştiricilere daha güçlü ve okunabilir kod yazma imkanı sunmuştur.
- ** 1995 - İlk Geliştirme:
Brendan Eich, Netscape Communications Corporation için, tarayıcı Netscape Navigator'ın bir bileşeni olarak ilk JavaScript prototipini geliştirdi. Bu dönemde dil, "Mocha" ve daha sonra "LiveScript" adlarıyla anıldı.

- ** 1996 - ECMAScript :
JavaScript, Avrupa Bilgisayar Üreticileri Derneği (ECMA) tarafından standartlaştırıldı ve "ECMAScript" adını aldı. Bu, dilin farklı tarayıcılarda tutarlı bir şekilde çalışmasını sağlamak için önemliydi.

- ** 2000'lerin Başları - AJAX ve Web 2.0:
JavaScript, Asenkron JavaScript ve XML (AJAX) teknikleri ile zengin internet uygulamalarının (RIA) gelişimine katkıda bulundu. Bu dönemde, kullanıcı etkileşimi daha hızlı ve daha duyarlı hale geldi.

- ** 2009 - ECMAScript 5 (ES5):
ES5, yeni dil özellikleri ekleyerek ve hataları düzelterek JavaScript'i geliştirdi. Bu, önceki sürümlerde bulunan tutarsızlıkları düzeltmeye odaklandı.

- ** 2015 - ECMAScript 2015 (ES6) ve Sonrası:
ES6, büyük bir güncelleme oldu. Arrow fonksiyonları, sınıflar, modüller gibi birçok yeni özellik ekledi. Bu sürüm, JavaScript'i daha modern ve güçlü bir dil haline getirdi. Sonraki yıllarda, ECMA tarafından yılda bir düzenli olarak yayımlanan güncellemelerle dil sürekli olarak gelişti.

- ** 2014 - Node.js ve Server-Side JavaScript:
Node.js, JavaScript'i sunucu taraflı uygulamalarda kullanılabilir kılarak dilin kapsamını genişletti. Bu, JavaScript'in yalnızca istemci tarafında değil, aynı zamanda sunucu tarafında da kullanılabilmesini sağladı.

- ** Günümüz - Modern Web Geliştirme:
JavaScript, web geliştirme ekosistemini şekillendirmeye devam ediyor. Framework'ler ve kütüphaneler (React, Angular, Vue.js gibi) ile birlikte, geliştiricilere daha etkili ve hızlı uygulama geliştirme imkanları sunuyor.
Bu gelişmeler, JavaScript'in sadece bir tarayıcı dili olmaktan çıkıp genel bir programlama dili haline gelmesini sağladı.

## 2. java ile javascript arasındaki fark nedir ? 

  Java ve JavaScript arasında isim benzerliği bulunsa da birbirinden oldukça farklı iki dildir. Aşağıda temek farklılıklarına değinilmiştir:

  1. Dil Tipi:

   - Java: Java, bir nesne yönelimli programlama (OOP) dilidir. Genellikle sunucu uygulamaları, masaüstü uygulamaları ve mobil uygulamalar gibi çeşitli platformlarda kullanılır.
   - JavaScript: JavaScript, bir tarayıcı tarafı betik dilidir. Web tarayıcılarında çalışır ve web sayfalarını etkileşimli hale getirmek için kullanılır.

2. Çalıştırma Ortamı:

   - Java, genellikle Java Virtual Machine (JVM) üzerinde çalışır. Bu, Java'nın platform bağımsız olmasını sağlar.
   - JavaScript, tarayıcılarda yerleşik olarak çalışır (örneğin, Chrome'un V8 motoru), ancak Node.js gibi ortamlarla sunucu tarafında da çalışabilir.

3. Kullanım Alanları:

   - Java çoğunlukla büyük ölçekli uygulamalar, işletim sistemleri, mobil uygulamalar ve büyük kurumsal projeler gibi geniş bir yelpazede kullanılır.
   - JavaScript, genellikle tarayıcılarda web sayfalarını etkileşimli hale getirmek için kullanılır, ancak artık sunucu tarafında (Node.js gibi) da kullanılmaktadır.

4. Nesne Yönelimli Programlama (OOP):

Hem Java hem de JavaScript nesne yönelimli programlama desteklese de Java bu paradigmayı daha katı bir şekilde uygular.

5. Derleme:
   - Java, genellikle kodun derlendiği ve ardından JVM üzerinde yürütüldüğü bir dil olarak kullanılır.
   - JavaScript ise çoğunlukla yorumlanan bir dildir, tarayıcı tarafından yukarıdan aşağıya her bir satır yorumlanarak çalıştırılır.
  
Bu farklılıklar, Java'nın genel amaçlı,büyük projelerde kullanılan bir dilken JavaScript'in daha tarayıcı tabanlı ve genellikle dinamik web sayfalarını güçlendirmek için kullanılmasını yansıtmaktadır.

## 3. Javascript teki veri tipleri nelerdir açıklayınız

JavaScript'te veri tipleri, primitive (ilkel) ve ilkel olmayan (non-primitive) olarak iki ana başlığa ayrılır.

 ## ilkel veri türü

 1. Primitive veriler, daha az karmaşık ve tek bir veriyi temsil eden yapılardır.

   1. **Number**: Sayı şeklindeki verileri temsil eder.
   1. **String**: Metin şeklindeki verileri temsil eder.
   1. **Boolean**: True veya False değerlerini alır. 
   1. **Undefined**:: Var olan değişkene atanmamış olan değeri temsil eder.
   1. **Null**: Temsil ettiği bir şey yoktur. Boş değer anlamına gelir.
   1. **Symbol**: Değişmeyen değerler oluşturur.

   ## ilkel olmayan veri türü
   
 1. ilkel olmayan veriler, daha complex yapılandırma için kullanılmaktadır. İlkel olmayan veriler, referans tipleridir. Bellekte belirli referanslarla saklanır ve bu referanslar sayesinde erişim sağlanır.

   1. **Object**:  Özellikler (properties) ve metodları içeren komplike verilerdir. Key- value ilişkisi ile çalışmaktadır.
   1. **Array**: Index numaralarına göre sıralanmış liste elemanlarıdır. Bİrden çok değeri tutar.
   1. **Function**: : Belirli bir görevi yerine getirmek için kullanılan scoplara sahip kod bloklarını temsil eder.

## 4. null ile undefined arasıdaki fark nedir açıklayınız

### null:

- `null`, bir değişkenin bilinçli olarak atanmamış veya boş bir değere sahip olduğunu belirtmek için kullanılır.
- Bir değişkenin `null` değerine sahip olması, programcının bilinçli bir şekilde bir değer atamadığını gösterir.
- `typeof null` ifadesi "object" döner, ancak bu bir dil hatasıdır ve `null` aslında bir nesne değildir.

```javascript
let degisken = null;
console.log(degisken); // null
console.log(typeof degisken); // "object" (ancak bu bir hata)
```

### undefined:

- `undefined`, bir değişkenin henüz bir değer atanmamış olduğunu gösterir. Değer belirsizdir.
- Bir değişken tanımlanmış ve değeri yoksa, JavaScript otomatik olarak  `undefined` değerini atar.
- `null` gibi, typeof `undefined` ifadesi "undefined" döner.

Temel farklar :

- `null`bir değer olmasına rağmen undefined, bir türdür.
- `null`'ın değeri ve türü aynıdır; yani, null bir değeri temsil eder.
- `undefined`, bir değişkenin tanımlı olmama durumunu ifade eder ve değeri `undefineddir`.
-JavaScript, değişkenlere başlangıçta otomatik olarak `undefined` değerini atar.
- `null` ve `undefined` genellikle koşullu ifadelerde veya veri işleme işlemlerinde kullanılır.

## 5. NaN nedir açıklayınız

`NaN`,  "Not-a-Number"ın demektir. Sayısal işlemlerde istenen çıktıya ulaşılamadığı veya sayısal olmayan bir değerlerle matematiksel işlem yapılmak istendiğinde kullanılır. JavaScript'te `NaN`, özel değerdir ve sayı olmayan bir işlemin sonucunu temsil eder.

## 6. Javascript’te yorum satırı eklemenin kaç farklı yolu vardır

 Yorumlar, kodun okunabilirliğini arttırarak birden fazla kişinin çalıştığı veya bireysel olan projelerde açıklayıcı notlar veya değiştirilebilir alanlar sağlar. Yorum satırı eklemenin birçok yolu varıdır. 

 1. Tek Satırlı Yorum:
  Genellikle iki tane eğik çizgi (//) kullanılır. Satırı sonuna kadar yorum olarak alır.
 
```javascript
   // Tek satırlık yorum
   let value = "Gamze"; // Değişkene bir değer atandı.
   ```
2. Çok Satırlı Yorum:
    Başlangıç işareti /* ve bitiş işareti */ olarak belirlenir.

   ```javascript
   /*
   Çok
   satırlı
   yorum
   .
   */
   ```
   
## 7. Global değişken ne demektir açıklayınız

Programın herhangi bir yerinde tanımlanmış olan değişkenin tekrar yer fark etmeksizin kullanılbildiği değişken türüdür. Her fonksiyon ve kod bloğu içerisinden erişim sağlabilir. Bu durum veri paylaşımı açısından avantajken kod karmaşıklığına sebep olması ve hata ayıklamanın zorlaşmasına sebeb olması sebebiyle dikkatli kullanılmalıdır.

```js

// Global değişken tanımlama
var globalValue = "Bu bir global değişkendir.";

// Fonksiyon içinde global değişken kullanımı
function showGlobalValue() {
    console.log("Global Değişken: " + globalDegisken);
}

// Fonksiyon çağrısı
globalDegiskeniGoster();
```

## 8. Javascript’te this anahtar kelimesi nedir açıklayınız

JavaScript'te `this` içerisinde kullanıldığı nesneyi işaret eder. Ancak `this` kullanıldığı yere göre değişik amaçlara hitap edebilir.

 1. Global Bağlam :

```js

console.log(this); // Tarayıcı ortamında: window objesi, Node.js ortamında: global objesi
```
    
 2. Fonksiyonlar :

```js

function useThisFunc() {
    console.log(this); // Tarayıcı ortamında: window objesi, Node.js ortamında: global objesi
}
exampleFunction();
```

 3. Objeler :
    
```js

var obj = {
    name: "Gamze",
    readName: function() {
        console.log(this.name); // "Gamze"
    }
};
obj.readName();
```
 4. Constructor Fonksiyonları:

 ```js

function Age(age) {
    this.name = age;
    console.log(this); // Age nesnesini gösterir.
}
var person1 = new Person('23');
```

## 9. == ile === farkını örnekler ile açıklayınız

1. == (Loose Equality):
Yalnızca değerleri karşılaştırır.
```js

console.log(1 == "1"); // true
console.log(true == 1); // true
console.log(null == undefined); // true

```
2. === (Strict Equality):
Hem değeri hem de veri tiplerini karşılaştırır.

```js

console.log(1 === "1"); // false
console.log(true === 1); // false
console.log(null === undefined); // false


```





  
