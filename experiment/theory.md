<h3>Theory</h3>
<p>Breadth-First Search (BFS) explores the search space level by level, moving to the next level only when all states at the current level have been explored. We implement BFS using two lists: open and closed. The open list stores generated states whose children have not been examined, while the closed list records states that have been explored. States are added to the open list in the order they are generated and are removed using a first-in-first-out (FIFO) queue structure. The objective is to find routes using BFS with open and closed lists based on user-provided input.</p>

<h5>Breadth-First Search (BFS) with open and closed lists</h5>
<ol>
<li>Initialization:</li>
<ul>
<li>start at the initial state.</li>
<li>Initialize an empty open list and closed list.
</li>
</ul>
<li>Add Initial State:</li>
<ul><li>Add the initial state to the open list.</li></ul>
<li>Explore States:</li>
<ul><li>While the open list is not empty:</li>
<li>Remove the first state from the open list (using a FIFO queue).</li>
<li>Add this state to the closed list to mark it as explored.</li>
<li>Generate all possible successor states from the current state.</li>
<li>For each successor state:</li>
<li>If it has not already been explored (not in the closed list):</li>
<li>Add it to the open list.</li>
<li>Mark it as a child of the current state.</li>
</ul>
<li>Termination:</li>
<ul>
<li>Repeat the process until either the goal state is found or the open list becomes empty.</ul>
