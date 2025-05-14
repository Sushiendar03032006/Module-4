## Dictionary Operations in Python: Merging Two Dictionaries

## Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def merge_files(file1_path, file2_path, output_file_path):
    with open(file1_path,'r') as file1:
        content1=file1.read()
        
    with open(file2_path,'r') as file2:
        content2=file2.read()
        
    with open(output_file_path,'w') as output_file:
        output_file.write(content1)
        output_file.write(content2)
    ############# ADD YOUR CODE HERE ###########


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()
    return content
```

## Output:
![Screenshot 2025-05-01 101552](https://github.com/user-attachments/assets/ffd5f51c-349d-4ff3-afcd-1eccaa458bd8)


## Result:
 Python program that merges **two dictionaries** and combines their key-value pairs is successfully executed.

