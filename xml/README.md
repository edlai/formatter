## Requirements

- libxml2-utils    

  ``` sh
  apt install libxml2-utils
  ```

## Usage

- `echo` a string and pipe to `xmllint`    

  ``` sh
  echo '<root><foo a="b">ccc</foo><bar value="ddd" /></root>' | xmllint --format -
  ```

- Result    

  ```xml
  <?xml version="1.0"?>
  <root>
    <foo a="b">ccc</foo>
    <bar value="ddd"/>
  </root>
  ```
