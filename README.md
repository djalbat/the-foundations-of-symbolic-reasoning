# The Foundations of Symbolic Reasoning

I started writing Occam[^1] with a view to providing an improved front end for existing theorem provers.
There turned out to be little interest in this from the wider community, however, but by the time I had come to this conclusion I was already committed to creating a formal reasoning system of my own.
The reason was that I became convinced that I had rediscovered an alternative understanding of mathematics and logic that was not founded on what is usually referred to as set theory plus first order logic, nor was it founded on some type theory. 
Rather it is based on the following approaches, what I call the four elephants.
By the way, I should mention that there is nothing heretical or even original in adopting any of these approaches.
Much of the thinking behind them predates type theory, for example, and some of it predates set theory.
So, the four elephants:

1. Intuitionisism, which goes back at least to Brouwer[^2].
2. Natural Deducation, due to Gentzen.

Before going any further I will remark that in my opinion intuitionism and natural deduction together constitute the most significant advance in formal reasoning since the greeks invented logic.
Intuitionsism frees us from the tyranny of classical thinking whilst natural deduction separates reasoning from logic altogether.
Both are so ubiquitous as to be almost transparent, however, and therefore their importance is seldom recognised.
We think, communicate and argue intuitionistically, for example, just as much as we do so classically;
and natural deduction is so commonplace in the sciences, computer science in particular, that it seems to go completely unnoticed.
So if this book does nothing more for the otherwise disinterested reader than to make them aware of these approaches then it has at least have acheived something.

Moving on:

3. Structural linguistics, in particular the work of Frege.
4. What might be termed modern grammars, specifically BNF, regular expresions and Unicode. 
The first two can be attributed to John Backus and Stephen Cole Kleene, respectively.

Each of these four elephants has a succeeding chapter devoted to it,
but because intuitionism is so general, and because it suffuses pretty much all of what follows, it is worth expanding on it further now.
We also touch briefly on the other three elephants towards the end.

Consider then the following list of questions.
I claim that this book provides answers to all of them.
Some may find this surprising or even shocking and some might accuse me of intellectual hubris, or worse, for making such a claim.
But we shall see.

1. What is truth?
2. What is mathematics?
3. What is logic?
4. What is meaning? 
5. What is a number? 

No doubt the reason why claiming to have answers to these questions and many others like them may seem almost maniacal is their general or even metaphysical nature. 
For example, what about my claim that I know what logic is.
No two logicians will agree on a preicse definition of logic after all, and yet here I am claiming that I know precisely what it is! Let me wriggle out of this by way of an example. 
Consider the question of what is justice.
There is a branch of philosophy concerned with this question, namely ethics.
But let us move away from philosophising for a moment and look at the question of what is justice from a more practical standpoint.

Whatever country you live in will have various laws, persons, institutions, etc that constitute its justice system.
The law in particular encompasses divers statutes, processes, precedents, etc, adherence to which and the machinations of the justice system in general we think of as justice.
Indeed, we talk of justice being done; or miscarriages of justice; or the wheels of justice, the latter almost as if justice were a physical thing.
Perhaps not a physical thing, but it is certainly for the most part tangible and recognisable.
And although it is not possible to define justice precisely, at least partly because of the vagaries of interpreting the law, it is still defintely a thing, for want of a better way of putting it.

In fact a better way of putting it would be to call it a concept.
This concept is not universal or metaphysical.
If you were to move to a different country, for example, then the justice system and therefore the concept of justice would differ, perhaps markedly.
To think of justice in this way is to think of it *intutitionistically*.
We avoid the ethereal and instead root ourselves in the practical.
Or, to put it another way, when considering *definitive* questions we eschew definitive answers and instead embrace *definite* ones.
In doing so what we lose in universality we gain in utility.

To give another example, consider again the question of what is logic.
If we narrow the question down to what is propositional logic then Occam can be used to provide a precise answer.
Actually let us narrow it down a little further to the question of what is minimal propositional logic.
It does not matter whether you have any prior idea of what this is, here is an answer:

[Open Mathematics - Minimal Propositinal Logic](https://openmathematics.org/package/minimal-propositional-logic)

Thus minimal propositional logic can be considered as nothing but a collection of inference rules.
It does not matter if you know what inference rules are, by the way, it is probably enough to know at this stage that they are fundamental to natural deduction.
Note that there are twelve inference rules in this case. 
Six are known as introduction rules and six elimination rules.
Some would argue that this is not what minimal propositional logic is, of course, and they would have a point.
But to *define* it precisely in this way, that is within the context of natural deduction as a collection of inference rules, is certainly one way of doing so, and arguably more useful than many an answer a logician would give.

We shall see that with the help of the third and fourth elephants it is possible to also give definite answers to the remaining questions and others besides.
We leave off those for now, however, and expand on intuitionism.

Earlier it was claimed that we think, argue and communicate intuitionistically.
To see this, consider the statement "it is raining".
We would not usually feel the need to assert additionally that such a statement were true.
We would rarely say, for example, something like "it is true that it is raining" or "it is raining is true" since the veractiy of such statements usually goes without saying.
Indeed it is entirely possible to think and communicate without the encoberance of the concepts of truth and falsehood altogether, and we often do.
To do so is to think and communicate intuitionistically.
We use only positive statements, so to speak, whose veracity is considered to be self evident.
You may wonder, if we do not have the concept of falsehood to hand then how to do refute statements.
The answer is of course that we have negation to hand.
We can refute the statement "it is raining" by negating it, retorting "it is not raining" or, more likely, the shortened "no it's not".
But this is still a positive statement in the sense that it is considered to be correct or, at a pinch, truthful, at least by the person who uttered it.
Now it is possible to refute a statement by asserting that it is false.
We might respond to the statement from a friend that 'it is raining" with the statement "that's not true", where "not true" means "false".
This is in a sense to communicate, or argue, classically.
In reality we segue between these to modes seemlessly and sometimes it would be pedantic to draw a distinction.
Nonetheless it is important to draw this distinction if only for the reason that the majority of us are vaguely familiar with classical reasoning, with its emphaisis on the dichotomy of truth and falsehood, 
whereas few will be familiar with intuitionstic reasoning, where the concepts of truth and falsehood play no part.

[^1]: The word Occam is used somewhat mebulously here.
It covers a suite of software and services together with the the theory that underlines them.
This book is an apologia for the latter and there is a companion book, called The Occam User Manual, that covers the former.

[^2]: Tom Koerner in his excellent book Fourier Analysis wrote that mathematicians make remarkably incompetent historians.
This is not a mathematics book but nor is it a history book.
I atttibute the occasional idea or theory to a particular person, as is usual, but this is meant to be no more than a pointer for the historically curious.
