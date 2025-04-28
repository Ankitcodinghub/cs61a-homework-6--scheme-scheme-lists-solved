# cs61a-homework-6--scheme-scheme-lists-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Homework 6- Scheme, Scheme Lists Solved](https://www.ankitcodinghub.com/product/cs61a-homework-6-scheme-scheme-lists-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119654&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A Homework 6- Scheme, Scheme Lists Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Instructions

Download hw06.zip. Inside the archive, you will find a file called hw06.scm, along with a copy of the ok autograder.

Using Ok: If you have any questions about using Ok, please refer to this guide.

Readings: You might find the following references useful:

Scheme Specification

Scheme Built-in Procedure Reference

Grading: Homework is graded based on correctness. Each incorrect problem will decrease the total score by one point. There is a homework recovery policy as stated in the syllabus. This homework is out of 2 points.

Required Questions

Getting Started Videos

YouTube link

Code Writing Questions

Q1: Thane of Cadr

Define the procedures cadr and caddr, which return the second and third elements of a list, respectively. If you would like a quick refresher on scheme syntax consider looking at Lab 10 Scheme Refresher.

“`py (define (cddr s) (cdr (cdr s)))

(define (cadr s) ‘YOUR-CODE-HERE ) (define (caddr s) ‘YOUR-CODE-HERE ) “`

Use Ok to unlock and test your code: py python3 ok -q cadr-caddr -u python3 ok -q cadr-caddr Q2: Ascending

Implement a procedure called ascending?, which takes a list of numbers lst and returns True if the numbers are in nondescending order, and False otherwise. Numbers are considered nondescending if each subsequent number is either larger or equal to the previous, that is:

py 1 2 3 3 4

Is nondescending, but:

py 1 2 3 3 2

Is not.

Hint: The built-in null? function returns whether its argument is nil.

py (define (ascending? lst) ‘YOUR-CODE-HERE )

Use Ok to unlock and test your code:

py python3 ok -q ascending -u python3 ok -q ascending

Q3: Interleave

Implement the function interleave, which takes a two lists lst1 and lst2 as arguments. interleave should return a new list that interleaves the elements of the two lists. (In other words, the resulting list should contain elements alternating between lst1 and lst2.)

If one of the input lists to interleave is shorter than the other, then interleave should alternate elements from both lists until one list has no more elements, and then the remaining elements from the longer list should be added to the end of the new list.

py (define (interleave lst1 lst2) ‘YOUR-CODE-HERE )

Use Ok to unlock and test your code: py python3 ok -q interleave -u python3 ok -q interleave Q4: My Filter

Write a procedure my-filter, which takes a predicate func and a list lst, and returns a new list containing only elements of the list that satisfy the predicate. The output should contain the elements in the same order that they appeared in the original list.

Note: Make sure that you are not just calling the built-in filter function in Scheme – we are asking you to re-implement this!

py (define (my-filter func lst) ‘YOUR-CODE-HERE )

Use Ok to unlock and test your code: py python3 ok -q filter -u python3 ok -q filter Q5: No Repeats

Implement no-repeats, which takes a list of numbers lst as input and returns a list that has all of the unique elements of lst in the order that they first appear, but no repeats. For example, (no-repeats (list 5 4 5 4 2 2)) evaluates to (5 4 2).

Hint: How can you make the first time you see an element in the input list be the first and only time you see the element in the resulting list you return?

py (define (no-repeats lst) ‘YOUR-CODE-HERE )

Use Ok to unlock and test your code:

py python3 ok -q no_repeats -u python3 ok -q no_repeats
