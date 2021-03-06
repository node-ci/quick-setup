# nci quick setting up

This repo contains sample configuration for setup
[nci](https://github.com/node-ci/nci) quickly.

Clone quick setup repo, go into it and install dependencies:

```sh

git clone https://github.com/node-ci/nci-quick-setup && cd nci-quick-setup && npm install

```

run nci:


```sh

node_modules/.bin/nci

```

that's all, now you can experiment with it by adding/changing projects,
use web interface (on http://127.0.0.1:3000 by default) for run project builds,
etc.

Currently web interface doesn't support adding new projects or editing of
existing projects. You have to do that by adding/editing project config
file.

See [basic tutorial](https://github.com/node-ci/nci/blob/master/docs/tutorials/standalone-web-ui.md)
for setup and usage details.
