# Sprint 11 - Chewbacca

<img src="https://images.unsplash.com/photo-1513704519535-f5c81aa78d0d?ixlib=rb-1.2.1&q=85&fm=jpg&cs=srgb&w=900&h=300&fit=crop">

## Goal

- Nexus API Docs
- Nexus Testing

## Changelog

#### `nexus-future`

- docs: schema guide backing types
- docs: schema guide nullability
- docs: schema guide object type
- docs: schema guide enum
- docs: more schema API
- docs: new introduction
- fix: layout with multiple graphql modules at varying directory depths ([commit](b2190af09ceefed7617cbdcb59e4ea8cfbde5ca8))
- feat: outputs nullable by default
- feat: setting to generate GraphQL SDL
- feat: initial backing types system ([commit](bb2401fb49682ef982a1ef1537d41cb4ade4216a))
- feat: remove `$ nexus generate`
- `addToContext` api
  - fix: dedupe imports in typegen
  - fix: no truncate types in typegen
  - feat: support native node types
  - feat: support intersections
  - feat: support aliases
  - feat: support interfaces
  - improve: simplify return type

#### `nexus-plugn-prisma`

- tests: e2e tests on every `nexus-plugin-prisma` trunk commit

#### `nexus-prisma`

- feat: support for prisma 0.23
- chore: proper pinning of Prisma 2 binaries
- design: alignment on `relateBy`

#### `other`

- moved `prisma-labs/nexus-future-examples` to `graphql-nexus/examples`
- moved `prisma-labs/nexus-prisma` to `graphql-nexus/nexus-prisma`

## Video

Will be posted later

## Details
