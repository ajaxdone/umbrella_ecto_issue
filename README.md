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
