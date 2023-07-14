# Description
Cli utility that allows you to export links from your deep.

# Installation
Navigate to the root directory of the project and then run

```shell
npm install --global deep-export
```

# Usage
Explain how to use the code and provide examples of command-line usage.
If downloaded locally:
```shell
npx deep-export --url <url> --jwt <jwt> --file <file> [--overwrite] [--debug]
```
If downloaded globally:
```shell
deep-export --url <url> --jwt <jwt> --file <file> [--overwrite] [--debug]
```

--url: The URL to export data from. (required)  
--jwt: The JWT token. (required)  
--file: [Optional] Name of dump.
--overwrite: [Optional] Whether to overwrite your links if it already exists.  
--debug: [Optional] Allows you to see which links are inserted and in what order, which allows you to track down errors.


# Related Links
https://deep.foundation
https://github.com/deep-foundation
