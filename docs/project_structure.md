# PivotPoint Project Structure

This document outlines the folder and file structure of the PivotPoint project.

## Root Directory

- `/PivotPoint`
  - `README.md`: Project overview and instructions.

## Source Code

- `/src`
  - `/pivotpoint`
    - `__init__.py`: Initializes the Python package.
    - `main_window.py`: Main application window class.
    - `data_handler.py`: Handles all data operations.
    - `config.py`: Configuration settings.
    - `/ui_components`
      - `__init__.py`
      - `data_view.py`: For displaying data.
      - `...`: Other UI components.

## Tests

- `/tests`
  - `__init__.py`
  - `test_main_window.py`
  - `test_data_handler.py`
  - `...`: Other test scripts.

## Documentation

- `/docs`
  - `main_window.md`
  - `data_handler.md`
  - `project_stucture.md`
  - `...`: Other documentation files.

## Logs

- `/logs`: Log files (if applicable).

## Distribution

- `/dist`: Distributable files, executables.

## Other Files

- `Pipfile`: Pipenv dependencies file.
- `Pipfile.lock`: Locked versions of dependencies.
- `setup.py`: Setup script for packaging.
