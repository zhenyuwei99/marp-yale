---
marp: true
theme: yale
paginate: true
math: mathjex
---

<!-- class: lead -->
<!-- paginate: skip -->

# Title

## A longer subtitle

### Name
### Date

---

<!-- paginate: true -->
<!-- class: section -->
<!-- header: Basic feature -->

<br>

This theme is used for academic presentation of SEU student.


1. A
2. B
3. 3

- Based on [gaia](https://github.com/marp-team/marp-core/blob/main/themes/gaia.scss)
- SEU logo

---

<!-- class: section -->
<!-- header: code -->

This is a demo of python code


```python
def grid2list(grid):
    list_in = [[]]
    for grid_temp in grid:
        list_out = []
        for val in grid_temp:
            for list_temp in list_in:
                list_out.append(list_temp + [val]) # 注释
        list_in = list_out
    return list_in
def grid2list(grid):
    list_in = [[]]
    for grid_temp in grid:
        list_out = []
        for val in grid_temp:
            for list_temp in list_in:
                list_out.append(list_temp + [val])
        list_in = list_out
    return list_in
```
---

<!-- header: Equation -->

This is equation rendered by **mathjax**

$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$

---

<!-- header: Figure -->

Here is a centered blur image, [more details here](https://marpit.marp.app/image-syntax)

![blur:2px width:800px center](https://www.ivywise.com/cdn-cgi/image/fit=scale-down,quality=90,format=auto,width=800/core/wp-content/uploads/2022/05/AdobeStock_4965413641-1024x682.jpeg)

---

<!-- header: Table -->

This is a centered table

<br>

| Fruit   | Colour | Amount |  Cost |
| ------- | ------ | :----: | ----: |
| Banana  | Yellow |   4    | £1.00 |
| Apple   | Red    |   2    | £0.60 |
| Orange  | Orange |   10   | £2.50 |
| Coconut | Brown  |   1    | £1.50 |

---

<!-- header: two columns -->
<!-- class: split -->

<div class=ldiv>
<br>
<br>

![center width:550px](https://www.ivywise.com/cdn-cgi/image/fit=scale-down,quality=90,format=auto,width=800/core/wp-content/uploads/2022/05/AdobeStock_4965413641-1024x682.jpeg)


</div>

<div class=rdiv>
<br>
<br>

| Fruit   | Colour | Amount |  Cost |
| ------- | :----- | :----: | ----: |
| Banana  | Yellow |   4    | £1.00 |
| Apple   | Red    |   2    | £0.60 |
| Orange  | Orange |   10   | £2.50 |
| Coconut | Brown  |   1    | £1.50 |

</div>


---

<!-- _header: Comment/Citation -->

Content
Content
Content
Content $^{[1]}$
Content
Content
Content

> [1] Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.