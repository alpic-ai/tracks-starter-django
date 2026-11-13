# Django starter

A minimal Django app in Python, managed with uv, with one view and the default SQLite settings, no models.

- `manage.py`: Django's command-line utility
- `mysite/settings.py`: the project settings
- `mysite/urls.py`: the URL routes
- `mysite/views.py`: the view answering `/`

## Run

```sh
uv sync
uv run python manage.py runserver
```

Then open http://localhost:8000.
