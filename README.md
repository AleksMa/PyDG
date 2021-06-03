# PDG generator
Библиотека генерации графа зависимости программ (program dependence graph) для языка Python 3.  
Автор инструментария - Thomas Schaper

## Использование
python >= 3.8
```bash
pip3 install -r requirements.txt
parser.py input_file.py > output_file.dot
```

По программе на языке Python порождает граф зависимости в формате dot - каждой функции исходного файла соответствует подграф.
