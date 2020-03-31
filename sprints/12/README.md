# Sprint 12 - Grand Chelem

<img src="https://images.unsplash.com/photo-1574781689744-c255032f79da?ixlib=rb-1.2.1&q=85&fm=jpg&cs=srgb&w=900&h=300&fit=crop">

## Goal

- Finish Nexus Transition
- Make Prisma Plugin functional

## Changelog

- `nexus-future`
  - unfeat: removed `nexus db`
  - unfeat: removed `server.custom`
  - perf: `nexus dev` refresh time `-1000ms`
  - feat: transitioned to nexus@0.20.0
  - feat: tree shakable plugin runtimes
  - design: plugin core deps design
  - tests: system test plugin system
  - improve: no ts-node in build system
  - improve: start module always inlines runtime plugins
- `nexus-plugin-prisma`
  - feat: support Prisma 2 preview 25
  - feat: no more auto-migrations
  - feat: support for introspection workflow
- Nexus website
  - Improved navigation
  - Standalone component docs
  - Code block height styles

## Video

Will be posted later

## Details

### `nexus-future`

#### feat: transitioned to nexus@0.20.0

![](nexus-transition.png)

#### perf: `nexus dev` refresh time `-1000ms`

_before_

![](nexus-before.png)

_after_

![](nexus-after.png)

#### feat: tree shakable plugin runtimes

![](nexus-plugin-shakable.png)

#### design: plugin core deps design

![](nexus-plugin-design.png)

#### unfeat: removed `server.custom`

![](nexus-server-express.png)

### Nexus Website

![](website-nav.png)

![](website-max-height.png)

![](website-schema.png)
