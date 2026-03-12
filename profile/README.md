<div align="center">
  <img src="https://azure-deliberate-dog-514.mypinata.cloud/ipfs/bafkreiay74jzankyzj2zh4zemmpidafbsrcr4hwjxnl5e3qk32xyi6t3hi" alt="FluidKit Logo" width="100">

  <h1>FluidKit</h1>
  <strong>Web development for the Pythonist</strong>

  <br/>
  <br/>

  <a href="https://fluidkit.github.io/">📖 Documentation & Website</a> &nbsp;·&nbsp;
  <a href="https://github.com/AswanthManoj/Fluidkit">📦 Framework Source Code</a> &nbsp;·&nbsp;
  <a href="https://pypi.org/project/fluidkit/">🐍 PyPI</a>
</div>

---

FluidKit bridges Python and SvelteKit into a unified fullstack framework. Write backend functions in Python — FluidKit registers them as FastAPI endpoints and wraps them in SvelteKit-native remote functions with full type safety, cookie forwarding, file uploads, redirects, and single-flight cache invalidation.

```bash
pip install fluidkit
```

## How it works

Decorate Python functions with `@query`, `@command`, `@form`, or `@prerender`. FluidKit generates colocated `.remote.ts` files that SvelteKit imports directly — no manual fetch calls, no duplicated types, no glue code.

| Decorator | Use case |
|---|---|
| `@query` | Read data — cached, refreshable |
| `@command` | Write data — single-flight cache invalidation |
| `@form` | Form actions — file uploads, progressive enhancement, redirects |
| `@prerender` | Build-time data fetching with optional runtime fallback |

## Repositories

| Repo | Description |
|---|---|
| [AswanthManoj/Fluidkit](https://github.com/AswanthManoj/Fluidkit) | Core framework source code |
| [Fluidkit.github.io](https://github.com/Fluidkit/Fluidkit.github.io) | Documentation website |
| [FluidFrame](https://github.com/Fluidkit/FluidFrame) | Earlier Python + HTMX experiment |
| [FluidSvelte](https://github.com/Fluidkit/FluidSvelte) | Earlier Python + Svelte experiment |

---

<div align="center">
  Built with <a href="https://svelte.dev/docs/kit">SvelteKit</a> · <a href="https://fastapi.tiangolo.com/">FastAPI</a> · <a href="https://docs.pydantic.dev/">Pydantic</a>
</div>
