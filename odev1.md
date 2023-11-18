# Odev

## 1. JavaScript nedir ve tarihsel gelişiminden bahsedin

> JavaScript, web tarayıcılarında çalışan ve web sayfalarına dinamik özellikler kazandıran bir programlama dilidir. 
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

   - Java: Java, bir nesne yönelimli programlama (OOP) dilidir. Sunucu uygulamarında kullanılmaktadır.
   - JavaScript: JavaScript, bir tarayıcı tarafında çalışan bir dildir.Bu v8 ile gerçekleşmektedir. İstemci-sunucu işlemlerini barındırır.

## 3. Javascript teki veri tipleri nelerdir açıklayınız

JavaScript'te veri tipleri, primitive (ilkel) ve ilkel olmayan (non-primitive) olarak iki ana başlığa ayrılır.

 ## ilkel veri türü

   1. **Number**: Sayı şeklindeki verileri temsil eder.
   1. **String**: Metin şeklindeki verileri temsil eder.
   1. **Boolean**: True veya False değerlerini alır. 
   1. **Undefined**:: Var olan değişkene atanmamış olan değeri temsil eder.
   1. **Null**: Temsil ettiği bir şey yoktur. Boş değer anlamına gelir.
   1. **Symbol**: Değişmeyen değerler oluşturur.

   ## ilkel olmayan veri türü

   1. **Object**:  Özellikler (properties) ve metodları içeren komplike verilerdir. Key- value ilişkisi ile çalışmaktadır.
   1. **Array**: Index numaralarına göre sıralanmış liste elemanlarıdır. Bİrden çok değeri tutar.
   1. **Function**: : Belirli bir görevi yerine getirmek için kullanılan scoplara sahip kod bloklarını temsil eder.

## 4. null ile undefined arasıdaki fark nedir açıklayınız

### null:

- `null`, bir değişkenin bilinçli olarak atanmamış veya boş bir değere sahip olduğunu belirtmek için kullanılır.

### undefined:

- `undefined`, bir değişkenin henüz bir değer atanmamış olduğunu gösterir. Değer belirsizdir.

Temel farklar :

- `null`bir değer, undefined ise bir türdür.
- `null` bir değer temsil eder.
- `undefined`, bir değişkenin durumunu temsil eder.
-Değişkenler default olarak `undefined` değerini alır.

## 5. NaN nedir açıklayınız

`NaN`,  "Not-a-Number"ın demektir. Sayısal,işlemsel hataları simgeler.

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
   merhaba
   ben
   gamze
   .
   */
   ```
   
## 7. Global değişken ne demektir açıklayınız

Programın herhangi bir yerinde tanımlı ve herhangi bir yerden erişimi mümkün olan değişken türleridir.

```js
var globalValue = "Global value";

function showGlobalValue() {
    console.log("Global value: " + globalValue);
}
showGlobalValue();
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
```
2. === (Strict Equality):
Hem değeri hem de veri tiplerini karşılaştırır.

```js
console.log(1 === "1"); // false
```

## 10. let var const farkını tablo yapınız


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

- **Normal Fonksiyon:**
  
  ```javascript
  const sum = function(a, b) {
    return a + b;


## 2. `this` Bağlamı

**Arrow Fonksiyon:**
Arrow fonksiyonlarda this, fonksiyon nasıl çağırıldığına bakılmaksızın yeni bir değere bağlanmaz. this her zaman onu çevreleyen kodun this değeriyle aynı değerde olur.

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

1. `case` Etiketleri :
   `switch` için bir `case` ve onun değeri ardından `break` gibi bir komut kullanılır.
```javascript
var secim = parseInt(prompt("Departman seçiniz: 1. Yazılım, 2. Satış, 3. İnsan Kaynakları"));

switch (secim) {
    case 1:
        alert("Yazılım departmanına hoş geldiniz");
        break;
    case 2:
        alert("Satış departmanına hoş geldiniz");
        break;
    case 3:
        alert("İnsan Kaynakları departmanına hoş geldiniz");
        break;
    default:
        alert("Geçersiz seçim. Lütfen doğru bir seçenek giriniz.");
        break;
}

## 13. Pure fonksiyon ne demektir açıklayınız

Pure türkçe kelime anlamı ile de saf demeiktir. Pure fonksiyonların sonucu alınan paramtereye bağlı olarak değişmektedir. Fonksiyonlarda dışardan static bir değer alınması durumunda asenkron durumlarda sıkıntılar ortaya çıkmaktadır. Çözüm olarak değişkenlerin parmetre olarak alınması ve fonksiyon içinde kullanılması düşünülebilir ki bu durum pure fonksiyon olarak açıklanmaktadır.

## 14. Rest operatör nedir örnekle açıklayınız

```javascript
const employees = [
  { id: 1, name: 'Gamze', department: 'HR', salary: 50000 },
  { id: 2, name: 'Gaye', department: 'Engineering', salary: 75000 },
  { id: 3, name: 'Cemil', department: 'Marketing', salary: 60000 }
];

const newEmployee = { id: 4, name: 'Halil', department: 'Finance', salary: 70000 };
const updatedEmployeesAdd = [...employees, newEmployee];

console.log(updatedEmployeesAdd);

const employeeIdToUpdate = 2;
const updatedSalary = 80000;

const updatedEmployeesSalary = employees.map(employee => {
  if (employee.id === employeeIdToUpdate) {
    return { ...employee, salary: updatedSalary };
  }
  return employee;
});

console.log(updatedEmployeesSalary);

   ``` 
Yukarıdaki örnekte `updatedEmployeesAdd` değişkenine rest, diğer adıyla spread operetörü ile mevcut olan tüm çalışanlar kopyalanmış ve yeni bir çalışan eklenmiştir. Aynı zamanda spread operetörünün ikinci bir işlevi olan güncelleme işlemi içinse `updatedEmployeesSalary` değişkeni map fonksiyonu ile seçili id'ye sahip çalışanın maaş değeri güncellenmiştir.

## 15. Object destructuring nedir örnekle açıklayınız
```javascript
const employee = {

  id: 1,
  name: 'Cemil',
  department: 'Engineering',
  salary: 350000
};

// Object destructuring 
const { id, name, department, salary } = employee;

console.log(id);   
console.log(name);     
console.log(department);
console.log(salary);     

   ```
`object destructuring` yukarıdaki örnekte de görüldüğü gibi bir nesnedeki özelliklerin ayrı değişkenlere atanmasında kullanılan bir özelliktir. Nesne içinden özelliği ayrıştırır. Gereksiz tanımlamaları önler.

## 16. 2 elemanlı bir objeyi 6 farklı şekilde oluşturunuz

1. Manuel 
 ```javascript
const simplifiedEmployee1 = {
  id: employeeId,
  name: employeeName
};
   ```

2.reduce() 
   
```javascript
const simplifiedEmployee2 = Object.keys(employee).slice(0, 2).reduce((obj, key) => {
  obj[key] = employee[key];
  return obj;
}, {});

   ```

3.Object.create():

```javascript
const employeePrototype = { name: '', position: '' };
const employee4 = Object.create(employeePrototype);
employee4.name = 'Gaye';
employee4.position = 'Analyst';
   ```

4.Object Constructor

```javascript
const employee4 = new Object();
employee4.name = 'Gamze';
employee4.position = 'Engineering';

   ```

5.Fonksiyon ile Oluşturma:

```javascript
function createEmployee(name, position) {
    const employee5 = {};
    employee5.name = name;
    employee5.position = position;
    return employee5;
}

const employee5 = createEmployee('Gamze', 'Coordinator');

   ```

6.ES6 Destructuring ile Oluşturma:

```javascript
const name = 'Mustafa';
const position = 'Manager';
const employee6 = { name, position };
   ```

## 17. 2 elemanlı bir objenin key ve value değerlerinin karakter sayısı ile 2 farklı döngü methodu kullanarak yeni bir obje oluşturunuz

```javascript
const employee = {
    name: 'Gamze',
    position: 'Developer'
};

// 1. for...in döngüsü
const newObj1 = {};
for (const key in employee) {
    if (employee.hasOwnProperty(key)) {
        newObj1[key] = employee[key].length;
    }
}

// 2. Object.entries() ve forEach kullanımı
const newObj2 = {};
Object.entries(employee).forEach(([key, value]) => {
    newObj2[key] = value.length;
});

console.log(newObj1); // { name: 5, position: 9 }
console.log(newObj2); // { name: 5, position: 9 }


   ```

## 18. Cookie, local storage ve session storage farkını tablo yapınız

| Özellik                  | Cookie                 | Local Storage          | Session Storage        |
|--------------------------|------------------------|------------------------|------------------------|
| **Saklama Kapasitesi**   | 4 KB (genel)      | 5 MB (tarayıcıya bağlı) | 5 MB (tarayıcıya bağlı) |
| **Veri Saklama Yeri**    | Tarayıcı ve Sunucu     | Tarayıcı               | Tarayıcı               |
| **Veri Saklama Süresi**  | Belirtilebilir (ayarlanabilir), varsayılan olarak tarayıcı oturumu süresince | Kalıcı (tarayıcı temizlenmediği sürece) | Oturum süresince (tarayıcı penceresi kapatıldığında silinir) |
| **Tarayıcıdan İletişim** | Otomatik olarak her HTTP isteği ile sunucuya gönderilir | Sunucuya gönderilmez, sadece tarayıcı içinde kullanılır | Sunucuya gönderilmez, sadece tarayıcı içinde kullanılır |
| **Kullanım Alanı**       | Genelde oturum yönetimi ve kullanıcı tercih bilgileri gibi küçük verilerin saklanması | Tarayıcıda kalıcı olarak saklanması gereken veriler (örneğin kullanıcı tercihleri) | Bir tarayıcı oturumu boyunca geçici olarak saklanması gereken veriler |
| **JavaScript Erişimi**   | Sınırlı (HttpOnly flag ile sadece sunucu tarafından okunabilir ve yazılabilir) | Evet, JavaScript tarafından okunabilir ve yazılabilir | Evet, JavaScript tarafından okunabilir ve yazılabilir |


## 19. asenkron ve senkron işlem farkı nedir

Asenkron işlemler ve senkron işlemler arasındaki en temel fark senkron işlemler adım adım gerçekleşirken, asenkron işlemler eş zamanlı olarak çalışabilmektedir.
Senkron işlemler adım adım gerçekleşirken asenkron işlemler bir işlemin tamamlanmasını beklemeden bir sonraki işlemi gerçekleştirebilmektedir.
Asenkron işlemler, zaman alan ve etkileşim gerektiren işlemlerde tercih edilmektedir.
Senkron işlem blokları daha basitken asenkron işlemlerde call back fonksiyonları, promiseler veya async await gibi yönetimler tercih edilmektedir.

## 20. promise nedir ve neden ihtiyaç duyarız

 Promise kelime anlamı olarak da söz demektir. Asenkron programlamanın yönetilmesinde kullanılan bir nesnedir. Promise, program içerisindeki değerin gelecek zamanda alacağı değeri temsil eder. Aynı zamanda hata durumu için de kullanılabilir.
Promise yapısına ihtiyaç durulmasının başlıca sebepleri:
 Asenkron işlemlerde zaman alan durumlar söz konusu olduğu için callbackler ile problemler çözülebilmektedir ancak callback hell sorunu sebebiyle derinleşen ve karmaşık bir hal alan kod satırlarının önüne promise yapısı ile geçilebilmektedir.
  Asenkron işlemler birbirini takip ederek değil, biri bitmeden diğeri başlayan işlemler olduğundan promisler sayesinde birinci işlemin bitmesi ardından ikincinin gerçekleşeceği sözünü verebilmektedir.
  Aynı zamanda promisler reject ile başarısız durumların yönetilmesi imkanı da sunabilmektedir.

## Array Soruları Ödev 2 var dolap = ["Shirt", "Pant","TShirt"];

Array Soruları Ödev 2 var dolap = ["Shirt", "Pant","TShirt"];

### 1.dolap arrayindeki son elemanı silip consola yazdırın
### 2. dolap arrayindeki ilk elamanı silip yerine “Hat” elemanını gönderip consola yazdırın
### 3. dolap değişkeninin array olup olmadığını kontrol edin ve sonucu bir değişkene eşitleyin
### 4. dolap arrayinde “Pant” elemanın olup olmadığını 3 farklı method ile kontrol edin
### 5. dolap arrayindeki elemanların karakter sayısını toplayıp geriye döndürecek fonksiyonu yazın
### 6.dolap arrayindki tüm elemanları büyük harfe çevirip yeni bir değişkene 3 farklı yöntemle atayın
### 7. dolap arrayini index sayıları key olacak şekilde objeye çeviriniz
### 8. slice ile splice farkı nedir

  ```javascript
var dolap = ["Shirt", "Pant", "TShirt"];

// Soru 1: dolap arrayindeki son elemanı silip consola yazdırın
var removedLastItem = dolap.pop();
console.log("Removed the last item", removedLastItem);

// Soru 2: dolap arrayindeki ilk elamanı silip yerine “Hat” elemanını gönderip consola yazdırına
var removedFirstItem = dolap.shift();
dolap.unshift("Hat");
console.log("Removed the first item and added 'Hat':", removedFirstItem);

// Soru 3: dolap değişkeninin array olup olmadığını kontrol edin ve sonucu bir değişkene eşitleyin
var isArray = Array.isArray(dolap);
console.log("Is 'dolap' variable an array?", isArray);

// Soru 4:  dolap arrayinde “Pant” elemanın olup olmadığını 3 farklı method ile kontrol edin
var includesMethod = dolap.includes("Pant");
var indexOfMethod = dolap.indexOf("Pant") !== -1;
var someMethod = dolap.some(item => item === "Pant");
console.log("Using includes method:", includesMethod);
console.log("Using indexOf method:", indexOfMethod);
console.log("Using some method:", someMethod);

// Soru 5:  dolap arrayindeki elemanların karakter sayısını toplayıp geriye döndürecek fonksiyonu yazın
function totalCharacterCount(array) {
  return array.reduce((total, item) => total + item.length, 0);
}

console.log("Total character count:", totalCharacterCount(dolap));

// Soru 6: dolap arrayindki tüm elemanları büyük harfe çevirip yeni bir değişkene 3 farklı yöntemle atayın
var upperCaseArray1 = dolap.map(item => item.toUpperCase());
var upperCaseArray2 = dolap.map(function(item) {
  return item.toUpperCase();
});
var upperCaseArray3 = dolap.map(String.prototype.toUpperCase);
console.log("Uppercase array (Method 1):", upperCaseArray1);
console.log("Uppercase array (Method 2):", upperCaseArray2);
console.log("Uppercase array (Method 3):", upperCaseArray3);

// Soru 7: dolap arrayini index sayıları key olacak şekilde objeye çeviriniz
var wardrobeObject = Object.fromEntries(dolap.entries());
console.log("Wardrobe as an object:", wardrobeObject);

// Soru 8: slice ile splice farkı
// - slice: Array'i parçalayarak yeni bir array oluşturur.
// - splice: Array'e eleman ekler, çıkarır.


   ```
   
## const arr = [1,2,3,4,5,6,7,7,8,6,10];

### arrayindeki yinelenen sayıları bulun
  ```javascript



   ```

### arrayindeki tüm yinelenen sayıları silip yeni bir arrayi 2 farklı method ile oluşturun

```javascript
const arr = [1, 2, 3, 4, 5, 6, 7, 7, 8, 6, 10];

function findDuplicateNumbers(arr) {
  const seen = [];
  const duplicateNumbers = [];

  arr.forEach(number => {
    if (seen.includes(number)) {
      duplicateNumbers.push(number);
    } else {
      seen.push(number);
    }
  });

  return duplicateNumbers;
}

const result = findDuplicateNumbers(arr);
console.log("Yinelenen Sayılar:", result);
   ```

### arrayindeki en yüksek ve en düşük değeri 2 farklı methodla bulun

```javascript
const arr = [1, 2, 3, 4, 5, 6, 7, 7, 8, 6, 10];

arr.sort((a, b) => a - b); // Küçükten büyüğe sırala

const minNumber = arr[0];
const maxNumber = arr[arr.length - 1];

console.log("En düşük değer:", minNumber);
console.log("En yüksek değer:", maxNumber);

   ```

```javascript
const arr = [1, 2, 3, 4, 5, 6, 7, 7, 8, 6, 10];

const maxNumber = Math.max(...arr);
const minNumber = Math.min(...arr);

console.log("En yüksek değer:", maxNumber);
console.log("En düşük değer:", minNumber);


   ```

## Kod Çıktıları

```javascript
// Bu kodun çıktısı nedir neden ?
function job() {
    return new Promise(function(resolve, reject) {
        reject();
}); }
let promise = job();
promise
.then(function() {
    console.log('Success 1');
})
.then(function() {
    console.log('Success 2');
})
.then(function() {
    console.log('Success 3');
})
.catch(function() {
    console.log('Error 1');
})
.then(function() {
    console.log('Success 4');
});
   ```
  
KOD ÇIKTISI:

```javascript
Error 1
Success 4
   ```

Yukarıdaki kodda job fonksiyonu promise döndürmektedir ve `reject` ile reddedilmiştir. Bu nedenle 1. blok atlanır.
2. blok da bir önceki işlem başarasız olduğu için atlanacaktır ve aynı durum 3. blok için de geçerlidir.
4. blok da job fonksiyonu reject ile hata ile sonuçlandığı için bu blok çalışır. Error 1 mesajı konsola yazdırlır.
5. blok da kendinden önceki işlem başarılı olduğudan çalışacak ve Success 4 çıktısını verecektir.

```javascript
// Bu kodun çıktısı nedir neden ?
function job(state) {
    return new Promise(function(resolve, reject) {
        if (state) {
            resolve('success');
        } else {
            reject('error');
        }
}); }
let promise = job(true);
promise
.then(function(data) {
    console.log(data);
    return job(true);
})
.then(function(data) {
    if (data !== 'victory') {
        throw 'Defeat';
    }
    return job(true);
})
.then(function(data) {
    console.log(data);
})
.catch(function(error) {
    console.log(error);
    return job(false);
})
.then(function(data) {

console.log(data);
    return job(true);
})
.catch(function(error) {
    console.log(error);
    return 'Error caught';
})
.then(function(data) {
    console.log(data);
    return new Error('test');
})
.then(function(data) {
    console.log('Success:', data.message);
})
.catch(function(data) {
    console.log('Error:', data.message);
});
   ```
ÇIKTI:
```
success
Defeat
error
Error caught
Success: test
```
 1.Kod incelendiğinde ilk then bloğunda `job(true)` sebebiyle 'success' mesajı konsola yazdırılır. Return ettiği job(true) fonksiyonunu döndürür.
 2.İkinci then bloğunda data 'success' e eşit ve victory'ye eşit olmadığından throw içine girerek 'Defeat' yazdırılır. 
 3.Throw sonrası durumun `reject` olması sebebiyle işlem durdurulur ve `catch` bloğua yönlendirilir. Return edilen job(false) döndürülür.
 4.Bir önceki işlemin hatayla sonuçlanması durumundan bu blok atlanır ve `catch` bloğuna atlanılır. 
 5.Önceki işlem hatayla sonuçlandığı için ekrana `error` çıktısı verilir ve 'Error caught' döndürülür.
 6. Bu then bloğunda bir önceki işlemde çıktı olan data ekrana yazdılır ve job(true) döndürülür.
 7.Son then bloğu da bir önceki işleminden data alınır(test) ve ekrana yazdırılır.


