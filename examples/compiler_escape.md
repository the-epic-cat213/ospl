<h1>Compiler Escape</h1>
<h2>What is a Compiler Escape?</h2>
<p>By default, OSPL code is put in a Java class by the compiler. However, there are some features of OSPL that need to be outside of the class. This can be done with a compiler escape. Compiler escapes are best used for including external classes.</p>
<h2Compiler Escape example: import</h2>
<p>You cannot import within a class in Java and by extension OSPL. However, you can use the compiler escape to import properly.</p>
<h3>example to import the class foo in com.example.bar(in compiler_escape.ospl class): </h3>
<p>#import com.example.bar.foo;</p>
<p>*(code)</p>
<h3>translates to:</h3>
<p>import com.example.bar.foo;</p>
<p>public class compiler_escape {//code}</p>
