# Python2Laba
print ("Чтобы найти длинну слова разделенного пробелом нажмите 1 \n чтобы найти длину слова разделенного точкой с запятой нажмите 2")
a = int(input())
if a == 1:
    print ("Введите нужное вам кол-во слов")
    s=input().split()
    k=0
    for i in s:
        if len(i)>k:
            p = i;
    print("Самое длинное слово: ",p)
if a == 2:
    print ("Введите нужное вам кол-во слов")
    s=input().split(";")
    k=0
    for i in s:
        if len(i)>k:
            p = i;
    print("Самое длинное слово: ",p)
if a == 3:
    print ("Введите нужное вам кол-во слов")
    s=input().split()
    k = 50
    for i in s:
        if len(i)<k:
            p = i;
    print("Самое короткое слово: ",p)
