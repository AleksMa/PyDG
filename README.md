# PDG generator
Библиотека генерации program dependence graph для программ на языке Python.  
Автор - Thomas Schaper, представлена на [CompSys2018](https://www.aanmelder.nl/101005)

## Использование
python >= 3.6
```bash
pip3 install -r requirements.txt
parser.py input_file.py > output_file.dot
```

По программе на языке Python порождает граф зависимостей в формате dot - каждой функции исходного файла соответствует подграф.
