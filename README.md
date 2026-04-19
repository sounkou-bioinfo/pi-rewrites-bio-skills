# pi-rewrites-bio-skills

Pi skills for AI-assisted bioinformatics rewrites, ports, and modernization work.

## Install

```bash
pi install git:github.com/sounkou-bioinfo/pi-rewrites-bio-skills
```

## Included skills

- `bioinformatics-rewrite-porting`
- `library-first-bio-rewrites`

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

## Update

If installed unpinned:

```bash
pi update
```

Or update just this package:

```bash
pi update git:github.com/sounkou-bioinfo/pi-rewrites-bio-skills
```
