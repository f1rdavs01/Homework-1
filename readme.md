# DOM (Document Object Model)

DOM, yoki Document Object Model, veb-dasturlashda HTML, XML yoki XHTML hujjatlarini nazorat qilish uchun ishlatiladigan bir modeldir. Bu README fayli, DOM haqida umumiy ma'lumotlarni va uni ishlatishni o'rganish uchun bir boshlang'ich qadam bo'ladi.

## Nima Uchun DOM?

DOM, veb-sahifalarda dinamik ravishda ma'lumotlarga murojaat qilish va ulardan foydalanish imkonini beradi. U HTML yoki XML-hujjatlardagi obyektlarni tashkil etadi va ularga JavaScript yoki boshqa skript tillari orqali murojaat qilishga imkon beradi.

## DOM Elementlari

DOM-ni tushunish uchun quyidagi asosiy element turlarini bilish kerak:

1. **Document**: DOM-ni boshqarish uchun asosiy obyekt.
2. **Element**: Hujjatning biror elementini ko'rsatadigan obyekt.
3. **Attribute**: Elementning atributlarini ko'rsatadigan obyekt.
4. **Text**: Elementning matnini ko'rsatadigan obyekt.

## JavaScript orqali DOM-ni ishlatish

JavaScript yoki boshqa skript tili orqali DOM bilan ishlash quyidagi bosqichlarda amalga oshiriladi:

1. **Elementni topish**:

```javascript
var element = document.getElementById("elementId");
```
