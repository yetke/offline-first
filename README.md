# Offline First

An opinionated list of tools that provide offline-first functionality for your software.

<details>

<summary>Table of Contents</summary>

**Software / Libraries**

* [RxDB](#rxdb)
* [Dexie.js](#dexie)
* [SignalDB](#signaldb)
* [Watermelondb](#watermelondb)
* [ElectricSQL](#electric-sql)
* [Fireproof](#fireproof)
* [Earthstar](#earthstar)
* [Evolu](#evolu)
* [Tinybase](#tinybase)
* [Kintojs](#kintojs)
* [Gun.eco](#guneco)
* [Simperium](#simperium)
* [Pouchdb](#pouchdb)
* [Orbitjs](#orbitjs)
* [Replicache](#replicache)
* [DXOS](#dxos)
* [Syncedstore](#syncedstore)
* [SQLSync](#sqlsync)


**[Interesting Articles](#interesting-articles)**
</details>

### RxDB

> "A fast, local first, reactive Database for JavaScript Applications"

🔗 [Website](https://rxdb.info/) | `</>` [Github](https://github.com/pubkey/rxdb)

Maintenance Status: ✅ Actively Maintained

📋 License: `Apache 2.0`, `SSPL`, `proprietary`

✅ Feature rich and "complete"

✅ Supports Full Text Search and Client Side Encryption (Premium)

✅ The author of RxDB has interesting [articles](https://rxdb.info/articles/local-first-future.html) about offline first which are worth reading even if you do not want to use RxDB.

⚠️ Be aware that for many essential features like IndexedDB Adapter (better performance in Web Applications), SQLite Adapter (better performance in Electron / Mobile applications) you need to pay for RxDB Premium

❌ A bit over-complicated structure, may be overkill for small projects

❌ Even if you use the RxServer backend you still have to do a bit to make it work as its not "batteries included".

💵 Pricing: 

- Core Package: Free & Open Source (Apache 2.0, SSPL)
- Premium: Including Features like IndexedDB & SQLite Adapter, Encryption, Server Adapters for Koa & Fastify for native apps 300€-1800€ yearly

Last updated: 29.03.2025

### Dexie

> "Dexie.js is a wrapper library for indexedDB - the standard database in the browser"

🔗 [Website](https://dexie.org/) | `</>` [Github](https://github.com/dexie/Dexie.js)

📋 License: `Apache 2.0` (Client), `Proprietary` (Backend)

✅ Docs for usage with React, Svelte, Angular, Vue and Vanilla JS.

⚠️ Even though the docs seem complete, navigating through it can be a hassle as the Table of Contents is not well-structured, documentation, API reference and Roadmap are not differentiated and there is no search functionality. Anyway, [this](https://dexie.org/docs/Tutorial/) is a good starting point if you want to use Dexie.js

❌ The backend is not Open Source

💵 Pricing:
* Hosted SaaS solution: 0.12ct/user/month (in 25 user packs at 3$)
* On Prem (self-hosted): 3495$ with five years of updates and 1 year support
* On Prem (self-hosted with source code access): 7995$ with five years of updates and 1 year support

Last updated: 28.03.2025

### SignalDB

"SignalDB is a reactive, local-first JavaScript database designed for modern web applications. It combines signal-based reactivity with powerful local data management and real-time synchronization capabilities."

🔗 [Website](https://signaldb.js.org/) | `</>` [Github](https://github.com/maxnowack/signaldb)

📋 License: `MIT License`

✅ Adapters for Angular, React, Solid, Svelte and Vue.js

✅ Examples for Replication with Backends like Supabase, Firebase, Appwrite etc.

💵 Pricing: Free

### Watermelondb

> "🍉 Reactive & asynchronous database for powerful React and React Native apps ⚡️"

WatermelonDB uses LokiJS in the web and SQLite when used with NodeJS (like in electron apps or mobile apps)

🔗 [Website](https://watermelondb.dev/docs) | `</>` [Github](https://github.com/nozbe/WatermelonDB)

📋 License: `MIT License`

✅ Lean yet thorough documentation

⚠️ You may need to write advanced / direct db [queries](https://watermelondb.dev/docs/Query) twice if you use both backends (SQLite on React Native and LokiJS on the web).

❌ React & React Native only

❌ You have to build your own backend. However there is [documentation](https://watermelondb.dev/docs/Sync/Intro) on how you should implement sync

💵 Pricing: Free

### Electric-SQL

> "Sync little subsets of your Postgres data into local apps and services."

🔗 [Website](https://electric-sql.com/) |`</>` [Github](https://github.com/electric-sql/electric)

📋 License: `Apache 2.0`

✅ Framework Agnostic, Examples for React, Tanstack etc exist

✅ Cloud Hosting in Private Beta (Though self-hosting is possible)

✅ [Supports](https://electric-sql.com/docs/guides/security#encryption) E2E encryption but you need to do a bit of work yourself

⚠️ When self-hosting you need to deploy a proxy in front of ElectricSQL for auth and PostgreSQL for storage.

💵 Pricing:
* self-hosted: free
* cloud: unkown (still in private-beta)

### Fireproof

> "Fireproof is the vibe coding database that lets you skip the backend."

🔗 [Website](https://fireproof.storage/) | `</>` [Github](https://github.com/fireproof-storage/fireproof)

📋 License: `Permissive License Stack` (`Apache 2.0` OR `MIT License`)

✅ React & SolidJS Tutorial

### Earthstar

> "Storage for private, distributed, offline-first applications."

🔗 [Website](https://earthstar-project.org/) | `</>` [Github](https://github.com/earthstar-project/earthstar)

📋 License: `LGPL-3.0`

⚠️ Beta Software (last check: 03.04.2025)

### Evolu

> "A local-first platform designed for privacy, ease of use, and no vendor lock-in"

🔗 [Website](https://www.evolu.dev/) | `</>` [Github](https://github.com/evoluhq/evolu)

📋 License: `MIT License`

✅ Supports E2E encryption

⚠️ The codebase is currently being rewritten (last check: 02.04.2025)

Note: Uses SQLite on all platforms. On the web via OPFS.

### Tinybase

> "The reactive data store for local‑first apps."

🔗 [Website](https://tinybase.org/) | `</>` [Github](https://github.com/tinyplex/tinybase)

📋 License: `MIT License`

### KintoJS

🔗 [Website](https://kintojs.readthedocs.io/en/latest/) | `</>` [Github](https://github.com/Kinto/kinto.js?tab=readme-ov-file)

📋 License: Apache 2.0

✅ [Kinto Storage](https://github.com/Kinto/kinto) as a backend (Python 3.9+ & PostgreSQL)

### Gun.eco

> "An open source cybersecurity protocol for syncing decentralized graph data."

🔗 [Website](https://gun.eco/) | `</>` [Github](https://github.com/amark/gun)

📋 License: `Triple Licensed` (`Zlib` / `MIT License` / `Apache 2.0`)

### Simperium

> "Simperium is a cross-platform data sync service."

🔗 [Website](https://simperium.com/overview/) | [Github](https://github.com/Simperium/simperium-js)

✅ Used by Simplenote

⚠️ Seems a bit abandoned

❌ Closed Source backend

💵 Pricing: [Starts](https://simperium.com/pricing/) at 25$ for up to 250k requests/month

### Pouchdb

> "🦘 - PouchDB is a pocket-sized database."

🔗 [Website](https://pouchdb.com/) | `</>` [Github](https://github.com/pouchdb/pouchdb)

📋 License: `Apache 2.0`

✅ Create a database for each user

⚠️ Syncs/Stores the entire revision history locally

❌ Needs CouchDB as a backend

### Orbitjs

"Composable data framework for ambitious web applications."

🔗 [Website](https://orbitjs.com/) | `</>` [Github](https://github.com/orbitjs/orbit)

📋 License: `MIT License`

⚠️ Maintenance Status: [unknown / not actively maintained](https://github.com/orbitjs/orbit/issues/994)

### Replicache

> "Realtime sync for any backend stack"

🔗 [Website](https://replicache.dev/) | `</>` [Source](https://github.com/rocicorp/mono/tree/main/packages/replicache)

📋 License: `Apache 2.0`

⚠️ The development is in "maintenance mode".

❌ You have to build your own backend

### Orbitdb

> "Peer-to-Peer Databases for the Decentralized Web"

🔗 [Website](https://orbitdb.org/) | `</>` [Github](https://github.com/orbitdb/orbitdb)

📋 License: `MIT License`

### DXOS

> "The Decentralized Operating System"

🔗 [Website](https://www.dxos.org/) | `</>` [Github](https://github.com/dxos/dxos)

📋 License: `MIT License`

⚠️ Stability and Security is **not guarenteed** as DXOS is currently in a ["preview state"](https://docs.dxos.org/guide/notice.html). - (last checked: 02.04.2025)

---

## Not actively maintained tools

These tools are not actively maintained so it is not recommended to use them in new projects. However they might provide insight and inspiration for your new project.

### SyncedStore

> "SyncedStore CRDT is an easy-to-use library for building live, collaborative applications that sync automatically."

🔗 [Website](https://syncedstore.org/docs/) | `</>` [Github](https://github.com/YousefED/SyncedStore)

📋 License: `MIT License`

### SQLSync

> "SQLSync is a collaborative offline-first wrapper around SQLite. It is designed to synchronize web application state between users, devices, and the edge."

🔗 [Website](https://sqlsync.dev/) | `</>` [Github](https://github.com/orbitinghail/sqlsync)

📋 License: `Apache 2.0`

### turtleDB

> "turtleDB is a JavaScript framework and in-browser database for developers to build offline-first, collaborative web applications. It provides a developer-friendly API to access an in-browser database built on top of IndexedDB."

`</>` [Github](https://github.com/turtle-DB/turtleDB)

📋 License: `MIT License`

## Interesting Articles

Interest articles regarding the topic offline first you may want to read.

* ["Local First / Offline First" / rxdb.info](https://rxdb.info/offline-first.html)
* ["Downsides of Local First / Offline First" / rxdb.info](https://rxdb.info/downsides-of-offline-first.html)
* ["Offline First" / signaldb.js.org](https://signaldb.js.org/offline-first/)
