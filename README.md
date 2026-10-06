print(" Om Kharade")



cost_price = float(input("Enter cost price: "))
selling_price = float(input("Enter selling price: "))

if selling_price > cost_price:
    print("Profit =", selling_price - cost_price)
elif selling_price < cost_price:
    print("Loss =", cost_price - selling_price)
else:
    print("No Profit, No Loss")


num = int(input("Enter a number: "))

if num % 2 == 0:
    print("The number is Even")
else:
    print("The number is Odd")

age = int(input("Enter your age: "))

if age < 0:
    print("Invalid age")
elif age < 18:
    print("Age is valid, but not eligible for voting")
else:
    print("Age is valid and eligible for voting")

word1 = input("Enter word1: ").replace(" ", "").lower()
word2 = input("Enter word2: ").replace(" ", "").lower()

if sorted(word1) == sorted(word2):
    print("The words are Anagrams")
else:
    print("The words are Not Anagrams")