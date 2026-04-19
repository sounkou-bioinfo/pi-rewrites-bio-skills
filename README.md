# pi-rewrites-bio-skills

Pi skills for AI-assisted bioinformatics rewrites, ports, and modernization work.

## Install

```bash
pi install git:github.com/sounkou-bioinfo/pi-rewrites-bio-skills
```

Pin the initial release:

```bash
pi install git:github.com/sounkou-bioinfo/pi-rewrites-bio-skills@v0.1.0
```

## Included skills

- `bioinformatics-rewrite-porting`
- `library-first-bio-rewrites`
- `bioinformatics-ffi-and-bindings`

## When to use `bioinformatics-rewrite-porting`

Load this skill when you are:

- porting or rewriting an existing bioinformatics tool
- targeting compatibility with an upstream tool
- defining validation scope, attribution, and maintenance expectations
- planning staged modernization work with AI assistance

## When to use `library-first-bio-rewrites`

Load this skill when you are:

- reusing battle-tested libraries instead of rewriting everything from scratch
- favoring C/library-first composition over dependency-heavy application rewrites
- designing low-dependency ports for embedded, CRAN, HPC, or wasm contexts
- fusing multiple pipeline passes into one pass with richer statistics

## When to use `bioinformatics-ffi-and-bindings`

Load this skill when you are:

- exposing native bioinformatics libraries through R, Python, SQL, or wasm
- designing FFI-friendly APIs and wrappers
- embedding one native engine across multiple frontends
- validating wrapper behavior separately from core native behavior

## Worked example direction

A good example of the library-first approach is the kind of work done in `duckhts`:

- reuse a battle-tested native library rather than replacing it wholesale
- expose it through a new host runtime
- make the capability available across multiple languages through that host
- enrich one-pass analytics with additional validated statistics instead of stacking more pipeline passes

## Update

If installed unpinned:

```bash
pi update
```

Or update just this package:

```bash
pi update git:github.com/sounkou-bioinfo/pi-rewrites-bio-skills
```

If pinned, move explicitly to the current release:

```bash
pi install git:github.com/sounkou-bioinfo/pi-rewrites-bio-skills@v0.1.0
```
