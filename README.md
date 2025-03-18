# Number System Conversion - Practice Exercises

This repository contains 50 exercises to help you practice converting numbers between different bases. Mastering these conversions will strengthen your understanding of how computers represent numbers.

## 📌 Topics Covered
1. **Decimal to Binary**
2. **Decimal to Octal**
3. **Decimal to Hexadecimal**
4. **Binary to Decimal**
5. **Binary to Octal**
6. **Binary to Hexadecimal**
7. **Octal to Decimal**
8. **Octal to Binary**
9. **Octal to Hexadecimal**
10. **Hexadecimal to Decimal**
11. **Hexadecimal to Binary**
12. **Hexadecimal to Octal**

---

## 📘 How to Convert

### 🔹 Decimal to Binary (Base-10 → Base-2)
**Steps:**
1. Divide the decimal number by 2.
2. Record the remainder (0 or 1).
3. Repeat with the quotient until it becomes 0.
4. Read the remainders in reverse order.

**Example:** Convert **25**₁₀ to Binary.
```
25 ÷ 2 = 12, remainder = 1
12 ÷ 2 = 6, remainder = 0
6 ÷ 2 = 3, remainder = 0
3 ÷ 2 = 1, remainder = 1
1 ÷ 2 = 0, remainder = 1
```
**Result:** 25₁₀ = **11001**₂

---

### 🔹 Decimal to Octal (Base-10 → Base-8)
**Steps:**
1. Divide the decimal number by 8.
2. Record the remainder.
3. Repeat until the quotient is 0.
4. Read the remainders in reverse order.

**Example:** Convert **125**₁₀ to Octal.
```
125 ÷ 8 = 15, remainder = 5
15 ÷ 8 = 1, remainder = 7
1 ÷ 8 = 0, remainder = 1
```
**Result:** 125₁₀ = **175**₈

---

### 🔹 Decimal to Hexadecimal (Base-10 → Base-16)
**Steps:**
1. Divide the decimal number by 16.
2. Record the remainder.
3. Repeat until the quotient is 0.
4. Convert remainders to hexadecimal digits (0-9, A-F).

**Example:** Convert **254**₁₀ to Hexadecimal.
```
254 ÷ 16 = 15, remainder = 14 (E)
15 ÷ 16 = 0, remainder = 15 (F)
```
**Result:** 254₁₀ = **FE**₁₆

---

### 🔹 Binary to Decimal (Base-2 → Base-10)
Use the **Positional Value Method**.
Multiply each digit by its place value (powers of 2) and sum the results.

**Example:** Convert **1011**₂ to Decimal.
```
(1 × 2³) + (0 × 2²) + (1 × 2¹) + (1 × 2⁰)
= (1 × 8) + (0 × 4) + (1 × 2) + (1 × 1)
= 8 + 0 + 2 + 1 = 11
```
**Result:** 1011₂ = **11**₁₀

---

### 🔹 Binary to Octal (Base-2 → Base-8)
**Steps:**
1. Group binary digits into sets of three (from right).
2. Convert each group into its octal equivalent.

**Example:** Convert **101110**₂ to Octal.
```
101 110
101 → 5
110 → 6
```
**Result:** 101110₂ = **56**₈

---

### 🔹 Binary to Hexadecimal (Base-2 → Base-16)
**Steps:**
1. Group binary digits into sets of four (from right).
2. Convert each group into its hexadecimal equivalent.

**Example:** Convert **110110101010**₂ to Hexadecimal.
```
1101 1010 1010
1101 → D
1010 → A
1010 → A
```
**Result:** 110110101010₂ = **DAA**₁₆

---

## 📝 Practice Exercises

### 🔹 **Decimal to Binary**
1. Convert 18₁₀ to Binary.
2. Convert 43₁₀ to Binary.
3. Convert 97₁₀ to Binary.
4. Convert 256₁₀ to Binary.
5. Convert 512₁₀ to Binary.

### 🔹 **Decimal to Octal**
6. Convert 56₁₀ to Octal.
7. Convert 200₁₀ to Octal.
8. Convert 345₁₀ to Octal.
9. Convert 999₁₀ to Octal.
10. Convert 1024₁₀ to Octal.

### 🔹 **Decimal to Hexadecimal**
11. Convert 100₁₀ to Hexadecimal.
12. Convert 255₁₀ to Hexadecimal.
13. Convert 500₁₀ to Hexadecimal.
14. Convert 1023₁₀ to Hexadecimal.
15. Convert 4096₁₀ to Hexadecimal.

### 🔹 **Binary to Decimal**
16. Convert 1100₂ to Decimal.
17. Convert 101010₂ to Decimal.
18. Convert 111111₂ to Decimal.
19. Convert 1000001₂ to Decimal.
20. Convert 10101010₂ to Decimal.

### 🔹 **Binary to Octal**
21. Convert 111₂ to Octal.
22. Convert 1001₂ to Octal.
23. Convert 110101₂ to Octal.
24. Convert 1011101₂ to Octal.
25. Convert 1111111₂ to Octal.

### 🔹 **Binary to Hexadecimal**
26. Convert 1000₂ to Hexadecimal.
27. Convert 110011₂ to Hexadecimal.
28. Convert 11110000₂ to Hexadecimal.
29. Convert 1010101010₂ to Hexadecimal.
30. Convert 1111111111₂ to Hexadecimal.

### 🔹 **Octal to Decimal**
31. Convert 24₈ to Decimal.
32. Convert 73₈ to Decimal.
33. Convert 144₈ to Decimal.
34. Convert 377₈ to Decimal.
35. Convert 1000₈ to Decimal.

### 🔹 **Octal to Binary**
36. Convert 7₈ to Binary.
37. Convert 21₈ to Binary.
38. Convert 55₈ to Binary.
39. Convert 101₈ to Binary.
40. Convert 777₈ to Binary.

### 🔹 **Octal to Hexadecimal**
41. Convert 10₈ to Hexadecimal.
42. Convert 77₈ to Hexadecimal.
43. Convert 144₈ to Hexadecimal.
44. Convert 257₈ to Hexadecimal.
45. Convert 765₈ to Hexadecimal.

### 🔹 **Hexadecimal to Decimal**
46. Convert A₁₆ to Decimal.
47. Convert 1F₁₆ to Decimal.
48. Convert 2B₁₆ to Decimal.
49. Convert 3E8₁₆ to Decimal.
50. Convert FFF₁₆ to Decimal.

---

## 🚀 How to Use This Repository
1. Attempt each exercise on paper or using a programming language.
2. Verify your answers using a calculator or code.
3. Discuss solutions with peers or a mentor.

Happy Learning! 🎉
