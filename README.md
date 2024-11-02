None
word = input("Wpisz słowo, którego nie rozumiesz (używaj wielkich liter!): ")
meme_dict1 = {"CRINGE": "Coś wyjątkowo dziwnego lub zawstydzającego"
                }
meme = {"LOL": "Częsta reakcja na coś zabawnego"
            }
if word in meme.keys():
    print ("Częsta reakcja na coś zabawnego")
if word in meme_dict1.keys():
    print ("Coś wyjątkowo dziwnego lub zawstydzającego")
