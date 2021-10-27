# Hello `npm`
## Instructions
1. Download or clone this repo to your workspace
2. Navigate to the root of the project on the command line.
3. Use your operating system to determine the file size of this new project and how many files there are:
    - File size: 188 kB on disk
    - Number of items: 5 files
4. Install dependencies with `npm install`
5. Check the file size and number again:
    - File size: 2.29
    - Number of files: 1090
6. Questions to ask:
    - What has changed? the file size had tripled, and my package.json when from super lines of code to 13 because all the information that was stored there is now in the node_modules.
    - What is taking up the extra disk space? the node_modules
    - Would we want to include `node_modules` in our repositories? Hint: the answer is no. No because you don't want to require everyone to download the node_module folder from git hub when they can just download it with npm locally ont their computer.


A `.gitignore` file is provided to exclude the `node_modules` directory. 