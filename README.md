# The Right Way to Get the Directory of a bash Script

based on article [here](https://www.ostricher.com/2014/10/the-right-way-to-get-the-directory-of-a-bash-script)

```bash
"$( cd "$( dirname "${BASH_SOURCE[0]}" )" && pwd )"
```

