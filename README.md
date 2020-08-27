# Intro mudlle-lsp

This is a language server protocol code for Mudlle which is an in-game development language of MUME (Multi-User Middle Earth) a Tolkien based text game (http://mume.org).

## Functionality

This Language Server works for any mudlle-file. It has the following language features:
- Completions
- Help for functions

## Structure

```
.
├── client // Language Client
│   ├── src
│   │   └── extension.ts // Language Client entry point
├── package.json // The extension manifest.
└── server // Language Server
    └── src
        └── server.ts // Language Server entry point
```
