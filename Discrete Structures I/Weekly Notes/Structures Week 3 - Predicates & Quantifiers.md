- <u>Predicate:</u> A logical statement who's truth value is a function of one or more variables
	- Either true or false depending on the values of the variables
	- Can only be evaluated if all of variables have been assigned values
	- For example, if P(x) = "x is greater than 90" then that would be a predicate.  But of you took P(70) then it becomes a proposition now that it has an assigned truth value
		- So once a value is given to the predicate, it becomes a proposition and has a truth value
- <u>Universal Quantifier:</u> Given "∀x P(x)" it means that P(x) is true for all x values in a given domain
	- Just like how in set builder notation we assert a property that is true for all values of a variable in a particular domain like every real number, every integer, etc.
- <u>Argument:</u> A series of propositions (refereed to as the "hypothesis") followed up by by a final proposition (called the "conclusion")
	- An argument is <u>valid</u> if the conclusion is true for every truth assignment to the variables that causes all of the hypotheses to be true, otherwise the argument is <u>invalid</u>.  In other words, if every hypothesis is true and the conclusion is false, then the argument is <u>invalid</u>.
	- Denoted as:
	  $h1$
	  $h2$
	  $h3$
	  ...
	  $hn$
	  ---
	  ∴ c
- <u>Existential Quantifier:</u> $∃x P(x)$ means there exists some value of $x$ such that $P(x)$ 
	- For example, given "$P(x): x^2 < 10$ and the domain {1,2,3,4}", it would be the same as saying $P(1)$ v $P(2)$ v$ P(3)$ v $P(4)$
		- To prove this statement, we only need to find one value of $x$ such that $∃x P(x)$ is true
		- Given: $∃x (x^2 = 2)$
			- The existential quantifier would be $√2$ since that value of $x$ makes the statement true
		- Given $∃x (x^2 = -1)$
			- The statement would be false, since there is no possible value of $x$ that would make this statement true
- <u>Quantified Statement:</u> A logical statement containing a universal or existential quantifier
	- Quantifiers are applied first when considering the order of logical operations
	- Given: $(∀x P(x))  ⋀ Q(x)$
		- In $P(x)$, $x$ is <u>bound</u> by the universal quantifier
		- In $Q(x)$, $x$ is <u>free</u>, therefore this statement is <u>not</u> a proposition
	- Given: $∀x(P(x) ⋀ Q(x))$
		- This statement <u>binds</u> both occurrences of $x$, therefore the statement <u>is</u> a proposition
	- If $x$ is <u>bound</u> then the statement is a proposition
- <u>Negation:</u> The negation of the statement: "Everyone loves discrete math", would be "There exists some student who does not love discrete math", because in order to make the original statement false, there needs to be only one student who does not love discrete math
- <u>Demorgan's Law For Universally Quantified Statements:</u>
	- $¬∀x P(x) ≡ ∃x ¬P(x)$
- <u>Demorgan's Law For Existentially Quantified Statements:</u>
	- $¬∃x P(x) ≡ ∀x ¬P(x)$