###  PROJEKT JEST ROZWINIĘCIEM I DODATKOWYM ELEMENTEM PROJEKTU " demo-bash-docker " Z MOJEGO REPOZYTORIUM GITHUB

Cel projektu : wdrożenie wcześniejszego projektu na instancje EC2 w usłudze chmurowej AWS

W danym repozytorium znajduje się jedynie plik deploy.tf, który tworzy i konfiguruje maszyne wirtualną w AWS na bazie systemu Ubuntu 24.04 a następnie pobiera do niej repozytorium mojego projektu "demo-bash-docker" i uruchamia skrypt.

Wymagania : 
1. System Ubuntu 20.04 lub nowszy 
2. Posiadanie konta AWS (może być w darmowej wersji próbnej) 
3. Skonfigurowane AWS CLI w systemie Ubuntu 
4. Zainstalowany Terraform

Uruchomienie : 
1. Wpisz w terminalu : 

terraform init

terraform plan

terraform apply

2. Po zakończeniu wdrożenia Terraform wyświetli publiczny adres IP.
3. Sprawdź aplikację w przeglądarce pod adresem http://<PUBLIC_IP>:5000