# salaam-academy-js-fundamentals-exam
### prompt ga oid
1.Foydalanuvchidan oylik maoshini so'rash kerak, va unga yillik maoshini hisoblash berish kerak.
##### Yechim
```javascript
var maosh = prompt("Oyligingiz qancha?");
var maoshSon = parseInt(maosh);
var yillikMaosh = maoshSon * 12;
alert(yillikMaosh);
```

---

2.Foydalanuvchidan oylik maoshini so'rash kerak, va unga yilda qancha pul yig'adi hisoblash berish kerak. Foydalanuvchi faqat 10% pulni saqlab qoladi, 90% ni esa sarflaydi.

---

3.Foydalanuvchidan ismini so'rang. So'ng "Assalomu alaykum `ISM`" deb chiqarib bering. `ISM` o'rniga ismini qo'yasiz.

---

4.Foydalanuvchidan joriy yilni so'rang. So'ng joriy oyni so'rang. So'ng joriy kunni so'rang.
Keyin esa 1970 yildan nechi kun o'tganini hisoblab bering.

---

### o'zgaruvchilarga oid

1.Benzinning narxi bor. Va har 100 kilometrga qanchadir benzin sarflanadi. Siz qanchadir pulga benzin oldingiz. Nechi kilometrga yetadi?
```js
var narx = 4500;
var har100kmga = 9;
var pul = 120000;

alert(??????);
```

2.Do'koningiz bor. Har bir molning ustiga 15% qo'yib sotasiz. Har kun 100000 so'mga ga pechenye sotasiz. Nechi kunda 500000 so'm sof foyda ko'rasiz?
```js
var sotilish = 100000;
var ustigaFoiz = 15;

alert(?????);
```

3.Firmangiz har oy qanchadir pul topadi. Reklamaga qanchadir pul sarflaydi. Ishchilarning oyligiga qanchadir pul sarflaydi. Bir yilda qancha pul yig'iladi?
```js
var kirim = 1100000;
var reklama = 1000;
var oyliklar = 700000;

alert(?????);
```

---

### if (agar)
1.Foydalanuvchidan yoshni so'raydigan dasturni tuzing. Yosh 50 dan y uqori bo'lsa, dastur "Siz kattasiz" deb chiqarib berishi kerak. Yosh 50 dan past bo'lsa "Siz yoshsiz" deb chiqarib berishi kerak.

---

2.Somsani narxini so'raydigan dastur. Narx 3000 dan yuqori bo'lsa - dastur "qimmat" deb chiqarib bersin. 3000 dan arzon bo'lsa - "arzon" deb chiqarib bersin.

---

3.Parolni tekshiradigan dastur. Foydalanuvchi "sarimsoqpiyoz" parolini kiritgan bo'lsa, u bilan salomlashing. Boshqa narsa kiritgan bo'lsa - unga "Xato!" deb yozing.

---

4.Foydalanuvchi yoshini kiritish kerak. Yoshi 0 dan 30 gacha bo'lsa, unga "yoshsiz" deb yozing. Yoshi 30 dan 60 gacha bo'lsa, unga "kattasiz" deb yozing. Yoshi 60 dan yuqori bo'lsa, unga siz qarisiz deb yozing.

---

5.Foydalanuvchidan ismini so'rang. Ismi "Ali" bo'lsa, unga "Salom og'a" deb yozing. Ismi "Ahmad" bo'lsa, unga "Ko'rinmayapsan dostim, nima qilyapsan?" deb yozing.

---

### funksiya (function)

1.Foydalanuvhi bilan salomlashadigan funksiyani tuzing.

Misol:
```js
function salomlashish(ism) {
  // ...
  // ...
}
```
---

2.Ikkita sonni ko'paytiradigan funksiyani tuzing. Natijani alert qilib chiqarib berish kerak.

```js
function kopaytirish(x, y) {
  // ...
  // ...
}
kopaytirish(4, 5);
```
---

3.Foydalanuvchidan joriy yilni so'rang. So'ng joriy oyni so'rang. So'ng joriy kunni so'rang. Keyin esa 1970 yildan nechi kun o'tganini hisoblab bering. Funksiyadan foydalanishingiz shart. Propmt va alert kerak emas.

Funksidan foydalanish misoli:
```js
hisob(2018, 11, 29);
```

### DOM

1.`input` va `button` qo'ying. Tugmaga bosganingizda `input`dagi yozuv `alert` oynachasiga chiqishi kerak.  
`onclick="..."` dan foydanaling.

---

## addEventListener
Quyidagi topshiriqlarda `addEventListener` dan foydanalish kerak.

---

1.`input` va `button` qo'ying. Tugmaga bosganingizda `input`dagi yozuv `alert` oynachasiga chiqishi kerak.
