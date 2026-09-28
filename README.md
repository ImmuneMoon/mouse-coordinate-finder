# Mouse Coordinate Finder

A tiny Python script that prints the live screen coordinates of your mouse pointer. Useful when you are writing automation scripts and need the exact position of a button or field.

## Usage

Install the one dependency:

```bash
pip install pyautogui
```

Run the script:

```bash
python mouse_finder.py
```

Move the mouse to the spot you care about and read the position from the terminal:

```text
Move your mouse to the desired position and press Ctrl+C to stop.
Current position: (1042, 617)
```

The reading updates ten times a second on a single line. Press **Ctrl+C** to stop.

## Notes

- Coordinates are in pixels, measured from the top-left corner of the primary display.
- On a scaled display the values match what `pyautogui` uses for clicks and moves, so you can paste them straight into a `pyautogui.click(x, y)` call.

## Requirements

- Python 3.8 or newer
- [`pyautogui`](https://pypi.org/project/PyAutoGUI/)

## ☕ Support the Project

If you find this project helpful and want to support further development by Fulllion Creative Works, consider leaving a tip!

* [Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=LCDZX75HR4CLC)
* [Support on Ko-fi](https://ko-fi.com/fulllion)

---
© 2026 Fulllion Creative Works. All rights reserved.
