# Lab 3 repository

A function that will write a text file to your PC with your name.
```def write_text_file_with_name():
    name = input("Enter your name: ")
    file_name = "my_name.txt"
    
    with open(file_name, "w") as file:
        file.write("My name is: " + name)
    
    print("File '{}' created successfully!".format(file_name))

# Example usage
write_text_file_with_name()
```
