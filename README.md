### Screenshot & PDF Generation API

One REST call to render any URL or HTML to **PNG**, **JPEG**, or **PDF**.  
Sub-2s renders. 99.9% uptime. Free tier included.

**[rendershot.io](https://rendershot.io)** | **[Docs](https://rendershot.io/docs)** | **[Dashboard](https://rendershot.io/dashboard)**

---

```python
import rendershot

client = rendershot.RenderShotClient(api_key="rs_...")

# Screenshot any URL
client.screenshot_url_to_file("https://example.com", "screenshot.png")

# Generate a PDF from HTML
client.pdf_html_to_file("<h1>Invoice #1001</h1>", "invoice.pdf")
```

---

#### SDKs & Integrations

| | |
|---|---|
| [![PyPI](https://img.shields.io/pypi/v/rendershot?label=rendershot&logo=python&logoColor=white&v=0.1.9)](https://pypi.org/project/rendershot/) | Python SDK &mdash; sync, async, and bulk rendering |
| [![npm](https://img.shields.io/npm/v/rendershot?label=rendershot&logo=npm&v=0.1.3)](https://www.npmjs.com/package/rendershot) | Node.js SDK &mdash; native fetch, zero dependencies |
| [![npm](https://img.shields.io/npm/v/@rendershot/mcp-server?label=@rendershot/mcp-server&logo=npm&v=0.1.5)](https://www.npmjs.com/package/@rendershot/mcp-server) | MCP server &mdash; use Rendershot from Claude, Cursor, and other AI agents |

#### Use Cases

PDF invoices &bull; OG images &bull; HTML reports &bull; Web screenshots &bull; Scheduled captures &bull; Visual regression in CI

---

<sub>Built in Tel Aviv &bull; [X/Twitter](https://x.com/RendershotIo)</sub>
