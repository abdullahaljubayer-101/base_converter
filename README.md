# 🔄 Base Converter

![Java](https://img.shields.io/badge/Language-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Type](https://img.shields.io/badge/Type-CLI-lightgrey?style=flat-square)

A number system converter in Java that converts between **Decimal, Binary, Octal and Hexadecimal**, with support for **fractional numbers** too (like `10.625` → `1010.101`).

I built every conversion manually instead of relying on Java's built-in helpers, because the whole point was to understand how number systems actually work under the hood. 🧠

---

## ✨ Features

- 🔢 All 4 number systems: decimal, binary, octal and hexadecimal
- 🔁 Convert **from any base to any base** (12 conversions)
- 🎯 Handles the **fractional part** as well as whole numbers
- 📋 Simple FROM → TO menu

## 🧮 Supported conversions

|            | → Decimal | → Binary | → Octal | → Hex |
| ---------- | :-------: | :------: | :-----: | :---: |
| **Decimal** | - | ✅ | ✅ | ✅ |
| **Binary**  | ✅ | - | ✅ | ✅ |
| **Octal**   | ✅ | ✅ | - | ✅ |
| **Hex**     | ✅ | ✅ | ✅ | - |

## 🚀 Run it

```bash
cd "Base Converter/src"
javac *.java
java Main
```

```text
FROM:
1 for Decimal.
2 for Binary.
3 for Octal.
4 for Hexadecimal.

Enter Your Choice: 1

TO:
...
Enter Your Choice: 2

Enter a Decimal Number: 10.625
```

## 📁 Project structure

Each conversion lives in its own class, so the logic stays small and easy to read:

```text
Base Converter/src/
├── Main.java               # Reads input and calls the right converter
├── MenuDriven.java         # FROM / TO menu
├── DecimalToBinary.java
├── DecimalToOctal.java
├── DecimalToHexadecimal.java
├── BinaryToDecimal.java
├── BinaryToOctal.java
├── BinaryToHexadecimal.java
├── OctalToDecimal.java
├── OctalToBinary.java
├── OctalToHexadecimal.java
├── HexadecimalToDecimal.java
├── HexadecimalToBinary.java
└── HexadecimalToOctal.java
```

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
