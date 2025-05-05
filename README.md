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

5. Podłączenie pod bazę danych Postgresql

Wywołanie migracji (podstawowej)
```shell
python manage.py migrate
```