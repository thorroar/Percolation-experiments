Some visualisation experiments i've been running for simple lattices on percolation. Mainly for distinct clusters, emphasising the colourful aspect of it.

Wish to find a nice way to extend what i learn for the Z^d lattice to other regular models

Observations for 3d

The spanning label at p = 0.35 is not 1 (which you would expect) its bigger but still relatively small like between 2 and 10 

It probably is (also) 1 but since you dont print out the whole spanning label and only the smallest, youre getting that there are many infinite clusters (which is intereesting in itself.)

# to do
- change the percolating functions so they output the whole spanning label array
- add boolean output of percolation functions to add to graph if system percolates or not

# theory questions

- why is the number of labeled clusters so large ?
- what is this strange gradient behaviour that appears in Z^2 for large n near the cirtical value.
    partially answered by Ott, solution is to only colour the 10th largest clusters.

# coding questions
- how to visualise different lattices ex hexagons
- how to visualise what is happening inside Z^3, interactively remove one colour?
    interactively being the key word.

