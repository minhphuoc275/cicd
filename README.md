## 1. Create a new repository on the command line
```
echo "# cicd" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:minhphuoc275/cicd.git
git push -u origin master
```

## 2. Push an existing repository from the command line
```
git remote add origin git@github.com:minhphuoc275/cicd.git
git push -u origin master
```