# eecs2011-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EECS2011 Assignment 1 Solved](https://www.ankitcodinghub.com/product/eecs2011-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91335&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS2011 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
This assignment is about the polygon hierarchy shown in the figure below.

We use double precision coordinates for vertices of the polygon. So, our Polygon interface is

different from the java.awt.Polygon class in the Java API (which uses int-coordinate vertices) . 3

</div>
</div>
<div class="layoutArea">
<div class="column">
«interface»

Polygon

«class»

SimplePolygon

«class»

ConvexPolygon

</div>
<div class="column">
1 4

non-simple 3 non-simple

</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
<div class="column">
2 76

8

25

</div>
</div>
<div class="layoutArea">
<div class="column">
47

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
<div class="layoutArea">
<div class="column">
594

116 0

1

</div>
</div>
<div class="layoutArea">
<div class="column">
simple

</div>
<div class="column">
convex

4

</div>
</div>
<div class="layoutArea">
<div class="column">
2

12 0 18 5

</div>
</div>
<div class="layoutArea">
<div class="column">
60

</div>
<div class="column">
1 1

2 3

</div>
</div>
<div class="layoutArea">
<div class="column">
14 16

</div>
<div class="column">
6 17

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Page 2 gives some preliminary descriptions.</li>
<li>Page 3 shows some useful facts that you may use.</li>
<li>Page 4 shows a summary of the interface and classes you are assigned to build and test.You may use additional types or members as you deem necessary in your design.</li>
<li>Page 5 gives a small sample of input polygons you should test your program against.You should also use a number of other, larger, test cases of your own.</li>
<li>Page 5 also lists what files you should submit.</li>
<li>Page 6 describes an extra credit and optional work.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Click here to see the code templates and their Javadocs.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Preliminaries:

An 𝑛-sided polygon 𝑃 (𝑛 ≥ 3) is a cyclic sequence 𝑣0, 𝑣1, ⋯ , 𝑣𝑛−1 of vertices as we walk around the polygon boundary. Each vertex 𝑣𝑖 (the 𝑖th vertex) is a point in the plane represented by its 𝐝𝐨𝐮𝐛𝐥𝐞 𝑥 and 𝑦 coordinates. The line-segment 𝑒𝑖 between vertex 𝑣𝑖 and the next vertex

𝑣 𝑖+1 𝑚𝑜𝑑 𝑛 (in cyclic order around the boundary) is called the 𝑖th edge of 𝑃, for 𝑖 = 0. . 𝑛 − 1.

You may use the Point2D.Double class in the java.awt.geom package of the Java API to represent polygon vertices.

The polygon is said to be simple if no two non-adjacent pair of edges intersect. That is, two edges 𝑒𝑖 and 𝑒𝑗 are completely disjoint from each other whenever 1 &lt; 𝑗 − 𝑖 &lt; 𝑛 − 1.

A simple polygon is said to be convex if the internal angle of every vertex is at most 180°. Equivalently, the simple polygon is convex if every turn is consistently in the same orientation (not clockwise or not counter-clockwise) as we walk around the polygon boundary. This latter condition is computationally more useful (see the description of the Delta Test on the next page).

The main methods we are interested in is polygon perimeter and area. Note that polygon area may not be well defined if the polygon is non-simple, since the notion of polygon “interior” may not be well defined in that case. We obviously need the boolean methods isSimple and isConvex as well.

Extra Credit and Optional work:

The last page talks about the contains(p) method which determines whether the polygon contains the given point p inside. The precondition is that the polygon is simple (otherwise, “inside” may not be well defined). This method can be implemented more efficiently on convex polygons than on simple polygons. Some hints are provided on how to implement this method.

Remark: There are some differences between our notions of polygon “interior” and “contains” and that of the Java API (especially when the polygon is non-simple). In the latter, Polygon implements the Shape interface which redefines the shape boundary as a path sequence, different from the vertex sequence. It implicitly adds edge crossings as new double vertices in the path sequence, and redirects the sequence to “simplify” the shape boundary. See the illustrative figure below. It uses the so called “winding number” to determine the “interior” of the shape.

In short, you should follow our definitions. 

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
Java API

</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
<div class="column">
non-simple

</div>
<div class="column">
2

</div>
<div class="column">
simplified

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Useful Facts:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Delta Test:

Suppose we are given an ordered sequence of three points 𝑎, 𝑏, 𝑐 ; each point given by its 𝑥 and 𝑦 coordinates (e.g., 𝑥𝑎 and 𝑦𝑎). We want to know what is the orientation as we go from 𝑎 to 𝑏 to 𝑐 and back to 𝑎: is it clockwise (i.e., right turn), counter-clockwise (i.e., left turn), or collinear? The answer is given by the determinant of the 3 × 3 matrix shown below:𝑥𝑎 𝑦𝑎 1 𝑑𝑒𝑙𝑡𝑎 𝑎,𝑏,𝑐 =𝑑𝑒𝑡 𝑥𝑏 𝑦𝑏 1 𝑥𝑐 𝑦𝑐 1This expression can be computed in 𝑂(1) time with arithmetic operations on the xy-coordinates of the three given points and is a very useful quantity with many geometric applications. (It is analogous to the compareTo method on Comparable types.) So, it’s worth providing a static helper method to compute 𝑑𝑒𝑙𝑡𝑎 𝑎, 𝑏, 𝑐 .</li>
<li>Triangle Signed Area:

The signed area of the oriented triangle (𝑎, 𝑏, 𝑐) is 12 𝑑𝑒𝑙𝑡𝑎 𝑎, 𝑏, 𝑐 , where the sign is positive, negative, or zero if the orientation is counter-clockwise, clockwise, or collinear, respectively.</li>
<li>Line-Segment Disjointness Test:

A line-segment can be represented by a pair of delimiting points. We want to know whether a given pair of (closed) line segments (𝑎, 𝑏) and (𝑐, 𝑑) are disjoint. The possible cases are depicted in the figure below.This test can be done in 𝑂(1) time (e.g., using the Delta Test). (How?) You would need repeated use of such a test in the polygon simplicity checking method. So, it’s worth providing a static helpermethodforline-segmentdisjointness test. Note:Youmustimplementthismethod yourself. You are not allowed to use the line intersection method provided by the Java API. Exercise your logical and analytical thinking and problem solving skills.</li>
<li>Polygon Area:

Consider the simple polygon 𝑣0, 𝑣1, ⋯ , 𝑣𝑛−1 , where we denote the xy-coordinates of vertex 𝑣𝑖 by the pair 𝑥𝑖,𝑦𝑖 . For notational simplicity, we assume 𝑣𝑛≡ 𝑣0 and 𝑣−1 ≡ 𝑣𝑛−1

(i.e., index arithmetic is modulo n). Then the area of the simple polygon is:1 𝑛−1𝑑𝑒𝑙𝑡𝑎(𝑜,𝑣,𝑣)=1 𝑛−1𝑥𝑦−𝑦 , 2 𝑖=0 𝑖 𝑖+1 2 𝑖=0 𝑖 𝑖+1 𝑖−1where 𝑜 = (0,0) denotes the origin.

(Note: it’s absolute value of the sum, not the sum of absolute values!)

This expression can be evaluated in 𝑂(𝑛) time using arithmetic operations.</li>
</ul>
</div>
<div class="column">
3

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Interface Polygon:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
getSize() getVertex(i)

perimeter() area()

</div>
<div class="column">
returns n, the number of edges of the polygon.

returns the 𝑖th vertex of the polygon with precondition 0 ≤ 𝑖 &lt; 𝑛.

Throws IndexOutOfBoundsException if the precondition is violated. returns the sum of the lengths of the edges of the polygon.

returns area of the interior of the polygon if this notion is well defined; throws an exception if it’s not.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Class SimplePolygon (implements Polygon):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
getNewPoly() toString()

</div>
<div class="column">
constructs &amp; returns a polygon, initialized by user provided data in O(n) time. returns a String representation of the polygon in O(n) time.

</div>
</div>
<div class="layoutArea">
<div class="column">
returns twice the signed area of oriented triangle (a,b,c) in O(1) time. Runs in 𝑂(1) time.

disjointEdges(i, j) returns true iff edges 𝑒𝑖 and 𝑒𝑗 of the polygon are disjoint. Runs in 𝑂(1) time.

isSimple() returns true iff the polygon is simple. Running time is 𝑂 𝑛2 .

area() returns area of the interior of the polygon with precondition that the polygon is simple. Throws NonSimplePolygonException if the polygon is not simple (since in that case the polygon “interior” may not be well defined). Runs in 𝑂(𝑛) time, not counting the simplicity test.

</div>
</div>
<div class="layoutArea">
<div class="column">
delta(a,b,c)

disjointSegments (a,b,c,d) returns true iff closed line-segments (𝑎, 𝑏) and (𝑐, 𝑑) are disjoint.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Class ConvexPolygon (extends SimplePolygon):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
isConvex() returns true iff the polygon is convex, with precondition that the polygon is simple. This method runs in 𝑂(𝑛) time. If the polygon is non-simple, the correctness of the returned result is not guaranteed.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Class NonSimplePolygonException (extends Exception):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Thrown to indicate that the polygon is non-simple.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Class PolygonTester:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
This class has a main method that allows the user to input a variety of polygons and thoroughly test all aspects of the above types and methods, and displays or logs informative input-output.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Sample polygon input format:

Below are some sample input polygons listed by the xy-coordinates of the vertices in sequence around the polygon boundary. You should test your program against these samples. You should also test it against many other larger and carefully chosen polygons as well.

[ Format: n, followed by xy-coordinates of n boundary vertices in sequence. ]

</div>
</div>
<div class="layoutArea">
<div class="column">
Poly1: Poly2: Poly3: Poly4: Poly5: Poly6:

Poly7:

</div>
<div class="column">
5 8.9 21.8 29.1 8.8 39.2 20.3 14 11 28 25

7 28 2 31 5 28 10 14 14 5 10 8 4 18 1

9 6 10 20 3 23 3 23 8 27 3 30 3 20 15 16 5 20 14

13 5 6 13 2 12 6 20 2 16 12 17 11 19 5 13 11 19 15 8 12 14 7 5 11 9 6

13 5 6 13 2 12 6 20 2 18 12 17 11 19 5 13 11 19 15 8 12 14 7 5 11 9 6

22 14 7 15 8 17 7 17 5 15 6 14 4 12 6 11 9 15 11 7 12 8 11 7 9 10 11 8 6 10 5 11 3 16 3 18 4 19 8 16 9 14 9 13 8

4 61 95 582 4

</div>
</div>
<div class="layoutArea">
<div class="column">
What files to submit:

<ul>
<li>Polygon.java</li>
<li>SimplePolygon.java</li>
<li>ConvexPolygon.java</li>
<li>NonSimplePolygonException.java</li>
<li>PolygonTester.java</li>
<li>TestIO.txtThis text file records the Input/Output results of your test cases. Use copy-&amp;-paste from the Java program console to this text file. It should clearly show that you have tested at least 7 different polygons (non-simple, simple, convex), and for each of them you have thoroughly tested the corresponding class methods.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Extra Credit and Optional:

</div>
</div>
<div class="layoutArea">
<div class="column">
Implement the new boolean instance method contains(p) in the SimplePolygon class . This method returns true iff the simple polygon contains the given point p in its interior or on its boundary. This method should take O(n) time, with the precondition that the polygon is simple (otherwise, “interior” may not be well defined).

Note: you are not allowed to use the Polygon.contains() method provided by Java API. We expect you to implemented this method yourself.

This method is now inherited by the ConvexPolygon class.

Now you override that method in the ConvexPolygon class, so that it runs in O(log n) time.

Hints on how to implement this method:

• SimplePolygon.contains(p):

Conceptually shoot a ray emanating from point p in a direction of your choice (e.g., in the direction of the x-coordinate axis) and count how many times does that ray “cross” the boundary of the polygon. If that count is odd, then p is inside. If that count is even, then p is outside the polygon. If point p lies on any edge or vertex, then it is considered inside too.

You can treat that ray as a sufficiently long line-segment, and use the disjointSegments test against edges of the polygon to count the number of crossings. Be careful to count properly if the ray passes through a vertex or is aligned with an edge of the polygon. Resolve the ambiguity by conceptually perturbing the ray with a slight angular rotation so that it does not pass through any vertex of the polygon.

• ConvexPolygon.contains(p):

Can be done by a rotational binary search on the vertex sequence around the convex polygon boundary (using the Delta Test for orientation) …

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
</div>
