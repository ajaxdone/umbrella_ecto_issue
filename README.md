# umbrella_ecto_issue

Steps to reproduce the issue:
```
  0 mix new hello_umbrella --umbrella
  1 cd hello_umbrella/
  2 cd apps
  3 mix phx.new hello_phx
  4 cd hello_phx/
  5 mix ecto.create
```


Error msg:
```
$ mix ecto.create
warning: could not find Ecto repos in any of the apps: [:hello_phx].

You can avoid this warning by passing the -r flag or by setting the
repositories managed by those applications in your config/config.exs:

    config :hello_phx, ecto_repos: [...]
```
