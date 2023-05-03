Download Link: https://assignmentchef.com/product/solved-cs-489-assignment-1
<br>
Reinforcement Learning

1 Introduction

The goal of this assignment is to do experiment with Dynamic Programming(DP), including iterative policy evaluation, policy iteration and value iteration. Your goal is to implement DP methods and test them in the small gridworld men­tioned in the slides of Lecture 3.

2 Small Gridworld

Figure 1: Gridworld

As shown in Fig.1, each grid in the Gridworld represents a certain state. Let st denotes the state at grid t. Hence the state space can be denoted as S = {st|t ∈ 0, .., 35}. S1 and <sub>S</sub><sub>35</sub> are terminal states, where the others are non-terminal states and can move one grid to north, east, south and west. Hence the action space is A = {n, e, s, w}. Note that actions leading out of the Gridworld leave state unchanged. Each movement get a reward of -1 until the terminal state is reached.

A good policy should be able to find the shortest way to the terminal state randomly given an initial non-terminal state.

3 Experiment Requirments
<ul>
 	<li>Programming language: python3</li>
 	<li>You should build the Gridworld environment and implement iterative pol­icy evaluation methods and policy iteration methods. Then run the two methods to evaluate and improve an uniform random policy π(n|·) = π(e|·) = π(s|·) = π(w|·) = 0.25</li>
</ul>
&nbsp;

[pdf-embedder url="https://assignmentchef.com/wp-content/uploads/2022/12/A1-DESCRIPTION.pdf" title="A1 DESCRIPTION"]