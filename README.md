<h3 align="center">
  project developed for the front end challenge
</h3>

<br/>

The application consists of parsing a text file (CNAB) and saving its information (financial transactions) in a database. Made with the intention of simulating a technical test in the FullStack development course at Kenze Academy Brasil.

---

<br/>

## Installation and running in development environments

### Create the virtual environment

```
python -m venv venv
```

### activate the venv

```bash
# linux
source venv/bin/activate

# windows
.\venv\Scripts\activate

```

### Instale as dependências

```
pip install -r requirements.txt
```

### Run the migrations

```
./manage.py migrate
```

### Run the application

```
./manage.py runserver
```

---

<br/>

File for testing: **[File CNAB](https://github.com/Kenzie-Academy-Brasil-Developers/desafio-backend-m6/blob/main/CNAB.txt)**

## Base URL

> http://127.0.0.1:8000/api/

## Documentation

> http://127.0.0.1:8000/docs/

## Routes

- File upload route [POST], and listing of all financial transactions [GET]

  > http://127.0.0.1:8000/api/cnab/

- Route to see the balance of all stores [GET]
  > http://127.0.0.1:8000/api/balance/
