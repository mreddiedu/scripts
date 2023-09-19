# scripts

My personal script repo to speed up the process.

## GitHub Script 
(reminder: create a script for this)

### How to create a new repository from IntelliJ on a local machine and connect to a remote repository:

1. **In IntelliJ**: Create a new 'Project...'.
2. **Navigate to the project directory**: 
    ```bash
    cd ~/GitHub/mreddiedu/newProject
    ```
3. **Stage your changes**: 
    ```bash
    git add .
    ```
4. **Commit your changes**: 
    ```bash
    git commit -m "Initial commit"
    ```
5. **On GitHub**: Create a new repository and copy its URL. For example: 
    ```
    https://github.com/mreddiedu/javaPlayground.git
    ```
6. **Get Personal Access Token**:
    - ![Example Image 1](https://github.com/mreddiedu/scripts/assets/50150815/2a3a35a9-3f4e-4d67-9b6b-667364dbbed5.png)
    - ![Example Image 2](https://github.com/mreddiedu/scripts/assets/50150815/a79bc78f-282b-4bbc-a3ec-6bd4c6fbc5e2.png)
    - ![Example Image 3](https://github.com/mreddiedu/scripts/assets/50150815/082f88b7-9f0b-4109-baa0-8d8ca7077495.png)
   
    Visit One Pass for personal access token: Search for `github.com`.

7. **On local machine**, in the same directory:
    ```bash
    git push -u origin master https://github.com/mreddiedu/<repo-name-here>.git
    ```
    When prompted:
    ```
    Username for 'https://github.com': mreddiedu
    Password for 'https://mreddiedu@github.com': <Personal-Access-Token>
    ```
8. **On GitHub Desktop**: Add repository.
