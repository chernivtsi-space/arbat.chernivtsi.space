# Arbat

Live site: https://arbat.chernivtsi.space

## About
Arbat — готель у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Звукова хвиля, що стихає до рівної лінії з підписом «звукоізольовані номери»: шум зліва, тиша справа. Над великою назвою Arbat.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Безкоштовна парковка
- Кондиціонер
- Звукоізольовані номери
- Ресторан
- Цілодобова рецепція
- Пральня
- Прасування

## Check-in / check-out
Заїзд з 14:00; Виїзд 11:30–12:00

## Rooms (Booking.com room table; T&S and Панський Двір 2 from the official site)
- Стандартний двомісний номер — 1 широке двоспальне або 2 односпальні ліжка
- Напівлюкс — 1 широке двоспальне ліжко
- Напівлюкс «Комфорт» — 1 особливо широке двоспальне ліжко
- Сімейний люкс — 2 особливо широкі двоспальні ліжка
- Суперлюкс — 1 особливо широке двоспальне ліжко й диван-ліжко

## House rules (Booking.com)
- Чи можна з дітьми? Так, діти будь-якого віку. Дитяче ліжечко для дітей до 6 років — безкоштовно, додаткове ліжко — 200 грн за ніч. Обидва — на запит і за наявності.
- Чи можна з домашньою твариною? Ні, розміщення з тваринами заборонене.
- Як оплатити проживання? Лише готівкою. Після бронювання готель зв’яжеться щодо передоплати.

## Reviews
Booking.com 8.5/10 (810), Google 4.1/5 (801). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 95 279 5555
- Booking.com: https://www.booking.com/hotel/ua/arbat.html
- Google Maps: https://maps.google.com/?cid=18096583820836862573
- Address: вул. Сторожинецька, 82, Чернівці

## Sources
Booking.com listing text (description, rooms, breakfast, house rules; guest reviews ignored), captured 30.09.2026, plus the official site where there is one. Verbatim quotes: `facts.json` in the build scratchpad.

## Not published
Кількість номерів (цифра 7 — з джерела 2023 року, не актуальна), час заїзду/виїзду, зірковість, email, сайт, Instagram, формат і години ресторану.

## Forms
HotelOS (`ch-arbat`): `stay-request` (проживання). Документ `hotels/ch-arbat` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Фасад Резиденції митрополитів узимку: pexels.com/photo/17280127 (Андрій Копічевський)
- Вулиця в Чернівцях: pexels.com/photo/17268858 (Андрій Копічевський)
- Цегляні склепіння: pexels.com/photo/17280128 (Андрій Копічевський)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
