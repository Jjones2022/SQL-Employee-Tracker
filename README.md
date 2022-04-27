# SQL-Employee-Tracker
A easy interactive app that allows the user to track the roles and titles of employees
# SQL Employee Tracker

This is an interactive app that allows the user to easily locate, make changes, and view the updated roles of employees.

## Installation

Use the package manager NPM. To get started, you must have Visual Studio Code and SQL installed along with GitBash or a terminal of your liking. The steps to operate the program are located below.

```bash 
#To get started first install the node modules.
npm i
#Once installed open SQL as seen below and enter password if needed and open the source files.
mysql -u (username) root -p (password)
SOURCE db/schema.sql
SOURCE db/seed.sql
#You can now close out the SQL by typing..
quit

#Now you are in the terminal and can run the application by typing the following below. The program will begin and direct the user to go through the application once completed.
node server.js
```

## Usage

```python
The gif file below shows an example of how the application should look.
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
