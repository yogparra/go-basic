
# Go
```
go mod init github/yogparra/go-basic
go mod tidy
```

# Git
```
gh auth login
gh repo create yogparra/go-basic
```

# Git Acctions
```
mkdir -p .github/workflows
touch .github/workflows/ci.yml
```

# Go test Ci git action
```
go test -v -cover ./../..
```