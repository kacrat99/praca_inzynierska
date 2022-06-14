# Aplikacja do wykrywania Złośliwego oprogramowania mobilnego stworzona na potrzeby Pracy Inżynierskiej

Plik requirments.txt zawiera niezbędnę biblioteki języka Python, które należy doinstalować, aby aplikacja uruchomiła się prawidłowo.__
Plik model.h5 jest to wyeksportowany wytrenowany na wcześniej przygotowanej bazie danych model ResNet50.__
Plik app.py zawiera skrypty potrzebne do uruchomienia aplikacji za pomocą platformy streamlit.__
W folderze modele_CNN zawarte są kody odpowiedzialne za trenowanie modeli użytych przy eksperymentach - ResNet50, MobileNet, VGG16 oraz InceptionV3.__

## Jak uruchomić aplikacje?

Należy użyć komendy w terminalu ```streamlit run app.py```

### Jak działa aplikacja? 

Należy wrzucić plik aplikacji mobilnej z rozszerzeniem ```.apk``` a następnie poczekać na wiadomość zwrotną.
Aplikacja po wrzuceniu przez użytkownika próbki zamieni plik na wizualizacje binarną wraz z entropią lokalną 
Obraz zostanie przekazany do modelu ResNet50, który dokona predykcji. 
Wiadomość o predykcji wyświetli się na ekranie aplikacji wraz z obrazem. 

![alt text](https://github.com/kacrat99/praca_inzynierska/blob/master/sample1.PNG?raw=true)

