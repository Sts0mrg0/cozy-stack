## cozy-stack fixer

A set of tools to fix issues or migrate content for retro-compatibility.

### Synopsis


A set of tools to fix issues or migrate content for retro-compatibility.

```
cozy-stack fixer [command] [flags]
```

### Options

```
  -h, --help   help for fixer
```

### Options inherited from parent commands

```
      --admin-host string   administration server host (default "localhost")
      --admin-port int      administration server port (default 6060)
      --client-use-https    if set the client will use https to communicate with the server
  -c, --config string       configuration file (default "$HOME/.cozy.yaml")
      --host string         server host (default "localhost")
  -p, --port int            server port (default 8080)
```

### SEE ALSO
* [cozy-stack](cozy-stack.md)	 - cozy-stack is the main command
* [cozy-stack fixer albums-created-at](cozy-stack_fixer_albums-created-at.md)	 - Add a created_at field for albums where it's missing
* [cozy-stack fixer jobs](cozy-stack_fixer_jobs.md)	 - Take a look at the consistency of the jobs
* [cozy-stack fixer md5](cozy-stack_fixer_md5.md)	 - Fix missing md5 from contents in the vfs
* [cozy-stack fixer mime](cozy-stack_fixer_mime.md)	 - Fix the class computed from the mime-type
* [cozy-stack fixer onboardings](cozy-stack_fixer_onboardings.md)	 - Add the onboarding_finished flag to user that have registered their passphrase

