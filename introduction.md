# Introduction

I started writing Occam[^1] with a view to providing an improved front end for existing theorem provers.
There turned out to be little interest in this from the wider community, however, but by the time I had come to this conclusion I was already committed to creating a formal reasoning system of my own.
The reason was that I became convinced by an alternative understanding of mathematics and logic that was not founded on what is usually referred to as set theory plus first order logic, nor was it founded on some type theory. 
Rather it is based on the following approaches, what I call the four elephants.
By the way, I should mention straight away that there is nothing heretical or even original in adopting any of these approaches.
Much of the thinking behind them predates type theory, for example, and some of it predates set theory.
So, the four elephants:

1. Intuitionisism, due to Brouwer.
2. Natural Deduction, due to Gentzen.

In my opinion intuitionism and natural deduction together constitute the most significant advance in formal reasoning since the greeks invented logic,
Intuitionsism frees us from the tyranny of the dichotomy of truth and falsehood whilst natural deduction separates reasoning from logic.
Both are so ubiquitous as to be almost transparent, however, and therefore their importance is seldom recognised.
We think and communicate intuitionistically just as much as we do so classically, for example;
and natural deduction is so commonplace in the mathematical sciences, computer science in particular, that it seems to go completely unnoticed.
So if this book does than to raise the awareness of these approaches then it has at least have acheived something.
Moving on:

3. Structural linguistics, or ast least a part thereof, in particular the work of Frege.
4. Modern grammars, specifically BNF, due to John Backus; regular expresions, due to Stephen Cole Kleene; and Unicode. 

Each of these four elephants has a chapter devoted to it, but because intuitionism suffuses pretty much all of what follows, it is worth expanding on it further here.
Consider then the following list of questions.
I claim that this book provides answers to all of them.
Some may find this surprising or even shocking and some might accuse me of intellectual hubris, or worse.
Still, here is the list, to which I could have added many more:

1. What is truth?
2. What is mathematics?
3. What is logic?
4. What is meaning? 
5. What is a number?

No doubt the reason why claiming to have answers to these questions seems surprising is their somewhat metaphysical nature.
However, we shall see that intuitionism can get us out of this fix.

We begin by looking at scientific method, which will be familiar to most.
Broadly speaking, when following scientific method we make observations of what we perceive to be the real world and use these as assumptions for a theory.
We then deduce certain conclusions within that theory, which we them ratify by further observation.
If our conclusions match closely with observation then we say that the theory is a good one.
If they do not then no matter how intrinsically appealling the theory may be, we must ditch it, or at least amend it.
The process of deduction will be more or less formal depending on the field of study but what is common to all is that the theory is seen as just that, namely a collection of interrelated concepts.

This last point is crucial because theories that may do a very good job of describing the real world may nonetheless be irreconcilable.
Consider the hackneyed dichotomy of general relativity versus quantum electrodynamics, for example.
The hypotheses of both theories can match observations to an extraordinary degree and yet it is common knowledge that they remain irreconcilable despite more than half a century of effort.
It is only an acceptance that these theories are wholly conceptual in nature that allows this situation to persist.
We concede that there can be different scientific views of the world, so to speak, and thus scientific method can be considered as a form of relativism.

On the other hand, many see mathematics and logic as unique and special, and regard mathematical and logical concepts as hainvg some objective existence aside from our understaning of them.
Consider the Platonic solids, for example, known since antiqutiy and often believed to have been there for the discovering, rather than having been invented by us.
Arguably this is not the case, however.
It could be argued that Mathematical and logical concepts are just that, namely concepts, even those as seemingly natural as, say, the natural numbers.
We may perceive these concepts in nature but that is not to say that they exist objectively aside from our perception of them.
Furthermore, it may come as a surprise to some but there is no broad agreement about the nature of mathematical and logical concepts.
Thus it seems unlikely that they exist universally and in perpetuity, however appealing such a belief may be.

Fortunately intuitionism gives us an alternative way of viewing mathematics and logic, being itself a form of relativism.
Within intuitionism we can formulate our own mathematical concepts and the logical rules we use to reason about them, often based on what we perceive as reality, but nonetheless understood to be separate from these perceptions.
The parallels between intuitionsim and scientific method should be obvious here and in fact we can extend intuitionism further in order to understand not just the nature of mathematical, logical and scientific concepts, but more general ones.

To give an example, consider the question of what is justice.
There is a branch of philosophy concerned with this question, namely ethics, but let us look at the question from a more practical standpoint.
Whatever country you live in will have various laws, persons, institutions and so on that constitute its justice system.
The law in particular encompasses divers statutes, processes and precedents, the adherence to which and the machinations of the justice system in general we think of as justice.
Indeed, we talk of justice being done, of miscarriages of justice or of the wheels of justice, the latter almost as if justice were a physical thing.
Perhaps not a physical thing, but nonetheless a tangible and recognisable concept.

Such concepts are certainly not universal.
If you were to move to a different country, for example, then the justice system and therefore the concept of justice would differ, perhaps markedly.
To think of justice in this way is to think of it *intutitionistically*.
We avoid the ethereal and instead root ourselves in the practical.
Or, to put it another way, when considering *definitive* questions we eschew definitive answers and instead embrace *definite* ones.
In doing so what we lose in universality we gain in utility.

In a similar vein, consider the question of what is logic.
If we narrow the question down to what is propositional logic then Occam can be used to provide a precise answer.
Actually let us narrow it down a little further to the question of what is minimal propositional logic.
Here is an answer:

[Open Mathematics - Minimal Propositinal Logic](https://openmathematics.org/package/minimal-propositional-logic)

Thus minimal propositional logic, indeed any logic, can be defined as nothing but a collection of inference rules.
Some would argue that this is not what logics are, of course.
But to *define* a logic precisely in this way is certainly one way of doing so and arguably more useful than many an imprecise answer that a logician might give.

Intuitionism's emphasis on the purely conceptual nature of mathematics and logic also has a profound effect on the notion of truth.
Because we accept that the mathematical and logical concepts that we devise are not univiersal, their truthfulness also looses any claim to universality.
The comparsion with scientitic method is again instructive and we recall the fact that the hypotheses of both general relativity and quantum electrodynamics match observations to an extraorddinary degree. 
They remain irreconcilable, however, and so which is true?
The answer has to be neither in any universal sense.
Therefore perhaps it is best not to say that a particular theory is true at all, and instead simply assert that if the hypotheses of a thoery closely match observation then it is a good theory.

Just as we can extend the intuitionistic view of mathematical, logical or scientific concepts to general ones such as justice,
so the intuitionistic notion of truth can also be extended.
Earlier it was claimed that we think and communicate intuitionistically, for example.
To see this, consider the statement "it is raining".
Normally we would not feel the need to additionally assert that such a statement were true.
We would rarely say, for example, "it is true that it is raining" or "it is raining is true".
Indeed it is entirely possible to think and communicate without the encumberance of the dichotomy of truth and falsehood altogether, and we often do.
We might use only positive statements, so to speak, the veracity of which is considered to be self evident.
We can also make use of negation in order to obviate the need to assert that statements are false.
We can refute the statement "it is raining", for example, by saying "it is not raining".
And, just as it is preferable to say that a particular scientific theory is good rather than true,
simimlarly we can assert that a particular statement holds rather than asserting that it is true.

It is of course possible to refute a statement by asserting that it is false.
We might respond to the statement that "it is raining" with the statement "that's not true", where "not true" is synonymous with "false".
This is in a sense to communicate classically rather than intuitionistically.
In reality we segue between these two modes seemlessly and indeed sometimes it would be pedantic to draw a distinction.
Nonetheless it is important to draw this distinction if only for the reason that the majority of us are vaguely familiar with the classical mode whereas few will be familiar with intuitionstic one.

Finally, we note that to draw attention to the distinction between classical and intutionistic reasoning is far from pedantry.
Modern proof assistants usually operate in one of these two modes.
Satisfiability solvers are inherently classical, for example, they *decide* whether statements are true or false.
On the other hand modern proof assistansts largely operate intuitionistically, they *derive* or *deduce* statements that hold.
Occam falls into that latter category and we now look at each of these four elements in greater detail.

[^1]: The word Occam is used somewhat mebulously here.
It covers a suite of software and services together with the the theory that underlines them.
This book is an apologia for the latter and there is a companion book, called The Occam User Manual, that covers the former.
