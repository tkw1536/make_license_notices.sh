__Superseded by https://github.com/tkw1536/gogenlicense__
 
# make_license_notices.sh

Generate some go code for license notices. 

This bash script automatically generates license information to be included as a string and as documentation inside a go package. 
It is intended to be used by means of the [`go generate`](https://golang.org/pkg/cmd/go/internal/generate/) command with a comment inside the code such as:

```bash
//go:generate bash make_license_notices.sh INPACKAGE OUTPACKAGE OUTFILE DECLARATION
```

The script achieves this by parsing various outputs of the excellent https://github.com/google/go-licenses package. 

`make_license_notices.sh` is licensed under the terms of the [MIT License](LICENSE). 
