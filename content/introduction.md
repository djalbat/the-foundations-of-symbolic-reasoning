# Introduction

I started writing Occam[^occam] with a view to providing an improved front end for existing theorem provers.
There turned out to be little interest in this from the wider community, however, but by the time I had come to this conclusion I was already committed to creating a system for formal reasoning of my own.
The reason for this was that I became convinced by an alternative understanding of mathematics and logic that was not founded on what is usually referred to as set theory plus first order logic, nor was it founded on some type theory or other. 
Rather it is based on the following approaches, what I call the four elephants.
By the way, there is nothing heretical or even original in adopting any of these approaches.
Much of the thinking behind them predates and indeed underlies type theories, for example, and some of it predates set theory.
So, the first two of the four elephants:

1. Intuitionism, due to Luitzen Brouwer.
2. Natural Deduction, due to Gerhard Gentzen.

In my opinion intuitionism and natural deduction together constitute the most significant advance in formal reasoning since the greeks invented logic.
Intuitionism frees us from the tyranny of classical thinking whilst natural deduction separates reasoning from logic.
Both are so ubiquitous as to be almost transparent, however, and their importance is seldom acknowledged.
We think and communicate intuitionistically just as much as we do so classically, however.
and natural deduction is so commonplace in the mathematical sciences, computer science in particular, that it seems to go completely unnoticed.
So if this book does no more than to raise the awareness of these approaches then it has at least have achieved something.
Moving on:

3. Structural linguistics, or at least a part thereof, in particular the work of Gottlob Frege.
4. Modern grammars, specifically BNF, due to John Backus; regular expressions, due to Stephen Cole Kleene; and Unicode. 

Each of these four elephants has a chapter devoted to it, but because intuitionism suffuses pretty much all of what follows it is worth expanding on it a little further here.
Consider then the following list of questions.
I claim that this book provides answers to all of them.
Some may find this surprising or even shocking and some might accuse me of intellectual hubris, or worse.
Still, here is the list, to which I could have added many more: 

* What is truth?
* What is mathematics? What is logic?
* What is a theorem? What is an axiom? What is a proof?
* What is a term? What is an expression? Are they fundamentally different? 
* What is a number? Specially, what are natural numbers, rational numbers, real numbers, etc 
* What is meaning? That is, if I were to say "what do you mean?", what message am I trying to get across?
* What is the Principle of Induction? Or to put it another way, why did Peano have to include it in his axioms?
* What is a foundation for mathematics, logic or indeed for any form of symbolic reasoning? What is symbolic reasoning?

No doubt one of the reasons why claiming to have answers to all of these questions and many more like them may seem surprising or even shocking to some is their somewhat metaphysical nature.
Nonetheless, we will see that intuitionism can get us out of this fix.

We begin by looking at scientific method, which will be familiar to most.
Broadly speaking, when we follow follow scientific method we make observations of what we perceive to be the real world and use these as assumptions for a theory.
We then deduce certain conclusions within that theory, which we go on to ratify by further observation.
If our conclusions match closely with observation then we say that the theory is a good one.
If they do not then no matter how intrinsically appealing the theory may be, we must ditch it, or at least amend it.
The process of deduction will be more or less formal depending on the field of study but what is common to all is that the theory is seen as just that, namely a collection of interrelated concepts.

This last point is crucial because theories that may do a very good job of describing the real world may nonetheless be irreconcilable.
Consider the hackneyed dichotomy of general relativity versus quantum electrodynamics, for example.
The hypotheses of both theories can match observations to an extraordinary degree and yet it is common knowledge that they have not been reconciled despite more than half a century of effort.
Thus it is only an acceptance that these theories are wholly conceptual in nature that allows this situation to persist.
We concede that there can be different scientific views of the world, so to speak, and thus scientific method can be considered as a form of relativism.

On the other hand, perhaps because of their abstract nature many see mathematics and logic as unique and special, and regard mathematical and logical concepts as having some kind of objective existence aside from our understanding of them.
Consider the Platonic solids, for example, known since antiqutiy and often believed to have been there for the discovering, rather than having been invented by us.
Arguably this is not the case, however.
Indeed it could be argued that mathematical and logical concepts are just that, namely concepts, even those as seemingly natural as, say, the natural numbers.
We may perceive these concepts in nature but that is not that same as saying that they exist objectively aside from our perception of them.
Furthermore, it may come as a surprise to some but there is no broad agreement about the nature of mathematical and logical concepts.
Thus it seems unlikely that they exist universally and in perpetuity, however appealing such a belief may be.

Fortunately intuitionism gives us an alternative way of viewing mathematics and logic, being itself a form of relativism.
Within intuitionism we can formulate our own mathematical concepts and the logical rules we use to reason about them, often based on what we perceive as reality, but nonetheless understood to be separate from it.
The parallels between intuitionism and scientific method should be obvious here. 
In fact we can extend intuitionism from an understanding of mathematical and logical concepts, past scientific concepts and on to more general ones.

To give an example, consider the question of what is justice.
There is a branch of philosophy concerned with this question, namely ethics, but let us look at the question from a more practical standpoint.
Whatever country you live in will have various laws, persons, institutions and so on that constitute its justice system.
The law in particular encompasses divers statutes, processes and precedents, the adherence to which and the machinations of the justice system in general we think of as justice.
Indeed, we talk of justice being done, of miscarriages of justice or of the wheels of justice, the latter almost as if justice were a physical thing.
Perhaps not a physical thing, but nonetheless a tangible and recognisable concept.

Such concepts are certainly not universal.
If you were to move to a different country, for example, then the justice system and therefore the concept of justice would differ, perhaps markedly.
To think of justice in this way is to think of it intuitionistically.
We avoid the ethereal and instead root ourselves in the practical.
Or, to put it another way, when considering definitive questions we eschew definitive answers and instead embrace definite ones.
In doing so what we loose in universality we gain in utility.

Intuitionism's emphasis on the purely conceptual nature of mathematics and logic also has a profound effect on the notion of truth.
Because we accept that the mathematical and logical concepts that we devise are not universal, their truthfulness also looses any claim to universality.
The comparison with scientific method is again instructive and we recall the fact that the hypotheses of both general relativity and quantum electrodynamics match observations to an extraordinary degree. 
They remain irreconcilable, however, as we have already pointed out, and so which is true?
The answer has to be neither in any universal sense.
Therefore perhaps it is best not to say that a particular theory is true at all, and instead simply assert that if the hypotheses of a theory closely match observation then it is a good theory.

Just as we can extend the intuitionistic view of mathematical and logical concepts past scientific and on to general ones, so the intuitionistic notion of truth can also be extended.
Earlier it was claimed that we think and communicate intuitionistically, for example.
To see this, consider the statement "it is raining".
Normally we would not feel the need to additionally assert that such a statement were true.
We would rarely say, for example, "it is true that it is raining" or "it is raining is true".
Indeed it is entirely possible to think and communicate without the encumbrance of the dichotomy of truth and falsehood altogether, and we often do.
We might use only positive statements, so to speak, the veracity of which is considered to be self evident.
We can also make use of negation in order to obviate the need to assert that statements are false.
We can refute the statement "it is raining" by saying "it is not raining", for example.
And, just as it is preferable to say that a particular scientific theory is good rather than it is true, so rather than asserting that a particular statement is true, we can assert that it holds.

It is possible to refute a statement by asserting that it is false, of course.
We might respond to the statement that "it is raining" with the statement "that's not true", where "not true" is synonymous with "false".
This is in a sense to communicate classically rather than intuitionistically.
In reality we segue between these two modes seamlessly and indeed sometimes it would be pedantic to draw a distinction.
Nonetheless it is important to draw this distinction if only for the reason that the majority of us are vaguely familiar with the classical mode of communication whereas few will be familiar with intuitionistic one.

Finally, we note that to draw attention to the distinction between classical and intuitionistic thinking is far from pedantry.
Modern proof assistants usually operate in one of these two modes.
Satisfiability solvers are inherently classical, for example, they decide whether statements are true or false.
On the other hand modern proof assistants largely operate intuitionistically, they derive or deduce statements that hold.
It almost goes without saying that Occam falls into the latter category.

[^occam]: The word Occam is used somewhat nebulously here.
It covers a suite of software and services together with the the theory that underlines them.
This book is an apologia for the latter and there is a companion book, called The Occam User Manual, that covers the former.

@footnotes

@pageNumber
