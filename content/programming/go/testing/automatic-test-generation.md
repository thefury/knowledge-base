---
title: "Automatic Test Generation"
date: 2019-10-25T11:47:13-04:00
---

{{< highlight sh >}}
# geterate test skeleton for all Decrypt methods in `crypt`
gotests -only "Decrypt*" crypt/
{{< /highlight >}}
