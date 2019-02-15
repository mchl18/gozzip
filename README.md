# gozzip
GO zip utility

## Usage example
```
err := gozzip.ZipFiles("archive.zip",  []string{"foo,jpg", "bar.jpg"})
```

If successfull, the zip will be created at the given file name.
