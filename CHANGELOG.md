# Changelog

## 0.5.1 (2025-12-20)

Full Changelog: [v0.5.0...v0.5.1](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.5.0...v0.5.1)

### Bug Fixes

* compat with Python 3.14 ([506a48f](https://github.com/AgentbaseHQ/agentbase-python/commit/506a48fb364425c839e712fda2c6232a547c04a7))
* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([26fcf8c](https://github.com/AgentbaseHQ/agentbase-python/commit/26fcf8cfaa707947604b7f21770e375bdd8f2505))
* ensure streams are always closed ([a5fbe1f](https://github.com/AgentbaseHQ/agentbase-python/commit/a5fbe1ff1cdb9577f78959979e26cbf051349a41))
* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([c8e85dc](https://github.com/AgentbaseHQ/agentbase-python/commit/c8e85dcadbd1c87e7eb467da4d5907d4be5ba067))
* use async_to_httpx_files in patch method ([15b8a78](https://github.com/AgentbaseHQ/agentbase-python/commit/15b8a78b1702ab6b3b5f81e5ffd7620f35b4666a))


### Chores

* add missing docstrings ([7f81914](https://github.com/AgentbaseHQ/agentbase-python/commit/7f81914d3ad703d6e516c4207af8be9b29639e62))
* add Python 3.14 classifier and testing ([e277845](https://github.com/AgentbaseHQ/agentbase-python/commit/e277845b95c046a36a261d5e541c3b834b9e6060))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([62a2800](https://github.com/AgentbaseHQ/agentbase-python/commit/62a2800278f735e3a60478f2f5bf073247f26df4))
* **docs:** use environment variables for authentication in code snippets ([6153b3a](https://github.com/AgentbaseHQ/agentbase-python/commit/6153b3ade4267a47d7e5c9f04f7df087736f14a9))
* **internal:** add `--fix` argument to lint script ([40a5771](https://github.com/AgentbaseHQ/agentbase-python/commit/40a57716ebac55d0f9474861c4a2fc6e4c30531e))
* **internal:** add missing files argument to base client ([fa1bf74](https://github.com/AgentbaseHQ/agentbase-python/commit/fa1bf74ee8af58a559cded1f9b3bdeab2bc9353b))
* **package:** drop Python 3.8 support ([27398f4](https://github.com/AgentbaseHQ/agentbase-python/commit/27398f431d61623cf51afd80eb96fa29a8d0bb17))
* speedup initial import ([ae80104](https://github.com/AgentbaseHQ/agentbase-python/commit/ae801043676a3027715757600d99416925b8e32f))
* update lockfile ([c45d94f](https://github.com/AgentbaseHQ/agentbase-python/commit/c45d94f06694f09c807bff2c994a9207b2e5568e))


### Documentation

* add more examples ([07cd970](https://github.com/AgentbaseHQ/agentbase-python/commit/07cd9702f78069d1480235504de363aa26008bd8))

## 0.5.0 (2025-11-06)

Full Changelog: [v0.4.0...v0.5.0](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.4.0...v0.5.0)

### Features

* **api:** manual updates ([bd37cc0](https://github.com/AgentbaseHQ/agentbase-python/commit/bd37cc02bc033ed9a02a0fe412304620b1312884))


### Bug Fixes

* **client:** close streams without requiring full consumption ([600e68b](https://github.com/AgentbaseHQ/agentbase-python/commit/600e68b0722c43c174af329d83a866dba0e62e7c))


### Chores

* bump `httpx-aiohttp` version to 0.1.9 ([1a2887c](https://github.com/AgentbaseHQ/agentbase-python/commit/1a2887c6b9db2682267a3a28999227c3f5d857de))
* **internal/tests:** avoid race condition with implicit client cleanup ([c01d166](https://github.com/AgentbaseHQ/agentbase-python/commit/c01d166af2db0d272a571f244c088ff3dcd91bed))
* **internal:** grammar fix (it's -&gt; its) ([e501e14](https://github.com/AgentbaseHQ/agentbase-python/commit/e501e1463942a61a8eea51fb86e83ed56cb76b59))

## 0.4.0 (2025-10-11)

Full Changelog: [v0.3.1...v0.4.0](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.3.1...v0.4.0)

### Features

* **api:** manual updates ([0dd1219](https://github.com/AgentbaseHQ/agentbase-python/commit/0dd12194314a6f967ee3ca879e3663da2b75a911))

## 0.3.1 (2025-10-11)

Full Changelog: [v0.3.0...v0.3.1](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.3.0...v0.3.1)

### Chores

* **internal:** detect missing future annotations with ruff ([e29d902](https://github.com/AgentbaseHQ/agentbase-python/commit/e29d902cfc0603b22a87acba662be95db8a4a29c))

## 0.3.0 (2025-10-03)

Full Changelog: [v0.2.0...v0.3.0](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.2.0...v0.3.0)

### Features

* **api:** manual updates ([1356607](https://github.com/AgentbaseHQ/agentbase-python/commit/1356607bd114f47701ad219980afd39ad510c07f))

## 0.2.0 (2025-10-03)

Full Changelog: [v0.1.1...v0.2.0](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.1.1...v0.2.0)

### Features

* **api:** manual updates for parameter updates ([69a7aca](https://github.com/AgentbaseHQ/agentbase-python/commit/69a7acadd162150cf9ae54fbebb2c200498e9507))

## 0.1.1 (2025-09-22)

Full Changelog: [v0.1.0...v0.1.1](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.1.0...v0.1.1)

## 0.1.0 (2025-09-22)

Full Changelog: [v0.0.1...v0.1.0](https://github.com/AgentbaseHQ/agentbase-python/compare/v0.0.1...v0.1.0)

### Chores

* configure new SDK language ([2e448ce](https://github.com/AgentbaseHQ/agentbase-python/commit/2e448ce075c5a14429adf3f0577fd1f357ed9f4f))
* update SDK settings ([812f1a4](https://github.com/AgentbaseHQ/agentbase-python/commit/812f1a4361f2319ea3339fa806c9e46c0ee1ebb2))
* update SDK settings ([f2fe6b8](https://github.com/AgentbaseHQ/agentbase-python/commit/f2fe6b84d51c36039583b2993fca76c3ad4f6125))
* update SDK settings ([cc64773](https://github.com/AgentbaseHQ/agentbase-python/commit/cc64773a3632a48301cdf7e505015d317fbc5aec))
