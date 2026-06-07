<!-- mcp-name: io.github.CSOAI-ORG/legacy-engineering-mcp -->
# legacy-engineering-mcp

[![MCP Scorecard: 28/100](https://img.shields.io/badge/proofof.ai-28%2F100-5b21b6)](https://proofof.ai/scorecard/legacy-engineering-mcp.html)

**Heritage & low-tech engineering calculations** — passive drainage, traditional lime-kiln calcination, breathable lime-mortar ratios, and passive thermal-mass analysis. An MCP server by MEOK AI Labs for restoration, conservation, and low-energy building work.

## Tools

| Tool | Description |
|---|---|
| `calculate_passive_drainage` | Passive drainage capacity from traditional (pre-pumped) drainage principles. |
| `get_lime_kiln_parameters` | Thermal setpoints for traditional lime-kiln calcination. |
| `get_fens_drainage_geometry` | Vectors for passive water-flow optimisation (Fens-style gravity drainage). |
| `get_lime_mortar_composition` | Traditional lime-mortar ratios for breathable masonry. |
| `analyze_thermal_mass` | Heat-retention properties for passive solar / thermal-mass design. |

## Install

```bash
pip install legacy-engineering-mcp
```

Then run the stdio MCP server:

```bash
python server.py
```

## Scorecard

This server is scored on the [proofof.ai MCP Scorecard](https://proofof.ai/scorecard/legacy-engineering-mcp.html) (100-point production-readiness rubric). Current: **28/100** — functional tools, but below the 80 merge gate; packaging, CI, and distribution hardening pending.

## License

MIT © MEOK AI Labs
