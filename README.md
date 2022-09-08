# ReactJs Interview Questions - ReactJs Interview Savollari O'zbekchada

## Savollar Jadvali
[React Yadrosi (Asosiy qismi)](#react-yadrosi(asosiy-qismi)---core-react)

1. [React nima?](#1-react-nima)
2. [Reactni asosiy xususiyatlarini nimalar?](#2-reactni-asosiy-xususiyatlarini-nimalar)
3. [Virtual DOM nima va u qanday ishlaydi?](#3-virtual-dom-nima-va-uqanday-ishlaydi)

## React Yadrosi(Asosiy qismi) - Core React

### 1. React nima?
>React - komponentalar asosida deklarativ(declarative) foydalanuvchi interfeysi (UI)ni yaratish uchun bepul va ochiq manbali Javascript kutubxonasi. React bir sahifali ilovalar(single-page applications, SPA) va mobil ilovalar yaratishi bilan mashhur. Reactning asosiy maqsadi keng qamrovli (extensive), tezkor(fast),  deklarativ(declarative), moslashuvchan(flexible) va sodda(simple) ilovalar yaratishda yordam berisgdir. 
>ReactJs 2011 yilda Facebook-da ishlaydigan dasturiy ta'minot muhandisi Jordane Walke tomonidan chiqarilgan. Kutubxona birinchi marta 2013 yil may oyida ochiq manbali kutubxona sifatida ommaga taqdim etilgan va hozirda veb-ishlab chiqish uchun eng ko'p ishlatiladigan frontend kutubxonalaridan biri hisoblanadi.

-----

### 2. Reactni asosiy xususiyatlarini nimalar?
>Reactning asosiy xususiyatlari quyidagilardir

>- JSX - JavaScript Syntax Extension
>- Virtual Document Object Model (VDOM)
>- Bir tomonlama malumotlarni uzatish(One-way Data Binding) 
>- Server-side rendering ni qo'llab quvatlaydi
>- Qayta foydalansa bo'ladigan va kompozitsiya qilinadigan UI componentalardan foydalaniladi
>- Oddiylik 
>- Conditional Statements 

-----

### 3. Virtual DOM nima va u qanday ishlaydi?

> DOM bu "Document Object Modal" atamasi bo'lib, ma'lumotlarni daraxt strukturasida saqlashning bir turi hisoblanadi. U ilova interfeysini ifodalaydi. Virtual DOM (VDOM) - bu dasturlash tushunchasi bo'lib, u erda foydalanuvchi interfeysining "virtual" ko'rinishi xotirada saqlanadi va Real DOM ​​bilan sinxronlashtiriladi. Bu shuni anglatadiki, bitta element brauzer DOMida(Real DOM) yaratilganda, u Virtual DOMda ob'ekt sifatida yaratiladi. Virtual DOM - bu xotiradagi Real DOMni ifodalovchi ob'ekt.

>React qaysi tugun o‘zgarganligini tekshirish uchun yangi Virtual DOM ob'ektini oldingi Virtual DOM ob'ekti bilan solishtirish uchun [ Diffing Algorithm](https://reactjs.org/docs/reconciliation.html#the-diffing-algorithm) algoritmidan foydalanadi va keyin Real DOMda o‘zgartirilgan qismlarni o'zgartirish orqali ilovada bitta qism o'zgartirilganda butun ilovani yangilash va sahifani qaytadan yuklashdan ancha tezroq ishlaydi.

>- Agar bola komponentlarining propslari asosiy komponentning yangilangan holatiga bog'liq bo'lsa, Browser(real) DOM virtual DOM kabi yangilanadi.
![1-xolat](/image/virtual-dom.png)

>- Agar bola komponentlarining rekvizitlari asosiy komponentning yangilangan holatiga bog'liq bo'lmasa, Browser(real) DOM virtual DOM bilan boshqacha yangilanadi.
![2-xolat](/image/virtual-dom-1.png)


-----

## Qo'shimcha 

Kamchiliklar yoki xatolarni topsangiz pull so'rovini yuborishingizni so'raymiz.
Taklif va mulohazalaringiz bo'lsa [Bizga murojat qiling](https://t.me/JahongirErgashev)
