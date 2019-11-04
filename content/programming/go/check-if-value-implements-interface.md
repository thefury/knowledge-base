---
title: "Check if Value Implements Interface"
date: 2019-11-04T12:27:08-05:00
---

{{< highlight go >}}

import (
  "io"
  "strings"
)

func main() {
    val := strings.NewReader("haloo!")
    _, ok := val.(io.Reader)
    
    fmt.Printf("val implements io.Reader: %v", ok)
}

{{< /highlight >}}
