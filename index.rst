############################
Table building test document
############################

The following table will not correctly compile to LaTeX in sphinx, or docutils:

+--------------------+----------------+
|  2 rows and 2 cols | 1 row x 3 cols |
|                    +----+-----+-----+
|                    |  A |  B  |  C  |
+---+----------------+----+-----+-----+
| 1 |       2        |  3 |  4  |  5  |
+---+----------------+----+-----+-----+

