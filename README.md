# Optimization

In this repository you'll find the analysis of the techniques behind each method and an example to help clarify how would work the implementation of them. 

<h2>How to choose an algorithm to optimization?</h2>

Based on the course of MIT for Multidisciplinary System Design Optimization we have a good start point
:
<table> 
<tbody><tr bgcolor="silver">
<td>&nbsp;</td>
<td>
    <b>Linear</b><p><i>All functions related to the problem</i></p>
</td>
<td>
    <b>Nonlinear</b><p><i>At least one function related to the problem</i></p>
</td>
<tr bgcolor="white">
<td><b>Continouous</b>, real x (all)</td>
<td>
    <p><a href="Simplex%20Algorithm.ipynb">Simplex</a></p>
<p>Barrier Methods</p>
</td>
<td>
    <p><a href="Sequential%20Least%20Squares%20Programming.ipynb">SQP (constrained)</a></p>
<p>Newton (unconstrained)</p>
</td>
</tr>
<tr bgcolor="white">
<td><b>Discrete</b> x (at least one)&nbsp;</td>
<td>MILP</td>
<td>
    <p><a href="Genetic%20Algorithm%20PyEasyGA.ipynb">Genetic Algorithm (GA)</a></p>
    <p><a href="Simulated%20Annealing.ipynb">Simulated Annealing (SA)</a></p>
<p>Tabu Search</p>
    <p><a href="Particle%20Swarm.ipynb">Particle Swarm Optimization (PSO)</a></p>
</td>
</tr>
</tbody>
</table>
