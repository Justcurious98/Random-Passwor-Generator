# Random-Passwor-Generator
This Python script generates a random password with adjustable length and strength. The strength of the password can be set to 'weak', 'strong', or 'very', and there's an option to include numerical digits in the password.
Here's a brief description you can use for your README:

---

# Random Password Generator

- `weak` strength passwords consist of lowercase letters only.
- `strong` strength passwords include both lowercase and uppercase letters.
- `very` strength passwords include lowercase and uppercase letters as well as special characters (punctuation).

If the `num` parameter is set to `True`, the password will include numeric digits. The number of numeric digits will be between 2 and 4, chosen randomly if the strength is 'very'. For 'weak' and 'strong', the number of digits will be 2.

Here's how to use it:

print(password(5,num=True)) # Generates a weak password of length 5 with numbers
print(password(10,num=True,strength='strong')) # Generates a strong password of length 10 with numbers
print(password(15,num=True,strength='very')) # Generates a very strong password of length 15 with numbers

feel free to experiment with different password lengths, strengths, and number inclusion to see how the password changes. Enjoy this simple but effective password generator!

---
