print('**HESAP MAKİNESİNE HOŞGELDİNİZ**')
print("""İŞLEMLER
1 = TOPLAMA
2 = ÇIKARMA
3 = ÇARPMA
4 = BÖLME
5 = ÜST ALMA
6 = KAREKÖK
7 = KARESİNİ HESAPLAMA
8 = MUTLAK DEĞER 
9 = FAKTÖRİYEL  
10 = LOGARİTMA 
11 = TRİGONOMETRİ
12 = MOD ALMA 
13 = ÇIKIŞ """)
print("*"*150)
print("*"*150)
while True:
    calculation = input('LÜTFEN YAPMAK İSTEDİĞİNİZ İŞLEM NUMARASINI GİRİNİZ : ')

    if calculation == '13':
        print('HESAP MAKİNESİNDEN ÇIKILIYOR ...')
        break

    elif calculation == '1':
        ineffective_element = 0
        while True:
            add = float(input('TOPLAMAK İSTEDİĞİNİZ SAYILARI GİRİNİZ  (Çıkmak için 0 a basınız):'))
            if add == 0:
                break
            ineffective_element += add
        print('TOPLAMA İŞLEMİNİN SONUCU: ', ineffective_element)

    elif calculation == '2':
        boolean = True
        ineffective_element = 0
        while True:
            subtract = float(input('ÇIKARMAK İSTEDİĞİNİZ SAYILARI SIRAYLA GİRİNİZ  (Çıkmak için 0 a basınız):'))
            if subtract == 0:
                break
            elif boolean == True:
                ineffective_element += subtract
                boolean = False
            else:
                ineffective_element -= subtract
        print('ÇIKARMA İŞLEMİNİN SONUCU : ', ineffective_element)
    elif calculation == '3':
        ineffective_element = 1
        while True:
            multiply = float(input('ÇARPMAK İSTEDİĞİNİZ SAYILARI GİRİNİZ  (Çıkmak için 1 a basınız):'))
            if multiply == 1:
                break
            ineffective_element *= multiply
        print('ÇARPMA İŞLEMİNİN SONUCU: ', ineffective_element)

    elif calculation == '4':
        ineffective_element = 1
        while True:
            divide = int(input('BÖLMEK İSTEDİĞİNİZ SAYILARI SIRAYLA GİRİNİZ  (Çıkmak için 1 a basınız):'))
            if divide == 1:
                break
            ineffective_element /= divide
        print('BÖLME İŞLEMİNİN SONUCU: ', ineffective_element)
