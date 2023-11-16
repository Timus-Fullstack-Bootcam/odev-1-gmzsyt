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

## 10. let var const farkını tablo yapınız

Aşağıda, JavaScript'te `let`, `var`, ve `const` değişken tanımlama anahtar kelimelerinin farklarını tablo halinde açıklamaya çalıştım:

# Değişken Tanımlama Anahtar Kelimeleri

Aşağıda, JavaScript'te yaygın olarak kullanılan değişken tanımlama anahtar kelimeleri olan `var`, `let`, ve `const` arasındaki temel farkları gösteren bir tablo bulunmaktadır.

| Özellik            | `var`                    | `let`                    | `const`                  |
| ------------------ | ------------------------ | ------------------------ | ------------------------ |
| **Kapsam**         | Fonksiyon kapsamı         | Blok kapsamı             | Blok kapsamı             |
| **Yeniden Atama**  | Yeniden atanabilir        | Yeniden atanabilir        | Yeniden atanamaz         |
| **Hoisting**       | Evet, hoisted             | Hayır     | Hayır  |
| **İlk Değer Atama** | İsteğe bağlı     | İsteğe bağlı    | Zorunlu                  |
| **Kapsam Dışında** | Global ve fonksiyon kapsamında| Sadece blok kapsamında  | Sadece blok kapsamında  |
| **Örnek Kullanım** | `var x = 1;`              | `let y = 2;`             | `const z = 3;`           |
| **Önerilen Kullanım** | Tercih edilmez  | Tercih edilir  | Tercih edilir (eğer tekrar atama olmayacaksa) |

## 11. Arrow fonksiyonun normal fonksiyondan farkları nelerdir

## 1. Sözdizimi (Syntax)

- **Arrow Fonksiyon:**
- 
  ```javascript
  const sum = (a, b) => a + b;
``

- **Normal Fonksiyon:**
- 
  ```javascript
  const sum = function(a, b) {
    return a + b;
``

## 2. `this` Bağlamı (Syntax)

**Arrow Fonksiyon:**
Arrow fonksiyonlarda this, fonksiyon nasıl çağırıldığına bakılmaksızın yeni bir değere bağlanmaz. this her zaman onu çevreleyen kodun this değeriyle aynı değerde olacaktır.

```

const function = () => {
    console.log(this); // Arrow fonksiyonunun bulunduğu kapsamdaki this'i alır.
};

```

**Normal Fonksiyon:**
Normal fonksiyonlar, kendi `this` bağlamını oluştururlar. Fonksiyonun nasıl çağrıldığına bağlı olarak `this` değeri değişebilir.

  ```javascript
function func() {
    console.log(this); // Normal fonksiyon kendi this bağlamını oluşturur.
}
};
```

## 3. Parametreler

**Arrow Fonksiyon:**
Arrow fonksiyonlarda, tek bir ifade varsa süslü parantezler kaldırılabilir ve parametre sayısı bir ise parantez kaldırılabilir.

 ```javascript
const square = a => a * a;
```

## 4. Reassignment

**Arrow Fonksiyon:**
Kendine ait `this` bağlamı olmadığı için yeniden atama yapılamaz.

**Normal Fonksiyon:**
`this` değiştirilebildiği için yeniden atama yapılabilir

 
## 5. `arguments` Erişimi

**Arrow Fonksiyon:**
Arrow fonksiyonları, `arguments` nesnesine erişemezler.

**Normal Fonksiyon:**
Normal fonksiyonlar, `arguments` nesnesine erişebilirler.

## 6. Constructor Kullanımı

**Arrow Fonksiyon:**
Arrow fonksiyonları, `constructor` yapısında kullanılamazlar.

**Normal Fonksiyon:**
Arrow fonksiyonları, `constructor` yapısında kullanılabilirler.

## 12. swich bloğu içinde hatasız nasıl değişken tanımlanır

  JavaScript'te bir `switch` ifadesi içinde değişken tanımlamanın iki ana noktası vardır. `case` etiketleri ile değişken tanımlama ve `switch` ifadesinin seçili değişkeni tanımlama.

1. `case` Etiketleri :
   `switch` ifadesi içinde değişkeni tanımlamak için, her `case` etiketi içinde `var`, `let` veya `const` anahtar kelimelerini kullanabilirsiniz. Bu şekilde tanımlanan değişkenler, yalnızca ilgili `case` etiketi içinde erişilebilir olacaktır. Örnek:

   ```javascript
   switch (sekil) {
     case "kare":
       let bildirim = "Kare seklini seçtiniz.";
       console.log(bildirim);
       break;

     case "daire":
       let bildirim = "Daire seklini seçtiniz."; // Hata: "mesaj" zaten tanımlandı
       console.log(bildirim);
       break;

     default:
       let bildirim = "Şekil seçtiniz"; // Hata: "mesaj" zaten tanımlandı
       console.log(bildirim);
   }
   ```

   Yukarıdaki örnekte zaten tanımlanmış olan bildirim değişkeni her case içerisinde tekrar tanımlanmıştır. Bu sebeple tekrar tanımlandığı alanlarda hata verir.

2. Değişkeni Önceden Tanımlama:
   `switch` ifadesinin dışında değişkeni tanımlamak ve daha sonra `case` etiketlerinde kullanmak bu hatayı ortadan kaldıracaktır.

   ```javascript
   let bildirim;

   switch (sekil) {
     case "kare":
       bildirim = "Kare seklini seçtiniz.";
       console.log(bildirim);
       break;

     case "daire":
       bildirim = "Daire seklini seçtiniz.";
       console.log(bildirim);
       break;

     default:
       bildirim = "Şekil seçtiniz";
       console.log(bildirim);
   }
   ```

   ## 13. Pure fonksiyon ne demektir açıklayınız

Pure türkçe kelime anlamı ile de saf demeiktir. Pure fonksiyonların sonucu alınan paramtereye bağlı olarak değişmektedir. Fonksiyonlarda dışardan static bir değer alınması durumunda asenkron durumlarda sıkıntılar ortaya çıkmaktadır. Çözüm olarak değişkenlerin parmetre olarak alınması ve fonksiyon içinde kullanılması düşünülebilir ki bu durum pure fonksiyon olarak açıklanmaktadır.

   ## 14. Rest operatör nedir örnekle açıklayınız

```javascript
   // Şirket çalışanları
const employees = [
  { id: 1, name: 'Gamze', department: 'HR', salary: 50000 },
  { id: 2, name: 'Gaye', department: 'Engineering', salary: 75000 },
  { id: 3, name: 'Cemil', department: 'Marketing', salary: 60000 }
];

const newEmployee = { id: 4, name: 'Halil', department: 'Finance', salary: 70000 };
const updatedEmployeesAdd = [...employees, newEmployee];

console.log(updatedEmployeesAdd);
/* Çıktı:
[
  { id: 1, name: 'Gamze', department: 'HR', salary: 50000 },
  { id: 2, name: 'Gaye', department: 'Engineering', salary: 75000 },
  { id: 3, name: 'Cemil', department: 'Marketing', salary: 60000 },
  { id: 4, name: 'Halil', department: 'Finance', salary: 70000 }
]
*/

const employeeIdToUpdate = 2;
const updatedSalary = 80000;

const updatedEmployeesSalary = employees.map(employee => {
  if (employee.id === employeeIdToUpdate) {
    return { ...employee, salary: updatedSalary };
  }
  return employee;
});

console.log(updatedEmployeesSalary);
*/

   ``` 
Yukarıdaki örnekte `updatedEmployeesAdd` değişkenine rest, diğer adıyla spread operetörü ile mevcut olan tüm çalışanlar kopyalanmış ve yeni bir çalışan eklenmiştir. Aynı zamanda spread operetörünün ikinci bir işlevi olan güncelleme işlemi içinse `updatedEmployeesSalary` değişkeni map fonksiyonu ile seçili id'ye sahip çalışanın maaş değeri güncellenmiştir.

   ## 15. Object destructuring nedir örnekle açıklayınız
```javascript
   // employee nesnesi
const employee = {
  id: 1,
  name: 'Cemil',
  department: 'Engineering',
  salary: 350000
};

// Object destructuring 
const { id, name, department, salary } = employee;

// Çıkartılan özellikleri kullanma
console.log(id);         // Çıktı: 1
console.log(name);       // Çıktı: Alice
console.log(department); // Çıktı: HR
console.log(salary);     // Çıktı: 50000

   ```
`object destructuring` yukarıdaki örnekte de görüldüğü gibi bir nesnedeki özelliklerin ayrı değişkenlere atanmasında kullanılan bir özelliktir. Nesne içerisinden istenen özelliklerin kullanılması aşamasında rol almaktadır. Yukarıdaki örnekte ise employee ile eşitlenmiş olan id, name, department ve salary propertyleri `object destructuring` ile ayıklanmıştır. 




  
