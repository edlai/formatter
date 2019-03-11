## Requirements

- astyle

  ```sh
  apt install astyle
  ```

## Pre

```
sed -i $'s/\t/    /g' *.txt
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
