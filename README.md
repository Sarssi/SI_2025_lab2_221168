Втора лабораториска вежба по Софтверско инженерство

Сара Симјаноска, бр. на индекс 221168

Control Flow Graph

![Control Flow Graph  drawio](https://github.com/user-attachments/assets/59fd39a4-ce81-4524-9135-dfa8c67f816c)

Цикломатска комплексност

Цикломатската комплексност на овој код е 9.
Цикломатската комплексност ја пресметуваме според бројот на предикатни јазли во функцијата checkCart, користејќи ја формулата:
CC = P + 1, каде што P е бројот на предикатни јазли.

Во функцијата ги има следниве предикатни јазли:
if (allItems == null)
for (int i = 0; i < allItems.size(); i++)
if (item.getName() == null || item.getName().length() == 0)
if (item.getPrice() > 300 || item.getDiscount() > 0 || item.getQuantity() > 10)
if (item.getDiscount() > 0)
if (cardNumber != null && cardNumber.length() == 16)
for (int j = 0; j < cardNumber.length(); j++)
if (allowed.indexOf(c) == -1)

Вкупно 8 предикатни јазли, цикломатска комплексност = 8 + 1 = 9.
