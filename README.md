# Unix101

Unix101 is a Django-based application for managing Unix commands. It allows you to add, search, and manage commands with ease.

## Features

- Add, view, and search Unix commands
- Manage command categories and aliases
- Supports MySQL and other databases

## Installation

1. Clone the repository or download the package
2. Install the dependencies:
   pip install unix101
   pip install -r requirements.txt

## Commands to run:

1. For help regarding any of the commands - unix101 command_name --help
2. To show the list of commands - unix101 show
3. To add a command - unix101 add "command_name" "category" "description" --alias "alias"
4. To search a command - unix101 search "keyword"
5. To update a command - unix101 update 'position of command' --description "description"
6. To filter by something - unix101 filter "category"
7. To delete a command - unix101 delete "position of command"


### Prerequisites

- Python 3.8+
- Django 5.0.6
- MySQL

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details

## Authors

* **Bijinepalli Surat Dhani** 








   
