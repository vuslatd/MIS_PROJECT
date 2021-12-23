from pytube import YouTube
url = YouTube(input("LÜTFEN BU ALANA İNDİRMEK İSTEDİĞİNİZ VİDEONUN LİNKİNİ YAPIŞTIRINIZ: "))
# for i in url.streams:
#     print(i)
print("VIDEO BASLIGI: ", url.title)
print("VIDEO SURESI: ", url.length)
print("IZLENME SAYISI :", url.views)
print("VIDEO RATINGI: ", url.rating)
print("*"*100)
if url.length > 120:
    confirmation = "yes", "Yes", "YES"
    user_confirmation = input("VIDEO SURESI 2 DAKİKADAN DAHA UZUN, YİNE DE İNDİRME İŞLEMİNİ ONAYLIYOR MUSUNUZ? ")
    if user_confirmation == confirmation:
        stream = url.streams.filter(progressive=True).get_by_itag(22)
        stream.download()
        print("INDIRME İŞLEMİ ONAYLANDI.. ")
    else:
        print("İNDİRME İŞLEMİ ONAYLANAMADI !! ")
else:
    stream = url.streams.filter(progressive=True).get_by_itag(22)
    stream.download()
    print("İNDİRME İŞLEMİ ONAYLANDI.. ")
