# SQL-Employee-Tracker
A easy interactive app that allows the user to track the roles and titles of employees

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

<div style="padding:54.17% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/703502192?h=3a2b809c26&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="New Recording - 4/26/2022, 7:31:43 PM"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
