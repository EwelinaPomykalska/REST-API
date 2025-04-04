# Flask API – Laboratorium

Proste API stworzone na potrzeby ćwiczeń z Flask.

## Endpointy

### `/hello`
- `GET /hello` – zwraca `"Hello!"`
- `GET /hello?name=Imie` – zwraca `"Hello Imie!"`

### `/api/v1.0/predict`
- `GET /api/v1.0/predict?num1=3&num2=4`
- Jeśli suma > 5.8 zwraca `1`, inaczej `0`.

## Uruchomienie

```bash
pip install -r requirements.txt
python app.py
```

Następnie otwórz w przeglądarce:
- `http://127.0.0.1:5000/hello`
- `http://127.0.0.1:5000/api/v1.0/predict?num1=3&num2=4`
