Steps to use the library:

Install dependencies: Make sure you have tkinterdnd2 and pyinstaller installed. You can install them with:

pip install tkinterdnd2 pyinstaller

Create the executable file: Navigate to the directory where your Python file is located and run:

pyinstaller --onefile --windowed your_file.py

--onefile creates a single executable file.
--windowed prevents a console window from opening (useful for GUI applications).
Find the executable file:

After running the above command, PyInstaller will create a dist folder in the same directory as your Python file.

Inside this folder, you will find the executable file. Here is an example of what the command would look like if your file is named translator.py:

pyinstaller --onefile --windowed translator.py