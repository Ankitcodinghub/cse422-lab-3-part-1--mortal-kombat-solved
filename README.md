# cse422-lab-3-part-1--mortal-kombat-solved
**TO GET THIS SOLUTION VISIT:** [CSE422 Lab 3 Part 1- Mortal Kombat Solved](https://www.ankitcodinghub.com/product/cse422-part-1-mortal-kombat-5-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131943&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE422  Lab 3 Part 1- Mortal Kombat Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In the world of Mortal Kombat, the ultimate battle between Scorpion and Sub-Zero is about to commence in the Earth realm. The air is thick with tension as these two legendary warriors prepare to face off in a fight to the death. Both fighters are masters of their respective arts, each with a full health bar, ready to unleash their fury upon one another. In this brutal, turn-based clash, the warriors will alternately strike at their opponent and ensure victory.

As the battle unfolds, every turn counts. Will it be Scorpion, with his fiery vengeance, who claims victory? Or will Sub-Zero’s icy precision lead him to triumph? The outcome depends on the initial setup: who strikes first, and how powerful their moves can be.

Your task is to simulate this epic showdown given the initial conditions – who starts the battle and determines who emerges as the victor. Prepare yourselves, for this is Mortal Kombat, where only one warrior will be left standing. Round 1, Fight!

Game Description &amp; Rules:

● Players: Scorpion and Sub-Zero.

● Turn-Based Gameplay: Players take turns to attack.

● Turns: The player specified by the first input number will take the first turn in the first round. The player who didn’t take the first turn in the previous round will start in subsequent rounds.

● Assume the branching factor = 2 and the max depth of the game tree = 5

● You have to create the appropriate number of leaf nodes and assign them utility values (-1 if scorpion wins, and 1 if sub-zero wins)

Input

● One single-digit number. The number indicates which player starts first (0 for Scorpion, 1 for SubZero).

Output

● The name of the game-winner.

● The number of rounds played. ● The winner of each round.

Sample Input:

0

Sample Output:

Game Winner: Scorpion

Total Rounds Played: 3

Winner of Round 1: Sub-Zero

Winner of Round 2: Scorpion

Winner of Round 3: Scorpion

Now apply the alpha-beta pruning algorithm to simulate the problem and find the winner.

Part 2: Games with Magic [5 Points]

In a strategic game simulation, Pacman and a ghost engage in a sequence of moves across three levels of depth. The competition starts with Pacman aiming to reach a power pellet by making the first move. The ghost then attempts to thwart Pacman’s progress at the second level, followed by Pacman’s final moves to reach the pellet at the leaf nodes, where the outcomes are scored as 3, 6, 2, 3, 7, 1, 2, 0. An added strategic element is Pacman’s ability to wield dark magic, allowing him to control the ghost’s move at a specific cost, c. This cost is deducted from his score, influencing his overall strategy to reach the pellet.

You are tasked with developing the function pacman_game(int c) to determine the most effective strategy for Pacman, considering whether the use of dark magic, given its cost, is beneficial.

Input (c) Output

2 The new minimax value is 5. Pacman goes right and uses dark magic

5 The minimax value is 3. Pacman does not use dark magic

In sample output 1, the left subtree has the highest value 6 and the right subtree has the highest value 7. If Pac-Man moves to the left and uses dark magic the result will be 6 – 2 = 4, If Pac-Man moves to the right and uses dark magic the result will be 7 – 2 = 5.

And now, using Alpha-beta pruning find the final value of the root node without using dark magic. Then check whether using dark magic is advantageous for Pac-Man or not.

[Hint: The final value of the root node will be 3. So using dark magic is advantageous for Pac-Man in both directions, but it’s more beneficial when Pac-Man goes right.]

Part 3: Food for thought [0 Points]

● Is the first player always a maximizer node?

● Can alpha-beta pruning handle stochastic environments?
