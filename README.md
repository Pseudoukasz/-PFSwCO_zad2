# Zadanie 2.

## podpunkt 1 [link do pliku action](.github/workflows/zad1.yml)
- wykonanie tego podpunktu sprowadza się do wykonania poszczególnych kroków z instrukcji do labolatorium 11

## podpunkt 2. [link do pliku action](.github/workflows/zad2.yml)
- aby stowrzyć obrazy na kilka platofrm trzeba zmodyfikować plik action z podpunktu pierwszego o dodatkowy parametr `platforms`
- dodatkowo trzeba zaciągnać emulator QEMU inaczej przy towrzeniu obrazu na platformach arm otrzymujemy błąd kompilacji

## podpunkt 3. [link do pliku action](.github/workflows/zad3.yml)
 - "Można gdyby to było złe to Bóg by inaczej swiat stworzył." K.Bosak
 - wystarczy dodać kolejny element pod `jobs` jako kolejne zadanie do wykonania  
 - https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#jobsjob_id
 - https://blog.gitguardian.com/shift-your-ci-to-github-actions/
 
 
