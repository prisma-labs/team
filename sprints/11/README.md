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
- fix: layout with multiple graphql modules at varying directory depths ([commit](https://github.com/graphql-nexus/nexus-future/commit/b2190af09ceefed7617cbdcb59e4ea8cfbde5ca8))
- feat: outputs nullable by default ([commit](https://github.com/graphql-nexus/nexus-future/commit/50d3e24de6c8d5cf85319f81d768eb8352bafacd))
- feat: setting to generate GraphQL SDL ([commit](https://github.com/graphql-nexus/nexus-future/commit/9ed366565443b2de5a956552dfffbec2c48e6923))
- feat: initial backing types system ([commit](https://github.com/graphql-nexus/nexus-future/commit/bb2401fb49682ef982a1ef1537d41cb4ade4216a))
- feat: remove `$ nexus generate` ([commit](https://github.com/graphql-nexus/nexus-future/commit/2abd73da23fd4564822bdf8c53c7d16b4b758aae))
- `addToContext` api
  - fix: dedupe imports in typegen ([commit](https://github.com/graphql-nexus/nexus-future/commit/f6e21135b74ab7bf51fa1c7c7d0dffd05b2b5824))
  - fix: no truncate types in typegen ([commit](https://github.com/graphql-nexus/nexus-future/commit/8eba6934579a01b725f1d8bbbe6b767415f9fc9f))
  - feat: support native node types ([commit](https://github.com/graphql-nexus/nexus-future/commit/bfca8cfbe9f451c9c0b78dcb50a127d4fc4b62a0))
  - feat: support intersections ([commit](https://github.com/graphql-nexus/nexus-future/commit/851b77da08fd1fddff19ee92db14b9658d84e12e))
  - feat: support aliases ([commit](https://github.com/graphql-nexus/nexus-future/commit/c457e5230da7343683b13fa3c488ec7a148dbff7))
  - feat: support interfaces ([commit](https://github.com/graphql-nexus/nexus-future/commit/ae0c70d2726d1bb5f291d11cd5b6c7c4eb9e2fef))
  - improve: simplify return type ([commit](https://github.com/graphql-nexus/nexus-future/commit/6f687ac442641f6666101a03178aa15c5aa6db26))

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

## Next Sprint

- Finish the Nexus transition
- Put forward a tentative system/direction for how schema/framework plugins play out
- Integrate Prisma plugin docs into the Nexus website
- Schema guide building blocks
- Schema API docs

## Details
