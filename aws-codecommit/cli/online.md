# Create Repo in CodeCommit 

## Step 1: Create Repo in code-commit 

![image](https://github.com/user-attachments/assets/56799e0b-bf73-4080-8d3e-c084e35bc649)

![image](https://github.com/user-attachments/assets/4dc3b110-0cff-4c3d-a4e5-9a3e45479525)

  * Finally: Click on "Erstellen"

![image](https://github.com/user-attachments/assets/3010511d-f5fe-42f5-9086-1747d2b86f40)

  * Click on "URL klonen" -> HTTPS clonen

![image](https://github.com/user-attachments/assets/a29cc874-b666-409a-9854-70d7833b9afd)

  * URL will be copied to clipboard

## Step 2: Reconnect to aws (if you have not been there for a while = token expired) 

```
# in the terminal 
aws sso login --sso-session my-sso
```

## Step 3: Rewrite url and use for pushing in PyCharm 

  * You must have a profile setup, in my case it is: Git_Schulung, because my profile looks like this:

![image](https://github.com/user-attachments/assets/6033ec22-62e4-4a7b-8cef-fc4ee71c1475)

```
# Put url in editor and rewrite it as follows:
# e.g.
https://git-codecommit.eu-central-1.amazonaws.com/v1/repos/git-schulung_JochenMetzger
# rewrite to: (Git_schuluung is your profile)
codecommit://Git_Schulung@git-schulung_JochenMetzger
```

```
git remote add origin codecommit://Git_Schulung@git-schulung_JochenMetzger
git push -u origin master
```



