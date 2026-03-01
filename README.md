# repo for my mvp minisys-lab

**add target repo**
```bash
git submodule add https://github.com/user/repo.git path/to/dir
git commit -m "feat(xxx): add xxx"
```

**clone this repo**
```bash
git clone --recurse-submodules <repo-url>
```

**update target repo**
```bash
cd path/to/submodule
git pull origin main
cd ..
git add path/to/submodule
git commit -m "update submodule"
```
> **OR** use .gitmodules
> config the branch in .gitmodules

**update all repos**

```bash
git submodule update --remote --recursive
```
> and more 
