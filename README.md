# PLP Python Week 7

This project demonstrates basic Python list operations, a shopping list manager, and list reporting.

## Files

- `list_warmup.py` — Practices accessing, adding, and removing items in a list, and counting the remaining items.
- `shopping_list.py` — Provides a menu to add, remove, and display shopping list items.
- `list_report.py` — Prints a numbered shopping list and reports the number of long item names and the longest item name.
- `screenshots/` — Contains screenshots showing the Python programs running.

## Why Check Before Removing an Item?

Checking whether an item exists in a list using `in` before calling `.remove()` is safer because `.remove()` raises a `ValueError` if the item is not found. The check allows the program to display a helpful message instead of stopping with an error. This makes the shopping list manager more reliable and user-friendly.