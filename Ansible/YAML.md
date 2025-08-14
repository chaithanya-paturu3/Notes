Understanding YAML
YAML (YAML Ain't Markup Language) is a human-readable data serialization format that is commonly used for configuration files and data exchange between languages with different data structures.


YAML Syntax

key: value
name: John
city: New York


Strings, Numbers and Booleans:
string: Hello, World!
number: 42
boolean: true

Lists:
fruits:
  - apple
  - banana
  - cherry

Dictionaries (Maps):
person:
  name: John Doe
  age: 30
  is_student: false


List of dictionaries
YAML allows nesting of lists and dictionaries to represent more complex data.

family:
  parents:
    - name: Jane
      age: 50
    - name: John
      age: 52
  children:
    - name: Jimmy
      age: 22
    - name: Jenny
      age: 20


      basic yaml structure
      key: value
      name: John
      city: New York
      lists:
        - item1
        - item2
        - item3
        maps:
          key1: value1
          key2: value2