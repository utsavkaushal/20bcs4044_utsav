internsctl
Command-line tool for Linux server operations

Installation
Clone the repository:

bash
Copy code
git clone <repository-url>
cd internsctl
Usage
Basics
bash
Copy code
./internsctl --help        # Display help
./internsctl --version     # Display version
Server Operations
CPU Information
bash
Copy code
./internsctl cpu getinfo
Memory Information
bash
Copy code
./internsctl memory getinfo
User Management
bash
Copy code
./internsctl user create <username>
./internsctl user list
./internsctl user list --sudo-only
File Information
bash
Copy code
./internsctl file getinfo <file-name>
./internsctl file getinfo --size <file-name>
./internsctl file getinfo --permissions <file-name>
./internsctl file getinfo --owner <file-name>
./internsctl file getinfo --last-modified <file-name>
Documentation
For detailed documentation, execute:

bash
Copy code
man ./internsctl.1
Replace <repository-url> with the actual URL of your GitHub repository. This snippet provides a quick overview of the key functionalities and usage examples for your internsctl command.
