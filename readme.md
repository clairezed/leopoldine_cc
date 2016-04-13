Léopoldine Ciné Club Website
=========

Website of the confidential Léopoldine Ciné Club, wonderful excuse to try out Jekyll

## Jekyll installation

```
$ gem install jekyll
~ $ jekyll new myblog
~ $ cd myblog
~/myblog $ jekyll serve
# => Now browse to http://localhost:4000
```

To install jekyll inside an existing directory : `jekyll new .`

If the existing directory isn’t empty : `jekyll new . --force`


## Jekyll usage

```
$ jekyll build
# => The current folder will be generated into ./_site

$ jekyll build --destination <destination>
# => The current folder will be generated into <destination>

$ jekyll build --source <source> --destination <destination>
# => The <source> folder will be generated into <destination>

$ jekyll build --watch
# => The current folder will be generated into ./_site,
#    watched for changes, and regenerated automatically.

$ jekyll serve
# => A development server will run at http://localhost:4000/
# Auto-regeneration: enabled. Use `--no-watch` to disable.

$ jekyll serve --detach
# => Same as `jekyll serve` but will detach from the current terminal.
#    If you need to kill the server, you can `kill -9 1234` where "1234" is the PID.
#    If you cannot find the PID, then do, `ps aux | grep jekyll` and kill the instance. [Read more](http://unixhelp.ed.ac.uk/shell/jobz5.html).
```

## Resources

- https://borisschapira.com/2016/02/jekyll-codeship/