
<p><img src="https://535485.smushcdn.com/2232832/wp-content/uploads/2022/03/SEAelectricBluebirdtTypeC.jpg?lossy=1&strip=0&webp=1"></p>

Every year, American high school students take SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. There are three sections - reading, math, and writing, each with a maximum score of 800 points. These tests are extremely important for students and colleges, as they play a pivotal role in the admissions process.

Analyzing the performance of schools is important for a variety of stakeholders, including policy and education professionals, researchers, government, and even parents considering which school their children should attend.

In this notebook, we will take a look at data on SATs across public schools in New York City. Our database contains a single table:

<h1 id="schools"><code>schools</code></h1>
<table>
<thead>
<tr>
<th>column</th>
<th>type</th>
<th>description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>school_name</code></td>
<td><code>varchar</code></td>
<td>Name of school</td>
</tr>
<tr>
<td><code>borough</code></td>
<td><code>varchar</code></td>
<td>Borough that the school is located in</td>
</tr>
<tr>
<td><code>building_code</code></td>
<td><code>varchar</code></td>
<td>Code for the building</td>
</tr>
<tr>
<td><code>average_math</code></td>
<td><code>int</code></td>
<td>Average math score for SATs</td>
</tr>
<tr>
<td><code>average_reading</code></td>
<td><code>int</code></td>
<td>Average reading score for SATs</td>
</tr>
<tr>
<td><code>average_writing</code></td>
<td><code>int</code></td>
<td>Average writing score for SATs</td>
</tr>
<tr>
<td><code>percent_tested</code></td>
<td><code>numeric</code></td>
<td>Percentage of students completing SATs</td>
</tr>
</tbody>
</table>
Let's familiarize ourselves with the data by taking a looking at the first few schools!
