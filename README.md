# Chapter13Sort

## 10. O(n)

## 18. It requires a maximum of 6 elements

## 24. `[-4, 17, 3, 94, 46, 8, 29, 12]`

## 25. 
a.
`[29, 17, 3, 94, 46, 8, -4, 12]`
`[-4, 17, 3, 94, 46, 8, 29, 12]`
`[-4, 3, 17, 94, 46, 8, 29, 12]`
`[-4, 3, 8, 94, 46, 17, 29, 12]`
`[-4, 3, 8, 12, 46, 17, 29, 94]`
`[-4, 3, 8, 12, 17, 46, 29, 94]`
`[-4, 3, 8, 12, 17, 29, 46, 94]`

b. 
`[33, 14, 3, 95, 47, 9, -42, 13]`
`[-42, 14, 3, 95, 47, 9, 33, 13]`
`[-42, 3, 14, 95, 47, 9, 33, 13]`
`[-42, 3, 9, 95, 47, 14, 33, 13]`
`[-42, 3, 9, 13, 47, 14, 33, 95]`
`[-42, 3, 9, 13, 14, 47, 33, 95]`
`[-42, 3, 9, 13, 14, 33, 47, 95]`

c. 
`[7, 1, 6, 12, -3, 8, 4, 21, 2, 30, -1, 9]`
`[-3, 1, 6, 12, 7, 8, 4, 21, 2, 30, -1, 9]`
`[-3, -1, 6, 12, 7, 8, 4, 21, 2, 30, 1, 9]`
`[-3, -1, 1, 12, 7, 8, 4, 21, 2, 30, 6, 9]`
`[-3, -1, 1, 2, 7, 8, 4, 21, 12, 30, 6, 9]`
`[-3, -1, 1, 2, 4, 8, 7, 21, 12, 30, 6, 9]`
`[-3, -1, 1, 2, 4, 6, 7, 21, 12, 30, 8, 9]`
`[-3, -1, 1, 2, 4, 6, 7, 21, 12, 30, 8, 9]`
`[-3, -1, 1, 2, 4, 6, 7, 8, 12, 30, 21, 9]`
`[-3, -1, 1, 2, 4, 6, 7, 8, 9, 30, 21, 12]`
`[-3, -1, 1, 2, 4, 6, 7, 8, 9, 12, 21, 30]`

d.
`[6, 7, 4, 8, 11, 1, 10, 3, 5, 9]`
`[1, 7, 4, 8, 11, 6, 10, 3, 5, 9]`
`[1, 3, 4, 8, 11, 6, 10, 7, 5, 9]`
`[1, 3, 4, 8, 11, 6, 10, 7, 5, 9]`
`[1, 3, 4, 5, 11, 6, 10, 7, 8, 9]`
`[1, 3, 4, 5, 6, 11, 10, 7, 8, 9]`
`[1, 3, 4, 5, 6, 7, 10, 11, 8, 9]`
`[1, 3, 4, 5, 6, 7, 8, 11, 10, 9]`
`[1, 3, 4, 5, 6, 7, 8, 9, 10, 11]`