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

By the way, in my opinion intuitionism and natural deduction together constitute the most significant advance in formal reasoning since the greeks invented logic,
because intuitionsism frees us from the tyranny of the dichotomy of truth and falsehood whilst natural deduction separates reasoning from logic altogether.
Both are so ubiquitous as to be almost transparent, however, and therefore their importance is seldom recognised.
We think and communicate intuitionistically just as much as we do so classically, for example;
and natural deduction is so commonplace in the mathematical sciences, computer science in particular, that it seems to go completely unnoticed.
So if this book does nothing more for the otherwise disinterested reader than to make them aware of these approaches then it has at least have acheived something.
Moving on:

3. Structural linguistics, in particular the work of Frege.
4. What might be termed modern grammars, specifically BNF, regular expresions and Unicode. 
The first two can be attributed to John Backus and Stephen Cole Kleene, respectively.

Each of these four elephants has a succeeding chapter devoted to it,
but because intuitionism is so general, and because it suffuses pretty much all of what follows, it is worth expanding on it further now.

Consider then the following list of questions.
I claim that this book provides answers to all of them.
Some may find this surprising or even shocking and some might accuse me of intellectual hubris, or worse, for making such a claim.
Still, here is the list:

1. What is truth?
2. What is mathematics?
3. What is logic?
4. What is meaning? 
5. What is a number? 
6. Many others.

No doubt the reason why claiming to have answers to these questions may seem almost maniacal is their general, metaphysical nature. 
For instance, what about the claim that I know what logic is.
No two logicians will agree on a preicse definition of logic, after all.
Let me wriggle out of this by way of an example. 
Consider the question of what is justice.
There is a branch of philosophy concerned with this question, namely ethics.
But let us move away from philosophising for a moment and look at the question of what is justice from a more practical standpoint.

Whatever country you live in will have various laws, persons, institutions, etc that constitute its justice system.
The law in particular encompasses divers statutes, processes, precedents, etc, adherence to which and the machinations of the justice system in general we think of as justice.
Indeed, we talk of justice being done; or of miscarriages of justice; or of the wheels of justice, the latter almost as if justice were a physical thing.
Perhaps not a physical thing, but it is certainly for the most part tangible and recognisable.
And although it is not possible to define justice precisely, at least in part because of the vagaries of interpreting the law, it is still defintely a thing, for want of a better way of putting it.

In fact a better way of putting it would be to call it a concept.
Such concepts are neither universal nor metaphysical.
If you were to move to a different country, for example, then the justice system and therefore the concept of justice would differ, perhaps markedly.
To think of justice in this way is to think of it *intutitionistically*.
We avoid the ethereal and instead root ourselves in the practical.
Or, to put it another way, when considering *definitive* questions we eschew definitive answers and instead embrace *definite* ones.
In doing so what we lose in universality we gain in utility.

Now consider again the question of what is logic.
If we narrow the question down to what is propositional logic then Occam can be used to provide a precise answer.
Actually let us narrow it down a little further to the question of what is minimal propositional logic.
Here is an answer:

[Open Mathematics - Minimal Propositinal Logic](https://openmathematics.org/package/minimal-propositional-logic)

Thus minimal propositional logic can be defined as nothing but a collection of inference rules.
Some would argue that this is not what minimal propositional logic is, of course, and they would have a point.
But to *define* it precisely in this way is certainly one way of doing so and arguably more useful than many an imprecise answer that a logician would give.

To continue, earlier it was claimed that we think and communicate intuitionistically.
To see this, consider the statement "it is raining".
Normally, we would not feel the need to additionally assert that such a statement were true.
We would rarely say "it is true that it is raining", for example, or "it is raining is true", since the veractiy of the original statement would usually go without saying.
Indeed it is entirely possible to think and communicate without the encumberance of the dichotomy of truth and falsehood altogether, and we often do.
We use only positive statements, so to speak, whose veracity is considered to be self evident.
And it is enough to assert only that these statements hold, rather than that they are true.
You may wonder, if we do not have the concept of falsehood to hand then how to do refute statements.
The answer is that we have negation to hand.
We can refute the statement "it is raining" by negating it, retorting "it is not raining".
But this is still a positive statement in the sense that it is considered to hold, at least by the person who uttered it.

It is of course possible to refute a statement by asserting that it is false.
We might respond to the statement that "it is raining" with the statement "that's not true", where "not true" is synonymous with "false".
This is in a sense to communicate classically rather than intuitionistically.
In reality we segue between these two modes seemlessly and indeed sometimes it would be pedantic to draw a distinction.
Nonetheless it is important to draw this distinction if only for the reason that the majority of us are vaguely familiar with the classical mode whereas few will be familiar with intuitionstic one.

It is also worth noting that to draw attention to the distinction between classical and intutionistic reasoning is far from pedantry.
Modern proof assistants usually operate in one of these two modes.
Satisfiability solvers are inherently classical, for example, they *decide* whether statements are true or false.
On the other hand modern proof assistansts largely operate intuitionistically, they *derive* or *deduce* statements that hold.
Occasionally verification software can operate in one or other mode and occassionaliy the waters are muddlied, but generally this distinction is a very good rule of thumb.

[^1]: The word Occam is used somewhat mebulously here.
It covers a suite of software and services together with the the theory that underlines them.
This book is an apologia for the latter and there is a companion book, called The Occam User Manual, that covers the former.
