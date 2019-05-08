## Coordination Games {#coordination}

At an almost maximal level of abstraction, a two player game where each player has two options looks like this.

                $a$                  $b$
  ----- -------------------- --------------------
    $A$  $r_{11}$, $c_{11}$   $r_{12}$, $c_{12}$
    $B$  $r_{21}$, $c_{21}$   $r_{22}$, $c_{22}$

I'm going to spend some time talking about games with these eight features.

-   $r_{11} > r_{21}$
-   $r_{22} > r_{12}$
-   $c_{11} > c_{12}$
-   $c_{22} > c_{21}$
-   $r_{11} > r_{22}$
-   $c_{11} \geq c_{22}$
-   $\frac{r_{21}+r_{22}}{2} > \frac{r_{11}+r_{12}}{2}$
-   $\frac{c_{12}+c_{22}}{2} \geq \frac{c_{11}+c_{21}}{2}$

The first four clauses say that the game has two (strict) Nash equilibria: $Aa$ and $Bb$. The fifth and sixth clauses say that the $Aa$ equilibria is **Pareto-optimal**: no one prefers the other equilibria to it. In fact it says something a bit stronger: one of the players strictly prefers the $Aa$ equilibria, and the other player does not prefer $Bb$. The seventh and eighth clauses say that the $Bb$ equilibria is **risk-optimal**. Risk-optimality is a somewhat complicated notion in general; see @HarsanyiSelten1988 for more details. But for current purposes, a simple characterisation of how it applies to these two-by-two games will suffice:

> An equiilbrium (in a two-by-two game) is risk-dominant if both players would play it if they thought the other player would flip a fair coin to decide between their available equilibrium strategies.

I'm going to offer an argument from Hans Carlsson and Eric van Damme [-@CarlssonVanDamme1993] for the idea that in these games, rational players will play the risk-dominant equilibrium. So in cases that meet these eight criteria, they will end up at $Bb$. The game that Human and The Radical Interpreter are playing fits these eight conditions, and The Radical Interpreter is perfectly rational, so in that game, The Radical Interpreter will say that $p \notin E$.

Games satisfying these eight inequalities are sometimes called *Stag Hunt* games. There is some flexibility, and some vagueness, in which of the eight inequalities need to be strict, but that level of detail isn't important here. The name comes from a thought experiment in Rousseau's *Discourse on Inequality*.

> \[T\]hey were perfect strangers to foresight, and were so far from
> troubling themselves about the distant future, that they hardly
> thought of the morrow. If a deer was to be taken, every one saw that,
> in order to succeed, he must abide faithfully by his post: but if a
> hare happened to come within the reach of any one of them, it is not
> to be doubted that he pursued it without scruple, and, having seized
> his prey, cared very little, if by so doing he caused his companions
> to miss theirs.  [@Rousseau1913 209--10]

It is rather interesting to think through which real-life situations are best modeled as Stag Hunts, especially in situations where people have thought was best modeled as a kind of Prisoners' Dilemma. Thinking through this model choice is one way in to appreciating the virtues of Rousseau's political outlook, and especially the idea that social coordination might not require anything like the heavy regulatory presence that, say, Hobbes thought was needed. But that's a story for another day. What I am going to look at is why Rousseau was right to think that if we are 'strangers to foresight', and are not planning ahead, we should take the rabbit.

To make matters a little less abstract, I'll focus on a version of the game with these particular values. (From here I'm following Carlsson and van Damme very closely; this is their example, with just the labelling slightly altered.)

         $a$    $b$
  ----- ------ ------
    $A$  4, 4   0, 3
    $B$  3, 0   3, 3

At first glance it might seem like $Aa$ is the right choice; it produces the best outcome. This isn't like Prisoners Dilemma, where the best collective outcome is dominated. In fact $Aa$ is the best outcome for each individual. But it is risky, and Carlsson and van Damme show how to turn that risk into an argument for choosing $Bb$.

The big trick is to embed this game in what Carlsson and van Damme call a *global game*. This can be done by starting the game with each player knowing just that they will play a game with the following payout table, with $x$ to be selected at random from a flat distribution over $[-1, 5]$.

         $a$    $b$
  ----- ------ ------
    $A$  4, 4   0, x
    $B$  x, 0   x, x

Before they play the game, each player will get a noisy signal about the value of $x$. There will be signals $s_R$ and $s_C$ chosen (independently) from a flat distribution over $[x - 0.25, x + 0.25]$, and shown to Row and Column respectively. So each player will know the value of $x$ to within $\frac{1}{4}$, and know that the other player knows it to within $\frac{1}{4}$ as well. But this is a margin of error model, and in those models there is very little that is common knowledge. That, Carlson and van Damme argue, makes a huge difference.

In particular, they prove that iterated deletion of strictly dominated strategies (almost) removes all but one strategy pair. (I will sketch their proof in subsection \@ref(cvdproof).) Each player will play $A$/$a$ if the signal is greater than 2, and $B$/$b$ otherwise. (Strictly speaking, we can't rule out various mixed strategies when the signal is precisely 2, but this makes little difference, since that occurs with probability 0.) Surprisingly, this shows that players should play the risk-optimal strategy even when they know the other strategy is Pareto-optimal. When a player gets a signal in $(2, 3.75)$, then they know that $x < 4$, so $Bb$ is the Pareto-optimal equilibrium. But the logic of the global game suggests the risk-dominant equilibrium is what to play.

Carlsson and van Damme go on to show that many of the details of this case don't matter. As long as (a) there is a margin of error in each side's estimation of the payoffs, and (b) every choice is a dominant option in some version of the global game, then iterated deletion of strongly dominant strategies will lead to each player making the risk-dominant choice.

I conclude from that that risk-dominant choices are rational in these games. There is a limit assumption involved here; what's true for games with arbitrarily small margins of error is true for games with no margin of error. (We'll come back to that assumption below.) And since The Radical Interpreter is rational, they will play the strategy that is not eliminated by deleting dominant strategies. That is, they will play the risk-dominant strategy.

In game with Human, the rational (i.e., risk-dominant) strategy for The Radical Interpreter is to say that $p \notin E$. And in the case of Parveen and Rahul, rational (i.e., risk-dominant) strategy for The Radical Interpreter is to say that it is not part of Parveen's evidence that Rahul is in the restaurant. And this is an interest-relative theory of evidence; had Parveen been playing a different game, The Radical Interpreter would have said that it is part of Parveen's evidence that
Rahul was in the restaurant.

And from this point all the intuitions about the case start to fit together. If it is part of Parveen's evidence that Rahul is in the restaurant, then she knows this. Conversely, if she knows it, then The Radical Interpreter would have said it is part of her evidence, so it is part of her evidence. Parveen will perform the action that maximises expected utility given her evidence. And she will lose knowledge when that disposition makes her do things that would be known to be
sub-optimal if she didn't lose knowledge.

In short, this model keeps what was good about the theory developed in the previous chapters, while also allowing that evidence can be interest-relative. It does require a slightly more complex theory of rationality than we had previously used. Rather than just say that agents maximise evidential expected utility, it says that they play risk-dominant strategies in coordination games. But it turns out that this is little more than saying that they maximise evidential expected utility, and they expect others (at least perfectly rational abstract others) to do the same, and they expect those others to expect they will maximise expected utility, and so on.
