# Unix
## Navigation
### man
-`space` to scroll down a page<br>
-`b` to go back a page<br>
-`q` to quit<br>
-arrow keys to scroll line by line
<br>
## Essential Commands
| The absolute basics | File control |Viewing, creating, or editing files | Misc. useful commands | Power commands | Process-related commands
| ---------- | ----------- | ----------- | ----------- | ---------- | ----------- |
| ls | mv | less | man | uniq | top |
| cd | cp | head | chmod | sort | ps |
| pwd | mkdir | tail | source | cut | kill |
| | rmdir | touch | wc | tr | |
| | rm | nano | | grep | |
| | (pipe) | | | sed | |
| | > (write to file) | | | | |
| | < (read from file) | | | | |

### grep
used to filter search a file for a particular pattern of characters and display all lines containing the pattern
#### command
`grep [options] pattern [files]`
#### options
-`-c` print a count of the lines matching the pattern<br>
-`-h` display matched lines but not filenames<br>
-`-i` ignore case when matching<br>
-`-l` display filenames only<br>
-`-n` display matched lines and their line numbers<br>
-`-v` print all lines that do not match the pattern<br>
-`-e exp` specifies the expression, can use multiple times<br>
-`-f file` takes patterns from file, one per line<br>
-`-E` treats pattern as extended regular expression<br>
-`-w` match whole word<br>
-`-o` print only the matched parts of a matching line, each part on a separate line<br>
-`-A n` prints searched lines and n lines after the result<br>
-`-B n` prints searched lines and n lines before the result<br>
-`-C n` prints searched lines and n lines after before the result<br>
-`-R` search recursively in a directory (replace `[files]` with `[directory]`)<br>
