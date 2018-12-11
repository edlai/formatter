## Requirements

- libxml2-utils `apt install libxml2-utils`

## Usage

- `echo` a string and pipe to `xmllint`
  ```
  echo '<root><foo a="b">ccc</foo><bar value="ddd" /></root>' | xmllint --format -
  ```

