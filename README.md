# cse224-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CSE224 Assignment 4 Solved](https://www.ankitcodinghub.com/product/cse224-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95951&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE224 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Overview

For this assignment, you’re going to read lines of text from stdin, break them into phrases, store them in an array, and record how many times each phrase occurs in the input. Upon reaching the end of the input (signaled by the user hitting CTRL-D alone on a line), your program should print out a list of all phrases it found, along with the number of times each phrase occurred. The list should be sorted in increasing order of length, i.e., print the shortest phrases first, the longest ones last (the order of phrases that are the same length does not matter).

Details

• convert everything to uppercase: Hello hello and HELLO are all treated the same;

• convert newlines and other whitespace (TAB, etc.) into spaces (so a phrase split on 2 lines doesn’t get broken by a newline) Use the isspace() function to detect whitespace

• ignore the following characters: ( ) ‘ ” –

• a phrase:

<ul>
<li>begins with any non-space character other than , . ; : ? !</li>
<li>is a collection of consecutive letters, characters and spaces, excluding , . ; : ? !</li>
<li>ends with any of the following characters , . ; : ? !
For your final output, print the occurrence count first, as a 5-digit integer with leading 0’s included; followed by the phrase enclosed in &lt;angle brackets&gt;

So here’s an example of some pseudocode:

1. read* from stdin until you find the beginning of a phrase

2. read* from stdin until you find the end of a phrase, storing each character in a temporary string

<ol start="3">
<li>if you’ve never seen this phrase before, save it, and record 1 for the # of occurrences
if you’ve already saved this phrase, increment the occurrence counter
</li>
<li>Repeat steps 1-3 until you hit EOF</li>
<li>sort the array of saved phrases by length</li>
<li>print the sorted array of phrases, along with the occurrence count.</li>
</ol>
*you may want to code your own getchar() function, to handle the following:
</li>
</ul>
<ul>
<li>ignore ( ) ‘ ” –</li>
<li>convert all whitespace to a space (‘ ‘)</li>
<li>convert letters to uppercase
You shpuld assume:
</li>
</ul>
<ul>
<li>each phrase is 200 or fewer characters (if a phrase is longer, ignore the remainder of the
phrase);
</li>
<li>there is a maximum of 1,000 phrases (if you encounter more phrases, just ignore them…but
keep tallying the first 1,000 phrases)

You should use statically-defined arrays, i.e., declare a char dictionary[1000][201] and int count[1000], where dictionary[i] stores the ith phrase and count[i] stores that phrase’s tally. Alternatively, you are free to use structures to simplify your coding 🙂

All code must be your own, other than routines from stdio.h, string.h, ctype.h and stdlib.h Do not use any pre-built sorting or hash functions.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Here’s a sample input file:

Hello, hahaha: this is a sample file. It contains

a number of lines, with different punctuations and spacings.

We can analyze this file, breaking the input into phrases, and tallying them.

But be careful: there are a lot of details to worry about! So, this is a test file.

Also, this is a sample file.

So, it is both! Hahaha.

and here is what it should output: 00002 &lt;SO&gt;

00001 &lt;ALSO&gt;

00001 &lt;HELLO&gt;

00002 &lt;HAHAHA&gt;

00001 &lt;IT IS BOTH&gt;

00001 &lt;BUT BE CAREFUL&gt;

00001 &lt;AND TALLYING THEM&gt;

00001 &lt;THIS IS A TEST FILE&gt;

00002 &lt;THIS IS A SAMPLE FILE&gt;

00001 &lt;WE CAN ANALYZE THIS FILE&gt;

00001 &lt;IT CONTAINS A NUMBER OF LINES&gt;

00001 &lt;BREAKING THE INPUT INTO PHRASES&gt;

00001 &lt;WITH DIFFERENT PUNCTUATIONS AND SPACINGS&gt; 00001 &lt;THERE ARE A LOT OF DETAILS TO WORRY ABOUT&gt;

I strongly recommend experimenting with different input files!

Suggestions

This assignment is an excellent opportunity on which to practice modular coding, and a top-down design methodology. Think carefully about your overall algorithm; break it into a few steps and code your main loop accordingly. Then begin coding the functions to implement each of those steps. Work in pieces, developing, testing and debugging each piece as you go. Some of the pieces you may need include:

<ul>
<li>a way to read stdin and pre-process the characters;</li>
<li>a way to detect the beginning of a phrase;</li>
<li>a way to detect the end of a phrase;</li>
<li>a way to store a phrase into a dictionary (either as a new entry or an additional tally on a
phrase you’ve already seen);
</li>
<li>a way to sort your dictionary;</li>
<li>a way to print your dictionary.</li>
</ul>
</div>
</div>
</div>
