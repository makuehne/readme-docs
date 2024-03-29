# Markdown readme

This document shows some formatting examples for a GitHub-flavored
markdown (gfm) readme.

## Basic formatting

This text contains words set **bold** and _italic_. And here is one in
`monospace`. This is a link to the 
[Help page on text formatting](https://help.github.com/en/github/writing-on-github)
from the GitHub website.

## Lists

### Unordered

- Item 1
- Item 2
  - Item 2.1
  - Item 2.2
- Item 3

### Ordered

1. Item 1
2. Item 2
   1. Item 2.1
   2. Item 2.2
3. Item 3

## Code blocks

For simple command line statements use a monospace block:

```
> command line 1
> command line 2
```

For Java code use a block with syntax highlighting:

```java
@FunctionalInterface
public interface HealthCheck {
    HealthCheckResponse call();
}
```

## Resources

- [A template for the readme document structure](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- [Advanced example for generating a PDF documentation with Pandoc](https://gist.github.com/Rokko11/8d089afe910790a07d9b989c7666ed17) (from: Javamagazin 12/2019)
