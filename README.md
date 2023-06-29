# Generate SSH key for Github Authentication
- Step 1: Run this in local `ssh-keygen -t rsa -b 4096 -C "hemt1912@gmail.com"`
- Step 2: Copy the content of public key `~\.ssh\id_rsa.pub` to Github.com > Settings > SSH and GPG keys > New SSH Key

# How to clone code to local
- git clone git clone git@github.com:hemt1912/sydney.git

# How to comit file on Github
- step 1: git add .\FILE_NAME.abc (file has to stay in reponsitory)
- step 2: git status
- step 3: git commit -m "any think"
- step 4: git status (once again)
- step 5: git push origin master
            