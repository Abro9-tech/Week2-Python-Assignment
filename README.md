# Python List Manipulation

## Description

This Python program demonstrates basic list operations such as adding, inserting, removing, sorting, and finding the index of an element. It manipulates a list by performing the following tasks:

1. Create an empty list called `my_list`.
2. Append elements to the list.
3. Insert a value at a specific position.
4. Extend the list with another list.
5. Remove the last element.
6. Sort the list in ascending order.
7. Find and print the index of a specific value.

This task is great for beginners to understand list manipulation in Python.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
    To clone the repository to your local machine, use the following command:

    ```bash
    git clone https://github.com/your-username/python-list-manipulation.git
    ```

2. Navigate to the project directory:
    Once the repository is cloned, go to the project folder:

    ```bash
    cd python-list-manipulation
    ```

3. Run the script:
    The program doesn’t require any additional dependencies. You can run the Python file directly:

    ```bash
    python list_manipulation.py
    ```

## Usage

The program performs the following list operations:

1. Create an empty list:
    ```python
    my_list = []
    ```

2. Append values:
    ```python
    my_list.append(10)
    my_list.append(20)
    my_list.append(30)
    my_list.append(40)
    ```

3. Insert a value at the second position:
    ```python
    my_list.insert(1, 15)  # Inserts 15 at index 1
    ```

4. Extend the list with another list:
    ```python
    my_list.extend([50, 60, 70])
    ```

5. Remove the last element:
    ```python
    my_list.pop()  # Removes the last item (70)
    ```

6. Sort the list in ascending order:
    ```python
    my_list.sort()
    ```

7. Find and print the index of the value `30`:
    ```python
    index_of_30 = my_list.index(30)
    print(f"The index of 30 is: {index_of_30}")
    ```


## Contributing

If you’d like to improve the program or add more features, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- Thanks to the Python community for providing excellent documentation and tutorials that helped me complete this task.


