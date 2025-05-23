# cs1301-lab-06-rock-paper-scissors-solved
**TO GET THIS SOLUTION VISIT:** [CS1301 Lab 06-Rock, Paper,Scissors Solved](https://www.ankitcodinghub.com/product/cs1301-lab-06-rock-paperscissors-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;54120&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1301 Lab 06-Rock, Paper,Scissors Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Good programmers think before they begin coding. Part I of this assignment involves brainstorming with a group of peers with no computers to talk about a strategy for solving this week’s lab. Breakup into groups based on your seating (3-4 people per group) and brainstorm about how to solve the problems below. Make sure everyone understands the problem and sketch out potential ways to move toward a solution.&nbsp; You may find it helpful to look over the required readings for this week.

<strong>Note: Brainstorms are to help you get started with the lab and get you in the habit of designing before you code.&nbsp; You won’t submit them to eLC. </strong>

<h1>Introduction</h1>
In the game <em>Rock, Paper, Scissors</em>, two players each choose either “rock,” “paper,” or “scissors,” and then show their choice to the other player at the same time. Each choice wins against one other choice and loses to one other choice:

<ul>
<li>Rock wins against scissors, but loses against paper.</li>
<li>Paper wins against rock, but loses against scissors.</li>
<li>Scissors win against paper, but lose against rock.</li>
<li>If both players make the same choice, the result is a tie.</li>
</ul>
&nbsp;

<h1>Assignment</h1>
In this lab, you will implement a version of <em>Rock, Paper, Scissors</em> where the user plays against the computer. The user puts in their choice as a String (either <strong>“rock”</strong>, <strong>“paper”</strong>, or <strong>“scissors” </strong><strong>– </strong>not case sensitive), and the computer will make its choice at random. The winner should be determined based on the rules above.

The user should be able to play <strong>multiple rounds</strong> of <em>Rock, Paper, Scissors</em> against the computer. The program should first <strong>ask the user how many wins they want to play</strong>. Your program should keep track of the score of both the computer and the user. <strong>If there is a tie, neither player gets a point</strong>. The program should keep running until either the player or the computer wins the number of games they specified at the start. So, for example, if the user inputs 3 when prompted, the game should continue until either the user <em>or </em>the computer wins three rounds (<em>not </em>once three rounds have been played).

After each turn, the program should print who won (either the player or the computer) and the score after that turn. Show the player’s score first (for example, if the computer has won once and the player has not won, show (0-1)).&nbsp; More examples of this can be seen in the sample runs below.

<h2>Instructions</h2>
Start by creating a new class named RockPaperScissors. Download the file ComputerOpponent.java from the CSCI 1301 site. It contains the code that generates the computer’s move for you. Once you have downloaded it, move the file into the src folder of your RockPaperScissors &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; project. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; It &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; should be &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; located &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; directly &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; alongside &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; your RockPaperScissors.java file in the same src folder.

Once you have both files in Eclipse, feel free to explore ComputerOpponent.java. There’s nothing in the code beyond anything we’ve covered already. Notice the variable,

<strong>static boolean TESTING_MODE = false; </strong>

When TESTING_MODE is false, ComputerOpponent.java will generate computer moves randomly using Math.random(). However, if you change TESTING_MODE to true, the moves that the computer generates will always come in a fixed order: <em>rock</em>, <em>paper</em>, <em>scissors</em>, <em>rock</em>, <em>paper</em>, <em>scissors</em>, <em>rock</em>, <em>paper</em>, <em>scissors</em>, … and so on. You may find it useful to change&nbsp; TESTING_MODE to true when you are testing and debugging your program, since the computer’s moves can be predicted.&nbsp; This will also help our TA’s when they are grading your code.

We will use our own version of ComputerOpponent.java when grading your lab, so don’t worry about messing with the functionality of that file (but make sure that all of the code <em>you </em>write stays in RockPaperScissors.java). <strong><em>Do not</em> rename </strong><strong>ComputerOpponent.java, as doing so will cause a compilation error when we try to grade your lab. </strong>

Once both java files are in the same src folder, you can get the computer move from ComputerOpponent.java by using its <strong>getMove() method.</strong> This method will return a String value which will be either “rock”, “paper”, or “scissors” (each being all lowercase).&nbsp; Here is the line of code to get the computer’s move:

<strong>String computerMove = ComputerOpponent.getMove();</strong>

On each turn, you should prompt the user for their move and retrieve it via the nextLine() method. The game should be able to recognize “rock”, “paper”, and “scissors” <em>regardless </em>of capitalization. If the user types something else, ask them to try again. <strong>Do not update either player’s score if the user did not enter a valid move</strong>.

<h2>Considerations While Brainstorming</h2>
Your program will be doing a lot of the same things over and over again, which means that a loop will be part of your code. Consider the following when brainstorming:

<ul>
<li>How do we keep track of the player’s and computer’s scores?</li>
<li>Which tasks belong <em>inside </em>the loop?
<ul>
<li>When you write your code, it may be easier to write the code for <em>one </em>iteration of the loop first, then putting that code inside a loop statement.</li>
</ul>
</li>
<li>Which tasks belong <em>outside</em> the loop?</li>
<li>Should our call to getMove() be <em>inside</em> or <em>outside</em> the loop? What happens if we don’t put it where it should be (i.e., inside the loop when it should be outside, or outside the loop when it should be inside)?</li>
<li>What should the condition for the loop be?
<ul>
<li>In other words, under what circumstances should the loop keep going? ● How do we handle unintended input, like Spock or gun?</li>
</ul>
</li>
</ul>
○ We can do better than simply ending the game immediately!
