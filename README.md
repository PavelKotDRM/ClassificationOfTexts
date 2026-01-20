# Classification of Texts

Проект для классификации текстов с использованием PyTorch и fastai.

## Требования

- Python 3.11
- uv (менеджер пакетов)

## Установка зависимостей

```bash
uv sync
```

## Работа с ноутбуками в VS Code

VS Code имеет встроенную поддержку Jupyter ноутбуков. Просто откройте файлы `.ipynb` в редакторе.

### Выбор интерпретатора Python

1. Откройте ноутбук (`.ipynb` файл)
2. Нажмите на кнопку выбора ядра (kernel) в правом верхнем углу
3. Выберите интерпретатор из `.venv` (Python 3.11)

### Запуск ячеек

- `Shift + Enter` - выполнить текущую ячейку и перейти к следующей
- `Ctrl + Enter` - выполнить текущую ячейку
- Используйте кнопки в интерфейсе VS Code для управления ноутбуком

## Структура проекта

- `src/fastaiModel.ipynb` - модель на базе fastai
- `src/PyTorchModel.ipynb` - модель на базе PyTorch
- `pyproject.toml` - конфигурация проекта и зависимости

## Основные зависимости

- PyTorch (torch, torchvision, torchaudio, torchtext)
- fastai
- spaCy (с поддержкой CUDA)
- transformers
- scikit-learn
- pandas, numpy, polars
- matplotlib, plotly
- и другие библиотеки для работы с данными и визуализации

## Полезные команды

```bash
# Добавить новый пакет
uv add package-name

# Удалить пакет
uv remove package-name

# Обновить зависимости
uv sync

# Запустить скрипт Python
uv run python script.py
```
