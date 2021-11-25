# kullan-c-girisi
print("Kullanıcı girişi programına hoşgeldiniz:")
a="mert"
b="1903"
hak=3
while True:
    c=input("LÜTFEN KULLANICI ADINI GİRİNİZ:")
    d=input("LÜTFEN SİFRE GİRİNİZ:")
    if(a==c and b!=d):
        print("Sifre hatalı")
        hak -=1
    elif(a!=c and b!=d):
        print("Kullanıcı adı ve şifre hatalı")
        hak -=1
    elif(a!=c and b==d):
        print("Kullanıcı adı hatalı")
        hak -=1
    else :
        print("Giriş Başarılı")
        break
    if(hak==0):
        print("Çok sayıda hatalı giriş yaptınız")
        break
