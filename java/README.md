## Requirements

- astyle

  ```sh
  apt install astyle
  ```

## Usage

- pipe to `astyle` with `kr` style and indent as 2-space

  ```sh
  echo 'public class HelloWorld {public static void main(String[] args) {System.out.println("Hello, World");}}' | astyle --style=java --indent=spaces=2 -p -U -f
  ```

- Result

  ```java
  public class HelloWorld {
    public static void main(String[] args) {
      ystem.out.println("Hello, World");
    }
  }
  ```
