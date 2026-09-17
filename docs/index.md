# Front Matter

ALTO Front Matter extracts document metadata, decodes a strict YAML subset,
and exposes the result through typed accessors without retaining the document
body.

It is designed for Markdown processors, static-site generators, content tools,
and other applications that need predictable metadata without a general-purpose
YAML runtime. Unsupported constructs fail explicitly with source coordinates.

## Introduction

- [Installation](installation.md) covers requirements and package installation.
- [Getting started](getting-started.md) reads a complete document and locates its body.

## Metadata

- [Typed metadata](metadata.md) documents accessors, defaults, enums, and dates.
- [Decoding](decoding.md) defines the accepted YAML subset and scalar typing.
- [Rendering](rendering.md) creates YAML, JSON, or TOML front matter.
- [Integration](integration.md) covers the decoder and renderer contracts.

## Reference

- [Errors](errors.md) explains the exception hierarchy and recovery boundaries.
- [Guarantees](design.md) records performance goals, guarantees, and limitations.

## Package

- [Changelog](https://github.com/altophp/frontmatter/blob/main/CHANGELOG.md)
- [Contributing](https://github.com/altophp/frontmatter/blob/main/CONTRIBUTING.md)
- [Support](https://github.com/altophp/frontmatter/blob/main/SUPPORT.md)
