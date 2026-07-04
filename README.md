# Ml and Grams Converter

A simple Python program that converts ingredient measurements between **millilitres (mL)** and **grams (g)** using ingredient densities.

## Features

- Convert mL to grams
- Convert grams to mL
- Supports:
  - Flour
  - Oats
  - Sugar
- User-friendly command-line interface

## How It Works

The program uses the following approximate densities:

| Ingredient | Density (g/mL) |
|------------|---------------:|
| Flour      |      0.50      |
| Oats       |      0.34      |
| Sugar      |      0.84      |

### Formula

**mL → g**

```
grams = millilitres × density
```

**g → mL**

```
millilitres = grams ÷ density
```

## Technologies Used

- Python 3

## Future Improvements

- Add a graphical user interface (Tkinter)
- Support more ingredients
- Improve input validation
- Round results automatically
- Store ingredient densities in a dictionary

## Author

Made by **Shailynn Devereux**
