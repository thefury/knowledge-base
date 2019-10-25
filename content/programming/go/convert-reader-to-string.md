---
title: "Convert io.Reader to String"
date: 2019-10-25T17:09:43-04:00
---

Converting from an `io.Reader` to a `string`

{{< highlight go >}}

func ToString(r io.Reader) string {
  var buf.BytesBuffer
  buf.ReadFrom(r)
  
  return buf.String()
}

{{< /highlight >}}
