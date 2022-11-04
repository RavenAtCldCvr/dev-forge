1. Configure authentication with GitHub
    ``` bash
    gh auth login
    ```
   
2. Choose the following options when prompted
    ```bash
    ? What account do you want to log into?
    GitHub.com
    
    ? What is your preferred protocol for Git operations?
    HTTPS
    
    ? Authenticate Git with your GitHub credentials?
    Yes
    
    ? How would you like to authenticate GitHub CLI?
    Login with a web browser
    ```

3. Verify your access via git CLI

    Clone a public repository.
    ```bash
    git clone https://github.com/github/dev.git github-test
    ```

    Sample output:
    ```bash
    Cloning into 'github-test'...
    remote: Enumerating objects: 19, done.
    remote: Total 19 (delta 0), reused 0 (delta 0), pack-reused 19
    Receiving objects: 100% (19/19), 5.10 KiB | 5.10 MiB/s, done.
    Resolving deltas: 100% (3/3), done.
    ```

4. The public repository should be cloned successfully.
    ```bash
    ls | grep github-test
    ```

5.  Remove the unused code used for testing github access.
    ```bash
    rm -rf github-test
    ```
