import os
import time

os.system("screen -S min")

defadress= "TRTLuweEwEqPstNHhkvxX6UPy4Nw9WAN8gFmeyDHE1Mr54WVPgwUq1L9DqHKCjmcKNHvoNfrh7w7VHVBj1efakotfkt2jeroLmy+407fe63ee1452fa358b7ff8c43fb9eca0e42bd23463c4bb913e0b7d2a34108e0"
xhvadress= "hvs1H7MP77YFJtFMndGZatheqt8cGrMqbZjvw4YcVt7xGfJptwPvvZvGAfJ9F6ZCeC9P7MQTrZ6sybL5KAnFNhCF7supyS8vJV"

workername="bricks1"

turtlecoinaddress = ""





def packet():
    xmrig = "https://github.com/xmrig/xmrig/releases/download/v6.12.2/xmrig-6.12.2-linux-x64.tar.gz"

    os.system("wget "+xmrig)
    time.sleep(1)
    os.system("tar -zxvf xmrig-6.12.2-linux-x64.tar.gz")
    time.sleep(1)

while True:
    coin = "xhv"
    print("Gerekli arac gerecler kuruluyor...")
    time.sleep(1)
    packet()
    print("Tüm kurulum tamamlandı mining sistemine geçiliyor...")
    time.sleep(3)
    if coin == "trtl":
        print("Mining Başlatıldı!")
        os.system("./xmrig-6.12.2/xmrig --donate-level 1 -o turtlecoin.herominers.com:10380 -u " + defadress + " -p " + workername + " -a argon2/chukwav2 -k")
        print("Hata oluştu başa alınıyor...")
        pass
    elif coin == "xhv":
        print("Mining Başlatıldı!")
        os.system("./xmrig-6.12.2/xmrig --donate-level 1 -o us.haven.herominers.com:10450 -u " + xhvadress + " -p " + workername + " -a cn-heavy/xhv -k")
        print("Hata oluştu başa alınıyor...")
    else:
        print("Hatalı coin tekrar deneyin...")
        pass
