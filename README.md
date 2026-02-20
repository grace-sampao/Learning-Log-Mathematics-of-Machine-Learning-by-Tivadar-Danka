# 📖 Learning Log: Mathematics of Machine Learning by Tivadar Danka

This repository documents my learning journey as I follow along and apply the concepts from the book [Mathematics of Machine Learning](https://www.packtpub.com/en-us/product/mathematics-of-machine-learning-9781837027866) by [Tivadar Danka](https://tivadardanka.com/about).

> **N/B:** Just got through a few pages in Chapter 1. Looking at other material on this topic, I'll need to study the foundations of Vectors and Vector Spaces such as Linear Algebra and Trigonometry.
<br><br>
For now I'll proceed with going through the book to get a general overview and will flesh out these concepts later.

## Part 1

### Chapter 1: Vectors and Vector Spaces

*Vectors* are a mathematical structure that allows us to reason about data more effectively in theory and in practice.

> **N/B:** Vectors are vectors not because they have direction and magnitude but because you can add them together.<br>This is formalized by the concept of **vector spaces**, which are best described by **bases** (minimal and linearly independent generating sets).

Vector spaces and their bases apply to *linear transformations* which is the most important building block of predictive models.

Vectorizing code enables compressing complex logic into one-liners e.g. data scaling:

```python
X_scaled = (X - X.mean(axis=0)) / X.std(axis=0)
```

*NumPy* (Numerical Python) is the most important library in the machine learning toolkit.

#### Mathematical Study Subjects 🧮

From what I've gathered so far in reading this book, I intend to study the following mathematical subjects in the order listed below:

- [ ] Linear Algebra
- [ ] Trigonometry
- [ ] Vectors
- [ ] Vector Spaces & their bases
- [ ] Linear Transformations