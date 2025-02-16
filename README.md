# ImageTextExtractor
# Tasvirdan Matn Ajratish

Bu loyiha tasvirdagi matnni ajratib olish uchun ishlatiladi. Dastur ikki xil usulda natija chiqaradi:
- **Konsolda natija chiqarish** (oddiy)
- **Brauzer orqali natija chiqarish** (PyWebIO yordamida)

## Loyihadagi fayllar

- `tasvir_matn.py` – Konsolda natijani chiqaradi.
- `brauzerda.py` – PyWebIO orqali natijani brauzerda chiqaradi.
- `a-1704914000276-2x.jpg` – Test uchun matnli tasvir.

## Talab qilinadigan kutubxonalar

Loyihani ishlatish uchun quyidagi kutubxonalar kerak:

```sh
pip install pytesseract pillow pywebio opencv-python numpy
```

## Dasturni ishga tushirish

### Konsolda ishga tushirish

Agar natijani terminalda chiqarishni istasangiz:

```sh
python tasvir_matn.py
```

Bu kod test tasviridan matnni ajratib olib, konsolda chiqaradi.

### Brauzerda ishga tushirish

Agar natijani brauzerda ko‘rmoqchi bo‘lsangiz:

```sh
python brauzerda.py
```

So‘ngra brauzerda `http://localhost:8080` manziliga kiring va rasm yuklab, matnni ajratib oling.

## Foydalanish

1. Dasturni ishga tushiring.
2. Rasm yuklang (brauzerda ishlatganda).
3. Tasvirdan ajratilgan matn ekranga chiqariladi.

Bu loyiha **pytesseract** va **PyWebIO** kutubxonalari yordamida amalga oshirilgan.

Agar sizga yoqsa, ⭐ yulduzcha qo‘yishni unutmang! 😊

