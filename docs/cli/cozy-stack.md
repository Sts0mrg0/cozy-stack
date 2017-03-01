## cozy-stack

cozy-stack is the main command

### Synopsis


Cozy is a platform that brings all your web services in the same private space.
With it, your web apps and your devices can share data easily, providing you
with a new experience. You can install Cozy on your own hardware where no one
profiles you.

```
cozy-stack
```

### Options

```
      --admin-host string      administration server host (default "localhost")
      --admin-port int         administration server port (default 6060)
      --assets string          path to the directory with the assets (use the packed assets by default)
  -c, --config string          configuration file (default "$HOME/.cozy.yaml")
      --couchdb-url string     CouchDB URL (default "http://localhost:5984/")
      --fs-url string          filesystem url (default "file://localhost//storage")
      --host string            server host (default "localhost")
      --log-level string       define the log level (default "info")
      --mail-disable-tls       disable smtp over tls
      --mail-host string       mail smtp host (default "localhost")
      --mail-password string   mail smtp password
      --mail-port int          mail smtp port (default 465)
      --mail-username string   mail smtp username
  -p, --port int               server port (default 8080)
      --subdomains string      how to structure the subdomains for apps (can be nested or flat) (default "nested")
```

### SEE ALSO
* [cozy-stack bug](cozy-stack_bug.md)	 - start a bug report
* [cozy-stack completion](cozy-stack_completion.md)	 - Output shell completion code for the specified shell
* [cozy-stack config](cozy-stack_config.md)	 - Show and manage configuration elements
* [cozy-stack doc](cozy-stack_doc.md)	 - Print the documentation
* [cozy-stack files](cozy-stack_files.md)	 - Interact with the cozy filesystem
* [cozy-stack instances](cozy-stack_instances.md)	 - Manage instances of a stack
* [cozy-stack serve](cozy-stack_serve.md)	 - Starts the stack and listens for HTTP calls
* [cozy-stack status](cozy-stack_status.md)	 - Check if the HTTP server is running
* [cozy-stack version](cozy-stack_version.md)	 - Print the version number
