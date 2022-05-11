# pyqt-auto-search-bar
PyQt auto search bar which is search icon on the left only exists as a label, not clickable button. See the preview below.

This is useful to instant search feature.

## Requirements
* PyQt5 >= 5.8

## Setup
`python -m pip install pyqt-auto-search-bar`

## Included Packages
* <a href="https://github.com/yjg30737/pyqt-resource-helper.git">pyqt-resource-helper</a>
* <a href="https://github.com/yjg30737/pyqt-svg-label.git">pyqt-svg-label</a>

## Preview
Code Sample
```python
from PyQt5.QtWidgets import QApplication
from pyqt_auto_search_bar import AutoSearchBar


if __name__ == "__main__":
    import sys

    app = QApplication(sys.argv)
    searchBar = AutoSearchBar()
    searchBar.show()
    app.exec_()
```

Result

![image](https://user-images.githubusercontent.com/55078043/155654257-4d31a17a-fc64-4292-aecc-cf46a9580f18.png)

## See Also

* <a href="https://github.com/yjg30737/pyqt-search-bar-menu.git">pyqt-search-bar-menu</a> - QMenu which has search bar as a first item to help you search the menu items.
* <a href="https://github.com/yjg30737/pyqt-search-bar.git">pyqt-search-bar</a> - This supports search button.
