# Multilingual Text Rose Animation

An animated, purely text-based rose created using Python's standard `tkinter` library. The script (`rose.py`) dynamically generates the shape of a rose, its stem, and leaves using words of love translated into 34 different languages.

No source images, external assets, or visible borders are used. The geometry acts as an invisible mask, and the visible shape is defined entirely by carefully packed and animated text.

## Features

* **Pure Text Geometry:** The entire floral shape is built from words packed into invisible polygon masks.
* **34 Languages:** Features expressions of love ("I love you", "Love", etc.) across 34 global languages.
* **Fluid Animation:** Words gently float into place with a subtle color-shifting and shadow effect.
* **Ambient Shimmer:** Once fully assembled, individual words continuously shimmer to give the rose a living, breathing appearance.
* **Zero Dependencies:** Runs on Python's built-in standard library. No `pip install` required.

## Prerequisites

* **Python 3.x** installed on your system.
* **Tkinter** (This is included in the standard Python library by default on most operating systems. Linux users may need to run `sudo apt-get install python3-tk` if it was omitted from their distribution).

## How to Run

1. Save the provided Python script as `rose.py` in your desired directory.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the file.
4. Run the script using the following command:

```bash
python rose.py
