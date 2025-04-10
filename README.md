
# Image Compression Using Singular Value Decomposition (SVD)

This repository provides a detailed implementation of image compression using Singular Value Decomposition (SVD). SVD is a powerful mathematical method that decomposes a matrix into simpler, meaningful components. This project demonstrates how SVD can compress images by retaining only the most significant features, significantly reducing file sizes while preserving visual quality.

### Project Overview:

### **1. Singular Value Decomposition (SVD):**
- **Objective**: Decompose image matrices to efficiently compress images.
- **Implementation Details**:
  - Computed singular values and corresponding eigenvectors from image matrices.
  - Filtered eigenvalues to retain the most important image features, ensuring a balance between compression and image quality.

### **2. Image Compression Process:**
- **Objective**: Reconstruct images using fewer singular values, demonstrating effective compression.
- **Methodology**:
  - Reconstructed images by selectively choosing significant singular values.
  - Compared compressed images to the original, visualizing the trade-off between image quality and compression rate.

### **3. Orthogonal Basis Construction:**
- Employed the Gram-Schmidt process to extend orthonormal sets to form a complete orthonormal basis, crucial for ensuring numerical stability and correctness in computations.

### Key Concepts Explained:
- Detailed understanding of Singular Value Decomposition.
- Application of eigenvalue and eigenvector analysis in practical image processing tasks.
- Gram-Schmidt orthogonalization and its role in constructing complete bases.

### Learning Outcomes:
- Mastery of the theoretical concepts behind SVD.
- Practical skills in applying SVD for effective image compression.
- Insight into trade-offs between image quality and compression ratio.

### Libraries and Tools Used:
- Python
- NumPy (Numerical computations and matrix operations)
- PIL (Image handling)
- Matplotlib (Image visualization)

This project provides essential skills in numerical linear algebra, particularly in applying SVD for practical tasks such as image compression, useful for both educational purposes and real-world applications.
