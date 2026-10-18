# OOP Design Patterns Demo

Two small Python scripts demonstrating classic object-oriented design patterns.

## Contents

### `Task_1.py` — Abstract Factory

Models vehicles (cars and motorcycles) with region-specific variants, using an `VehicleFactory` abstract base class with `USVehicleFactory` and `EUVehicleFactory` implementations that produce region-tagged vehicle instances.

### `Task_2.py` — Dependency Inversion / Library Manager

Implements a simple interactive library system: a `Library` class implementing a `LibraryInterface`, and a `LibraryManager` that depends only on the interface, decoupling the manager from the concrete storage implementation. Supports an interactive CLI with `add`, `remove`, `show`, and `exit` commands.

## Stack

- Python 3 (standard library only)

## Usage

```bash
python Task_1.py
python Task_2.py
```
