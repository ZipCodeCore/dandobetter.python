# Python Fundamentals

### **Objective:**
* To complete the method stubs in each of the provided python modules
	* `calculator.py`
	* `predicator.py`
	* `string_manipulator.py`

### **Purpose:**
* To establish familiarity with
    * [method signatures and return statements]()
    * [primitive data-types]()
    * [class and object-definition]()
    * [unit-testing]()
    * [arrays]()
    * [for loops]()

## Predicate Utilities
* A _predicate_ is a clause which states something about a subject. (_e.g., **is assigning**_ in _"Leon **is assigning** homework"_)
* Ensure each of the test cases passes successfully in the class [predicator_test.py](./src/test/predicator_test.py) by completing each of the method stubs in the class [predicator.py](./src/main/predicator.py).
* Method Stubs to be completed
	* `is_greater_than_5(some_value)`
	* `is_greater_than_8(some_value)`
    * `is_less_than_4(some_value)`
    * `is_less_than_1(some_value)`

## Math Utilities
* Ensure each of the test cases passes successfully in the class [calculator_test.py](./src/test/calculator_test.py) by completing each of the method stubs in the class [calculator.py](src/main/calculator.py).
* Method Stubs to be completed	
	* `add(first_value, second_value)`
	* `subtract(first_value, second_value)`
	* `divide(first_value, second_value)`
	* `multiply(first_value, second_value)`


## String Utilities
* Ensure each of the test cases passes successfully in the class [string_evaluator_test.py](./src/test/string_evaluator_test.py) by completing each of the method stubs in the class [string_evaluator.py](src/main/string_evaluator.py).
* Method Stubs to be completed
    * `get_hello_world()`
    * `concatenate(first_value, second_value)`
    * `substring_inclusive(string_to_fetch_from, starting_index, ending_index)`
    * `substring_exclusive(string_to_fetch_from, starting_index, ending_index)`
    * `compare(first_value, second_value)`
    * `get_middle_character(string_to_fetch_from)`
    * `get_first_word(string_to_fetch_from)`
    * `get_second_word(string_to_fetch_from)`
    * `reverse(string_to_reverse)`



## How to Download

### Part 1 - Forking the Project
* To _fork_ the project, click the `Fork` button located at the top right of the project.


### Part 2 - Navigating to _forked_ Repository
* Navigate to your github profile to find the _newly forked repository_.
* Copy the URL of the project to the clipboard.

### Part 3 - Cloning _forked_ repository
* Clone the repository from **your account** into the `~/dev` directory.
    * if you do not have a `~/dev` directory, make one by executing the following command:
        * `mkdir ~/dev`
    * navigate to the `~/dev` directory by executing the following command:
        * `cd ~/dev`
    * clone the project by executing the following command:
        * `git clone https://github.com/MYUSERNAME/NAMEOFPROJECT`

### Part 4 - Check Build
* Ensure that the tests run upon opening the project.
    * You should see `Tests Failed: ${number-of-tests} of ${number-of-tests} tests`
* Execute the command below to run `unittest` of all python files with a suffix of `_test.py`
        * `python -m unittest discover -s ./src/test/ -p '*_test.py'`







## How to Submit

### Part 1 -  _Pushing_ local changes to remote repository
* from a _terminal_ navigate to the root directory of the _cloned_ project.
* from the root directory of the project, execute the following commands:
    * add all changes
        * `git add .`
    * commit changes to be pushed
        * `git commit -m 'I have added changes'`
    * push changes to your repository
        * `git push -u origin main`

### Part 2 - Submitting assignment
* from the browser, navigate to the _forked_ project from **your** github account.
* click the `Pull Requests` tab.
* select `New Pull Request`
