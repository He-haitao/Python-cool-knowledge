今日优雅代码介绍

```
R, C = len(matrix), len(matrix[0])
def neighbours(r,c):
for nr,nc in ((r,c-1),(r-1,c),(r,c+1),(r+1,c)):
		if 0<=nr<R and 0<=nc<C:
			yield nr,nc

```
