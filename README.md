# Projekt portal SciNet
1. Klonowanie projektu

```sh
git clone https://github.com/revelium/nauka-python.git
```

2. Tworzenie wirtualnej zmiennej środowiskowej
```sh
python -m venv .venv
```

3. Aktywacja zmiennej środowiskowej
```shell
.venv/Scripts/activate
```

4. Instalacja pakietów / paczek
```shell
pip install -r requirements.txt
```

5. Stworzenie bazy danych / podłączenie pod bazę danych Postgresql
- stworzenie pliku .env
- skopiowanie zawartości z pliku .env.example
- wklejenie zawartości do pliku .env
- uzupełnienie o dane lokalne (Twoje dane konfiguracyjne z postgres)


Wywołanie migracji (podstawowej)
```sh
python manage.py migrate
```