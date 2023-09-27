# plugin-boilerplate
Build docker image with NocoBase and custom plugin

## Development

```bash
git clone git@github.com:nocobase/nocobase.git my-nocobase-app
git clone git@github.com:nocobase/plugin-boilerplate.git my-nocobase-app/packages/plugins/@nocobase/plugin-boilerplate
cd my-nocobase-app
yarn install
```

Modify `.env`

```bash
APPEND_PRESET_LOCAL_PLUGINS=boilerplate
```

Install and start

```bash
yarn nocobase install
yarn dev
```
