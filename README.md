# Final-proje-g-derimi
projemi
# DataFlair Adam Asmaca Oyununa Ho� Geldiniz:


 rastgele i�e aktar
 ithalat zaman�

 # Oyuna davet etmek i�in ilk ad�mlar:
 print("\nDataFlair'den Adam Asmaca oyununa ho� geldiniz\n")
 isim = input("Ad�n�z� giriniz: ")
 print("Merhaba " + isim + "! Bol �anslar!")
 zaman.uyku(2)
 print("Oyun ba�lamak �zere!\n Adam Asmaca oynayal�m!")
 zaman.uyku(3)


 # Oyunu y�r�tmek i�in ihtiyac�m�z olan parametreler:
 tan�m ana():
     k�resel say�
     k�resel ekran
     k�resel kelime
     k�resel zaten_tahmin edildi
     k�resel uzunluk
     k�resel play_game
     word_to_guess = ["ocak","s�n�r","g�r�nt�","film","s�z","�ocuklar","ci�erler","bebek","kafiye","hasar"
                    ,"bitkiler"]
     kelime = rastgele. se�im(words_to_guess)
     uzunluk = len(kelime)
     say� = 0
     g�r�nt� = '_' * uzunluk
     Zaten_tahmin edilmi� = []
     play_game = ""

 # �lk tur bitti�inde oyunu yeniden y�r�tmek i�in bir d�ng�:

 def play_loop():
     k�resel play_game
     play_game = input("Tekrar oynamak istiyor musunuz? y = evet, n = hay�r \n")
     play_game ["y", "n","Y","N"] i�inde de�ilken:
         play_game = input("Tekrar oynamak istiyor musunuz? y = evet, n = hay�r \n")
     if play_game == "y":
         ana()
     elif play_game == "n":
         print("Oynad���n�z ��in Te�ekk�rler! Tekrar bekleriz!")
         ��k��()

 # Oyun i�in gerekli t�m ko�ullar�n ba�lat�lmas�:
 def adam asmaca():
     k�resel say�
     k�resel ekran
     k�resel kelime
     k�resel zaten_tahmin edildi
     k�resel play_game
     s�n�r = 5
     tahmin = input("Bu Adam Asmaca Kelimesidir: " + display + " Tahmininizi girin: \n")
     tahmin = tahmin.�erit()
     if len(guess.strip()) == 0 veya len(guess.strip()) >= 2 veya tahmin <= "9":
         print("Ge�ersiz Girdi, Bir harf deneyin\n")
         cellat()


     kelimede elif tahmin:
         zaten_guessed.extend([tahmin])
         indeks = kelime.find(tahmin)
         s�zc�k = s�zc�k[:dizin] + "_" + s�zc�k[dizin + 1:]
         g�r�nt� = g�r�nt�[:dizin] + tahmin + g�r�nt�[dizin + 1:]
         yazd�r(ekran + "\n")

     elif tahminde zaten_guessed:
         print("Ba�ka bir harf deneyin.\n")

     Ba�ka:
         say += 1

         e�er say� == 1:
             zaman.uyku(1)
             print(" ___ \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   "_|_\n")
             print("Yanl�� tahmin. " + str(limit - say�) + " kalan tahminler\n")

         elif say�s� == 2:
             zaman.uyku(1)
             print(" ___ \n"
                   " | | \n"
                   " | |\n"
                   " | \n"
                   " | \n"
                   " | \n"
                   " | \n"
                   "_|_\n")
             print("Yanl�� tahmin. " + str(limit - say�) + " kalan tahminler\n")

         elif say�s� == 3:
            zaman.uyku(1)
            print(" ___ \n"
                  " | | \n"
                  " | |\n"
                  " | | \n"
                  " | \n"
                  " | \n"
                  " | \n"
                  "_|_\n")
            print("Yanl�� tahmin. " + str(limit - say�) + " kalan tahminler\n")

         elif say�s� == 4:
             zaman.uyku(1)
             print(" ___ \n"
                   " | | \n"
                   " | |\n"
                   " | | \n"
                   " | O \n"
                   " | \n"
                   " | \n"
                   "_|_\n")
             print("Yanl�� tahmin. " + str(limit - say�) + " kalan son tahmin\n")

         elif say�s� == 5:
             zaman.uyku(1)
             print(" ___ \n"
                   " | | \n"
                   " | |\n"
                   " | | \n"
                   " | O \n"
                   " | /|\ \n"
                   " | / \ \n"
                   "_|_\n")
             print("Yanl�� tahmin. As�ld�n�z!!!\n")
             print("Kelime:",zaten_tahmin edildi,kelime)
             play_loop()

     if word == '_' * uzunluk:
         print("Tebrikler! Kelimeyi do�ru tahmin ettiniz!")
         play_loop()

     elif say�s� != limit:
         cellat()


 ana()