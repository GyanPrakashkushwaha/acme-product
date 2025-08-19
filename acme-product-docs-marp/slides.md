---
marp: true
title: Product Documentation
author: 23f3004091@ds.study.iitm.ac.in
theme: gaia
paginate: true
---

<style>
/* Custom Theme */
section {
  background: #f0f4f8;
  color: #333;
}
h1, h2 {
  color: #005f73;
}
a {
  color: #0a9396;
}
</style>

# Product Documentation Presentation

**A guide to our new software solution.**

---

## Slide with Background Image

![bg cover](https://via.placeholder.com/800x600.png/005f73/FFFFFF?text=Replace+with+Your+Image)

---

## Custom Styling with Directives

This slide uses custom directives to change the background and text color. This is useful for highlighting important sections of your documentation.

---

## Algorithmic Complexity

Understanding the performance of our algorithms is crucial. Here are some key complexity examples:

**Inline Math:** The complexity of a linear search is $O(n)$.

**Block Math:**
$$
\text{Binary Search Complexity} = O(\log n)
$$

---

## Code Examples

Our software includes a robust API. Here’s a quick example in Python:

```python
def get_data(api_key):
    """
    Fetches data from the API.
    """
    if not api_key:
        return {"error": "API key is missing"}
    # ... implementation ...
    return {"data": "Sample data"}
