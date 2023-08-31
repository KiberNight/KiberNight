data= 31 ,8 ,2023
print (data)

name_a=input("фамилия ")
name_b=input("имя")

print("укажите дату рождения ")
data_dd= int(input("день "))
data_mm=int(input("месяц "))
data_gg=int(input("год "))

if (data_gg<=2015) and (1<=data_mm<=12)and(1<=data_dd<=31):
    print("добро пожаловать")
    print (name_a)
    print (name_b)
else:
    print ("ошибка")
