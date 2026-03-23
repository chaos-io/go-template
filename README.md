# <repo>

## create project 

```bash
fino2 create --package=. --output=.. --repo=github.com/chaos-io/<repo> --version=v0.1.0 --license=MIT --author=cc --email=cc@email.com --organization=cc.org
```

## build api
```bash
fino2 build --targets=api
```

## build service
```bash
fino2 build --targets=api,serivce
```
