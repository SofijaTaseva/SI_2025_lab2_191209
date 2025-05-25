Име: Софија
Презиме: Тасева
Индекс: 191209

Control Flow Graph
![image](https://github.com/user-attachments/assets/9d7e7a0c-500d-47da-b943-70200be50e2a)


Ciklomatska Kompleksnost
M = E − N + 2P -> Formula
E-edges N-nodes P-Connected Components

Main control structures:
1-if (allItems == null)
2-for (i < allItems.size())
3-if (item.getName() == null || item.getName().length() == 0)
4-if (item.getPrice() > 300 || item.getDiscount() > 0 || item.getQuantity() > 10)
5-if (item.getDiscount() > 0) → else
6-if (cardNumber != null && cardNumber.length() == 16) → else
7-for (j < cardNumber.length())
8-if (allowed.indexOf(c) == -1)

N-16
E-19
P-1 - edna komponenta 1 funckija

M = E − N + 2P
M = 19 − 16 + 2×1
M = 3 + 2 = 5
M=5

Every Statement Критериум
Minimum broj na testovi za site possible statements = 3
test slucaj 1 - Valid Inputs, No Discounts
test slucaj 2 – Invalid Item Name
test slucaj 3 - – Discounted Item + Card Validation

Multiple Condition Criteria
3 prosti uslovi - se dobiva 2^3=8kombinacii
Price>300 Discount>0 Quantity>10
