# Andrey Domozhirov

![My favorite avatar](https://cdn.rs.school/abrlis.png?size=192)

---

## Contact information

E-mail: abrwet@gmail.com
Telegram: @Lisinka
Discord: Lisinla#2894 (rsSchool nick is Lisinka(@abrlis))

---

### A Little About Me

I've been interested in programming since an early age, but I've never taken any courses or thematic training. This is my first experience in this field.

---

### Skills and Proficiency

- VS Code, JetBrains IDE
- Python, C++ (basic level)

---

### Code example

- Example code from CODEWARS:

Linked Lists - Sorted Intersect

Write a SortedIntersect() function which creates and returns a list representing the intersection of two lists that are sorted in increasing order. Ideally, each list should only be traversed once. The resulting list should not contain duplicates.

```python
class Node(object):
    def __init__(self, data=None):
        self.data = data
        self.next = None


def sorted_intersect(first, second):
    first_list = []
    second_list = []
    while first or second:
        if first:
            first_list.append(first.data)
            first = first.next
        if second:
            second_list.append(second.data)
            second = second.next
    tmp = sorted(list(set(first_list) & set(second_list)))
    return build_list(tmp)
```
---

### Courses

This is my first course. I mostly do self-education.

---

### Languages

- I speak English at the level of reading technical documentation. Conversational level is zero.
- Russian - Native
  