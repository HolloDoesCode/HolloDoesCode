# About me
- Gay/Asexual
- he/him

# Code things
### CSS
```css
@import url("https://fonts.googleapis.com/css?family=Playpen+Sans");
body {
  font-family: 'Playpen Sans';
}
```
### Python
```py
# pip install PyYAML
import yaml

def get_attrib(yaml_file: str, to_get: str):
  try:
    with open(yaml_file, 'r') as file:
      data = yaml.safe_load(file)
      attribute_list = to_get.split('/')
      for attribute in attribute_list:
        data = data[attribute]
      return data
  except (KeyError, TypeError):
    return None
```
### HTML
```html
```
