<p align="center">
  <h2 align="center">Sucuri-2-Disk</h2>
  <p>
  Script para descargar los eventos del Sucuri Web Application Firewall (WAF) en el disco como archivos CSV.
  </p>
</p>

---

#### Requerimientos:

* [Python3.8+](https://www.python.org/downloads/)

#### Como ejecutar:

Ejecute:

```
python3 -m venv env
```

En Windows, corra:

```
env\Scripts\activate.bat
```

En Unix o MacOS, corra:

```
source env/bin/activate
```

Luego ejecute:

```
pip install -r requirements.txt
```

Finalmente:

```
python3 app.py
```

#### Configuración:

```python

SUCURI_API_KEY = "..."
SUCURI_SITES = [
    {
        "secret": "...",   # Añadir tantos API_SECRET como le sea necesario.
        ...
    },
]
```

#### Referencias:

https://waf.sucuri.net/?apidocs
