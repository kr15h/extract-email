# extract-email

Extract email addresses as comma-separated list using sed and things.

## Usage

1. Create `guestlist.txt` with content that contains one email address per line.
2. Run `./extract-email` script
3. Check output in `guestlist-out.txt`

```
$ ./extract-email
Reading from guestlist-src.txt
Result saved in guestlist-out.txt
$ _
```
## Limitations

Works on Mac OS X for now. Because of the `-E` flag. Should be `-r` on Unix / Linux.
