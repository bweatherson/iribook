### Arbitrary Choices {#ties}

#### Notes

Start with Frankie Lee and Judas Priest

* Ties


I've written a lot of the examples discussed so far in the book. This section is about when people have to make a choice from a set of equally good options, and there are enough famous examples of this in the literature that I don't need to add to it. So let's instead focus on this famous case.

| Well, Frankie Lee and Judas Priest
| They were the best of friends
| So when Frankie Lee needed money one day
| Judas quickly pulled out a roll of tens
| And placed them on a footstool
| Just above the plotted plain,
| Sayin', take your pick, Frankie Boy
| My loss will be your gain
|         Bob Dylan, _The Ballad of Frankie Lee and Judas Priest_

There is a lot going on there, but I want to stress something in the second last line. Judas asks Frankie to pick one of the ten dollar bills. But what possible reason could Frankie have to pick one of them rather than another? Maybe one of them is torn or dirty, or, something we'll think about a bit, maybe one of them looks badly forged. But in the ordinary case, they are just alike.

Brian Kim and Matthew McGrath [-@KimMcGrathIntro], citing a lecture by John Hawthorne from "circa 2007", note that this case poses a problem for the kind of view I used to defend. Assume that one constraint on believing that $p$ is that conditionalising on _p_ does not change one's preferences over salient options. And  assume a bunch of plausible things about the setup of the example. Frankie prefers legitimate money to forgeries, the notes all look legitimate to him, none of them looks any more likely to be a forgery, but there are forgeries around, and Judas isn't so honest, or so good at telling forgeries from real banknotes that he wouldn't have any forgeries in his bankroll. Assume there are twenty banknotes in the roll, and number them $n_1, \dots, n_20$, name the choice of taking note $n_i$ as $c_i$, and name the proposition that $n_i$ is a forgery as $f_i$. Then each of the following two claims is true, for any distinct pair $i, j$.

* Frankie is indifferent between $c_i$ and $c_j$.
* Conditional on $\neg f_j$, Frankie is not indifferent between $c_j$ and $c_i$, he prefers $c_j$ to $c_i$.

And this can be true no matter how unlikely Frankie thinks each of the $f_i$ are antecedently. This seems like a mistake. If the starting probability of each of the $f_i$ is arbitrarily low, then Frankie believes of each banknote that it is not a forgery. So this refutes the theory that belief requires conditionalising on the believed does not change preferences over salient options. That's unfortunate for me, since I used to defend the theory that belief requires conditionalising on the believed does not change preferences over salient options.

But note that this does not refute the hybrid pragmatic theory, at least as I've written it. On the most natural way to read the story, the main questions Frankie is interested in is whether to take Judas's money, and if so which bill to take. Now what happens to those two questions when we conditionalise on $\neg f_j$? The answer to the first question doesn't change - Frankie needs the money and should take some. And the answer to the second question is now settled - it's $c_j$. But note, and this is the crucial thing, that $c_j$ was an acceptable answer to the original question. So every acceptable answer to every question of interest is still an acceptable answer after conditionsalising on $\neg f_j$. So it is consistent with the hybrid pragmatic theory that Frankie believes $\neg f_j$.

The analysis of the previous paragraph turns on a subtlety in how I've framed the hybrid pragmatic theory, and it's worth spending time on this point. Imagine I'd added to the theory either of the following conditions.

* _S_ believes that $p$ only if every acceptable answer to every interesting question is still an acceptable answer conditional on $p$.
* _S_ believes that $p$ only if every answer that is prohibited conditional on $p$ is unconditionally prohibited.

Then Frankie would not believe any of the $\neg f_i$. Conditionalising on $\neg f_i$ turns the acceptable answers $c_j$ into unacceptable answers (at least for all $j: i \neq j$). And conditional on $\neg f_i$, $c_j$ is prohibited, so if Frankie believes $\neg f_i$, it should be unconditionally prohibited, but it is not. So adding either of these principles would mean that we got the wrong result in this case. So, we should not add either of them.

I've referred to these as two principles, but if we assume that every answer is either acceptable or prohibited, then the principles are equivalent. I don't want to make that assumption in general, but it seems safe enough to make in this case. So I'll just focus on the second principle, the one about prohibitions. Because while I can avoid the problem Frankie's case poses by simply denying the principle, we might wonder how that denial can be motivated. How can the equivalent principle about acceptable answers (i.e., every acceptable answer is acceptable conditional on $p$) be part of the analysis of belief, while this principle is not even true?

One answer is that conditional prohibitions are weird things, and they do not behave at all intuitively. Even if the proposed principle were intuitive (and I'm not sure it is), intuitions about conditional prohibitions seem of low evidential value. If I was trusting my intuitions, for example, I would have thought this implication was valid.

1. Conditional on $q$, X is prohibited.
2. Conditional on $r$, X is prohibited.
3. So, conditional on $q \vee r$, X is prohibited.

But this fails when X is a safe option, and there are two other risky options, one of which is best given $q$ and the other of which is best given $r$. So I'm a little dubious intuitions about conditional prohibitions.

Another answer is that we're really interested here in questions and answers. If Frankie doesn't know what to do, and so asks me what to do, it's not much help to say "Don't pick $n_7$; it looks dirty." That is, to use a familiar distinction, a response to Frankie's question, and not an answer to it. And that's true in general. Saying that something is an admissible answer is an answer to a question; saying that something is a prohibited answer is a response to the question.
