# kube-devel-stuff
Notes / scripts / tools for developing kubernetes


make test WHAT=./pkg/kubectl KUBE_COVER=y

```sh
cat ~/go_dists/go-1.11.2/gorc
#!/bin/bash
cd $(dirname $0)
echo $PWD
export GOROOT=$PWD
export PATH=$GOROOT/bin:$PATH
```
