# Setup

when ssh key exist in your mechine

```cmd
cat ~/.ssh/id_rsa.pub
```

then copy and past ssh key in your github account

test github access:

```cmd
ssh -T git@github.com
```

set this type of url to push github change

```cmd
git remote set-url origin git@github.com:tawfiqh58/aws-amplify.git

git push -u origin main
```
