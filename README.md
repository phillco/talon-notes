# talon-notes

Miscellaneous snippets and things I've learned from using [Talon](https://talonvoice.com/).

### Inspect the contents of a list from the REPL

```
registry.lists['user.listname'][-1]
```

For example:
```
>>> registry.lists['user.launch'][-1]
{
    'vimac': '/Applications/Vimac.app',
    'dragon': '/Applications/Dragon.app',
    'lastpass': '/Applications/LastPass.app',
    'visual studio code': '/Applications/Visual Studio Code.app',
    'visual': '/Applications/Visual Studio Code.app',
    'studio': '/Applications/Visual Studio Code.app',
    'code': '/Applications/Visual Studio Code.app',
    ...
   ```

Caveat from aegis (Talon creator):
> (Please do not use the registry to implement functionality in your scripts besides debug/help code, there's ~always a better way)
