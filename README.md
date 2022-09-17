# ProMC Suite of Plugins

This repository aims to act as the home to our most popular ProMC plugins. The aim is to simplify the process
that those wanting to contribute have to go through to configure their work environment. By providing
everything in a central location, we can easily centralize dependencies, versioning, etc.

## Cloning & Building
To clone down the whole project, simply run:
```bash
git clone --recurse-submodules git@github.com:promcteam/promc-parent.git && cd promc-parent
```

From there, one can package the entire suite by running `mvn package` -- Assuming all the appropriate GitHub
Packages authentication has been set up, everything should be pretty seamless and generate a `./ProBuilds`
directory containing all the built plugins, ready to go!