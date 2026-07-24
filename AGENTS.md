# AGENTS.md

Guidance for AI coding agents working in this repository.

## Repository overview

This repository is a documentation-only project. It does not contain any
source code, build system, package manifests, linters, or tests. Its sole
content is `README.md`, a long-form policy/research document (written in
Norwegian) that outlines a roadmap ("Veikart For Global Fred") for global
governance reform, proposing concepts such as "Collaborative Super
E-Democracy" and the "Universalis" worldview.

There is no application to run, build, or test. Agents should treat this as
a writing/editorial repository rather than a software engineering one.

## Working in this repository

- The primary (and currently only) content file is `README.md`. Most tasks
  will involve reading, editing, restructuring, or extending this document.
- Preserve the existing language of the document (Norwegian) unless a task
  explicitly asks for translation or the addition of content in another
  language.
- Preserve the existing document structure and section numbering
  (Abstrakt, Introduksjon, Dagens Globale Situasjon, Den Ideelle Fremtid,
  Mekanismene for Samhandling, Veikart for Global Transformasjon, etc.)
  when making edits, unless explicitly asked to restructure it.
- Make surgical edits: change only the sections relevant to the requested
  task, and avoid reflowing or rewriting unrelated paragraphs.
- There are no build, lint, or test commands to run for changes to this
  repository. Validation consists of proofreading the Markdown for
  correctness (formatting, headings, links, tables) and ensuring content
  is coherent with the surrounding text.
- Since this is a plain-text/Markdown repository, there is no risk of
  introducing code security vulnerabilities, but agents should still avoid
  introducing secrets, credentials, or unrelated/unverified factual claims.

## Adding new files

If a task requires adding new files (e.g., additional documentation,
images, or diagrams), place them in clearly named files or directories at
the repository root and reference them from `README.md` as needed. Do not
introduce build tooling, dependencies, or scaffolding unless explicitly
requested.
