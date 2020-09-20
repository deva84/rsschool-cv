# Svitlana Dasgupta
## Junior Front-End Developer
<br>
+38(080)123-45-67

mymailbox@gmail.com<br>
[www.linkedin.com/in/someprofile](www.linkedin.com/in/someprofile)

---
> Summary

My experience includes working as a marketing, public relations, sales and
consultant. Last few years I've been working with international clients. I'm wellbalanced
and equipped with analytical and time-management skills . Over the
last year I've been studying programming on Python, PHP, basic front-end
(HTML, CSS, JS, Bootstrap4). I speak Ukrainian, Russian and English.
<br><br>

> Experience

  Period | Position
  :---|---:
  2020 - present | Student<br> online courses
  2011 - 2019 | Consultant<br> Docler Media
  2010 - 2011 | Marketing<br> AC-Step
  2010 - 2010 | Marketing<br> Anzer IT Solutions
  2008 - 2009 | PR Manager<br> Global Spirits
  2006 - 2008 | Project Executive<br> Tourism, the Magazine
---
<br>

> Education

&nbsp; 2005-2009 &nbsp; Odessa State Economic University<br>
<br>

> Certificates

&nbsp; 2020 &nbsp; HTML & CSS, Landing development, UserCMS<br>

&nbsp; 2019 &nbsp; Basics of programming by Kyiv Polytechnic Institute<br>
<br>

> Code example

```python
def make_sudoku(size):
	el = []
	for i in range(1, size**2 + 1):
		el.append(i)
	m = [el for i in range(size**2)]
	count = 0
	step = 0
	m2 = []
	while count < len(m):
		for el in m:
			el2 = el[step:] + el[:step]
			m2.append(el2)
			step += 1
			count += 1
	start = 0
	stop = len(m2)
	m4 = []
	while start < size:
		m3 = m2[start: stop: size]
		m4 = m4 + m3
		start += 1
	return m4
```
