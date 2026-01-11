# Conditional Probability
To Calculate the probability for if someone is Obese and likes Chocolate preference we first make a contingency table of the total amount of the people who are obese, likes chooclate, isnt obese, likes chocolate, obese, doesnt like chocolate, and isnt obese and doesnt like chocolate in a table:
|          | Likes Chocolate | Hates Chocolate |
|----------| :---------------| :---------------|
| Is Obese | 8               | 2               |
| Is Not Obese | 4           | 6               |

then we do the formula:
for each element: p=amount/total

|          | Likes Chocolate | Hates Chocolate |
|----------| :---------------| :---------------|
| Is Obese | 8               | 2               |
|          | p = 8/20 = 0.4  | p = 2/20 = 0.1  |
| Is Not Obese | 4           | 6               |
|          | p = 4/20 = 0.2  | p = 6/20 = 0.3  |

so that means there is a 40% percent chance we'll see someone who is obese and likes chocolate.
if we only want to know if someone is obese or not obese regardless of their opinion of chocolate, we first make the row totals:

|          | Likes Chocolate | Hates Chocolate | Row Total |
|----------| :---------------| :---------------| :---------|
| Is Obese | 8               | 2               | 8 + 2 = 10|
|          | p = 8/20 = 0.4  | p = 2/20 = 0.1  |           |
| Is Not Obese | 4           | 6               | 4 + 6 = 10|
|          | p = 4/20 = 0.2  | p = 6/20 = 0.3  |           |


then we calculate the the probailities for each row

|          | Likes Chocolate | Hates Chocolate | Row Total |
|----------| :---------------| :---------------| :---------|
| Is Obese | 8               | 2               | 8 + 2 = 10|
|          | p = 8/20 = 0.4  | p = 2/20 = 0.1  | p = 10/20 = 0.5         |
| Is Not Obese | 4           | 6               | 4 + 6 = 10|
|          | p = 4/20 = 0.2  | p = 6/20 = 0.3  | p = 10/20 = 0.5          |

so there is a 50 % chance the next one is obese or not.
then we can caluculate the probability that someone likes chocolate or not:

|          | Likes Chocolate | Hates Chocolate | Row Total |
|----------| :---------------| :---------------| :---------|
| Is Obese | 8               | 2               | 8 + 2 = 10|
|          | p = 8/20 = 0.4  | p = 2/20 = 0.1  | p = 10/20 = 0.5         |
| Is Not Obese | 4           | 6               | 4 + 6 = 10|
|          | p = 4/20 = 0.2  | p = 6/20 = 0.3  | p = 10/20 = 0.5          |
| Column Total | 8 + 4 = 12  | 2 + 6 = 8       |           |
|          | p = 12/20 = 0.6 | p = 8/20 = 0.4  |           |

so that means there is a 60% chance the next person likes chocolate and a 40% chance they dont like chocolate
if we see someone obese and we want to know the probability that they like chocolate or not we do:

let c be chocolate.
let o be obese.
p(likes **c** and is **o** | is **o**) = p(likes **c** and is **o**)/p(is **o**) = 8/10 = 0.8

word term:
the probability that someone likes **chocolate** given that **we know they are obese**, is **0.8**.

summary:
condition probability is the probability that something will happen scaled by whatever knowledge we already have about the event.
