+++
type="page"
title="Specifying a specific version"
+++

When using modules, it is possible to use specific package versions
when compiling. I've found that the easiest way to do this is through
`go mod` using `tidy`, `vendor`, and `go get`.


{{< highlight sh >}}

# make sure you're outside of your GOPATH and you have modules initialized
go mod init github.com/thefury/sooperpackage

# get the specific version needed: hash, tag, branch can all be used
go get github.com/thefury/required_package@978da6523
go mod vendor # I like to do this in any case

# you should see that the correct version is now used
cat go.mod

{{< /highlight >}}

