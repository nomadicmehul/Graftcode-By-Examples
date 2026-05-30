# Graftcode By Examples

Collection of hands-on examples built, tested, and run against [GraftCode](https://graftcode.com/) — capturing the best practices I've learned for using the platform.

The goal of this repo is to serve as a practical reference for:

- Exposing existing services (Python, Node.js, etc.) as MCP servers via the GraftCode Gateway.
- Integrating those services with AI assistants like Claude Desktop.
- Comparing local-vs-containerized approaches and documenting trade-offs.
- Sharing repeatable, copy-pasteable patterns for common GraftCode workflows.

## Learn more about GraftCode

- Website: [graftcode.com](https://graftcode.com/)
- Academy (courses & guides): [academy.graftcode.com](https://academy.graftcode.com/)
- Quick-start guides: [academy.graftcode.com/quick-start](https://academy.graftcode.com/quick-start)

## Examples in this repo

| Folder | Description |
| :--- | :--- |
| [`py-ai-backend/`](py-ai-backend/) | Python energy-price calculator exposed as an MCP server, both as a local `FastMCP` script and via Docker + the GraftCode Gateway. Follows the [Expose MCP (Python) quick-start](https://academy.graftcode.com/quick-start/expose-mcp/python). |

More examples will be added over time as I explore additional GraftCode features and integration patterns.

## How to use this repo

1. Pick an example folder that matches what you want to try.
2. Read its local `README.md` — each example is self-contained with its own setup, run, and integration steps.
3. Follow along with the linked GraftCode Academy guide for the full context.

## Contributing / feedback

This is primarily a personal learning repo, but suggestions and corrections are welcome via issues or pull requests.
