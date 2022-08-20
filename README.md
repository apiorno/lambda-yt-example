### Build for Linux to work on AWS
```
GOARCH=amd64 GOOS=linux go build main.go
```

### Zip to upload to AWS lambda function

```
zip function.zip main 
```