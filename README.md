# Local Linear Embedding LLE
## Key Concepts in LLE
* **Manifold Learning** - Data lies on a low dimensional manifold
* **Local linearity** - Points approximated by neighbors
* **Neighborhood Preservation** - Maintains local relationships
* **Non-linear reduction** - Captures complex structure
* **Eigenvalue embedding** - Low dimensional representation via eigenvectors

## Importance in dimensionality reduction
LLE is important in dimensionality reduction because:

* **Preserves local structure** - maintains relationship between neighboring points
* **Captures non-linear patterns** - models complex manifolds beyond linear methods
* **Reduces dimensionality** - simplifies high dimensional data for analysis
* **Improves visualization** - projects data into 2D or 3D for exploration
* **Reveals hidden structures** - Uncovers latent patterns not visible in the original space
* **Enhances feature extraction** - Identifies intrinsic features for downstream tasks
* **Facilitates Similarity Analysis** - Preserves neighbourhoods for similarity measure of clastering
* **Support noise reduction** - Filters out irrelevant variations in data

**Consider a Swiss roll dataset a 3D shape that looks like a rolled up sheet. Even though it’s curved and complex LLE can “unroll” it into a flat 2D shape while keeping the original structure and relationships between points.**

```bash
xi​≈∑j∈N(i)​wij​xj
```