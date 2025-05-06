
---
## SVD Image Compression

### Overview

**Singular Value Decomposition (SVD)** is a matrix factorization technique that decomposes any real matrix **A** into three matrices:

- **U**: An \( m \times m \) orthogonal matrix. The columns of \( U \) are called the *left singular vectors* of \( A \).
- **Σ (Sigma)**: An \( m \times n \) diagonal matrix. The diagonal entries \( \sigma_i \) are the *singular values* of \( A \), ordered such that \( \sigma_1 \geq \sigma_2 \geq \dots \geq \sigma_r > 0 \).
- **\( V^T \)**: The transpose of an \( n \times n \) orthogonal matrix \( V \). The columns of \( V \) are called the *right singular vectors* of \( A \).

Mathematically:

$$A = U \Sigma V^T$$

This decomposition can also be expressed as a sum:


$$A = \sum_{i=1}^{r} \sigma_i u_i v_i^T$$


Where:
- \( \sigma_i \) is the \( i \)-th singular value.
- \( u_i \) is the \( i \)-th column of \( U \).
- \( v_i^T \) is the transpose of the \( i \)-th column of \( V \).

By truncating the sum to the top \( k \) terms, we can approximate \( A \) with a lower-rank matrix:


$$A_k = \sum_{i=1}^{k} \sigma_i u_i v_i^T
$$

This allows us to **compress** the image by storing only the top \( k \) singular values and corresponding vectors.

### Objective

**Task:** Produce compressed versions of an input image using SVD and qualitatively analyze the image quality at various levels of compression.

### Tools and Libraries

- `numpy` – Matrix operations  
- `matplotlib` – Image visualization  
- `cv2` – Image processing  
- `io` – Input/output utilities  
- `PIL` – Image loading and display  

---
