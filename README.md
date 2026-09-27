# SUAVE design space

Two interactive 3-D maps of [SUAVE](https://github.com/suavecode/SUAVE), the conceptual
aircraft design framework.

| Page | What it shows |
|---|---|
| `index.html` | overview and the numbers |
| `component_graph.html` | the seventeen energy networks and the forty components they are built from |
| `suave_catalog_graph.html` | the whole package as a sunburst: 175 packages, 409 modules, 289 classes |

Every node and edge is extracted from the SUAVE source by parsing it — package tree,
class bases resolved through each module's own import table, and intra-SUAVE import
statements. Nothing is drawn by hand.

The pages are static, self-contained and dependency-free: no build step, no backend, no
tracking. Open any of them directly or serve the folder.

## Attribution

SUAVE is developed by the SUAVE team and licensed under LGPL-2.1. These pages contain
only derived metadata about the codebase — class names, module paths and the relationships
between them — and no SUAVE source code.
