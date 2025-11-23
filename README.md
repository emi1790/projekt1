None
meme_dict = {
            "CRINGE": "Coś wyjątkowo dziwnego lub zawstydzającego",
            "LOL": "Częsta reakcja na coś zabawnego",
            }

word = input("Wpisz słowo, którego nie rozumiesz (używaj wielkich liter!): ")

if word in meme_dict.keys():
    print('te słowo jest w słowniku i oznaca ono:')
    print(meme_dict[word])
else:
    print('nie ma takiego słowa, morzesz je dodać')
    head = input('wpisz jake słowo dodajesz')
    body = input('wpisz jakie znaczenie')
    meme_dict[head]=body
    print('dodano nowe słowo do słownika')
    print(head, ':', body)
