# ml-cource

Учебный трек по ML/LLM — год практики, от NumPy до обучения моделей на GPU.
Репозиторий = портфолио: код версионируется с первого дня.

## Окружение

- **Python 3.12** (управляется через [uv](https://docs.astral.sh/uv/))
- Основные библиотеки: NumPy, pandas, matplotlib, seaborn, JupyterLab

### Как поднять окружение

```powershell
# 1. Установить uv (если ещё нет): https://docs.astral.sh/uv/getting-started/installation/
# 2. Из корня проекта — одна команда ставит нужный Python и все зависимости:
uv sync
```

`uv sync` читает `pyproject.toml` + `uv.lock` и создаёт `.venv` с точными версиями.

### Как запускать код

```powershell
uv run python main.py          # запустить скрипт
uv run jupyter lab             # открыть ноутбуки
uv run python                  # интерактивный питон
```

`uv run` сам подхватывает `.venv` — активировать окружение вручную не нужно.

## Прогресс

- **День 1** — окружение (uv, Python 3.12, git) + первый контакт с NumPy (векторизация).
