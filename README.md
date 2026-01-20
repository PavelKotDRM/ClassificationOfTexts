# Classification of Texts

A project for text classification using PyTorch and fastai.

## Requirements

- Python 3.11
- uv (package manager)

## Installing Dependencies

```bash
uv sync
```

## Working with Notebooks in VS Code

VS Code has built-in support for Jupyter notebooks. Simply open `.ipynb` files in the editor.

### Selecting Python Interpreter

1. Open a notebook (`.ipynb` file)
2. Click on the kernel selector button in the top right corner
3. Select the interpreter from `.venv` (Python 3.11)

### Running Cells

- `Shift + Enter` - run current cell and move to next
- `Ctrl + Enter` - run current cell
- Use buttons in VS Code interface to manage the notebook

## Project Structure

- `src/fastaiModel.ipynb` - fastai-based model
- `src/PyTorchModel.ipynb` - PyTorch-based model
- `pyproject.toml` - project configuration and dependencies

## Main Dependencies

- PyTorch (torch, torchvision, torchaudio, torchtext)
- fastai
- spaCy (with CUDA support)
- transformers
- scikit-learn
- pandas, numpy, polars
- matplotlib, plotly
- and other libraries for data processing and visualization

## Useful Commands

```bash
# Add a new package
uv add package-name

# Remove a package
uv remove package-name

# Update dependencies
uv sync

# Run a Python script
uv run python script.py
```

---

# Классификация текстов

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
