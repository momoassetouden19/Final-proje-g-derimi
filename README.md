# Final-proje-g-derimi
projemi
# DataFlair Adam Asmaca Oyununa Hoş Geldiniz:


 rastgele içe aktar
 ithalat zamanı

 # Oyuna davet etmek için ilk adımlar:
 print("\nDataFlair'den Adam Asmaca oyununa hoş geldiniz\n")
 isim = input("Adınızı giriniz: ")
 print("Merhaba " + isim + "! Bol Şanslar!")
 zaman.uyku(2)
 print("Oyun başlamak üzere!\n Adam Asmaca oynayalım!")
 zaman.uyku(3)


 # Oyunu yürütmek için ihtiyacımız olan parametreler:
 tanım ana():
     küresel sayı
     küresel ekran
     küresel kelime
     küresel zaten_tahmin edildi
     küresel uzunluk
     küresel play_game
     word_to_guess = ["ocak","sınır","görüntü","film","söz","çocuklar","ciğerler","bebek","kafiye","hasar"
                    ,"bitkiler"]
     kelime = rastgele. seçim(words_to_guess)
     uzunluk = len(kelime)
     sayı = 0
     görüntü = '_' * uzunluk
     Zaten_tahmin edilmiş = []
     play_game = ""

 # İlk tur bittiğinde oyunu yeniden yürütmek için bir döngü:

 def play_loop():
     küresel play_game
     play_game = input("Tekrar oynamak istiyor musunuz? y = evet, n = hayır \n")
     play_game ["y", "n","Y","N"] içinde değilken:
         play_game = input("Tekrar oynamak istiyor musunuz? y = evet, n = hayır \n")
     if play_game == "y":
         ana()
     elif play_game == "n":
         print("Oynadığınız İçin Teşekkürler! Tekrar bekleriz!")
         çıkış()

 # Oyun için gerekli tüm koşulların başlatılması:
 def adam asmaca():
     küresel sayı
     küresel ekran
     küresel kelime
     küresel zaten_tahmin edildi
     küresel play_game
     sınır = 5
     tahmin = input("Bu Adam Asmaca Kelimesidir: " + display + " Tahmininizi girin: \n")
     tahmin = tahmin.şerit()
     if len(guess.strip()) == 0 veya len(guess.strip()) >= 2 veya tahmin <= "9":
         print("Geçersiz Girdi, Bir harf deneyin\n")
         cellat()


     kelimede elif tahmin:
         zaten_guessed.extend([tahmin])
         indeks = kelime.find(tahmin)
         sözcük = sözcük[:dizin] + "_" + sözcük[dizin + 1:]
         görüntü = görüntü[:dizin] + tahmin + görüntü[dizin + 1:]
         yazdır(ekran + "\n")

     elif tahminde zaten_guessed:
         print("Başka bir harf deneyin.\n")

     Başka:
         say += 1

         eğer sayı == 1:
             zaman.uyku(1)
             print(" ___ \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   "_|_\n")
             print("Yanlış tahmin. " + str(limit - sayı) + " kalan tahminler\n")

         elif sayısı == 2:
             zaman.uyku(1)
             print(" ___ \n"
                   " | | \n"
                   " | |\n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   "_|_\n")
             print("Yanlış tahmin. " + str(limit - sayı) + " kalan tahminler\n")

         elif sayısı == 3:
            zaman.uyku(1)
            print(" ___ \n"
                  " | | \n"
                  " | |\n"
                  " | | \n"
                  " | \n"
                  " | \n"
                  " | \n"
                  "_|_\n")
            print("Yanlış tahmin. " + str(limit - sayı) + " kalan tahminler\n")

         elif sayısı == 4:
             zaman.uyku(1)
             print(" ___ \n"
                   " | | \n"
                   " | |\n"
                   " | | \n"
                   " | O \n"
                   " | \n"
                   " | \n"
                   "_|_\n")
             print("Yanlış tahmin. " + str(limit - sayı) + " kalan son tahmin\n")

         elif sayısı == 5:
             zaman.uyku(1)
             print(" ___ \n"
                   " | | \n"
                   " | |\n"
                   " | | \n"
                   " | O \n"
                   " | /|\ \n"
                   " | / \ \n"
                   "_|_\n")
             print("Yanlış tahmin. Asıldınız!!!\n")
             print("Kelime:",zaten_tahmin edildi,kelime)
             play_loop()

     if word == '_' * uzunluk:
         print("Tebrikler! Kelimeyi doğru tahmin ettiniz!")
         play_loop()

     elif sayısı != limit:
         cellat()


 ana()