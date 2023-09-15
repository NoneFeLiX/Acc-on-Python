# Acc-on-Python
name = input("Ваше имя: ")
age = int(input("Ваш возраст: "))
pas = input("Пароль: ")

if age < 18:
    print("Простите, но Вам вход запрещён")
else:
    print(f"Привет {name}!")
    print(f"Запомните Ваш пароль: '{pas}'")

