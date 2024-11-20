
# Vector Dot-Product Algorithm

## Mathematical Expression
The dot product of two vectors **A** and **B** is given by the formula:

\[
A \cdot B = \sum_{i=1}^{n} A_i \cdot B_i
\]

Where:
- \(A_i\) and \(B_i\) are the components of vectors **A** and **B**.
- \(n\) is the number of dimensions in the vectors.

## Example Code

```python
  # Output: 32
```
## Picture
![alt.txt](https://cdn1.byjus.com/wp-content/uploads/2018/11/maths/2016/06/02115120/Dot-Product-Of-Vectors.jpg)

## Table Showing comparison
> |version|Time complexity|Space Complexity| Remarks|
> |---|---|---|---|
> |v1|O(1)|O(1)|Basic implementation|
> |v2|O(1)|O(1)|optimized using numpy|
> |v3|O(1)|O(1)|parallel computation|

1.**Headings:**
   - Use `#` for the main title (`Vector Dot-Product Algorithm`) and `##` for subsections like `Mathematical Expression`, `Example Code`, `Diagram`, etc.

2.**Styling:**
   - Use `**` for bold text, e.g., **A** and **B**
   - Use `*` or `_` for italics

**3.Quoting text:**
- Use `>` for blockquotes.eg.
> this is blockquote.

**4.Link:**
- use '\[]()' for link.eg
[this is link](https://www.google.com/)

**5.Images:**
- use '!\[]()' for image.eg
![alt text](https://cdn1.byjus.com/wp-content/uploads/2018/11/maths/2016/06/02115120/Dot-Product-Of-Vectors.jpg)

**6.Lists (along with task lists):**
-  Use `-` or `1.` for unordered or ordered lists.

**7.Footnotes:**

 - Footnotes example.
     ```
     [1]: Reference
     ```
**8.Alerts:**
 - Use blockquotes for alerts and warnings,
 > alert

 **9.Tables:**
 - Use `|` to create tables.eg.

 |version|Time complexity|Space Complexity| Remarks|
 |---|---|---|---|

 **10.Code:**
 - use '\```' for code.eg.

 ```python
def dot_product(A, B):
    return sum(a * b for a, b in zip(A, B))

A = [1, 2, 3]
B = [4, 5, 6]
print(dot_product(A, B))  # Output: 32
```

**11.Mathematical Expressions:**

\[
A \cdot B = \sum_{i=1}^{n} A_i \cdot B_i
\]
**thanks**