# Youtube GO

A Go package prepared for Video searching on youtube.

> This project was developed inspired by [youtube-sr](https://github.com/DevAndromeda/youtube-sr)

## Installation
```bash
go mod init project_name && go get github.com/SherlockYigit/youtube-go
```

## Example
```go
package main

import (
    "fmt"
    youtube "github.com/SherlockYigit/youtube-go"
)

func main() {
    res := youtube.SearchVideos("Jim Yosef Hate You")

    fmt.Println(res)
}
```
