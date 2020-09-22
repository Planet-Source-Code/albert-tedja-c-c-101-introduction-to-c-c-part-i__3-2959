<div align="center">

## C/C\+\+ 101: Introduction to C/C\+\+ \(Part I\)


</div>

### Description

This tutorial is made to help people learning C/C++ language which is commonly believed as a hard language.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Albert Tedja](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/albert-tedja.md)
**Level**          |Beginner
**User Rating**    |4.6 (78 globes from 17 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Documents](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/documents__3-27.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/albert-tedja-c-c-101-introduction-to-c-c-part-i__3-2959/archive/master.zip)





### Source Code

<html>
<head>
<title>C/C++ 101: Introduction to C/C++ (Part I)</title>
</head>
<body>
<p><font size="6">C/C++ 101: Introduction to C/C++</font></p>
<p>&nbsp;</p>
<p><font size="4">Part I: C for beginners, not C++, and the main function.</font></p>
<p>This tutorial (or article) is designed for those who want to learn C++ but
find a great difficulty in learning it. I also had the same experience when I
tried to learn C++, but then, I discovered something that causes the learning
gets very difficult. I'll show you that C/C++ is an easy language.</p>
<p>I'll assume that you are beginners to C/C++ because you're reading this. I'll
ask you something, what is the difference between C and C++? You probably don't
know or try to guess. At first, I thought the difference was that C was old, C++
was new. If you think the same way like I did, you're wrong. That's not the
difference, there's something else--more important. That what makes the language
C++ gets so hard. Unless you understand the difference, you will always find
trouble in learning C++. Let's take a look at our favorite/boring/hard/confusing
&quot;Hello World&quot; program written in C++, not C.</p>
<table border="0" width="100%">
 <tr>
  <td width="100%" bgcolor="#99FFCC"><font face="Courier New" size="2">#include
   &lt;iostream.h&gt;<br>
   <br>
   main()<br>
   {<br>
   &nbsp;&nbsp;&nbsp; cout &lt;&lt; &quot;Hello World&quot; &lt;&lt; endl;<br>
   }</font></td>
 </tr>
</table>
<p>For those who haven't seen this code before, welcome to the wonder of
confusion. I'm sure you get really confused looking that code. That code will
print a text &quot;Hello World&quot; on the screen. For those you have seen the
code and still confused with C++, you will recall that confusion. Let's ask,
what does symbol <font face="Courier New" size="2" color="#000080">&lt;&lt;</font>
actually mean? If we consult our trusty Help manual, it will give you something
like this: &quot;bitwise shift operation.&quot; Hmm...and what is that supposed
to mean? Well, honesty, it's something related to computation, the same like +
and -, only it relates to binary operation. Maybe you're asking, do we really
need those stuff if we want to print just a &quot;Hello World&quot; on screen?
No. The symbol <font face="Courier New" size="2" color="#000080">&lt;&lt;</font>
in the above code is <i>overloaded</i> by the <i>object</i> <font face="Courier New" size="2" color="#000080">cout</font>.
The object <font face="Courier New" size="2" color="#000080">cout</font> uses
symbol <font face="Courier New" size="2" color="#000080">&lt;&lt;</font> to
print the &quot;Hello World.&quot; Wait. Overload? Object? Yes, overload,
object. Don't get it? Of course, those terms are used when you learn about
classes which is unique to C++. Classes are the actual thing that differ C++
from C, and those are advanced stuff. I never understand why they use such thing
to teach beginners. <font face="Courier New" size="2" color="#000080">cout</font>
is definitely not for beginners, especially that symbol <font face="Courier New" size="2" color="#000080">&lt;&lt;</font>
that initializes the confusion. At the first time I looked at that symbol, I
said, &quot;Wow, that's so weird.&quot; And I looked at another symbol: <font face="Courier New" size="2" color="#000080">&gt;&gt;</font>
used by <font face="Courier New" size="2" color="#000080">cin</font>, I
commented even more, &quot;Do I have to do this in C++? It doesn't make
sense.&quot; It doesn't make sense because people use it like this:</p>
<table border="0" width="100%">
 <tr>
  <td width="100%" bgcolor="#99FFCC"><font face="Courier New" size="2">cin
   &gt;&gt; a_variable;</font></td>
 </tr>
</table>
<p>when they want to get input from user and put it into <font face="Courier New" size="2" color="#000080">a_variable</font>.
They don't use the popular equal sign operator like other languages. If you know
Pascal or BASIC, you might say, &quot;What the....&quot; and your face starts to
get squashed. You don't understand what it actually does because of the weird
symbol <font face="Courier New" size="2" color="#000080">&lt;&lt;</font> and <font face="Courier New" size="2" color="#000080">&gt;&gt;</font>,
then you give up learning, and say, &quot;C++ is hard.&quot; I'm telling you,
there's nothing special with C/C++. They're languages, just like Pascal and
BASIC, and are learnable. Books and tutorials out there do not give you an easy
way to learn it. They give you the hard way by using classes and overloaded
operators without giving any details about them. They did that because they
think that it's the most basic thing they can teach you, while in fact, it's not
basic.</p>
<p>So, now do you understand why you couldn't learn C++ in the past? I hope you
do. Let's forget about all those things and start this tutorial. This tutorial
will teach you about C (not C++) language. Don't worry, you are not going to
learn something obsolete. As I mentioned before, the biggest difference about C
and C++ are an advanced stuff calles <i>class</i>. For beginners, they are the
same. All you learn here is still valid and still used by people. In fact, it
will become your road in learning more advanced stuff about C and C++. Once you
grasp the knowledge of C, you can start learning about classes (C++) and then
you can say, &quot;Hey, C++ is easy.&quot;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><font size="4"><b>The C Structure</b></font></p>
<p>Before we start, I highly recommend that you have a working C/C++ compiler on
your computer. It may be C or C++ compiler, doesn't matter, as long as it works.
Without one, all learning process will be vague. Learn how to compile using your
compiler so you know that your code works. One more thing, all we are going to
program here run under DOS. We're not talking about Windows programming here
because it's different case and much difficult. So, if everything is ready and
you feel ready too, let's get started.</p>
<p>What is the simplest C program? The &quot;Hello World?&quot; Could be, but
I'll tell you what are the most important things in C, that you must have in
every C program (that runs under DOS). Look at the code below:</p>
<table border="0" width="100%">
 <tr>
  <td width="100%" bgcolor="#99FFCC"><font face="Courier New" size="2">main()<br>
   {<br>
   <br>
   }</font></td>
 </tr>
</table>
<p>&nbsp;</p>
<p>If you try to compile it, it will compile but does nothing. Why? Because we
haven't put anything in the code. What about that <font face="Courier New" size="2" color="#000080">main()</font>
and those two braces? What are they doing there? Let's discuss them one by one.</p>
<p>The above code must always present in any C program written for DOS. The <font color="#000080" face="Courier New" size="2">main()</font>
in the above code is called the main <i>function</i>. The main function is the
function that is considered the body of your program. Without one, your code
won't compile. You will type your actual program inside this function. But, how
do we know that we are typing inside the main function? The two braces do the
job. They simply mean BEGIN and END. The open brace ( <font color="#000080">{</font>
) means BEGIN, and the closing brace ( <font color="#000080">}</font> ) means
END. This illustration shows how they actually works.</p>
<table border="0" width="100%">
 <tr>
  <td width="100%" bgcolor="#99FFCC"><font face="Courier New" size="2"><i>a_something<br>
   {<br>
   &nbsp;&nbsp;&nbsp; whatever between these braces..<br>
   &nbsp;&nbsp;&nbsp; belong to a_something<br>
   }</i></font></td>
 </tr>
</table>
<p>So, if we apply the above illustration to our code above, we know that
whatever inside the braces belong to <font face="Courier New" size="2" color="#000080">main()</font>.
But in our code, we see nothing between the braces, that's why the code does
nothing.</p>
<p>Now, let's discuss more about <font face="Courier New" size="2" color="#000080">main()</font>.
Why are those parentheses sitting there? Can't we just use <font face="Courier New" size="2" color="#000080">main</font>
instead of <font face="Courier New" size="2" color="#000080">main()</font>. As
said before, <font face="Courier New" size="2" color="#000080">main()</font> is
a function, and a function can take arguments or parameters. The parentheses are
used to define those arguments even if we don't have any arguments. If we define
an argument, the <font face="Courier New" size="2" color="#000080">main()</font>
will look like this:</p>
<table border="0" width="100%">
 <tr>
  <td width="100%" bgcolor="#99FFCC"><font face="Courier New" size="2">main(argument)</font></td>
 </tr>
</table>
<p>Since we don't have any arguments, we define nothing between the parentheses.
But what about if we do? What happens? If you ever tried to run an old program
in DOS, sometimes you are asked to specify some special commands like this:</p>
<p><font face="Courier New" size="2">program.exe /mode /open:sample.txt /scan</font></p>
<p><font face="Courier New" size="2">/mode</font>, <font face="Courier New" size="2">/open:sample.txt</font>,
and<font face="Courier New" size="2"> /scan</font> are the arguments of the main
function of <font face="Courier New" size="2">program.exe</font>. We define
arguments for main function when we want to make our program to accept some
special commands like the above example. These arguments are called <i>command-line
arguments</i>. For now, we don't talk about it, so just leave it blank.</p>
<p>Now, let's complicate the code a little bit by adding one more word.</p>
<table border="0" width="100%">
 <tr>
  <td width="100%" bgcolor="#99FFCC"><font face="Courier New" size="2"><font color="#0000FF">int</font>
   main()<br>
   {<br>
   <br>
   }</font></td>
 </tr>
</table>
<p>We've just added one word called <font face="Courier New" size="2" color="#000080">int</font>.
We put it before the function <font face="Courier New" size="2" color="#000080">main()</font>
because it has special meaning to <font face="Courier New" size="2" color="#000080">main()</font>.
The word <font face="Courier New" size="2" color="#000080">int</font> represent
the type of the return value of the function <font face="Courier New" size="2" color="#000080">main()</font>.
Type of return value? Correct. A function can generate a return value to tell
many different things. It can say whether the function has succeed or not. It
can say other things too, depends on the programmers. So, what about the type.
The type defines what kind of return value the function pass. Is it a number?
How big the number? Does the number has decimals? Or maybe it's a string. It can
be anything, and again, depends on the programmers. What we have here is <font face="Courier New" size="2" color="#000080">int</font>.
<font face="Courier New" size="2" color="#000080">int</font> means integer, a
16-bit numeric value that vary from -32768 to 32767. So, the statement <font face="Courier New" size="2" color="#000080">int
main()</font> simply means that the function <font face="Courier New" size="2" color="#000080">main()</font>
will return a value vary from -32768 to 32767.</p>
<p>But wait, before this one, we didn't mention the type of return value of
function <font face="Courier New" size="2" color="#000080">main()</font>, would
that be okay? Technically, no. However, it depends on the compiler you use. Some
compilers put a default type if we don't specify it. For example, Borland Turbo
C++ 3.0 use <font face="Courier New" size="2" color="#000080">int</font> as the
default.</p>
<p>&nbsp;</p>
<p>OK, if I continue this tutorial, it will be very long. I think I will stop
here and continue it in the next section. The next section will talk about the
data types, how to return a value, and how to print a text on screen in a more
understandable C way.</p>
<p>&nbsp;</p>
<p>Some words used in this tutorial:</p>
<table border="1" width="97%">
 <tr>
  <td width="20%"><b>to overload</b></td>
  <td width="80%">to use operators in different ways.</td>
 </tr>
 <tr>
  <td width="20%"><b>classes</b></td>
  <td width="80%">a group of variables and functions, concept of
   object-oriented programming.</td>
 </tr>
 <tr>
  <td width="20%"><b>objects</b></td>
  <td width="80%">variables defined of type class.</td>
 </tr>
 <tr>
  <td width="20%"><b>functions</b></td>
  <td width="80%">a set of code used to perform special tasks using available
   arguments.</td>
 </tr>
 <tr>
  <td width="20%"><b>arguments</b></td>
  <td width="80%">variables passed to a function.</td>
 </tr>
</table>
<p>&nbsp;</p>
<p>Note: all words, materials, and definitions defined in this tutorial are my
own opinions which I consider true. If in any case you find them wrong,
corrections would be very helpful. This tutorial is made to help people learning
C/C++ language which is commonly believed as a hard language.</p>
<p>Copyright (C) 2001, Albert Tedja.</p>
</body>
</html>

