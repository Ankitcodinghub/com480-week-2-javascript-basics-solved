# com480-week-2-javascript-basics-solved
**TO GET THIS SOLUTION VISIT:** [COM480 Week 2-JavaScript basics Solved](https://www.ankitcodinghub.com/product/com480-week-2-javascript-basics-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96762&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM480 Week 2-JavaScript basics Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1 id="javascript-basics">JavaScript basics</h1>
In this exercise we will practice programming with (JavaScript)[https://developer.mozilla.org/en-US/docs/Web/JavaScript], which we will need to create interactive visualizations in the browser. Today we will focus on processing data in JS, the functions used to plot the data are provided.

We would like to practice the functional style of programming, because it fits well with the d3.js library which we are going to use for the visualizations. This means that instead of&nbsp;<code>for</code>&nbsp;or&nbsp;<code>while</code>&nbsp;loops to iterate over arrays, we would use&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach"><code>forEach</code></a>,&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map"><code>map</code></a>,&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce"><code>reduce</code></a>&nbsp;and&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter"><code>filter</code></a>&nbsp;– if you haven’t seen them before, please take a look at the linked documentation which contains intuitive examples.

Please write your solutions in&nbsp;<code>exercise/exercise.js</code>&nbsp;and open the site&nbsp;<a href="exercise/index.html"><code>exercise/index.html</code></a>&nbsp;to execute them. Reload the page to re-run your script after applying changes. Remember that you can use the developer tools to interactively call your functions or see the values of variables.

<h2 id="functions-and-iteration">Functions and iteration</h2>
<h3 id="iseven">isEven</h3>
Let’s try a basic function&nbsp;<code>isEven</code>&nbsp;that will check if an integer is divisible by 2.

Then apply it over an array of integers to see the results:

<ul>
<li>Apply&nbsp;<code>isEven</code>&nbsp;to each element of&nbsp;<code>[1, 2, 3, 4, 5]</code>&nbsp;using&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map"><code>map</code></a>.</li>
<li>Choose even numbers from&nbsp;<code>1...5</code>&nbsp;by using&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter"><code>filter</code></a>.</li>
</ul>
<h3 id="multiply">multiply</h3>
Now, imagine, you do not know how many numbers in your array. In JS, there is a way to create functions with arbitrary number of parameters. This is also called&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax">Spread syntax</a>. Let’s implement a function&nbsp;<code>multiply</code>&nbsp;that computes a product of all numbers specified as parameters. For example,&nbsp;<code>multiply(1,2,3,4,5)</code>&nbsp;should return&nbsp;<code>120</code>.

<h2 id="closures">Closures</h2>
In JS, functions are treated as objects. When a function is created, it has access to all currently visible variables – the newly created function and these variables form a closure. The details are in the&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures">documentation about closures</a>.

<h3 id="divisibleby">divisibleBy</h3>
Let’s generalize the above example, and create the function&nbsp;<code>divisibleBy</code>&nbsp;which:

<ul>
<li>takes an argument&nbsp;<code>divisor</code></li>
<li>returns a function&nbsp;<code>f</code>&nbsp;such that&nbsp;<code>f(x)</code>&nbsp;returns&nbsp;<code>true</code>&nbsp;when&nbsp;<code>x</code>&nbsp;is divisible by&nbsp;<code>divisor</code></li>
</ul>
The&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions">arrow function</a>&nbsp;syntax is a convenient way to construct functions.

Now we have an alternative solution to the previous task&nbsp;<code>const isEvenNew = divisibleBy(2)</code>. Try filtering&nbsp;<code>[0, 1, 2, 3, 4, 5, 6]</code>&nbsp;by&nbsp;<code>divisibleBy(3)</code>.

<h3 id="increment">increment</h3>
Sometimes, in JS, you will have to deal with nested functions. Implement a function&nbsp;<code>increment</code>&nbsp;such that it can be called as&nbsp;<code>increment(100)(2)</code>&nbsp;with the first parameter as an initial value (<code>0</code>&nbsp;as a default parameter) and second params as a step size (<code>1</code>&nbsp;as a default parameter).

<h3 id="colorcycle">colorCycle</h3>
In plots, we often want to apply different colors, for example to distinguish between lines illustrating different quantities. When making a general mechanism, we can’t predict how many colored objects there are going to be, so we will make the colors repeat in a cycle.

Create a function&nbsp;<code>colorCycle</code>&nbsp;such that

<ul>
<li>it takes one argument: an array of colors,</li>
<li>the default value of the the color array is&nbsp;<code>COLOR_CYCLE_DEFAULT</code></li>
<li>it returns a function which repeats the colors in the cycle, for example
<code>cc = colorCycle(['red', 'green']); console.log([cc(), cc(), cc(), cc()]); // ['red', 'green', 'red', 'green']</code>
</li>
</ul>
Now create a cycle&nbsp;<code>my_cc</code>&nbsp;with your chosen colors and run&nbsp;<code>showColorCycle(my_cc)</code>&nbsp;to apply the colors to a demo plot on the website&nbsp;<a href="exercise/index.html"><code>index.html</code></a>.

<figure><img decoding="async" data-src="task_images/color_cycle.png" width="640" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></figure>
<h2 id="range">Range</h2>
In the above task, we were writing the sequences&nbsp;<code>[1, 2, ..., N]</code>&nbsp;explicitly, now let’s automate it.

<ul>
<li>Create a function&nbsp;<code>range(N)</code>&nbsp;which constructs a range of integers [0, 1, …, N-1].
For an additional challenge, you can try using a functional approach, that is without a&nbsp;<code>for</code>&nbsp;or&nbsp;<code>while</code>&nbsp;loop.

We could try creating an empty array of size&nbsp;<code>N</code>:&nbsp;<code>Array(N)</code>. However, the elements of the array are not created and&nbsp;<code>forEach</code>&nbsp;or&nbsp;<code>map</code>&nbsp;does nothing. Try it yourself:&nbsp;<code>Array(10).forEach(console.log)</code>

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from">Array.from</a>&nbsp;allows us to create an array from another sequence – for example convert a string to an array like we did with letter counting.&nbsp;<code>Array.from(Array(10))</code>&nbsp;actually creates the elements and we could iterate over them (the elements are&nbsp;<code>undefined</code>).

Additionally, we can pass a function as the second argument – this function will be applied on every element of the newly created array.&nbsp;<code>Array.from(seq, f)</code>&nbsp;is equivalent to&nbsp;<code>Array.from(seq).map(f)</code>&nbsp;but more efficient because it does not create the intermediate array. Remember that the mapping function receives as arguments both the current element and the current index.
</li>
<li>Let’s find the integers from 0 to 100 which are divisible by 13. Create a range&nbsp;<code>[0, ..., 99]</code>&nbsp;and filter it by divisibility by 13</li>
<li>Implement a function&nbsp;<code>randomInRange(min_val=0, max_val=100)</code>&nbsp;which returns a random float value between&nbsp;<code>min_val</code>&nbsp;and&nbsp;<code>max_val</code>.</li>
<li>Implement a function&nbsp;<code>randomArray(N, min_val=0, max_val=100)</code>&nbsp;which generates an array of&nbsp;<code>N</code>&nbsp;random values between&nbsp;<code>min_val</code>&nbsp;and&nbsp;<code>max_val</code>.</li>
</ul>
<h2 id="counting">Counting</h2>
<ul>
<li>Create a function&nbsp;<code>countOccurences(string)</code>&nbsp;which counts the number of occurences of each letter in a string. For example&nbsp;<code>countOccurences("hello")</code>&nbsp;yields&nbsp;<code>{'h': 1, 'e': 1, 'l': 2, 'o': 1 }</code>. A string is not an array and it does not have the&nbsp;<code>forEach</code>&nbsp;or&nbsp;<code>map</code>&nbsp;methods, so to use them, convert a string to an array with&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from">Array.from</a>, for example&nbsp;<code>let a = Array.from('a string!');</code>.
To store the counts, use an&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object">Object</a>&nbsp;which is key-value container with strings as keys (in our case, the key will be the letter).

To perform functional-style iteration over Objects, use&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys"><code>Object.keys</code></a>,&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values"><code>Object.values</code></a>&nbsp;and&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries"><code>Object.entries</code></a>. Please remember that they have to be called&nbsp;<code>Object.entries(obj)</code>&nbsp;instead of&nbsp;<code>obj.entries()</code>.
</li>
<li>Create the function&nbsp;<code>normalizeCounts</code>&nbsp;which takes the character counts outputted by&nbsp;<code>countOccurences</code>, and calculates normalized counts – that is divided by the total sum. Please calculate the sum using&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce"><code>reduce</code></a>. For example:&nbsp;<code>normalizeCounts({'h': 1, 'e': 1, 'l': 2, 'o': 1})</code>&nbsp;yields&nbsp;<code>{'h': 0.2, 'e': 0.2, 'l': 0.4, 'o': 0.2}</code></li>
<li>Create&nbsp;<code>countOccurencesNormalized</code>&nbsp;– a function which given a string, first applies&nbsp;<code>countOccurences</code>&nbsp;and then normalizes the counts using&nbsp;<code>normalizeCounts</code>.</li>
<li>Visualize the results by calling&nbsp;<code>setCharacterCountingFunction(countOccurencesNormalized);</code>&nbsp;– look at&nbsp;<code>index.html</code>, now you should be able to count the distribution of characters in any text you input. You can pass a&nbsp;<code>colorCycle</code>&nbsp;with your colors as the second argument to color the bars.</li>
</ul>
<figure><img decoding="async" data-src="task_images/character_counting.png" width="640" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></figure>
<h2 id="advanced-exercise.-throwing-balls-optional">Advanced exercise. Throwing balls (optional)</h2>
We will simulate a ball thrown at angle&nbsp;<span class="math inline"><em>b</em></span>&nbsp;with velocity&nbsp;<span class="math inline"><em>v</em><sub>0</sub></span>. The initial velocity&nbsp;<span class="math inline">(<em>v</em><sub><em>x</em></sub>, <em>v</em><sub><em>y</em></sub>)</span>&nbsp;is:

<span class="math display"><em>v</em><sub><em>x</em></sub> = <em>v</em><sub>0</sub><em>c</em><em>o</em><em>s</em>(<em>b</em>)</span>

<span class="math display"><em>v</em><sub><em>y</em></sub> = <em>v</em><sub>0</sub><em>s</em><em>i</em><em>n</em>(<em>b</em>)</span>

The position of the ball at time&nbsp;<span class="math inline"><em>t</em></span>&nbsp;is given by:

<span class="math display"><em>x</em>(<em>t</em>)=<em>v</em><sub><em>x</em></sub> * <em>t</em></span>

<span class="math display"><em>y</em>(<em>t</em>)=<em>v</em><sub><em>y</em></sub> * <em>t</em> + (<em>a</em> * <em>t</em><sup>2</sup> * 0.5)</span>

where&nbsp;<span class="math inline"><em>a</em></span>&nbsp;is the acceleration caused by gravity, usually -9.81&nbsp;<span class="math inline"><em>m</em>/<em>s</em><sup>2</sup></span>.

Implement a function&nbsp;<code>simulateBall(v0, angle, num_steps, dt, g)</code>&nbsp;such that:

<ul>
<li><code>v0</code>&nbsp;is the magnitude of the initial velocity</li>
<li>‘angle’ is the inclination angle in degrees, multiply by&nbsp;<code>DEG_TO_RAD = Math.PI / 180.</code>&nbsp;to get radians for the trigonometric functions,</li>
<li><code>num_steps</code>&nbsp;is the number of steps of the simulation, the default value should be 256,</li>
<li><code>dt</code>&nbsp;is the time that advances between steps, default value 0.05,</li>
<li><code>g</code>&nbsp;is the acceleration, default value -9.81,</li>
<li>it returns an array of ball positions at each time step,</li>
<li>each position is given as a array&nbsp;<code>[x, y]</code>,</li>
</ul>
Use the&nbsp;<code>range</code>&nbsp;function to create the array of time points, then&nbsp;<code>map</code>&nbsp;them to the&nbsp;<code>[x, y]</code>&nbsp;values given by the equations above.

<ul>
<li>We want to finish the plot when the ball hits the ground (y=0), so please filter the point array to remove points with y below 0.</li>
<li>Visualize the ball trajectories using&nbsp;<code>plotBall</code>&nbsp;(the 2nd optional argument is the line color):</li>
</ul>
<pre><code>const ball_cc = colorCycle(['hsl(160, 100%, 64%)', 'hsl(200, 100%, 64%)', 'hsl(240, 100%, 64%)', 'hsl(120, 100%, 64%)', 'hsl(80, 100%, 64%)']);
plotBall(simulateBall(40, 60), ball_cc());
plotBall(simulateBall(40, 30), ball_cc());
plotBall(simulateBall(40, 45), ball_cc());</code></pre>
<ul>
<li>Use&nbsp;<code>randomArray</code>&nbsp;to create 20 random angles between 0 deg and 90 deg, then plot the ball trajectories for each angle.</li>
</ul>
