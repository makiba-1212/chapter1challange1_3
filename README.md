# Config File Reader (Java)

## Description
This Java program reads and validates a configuration file named `config.txt`.

## How It Works
- Reads the **first line** as a configuration version number
- Throws an error if the version is **less than 2**
- Reads the **second line** as a file path
- Checks if the specified file exists
- Displays clear error messages if something goes wrong

## config.txt Format
