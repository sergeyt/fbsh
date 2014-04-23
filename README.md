[![Deps Status](https://david-dm.org/sergeyt/fbsh.png)](https://david-dm.org/sergeyt/fbsh)
[![DevDeps Status](https://david-dm.org/sergeyt/fbsh/dev-status.png)](https://david-dm.org/sergeyt/fbsh#info=devDependencies)

[![NPM][npm]](https://nodei.co/npm/fbsh/)

# fbsh

FogBugz shell

Installation
------------

Install with `npm`:

``` bash
$ npm install [-g] fbsh
```

Commands
--------
``` bash
ls                           - list active cases from current filter
ls f                         - list available filters
ls p                         - list available projects
ls m                         - list available milestones
ls u                         - list available users
ls c                         - list available case categories
ls s                         - list available case statuses
u id                         - print user info
search q                     - searches cases by specified q
take case [comment]          - assign given case to logon user
resolve [case] [comment]     - resolves current or given case
close case [comment]         - close given case
reopen case [comment]        - reopen given case
assign case userId [comment] - assign given case to given user
kick case [comment]          - return given case back to team
log [case] [comment]         - logs specified comment to given case
q[uit]                       - exit from this shell
exit                         - exit from this shell
help                         - print this command list
```

## TODO
* move fbsh from fogbugz.js to reduce fogbugz.js dependecies
* document fbsh commands in readme.md

[npm]: https://nodei.co/npm/fbsh.png?downloads=true&stars=true
