# C++ STL Cheat Sheet

## Vector

```cpp
vector<int> v;
v.push_back(10);
v.pop_back();
v.size();
v.clear();
```

---

## Sort

```cpp
sort(v.begin(), v.end());
```

---

## Reverse

```cpp
reverse(v.begin(), v.end());
```

---

## Max Element

```cpp
*max_element(v.begin(), v.end());
```

---

## Min Element

```cpp
*min_element(v.begin(), v.end());
```

---

## Binary Search

```cpp
binary_search(v.begin(), v.end(), x);
```

---

## Lower Bound

```cpp
auto it = lower_bound(v.begin(), v.end(), x);
```

---

## Upper Bound

```cpp
auto it = upper_bound(v.begin(), v.end(), x);
```

---

## GCD

```cpp
__gcd(a, b);
```

---

## Swap

```cpp
swap(a, b);
```