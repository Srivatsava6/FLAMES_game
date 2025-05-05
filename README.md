# FLAMES Game Calculator

This is a simple Python project that calculates the relationship between two names using the classic childhood game **FLAMES** (Friends, Love, Affection, Marriage, Enemies, Siblings). The project is implemented in a modular fashion using well-defined functions for clarity and reusability.

---

## Project Structure

- `flames_game.ipynb` — Main Jupyter Notebook containing the full implementation using functions.
- Functions used:
  - `clean_name()` — Cleans and formats the input names.
  - `count_characters()` — Counts character occurrences.
  - `print_character_counts()` — Displays character frequency.
  - `get_dissimilar_counts()` — Calculates differences between names.
  - `count_total_difference()` — Totals the dissimilar character count.
  - `eliminate_flames()` — Applies the FLAMES elimination logic.
  - `computer_flames()` — Main orchestrating function.

---

## How It Works

1. The user inputs two names.
2. The characters in both names are compared.
3. Common characters are removed, and the count of remaining characters is calculated.
4. This count is used to cycle through the word `FLAMES` until one letter remains.
5. Each letter in `FLAMES` corresponds to a type of relationship:
   - `F` - Friends
   - `L` - Love
   - `A` - Affection
   - `M` - Marriage
   - `E` - Enemies
   - `S` - Siblings
6. You also get a **"second chance"** with a randomly shuffled FLAMES string.

---


