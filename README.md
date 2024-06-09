### Установка Sphinx
```
pip install sphinx
```

### Инициализация Sphinx:
```
sphinx-quickstart
```

### Настройка конфигураций:
```
import os
import sys
sys.path.insert(0, os.path.abspath('..'))
```

### Использование sphinx-apidoc для генерации файлов .rst:
```
sphinx-apidoc -o source ../
```

### Создание HTML-документации:
```
sphinx-build -b html source build
```
