## Requirements

- astyle

  ```sh
  apt update
  apt install astyle
  ```

## Usage

- pipe to `astyle` with `kr` style and indent as 2-space

  ```sh
  echo 'int main() { return 0; }' | astyle --style=kr --indent=spaces=2 -p -U -f
  ```

- Result

  ```c
  int main()
  {
    return 0;
  }
  ```
