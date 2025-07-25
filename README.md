# roman-converter
# Roman Numeral to Integer Converter

This Java program converts a Roman numeral string into its equivalent integer value.

## 📁 Package
`projectUpload`

## 📌 Features

- Converts valid Roman numerals (e.g., `III`, `LVIII`, `MCMXCIV`) into integers.
- Follows standard Roman numeral rules, including subtraction rules (`IV`, `IX`, `XL`, etc.).
- Handles characters using a switch-case for mapping values.

## 🚫 Note
If you enter an invalid Roman numeral (e.g., `"JIHIN"`), the program will treat unrecognized characters as `0` and may give incorrect results. You can improve the code by adding input validation (optional enhancement).

## 📥 Input
Set the Roman numeral string directly in the code:
String s = "LVIII"; // Change this to test other values
📤 Output
Displays the Roman numeral and its integer value:

LVIII 58
🧠 How It Works
Iterates through the Roman numeral string from right to left.

Compares each numeral with the one after it:

If it's smaller, subtract it.

If it's equal or greater, add it.

Returns the final total.

✅ Example
Input:
String s = "MCMXCIV";

Output:
MCMXCIV 1994
