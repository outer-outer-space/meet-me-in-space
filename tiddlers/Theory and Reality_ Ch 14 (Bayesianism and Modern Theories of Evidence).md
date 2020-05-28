## 14.1 (New Hope)
-> **The unsolved problem of confirmation**

* Logical Empiricists tried tackling the problem of confirmation by starting from simple, obvious ideas and building from there to an inductive logic that would help us understand testing in science.

* Popper opposed the problem of confirmation as an essential part of science

* Bayesianism was a third approach to the problem of confirmation

---

## 14.2 (Understanding Evidence With Probability)
-> **Evidence over confirmation**

### Probability Outside of Philosophy
* Statistics and data analysis are used in probability theory to describe the kinds of conclusions that can be drawn from surveys and samples.
* In the court of law, forensic evidence is described in terms of probability.

### Probability Within Philosophy
When there's uncertainty about a hypothesis, observational evidence can sometimes raise or lower the probability of the hypothesis.
* Bayesianism is one version of this idea

### Bayes's Theorem for Evidence
-> A 'magical bullet' formula

> **Bayes's Theorem:** 
-> 'h' = hypothesis
-> 'e' = piece of evidence

> P(h|e) = P(e|h)P(h)P(e)

a.k.a.

> P(h|e) = P(e|h)P(h) / P(e|h) + P(e|not-h)P(not-h)

a.k.a.

> P(X) is the probability of X.
P(X|Y) is the probability of X conditional upon Y, or the probability of X given Y.

#### Bayes's Theorem Explained
* Think of P(h) as the probability of 'h' measured without regard for evidence 'e'
*  P(h|e) is the probability of 'h' given 'e', a.k.a. the probability of the hypothesis in the light of 'e'
    * Bayes's theorem tells us how to calculate 'e'

Thus, we can measure what difference evidence 'e' makes to the probability of 'h'.
 * So we can say that evidence 'e' confirms 'h' if P(h|e) > P(h)
        * a.k.a. 'e' confirms 'h' if it makes 'h' more probable than it would otherwise be

**Bayes's theorem tells us how to update probabilities in the light of evidence.**

#### The Two Central Ideas of Bayesianism
1. The idea that 'e' confirms 'h' if 'e' raises the probability of 'h'
2. The idea that probabilities should be updated in a way dictated by Bayes's theorem

Bayes's theorem expresses P(h|e) as a function of two different kinds of probability:

1. **Prior Probabilities:** Probabilities of hypotheses in the form of P(h) and P(not-h): 
    * P(h) is the prior probability of 'h'
    * P(not-h) is the prior probability of the negation of 'h'
    * The prior probabilities of both P(h) and P(not-h) need to add up to 1

2. **Likelihoods:** Likelihoods of evidence of theory, which don't need to add up to 1:
    * P(e|h) is the posterior probability of 'h'
    * P(e|not-h) is the posterior probability of the negation of 'h'

#### Bayes's Theorem In Practice

1. Imagine you're unsure about someone's presence at a party

2. The hypothesis that he is at the party is 'h'

3. You then see that person's car outside of the party. That counts as evidence 'e'

4. Before seeing the car, you think the probability of his being at the party is 0.5

5. The probability of his car's being outside the party if he is at the party is 0.8 because he usually drives to such events

6. The probability of his car being outside of the party if he's not at the party is 0.1

7. We can then work out the probability that he is at the party given that his car is outside.

8. Plugging the numbers in, leads to: 
P(h|e) = (.5)(.8) / [(.5)(.8) + (.5)(.1)] = almost .9

9. So seeing the car raises the probability of 'h' from 0.5 to about 0.9

10. Therefore seeing the car strongly confirms the hypothesis that the person is at the party.

#### Problems With Bayes's Theorem
-> Many interpretations of probability don't allow for Bayes's Theorem to discuss evidence because they can't make sense of prior probabilities.

> **Subjectivist Interpretation:** an interpretation of probability created by Bayesians to talk about prior probabilities (within philosophy?).

---

## 14.3 (The Subjectivist Interpretation of Probability)
-> Degrees of belief

Pioneered by Frank Ramsey and Bruno de Finetti in the 1920's and 1930's.

* Most attempts to analyze probability view probabilities as measuring a real and 'objective' feature of events.
	 * A probability value is seen as measuring the chance of an even happening.

* The subjectivist interpretation of probability views probabilities as **degrees of belief.**
	 * A probability value measures someone's confidence in the truth of a proposition

The subjectivist interpretation of probability is important in decision theory, which in turn is important in the social sciences – especially economics.

Most philosophers who want to use Bayes's Theorem to understand evidence hold a subjectivist view of probability for applications of probability theory to this set of problems.
* The philosophical debates about Bayesianism connect with debates about mathematical statistics itself.

### A Primer on Subjectivism About Probability

> **Probabilities:** (in Subjectivist Philosophy) Degrees of belief in propositions or hypotheses about the world.

To find out an ideal someone's degree of belief in a proposition, we look at that person’s gambling behavior (both actual and possible). (a.k.a. look at indirect indicator as opposed to claimed attitudes or mind-reading)
* Degrees of belief are revealed by which bets that person would accept vs reject. 
* We're dealing with idealized as opposed to 'real' people because real people might be averse to gambling despite good odds, or they might love gambling despite bad odds.

If you know a person's subjectively fair odds for a bet, you can read off his degree of belief in the proposition that the bet is about.

> **Subjectively fair odds:** when a person’s equally willing to take either side of a bet

A persons’ belief system at a particular time can be described as a network of subjective probabilities which work in concert with the person’s preferences (‘utilities’) to generate his or her behavior.

In the Bayesian view:
* all life is a series of gambles in which our behavior manifests our bets about what the world is like.
* For a person’s total network of degrees of belief to be ‘coherent’ or rational, it has to follow the standard rules of the mathematics of probability.

### Kolmogorov’s Probability Axioms
-> These axioms (most basic principles) are used by Subjectivists

**Axiom 1:** All probabilities are numbers between 0 and 1 (inclusive)
**Axiom 2:** If a proposition is a tautology (trivially or analytically true), then it has a probability of 1.
**Axiom 3:** If ‘h’ and ‘h* ’ are exclusive alternatives (they can’t both be true), then P(h-or-h* ) = P(h) + P(h*).
**Axiom 4:** P(h|j) = P(h&j)/P(j), provided that P(j) > 0.
 
Bayes’s Theorem is a consequence of Axiom 4.
* because P(h&j) can be broken down as:
	* P(h|j)P(j) and as P(j|h)P(h)
* These are equal to each other, so Bayes’s Theorem follows

### The Dutch Book Argument
-> The subjectivist argument for why degrees of belief should follow Kolmogorov’s axioms

1. Suppose your degree of belief that a coin toss will land heads is 0.6
2. Suppose your degree of belief that the same coin toss will land tails is also 0.6
3. In doing so, you’ve violated the third and first of Kolmogorov’s axioms because P(heads or tails) = 1.2
4. If you chose to persist with those degrees of belief and were willing to bet on them, then when someone offers you bets that you’re guaranteed to lose, you’d take them because they’d still be subjectively fair odds to you
5. This qualifies you as quantifiably irrational

To avoid falling victim to the Dutch book, you need to make sure your degrees of belief follow the rules of probability theory.

So far, these ideas about probability and belief apply to a person’s beliefs at **a specific time**.

#### The Rational Updating of Beliefs as Evidence Comes In (Bayesianism)
-> The rational agent will update her degrees of belief so that her new overall confidence in ‘h’ is derived from her old value of P(h|e).

So the key relationship in the updating process is:
> P{new}(h) = P{old}(h|e)

> **Today’s posteriors are tomorrow’s priors.**

### Summary
According to (strict) Subjectivist interpretations of probability, there’s no way for one set of degrees of belief to be ‘closer to the real facts about probability’ than another if both sets of degrees of belief follow the axioms of probability.

---

## 14.4 (Asessing Bayesianism)
Many debates about Bayesianism have centered around prior probabilities. 

In standard versions of Bayesianism, a person starts off with an initial set of prior probabilities for various hypotheses that’s a sort of ‘free choice’ because no initial set is better than another as long as the axioms of probability are followed.
* sometimes seen as a strength
	* convergence -> the starting point gets washed out by incoming evidence (but this could take awhile)
	* for any initial disagreement about ’h’, there will be some amount of ‘e’ that will get people to any specified degree of closeness in their final probabilities for ‘h’.
* sometimes seen as a weakness
	* because Bayesianism can’t criticize very strange initial assignments of probability

Henry Kyburg pointed out that in this case, you must also accept that for *any* amount of evidence and/or measure of agreement, there’s *some* initial set of priors such that this evidence *won’t* get the two people to agree by the end.

### A More Basic Problem: Convergence
Convergence assumes that despite starting out with different priors, people still have the same likelihoods in a given situation.
* their disagreements could affect their views on the relevance of possible observations
	* so convergence results may not help much with problems about theory choice in science 

#### The Bayesian Solution to Goodman’s New Riddle of Induction
-> Prior probabilities are the key

> Suppose we’re presented with two inductive arguments made from the same set of observations of green emeralds. One induction concludes that all emeralds are green, and the other concludes that all emeralds are true. Why is one induction good and the other bad?

Bayesian reply says both inductive arguments are okay because both hypotheses are confirmed by the observations of green emeralds. 
* But the “all emeralds are green” hypothesis will have a higher **prior** probability than “all emeralds are true”. Despite both hypotheses being confirmed by observations the green-emerald hypothesis will end up with much higher posterior probability.

If your probabilities are internally coherent and you update properly, then regardless of whether they’re right or wrong, Bayesianism has no criticism for them.

---

## 14.5 (Scientific Realism and Theories of Evidence)
A lot of empiricism in the 1900’s discussed evidence based on the (failed) belief that:
> the aim of testing is to confirm or disconfirm generalizations by means of observation.
* in the case of disconfirmation, deductive logic suffices
* confirmation requires inductive logic

This view ultimately failed because it couldn’t even make sense of confirmation within the simple picture within which it was being used.

### A Better Picture of What Scientific Testing Aims to Do
Testing attempts to choose between rival hypotheses about the hidden structure of the world (e.g. causal mechanisms, mathematical relationships, etc).

During the Scientific Revolution, a clock analogy was used to describe the problem of evidence.
* a scientist is like someone observing the motions of a clock and trying to make inferences about the clock’s inner workings.

We may need to get used to a mixed/pluralist view of evidence in science because:
* Different theories and paradigms can bring with them different accounts of what good scientific theories should do (as emphasized by Kuhn and Laudan).

### Explanatory Inference
Understanding explanatory inference is important in any future account of testing.

> **Explanatory Inference:** Inference from a set of data to a hypothesis about a structure or process that would explain the data

Explanatory inference is more important in actual science than the traditional conception of induction.
* good inferences about what to expect and what patterns will continue in our experience typically are developed via inferences about what the world is like and what processes are operating

#### Understanding Explanatory Inference

> **Elimination of Alternatives:** Supporting one option by ruling out others. a.k.a. **Eliminative Inference**
* this is what Sherlock Holmes does

The elimination of alternatives wasn’t taken seriously at first because philosophers assumed that in science there’s always an infinite number of possible alternatives to any given theory.
* but what if you can find a way of constraining the relative alternatives to a theory?

John Platt argued that, “good science is generally based on eliminative inference” in 1964.
* he viewed it like a modified version of Popperian testing

Eliminative inference can have a deductive or non-deductive form.
* if you can decisively rule out all options but one, then the inference can be presented as a deductive argument (which is still only as good as its premises) (non-deductive)
* if you have a less decisive ruling out of alternatives, then all you can say is that all alternatives but one are very unlikely
* if you can rule out most, but not all, of the alternatives to a hypothesis, then the theory becomes increasingly likely to be true (non-deductive)

Eliminative inference can be found in the arguments typically given by scientists all the time – it’s not just a philosophical fiction. It can even be found between paradigms/modes of thought:
* Darwin vs 19th century creationism
* Galileo vs Aristotelian physics
* Skinner’s behaviorist theory of language vs Chomsky’s cognitivist approach

Bayesianism handles evidence in a comparative manner
* Because of this, non-deductive cases let us embed eliminative inference within a Bayesian framework so that we can handle the idea of probability in a precise way.

A focus on eliminative inference can illuminate both the successes and failures found in scientific reasoning.

### Appeals to Simplicity (Parsimony)
-> another crucial form of reasoning often seen in actual science

> Given two possible explanations for the data, scientists often prefer the simpler one.

---

## 14.6 (Procedural Naturalism)
-> Godfrey-Smith’s ideas about evidence and testing – a procedure-oriented view that’s an alternative to Bayesianism, yet compatible both with it and with eliminative inference.

### Procedures
> We should analyze evidence, confirmation, and testing by focusing on **procedures.**

Hans Reichenbach was an important source for the procedure-oriented view – was influenced by statistical methods used in science. He didn’t follow standard logical positivist thinking about confirmation, but *was* he still one?

> **Reliability:** A good procedure is one that has the capacity to reliably answer the questions we put to it.

Example of a common type of procedure in science:
* using random samples to make inferences about the characteristics of a larger population

#### Two Philosophical Puzzles from a Procedure-Based View
-> The Ravens Problem & Goodman’s ‘true’ problem

##### The Raven’s Problem:
* If generalizations are confirmed by their instances, and if any observation that confirms H also confirms anything logically equivalent to H, then it seems that a white shoe confirms the hypothesis that all ravens are black. 
* This is because a white shoe is a non-black non-raven, so it’s an instance of the generalization “all non-black things are non-ravens,” which is logically equivalent to “all ravens are black”.

Imagine that a biologist uses a statistical method to learn about bird color instead of relying on casual observation. He could then distinguish two questions about ravens:

1. The general raven question
	1. What is the proportion of blackness among ravens?
2. The specific raven question
	1. Is it the case that 100% of ravens are black?

###### Sampling Methods/Procedures
Statistical theory tells us that collecting a random population of a reasonable size could allow questions of this type to be reliably answered provided we meet a certain sample size relative to the desired degree of reliability we want.

1. You could answer both the specific and general ravens problems by collecting a random sample of ravens and recording their colors and using normal statistical methods.
2. Collecting a sample of all non-black things and recording whether or not they’re ravens would be the inverse of method 1. It would be useless for answering the general raven question, but would succeed in answering the specific raven question
3. You could collect a sample of non-ravens
	* Can’t be used to answer either of the raven questions (general or specific)
4. You could collect a sample of black things
	* Can’t be used to answer either of the raven questions (general or specific)

###### The Role of Particular Observations
-> The effectiveness of an observation depends on what procedures the observation was part of.
* An observation is only evidence if it is embedded in the right kind of procedure. -> this is a general fact about confirmation and evidence
	* Carl Hempel was wrong, generalizations aren’t always confirmed by observations of their instances
	* There’s only confirmation/support if the underlying procedure was the right kind.
		* But this doesn’t apply in deductive relationships.
			* A black raven refutes the hypothesis that no ravens are black, regardless of the procedure behind the observation.

* If you observe a white shoe, and you encounter it as part of a random sample of non-black things, then it counts as evidence because it’s a non-black thing that turned out not to be a raven. 
	* It’s part of a sample that we can use to answer the specific raven problem and to work out whether there are nonblack ravens
* If you observe the same white shoe in a sample of non-ravens, it tells us nothing and is now part of a procedure that can answer neither question.
* Same with back ravens. If you observe a black raven in a random sample of ravens, it’s part of an informative sample
* but if you observe the same raven in a sample of black things, it tells us nothing

> All of this is a more elaborate development of the idea that the order of observation is important , but what’s important is not order, but procedures

##### The “Grue” Problem
-> a.k.a. the Confounding Variable problem, familiar in statistical methodology

still using inferences made from samples, using statistical methods

When the act of observing or collecting data changes the particular objects being observed in a way relevant to the question being asked, then these statistical methods can’t be used in their simple forms because the testing situation has been compromised.

Goodman’s term “grue” turns observation (or sampling) itself into a confounding variable.