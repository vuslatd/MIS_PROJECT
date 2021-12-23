from pytube import YouTube
url = YouTube(input("LÜTFEN BU ALANA İNDİRMEK İSTEDİĞİNİZ VİDEONUN LİNKİNİ YAPIŞTIRINIZ: "))
for i in url.streams:
    print(i)
print("VIDEO BASLIGI: ", url.title)
print("VIDEO SURESI: ", url.length)
print("IZLENME SAYISI :", url.views)
print("VIDEO RATINGI: ", url.rating)
print("*"*100)
stream = url.streams.filter(progressive=True).get_by_itag(22)
stream.download()
