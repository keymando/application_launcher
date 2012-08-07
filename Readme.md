Application Launcher
-----

This is a Keymando plugin that pulls applications from a directory and creates Keymando commands


Usage
=======

```ruby
ApplicationLauncher.register('/Applications', :max_depth => 2)
ApplicationLauncher.register('/Developer/Applications', :max_depth => 3)

```

Requirements
=======

Keymando version 1.1
