## Requirements

- pjson `pip install pjson`

## Usage

 - `echo` the string and pipe to `pjson`    
   
   ``` sh
   echo '{"object": {"a": "b","c": "d","e": "f"},"array": [1,2],"string": "Hello World"}' | pjson
   
- Result    

  ```json
  {
    "object": {
      "a": "b",
      "c": "d",
      "e": "f"
    },
    "array": [
      1,
      2
    ],
    "string": "Hello World"
  }
  ```
