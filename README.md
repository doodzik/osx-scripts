# rmapp

Removes an app completely from your osx system

# installation

```
$ brew tap doodzik/tap https://github.com/doodzik/tap
$ brew instal rmapp
```

## add the autocompletion feature
```bash
# add this if you use zshrc
autoload bashcompinit
bashcompinit

# add this to your bashrc get autocomplete
complete -F _rmapp_app_list rmapp
```

# usage

```
$ rmapp $APP
```

It has autocompletion to look up all available app names build in

#LICENSE 

GPL v3
