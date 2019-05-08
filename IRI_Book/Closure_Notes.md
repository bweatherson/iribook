Earlier I said that belief in $A$ requires two conditions be met:

1. For all relevant questions, the current answer and the answer upon updating on $A$ are the same.
2. For some possible practical question, the agent is disposed to use $A$ as given when reasoning through the problem.

Now consider the special case where $p, q$ and $p \wedge q$ are all propositions the agent is thinking about. And remember that the relevant questions are the ones an agent is thinking about, and conditional versions of those questions, conditional on all propositions she is thinking about. I'm going to argue that belief in $p$, and belief in $q$, and thinking about all three of $p, q$ and $p \wedge q$

\begin{enumerate*}
\renewcommand{\labelenumi}{(\arabic{enumi})}
\setcounter{enumi}{2}
\item $\forall$A$\forall$B$\forall r$ (A $\geq_r$ B $\leftrightarrow$ A $\geq _p  \wedge r$ B)
\item $\forall$A$\forall$B$\forall r$ (A $\geq_r$ B $\leftrightarrow$ A $\geq _q  \wedge r$ B)
\item $\forall$A$\forall$B$\forall r$ (A $\geq_r$ B $\leftrightarrow$ A $\geq _{p \wedge q \wedge r}$ B)
\end{enumerate*}

\noindent Assume that (5) isn't true. That is, there are A, B and $s$ such that $\neg$(A $\geq_s$ B $\leftrightarrow$ A $\geq _{p \wedge q \wedge s}$B). By hypothesis $s$ is active, and consistent with $p \wedge q$. So it is the conjunction of relevant, salient propositions. Since $q$ is salient, this means $q \wedge s$ is also active. Since $s$ is consistent with $p \wedge q$, it follows that $q \wedge s$ is consistent with $p$. So $q \wedge s$ is a possible substitution instance for $r$ in (3). Since (3) is true, it follows that A $\geq _{q \wedge s}$ B $\leftrightarrow$ A $\geq _{p \wedge q \wedge s}$ B. By similar reasoning, it follows that $s$ is a permissible substitution instance in (4), giving us A $\geq_s$ B $\leftrightarrow$ A $\geq _{q \wedge s}$ B. Putting the last two biconditionals together we get A $\geq_s$ B $\leftrightarrow$ A $\geq _{p \wedge q \wedge s}$B, contradicting our hypothesis that there is a counterexample to (5). So whenever (3) and (4) are true, (5) is true as well, assuming $p, q$ and $p \wedge q$ are all salient.


\section{Defending Closure}

So on my account of the connection between degrees of belief and belief \textit{tout court}, probabilistic coherence implies logical coherence amongst salient propositions. The last qualification is necessary. It is possible for a probabilistically coherent agent to not believe the \textit{non}{}-salient consequences of things they believe, and even for a probabilistically coherent agent to have inconsistent beliefs as long as not all the members of the inconsistent set are active. Some people argue that even this weak a closure principle is implausible. David \cite{Christensen2005}, for example, argues that the preface paradox provides a reason for doubting that beliefs must be closed under entailment, or even must be consistent. Here is his description of the case.

\begin{quote}
We are to suppose that an apparently rational person has written a long non-fiction book---say, on history. The body of the book, as is typical, contains a large number of assertions. The author is highly confident in each of these assertions; moreover, she has no hesitation in making them unqualifiedly, and would describe herself (and be described by others) as believing each of the book's many claims. But she knows enough about the difficulties of historical scholarship to realize that it is almost inevitable that at least a few of the claims she makes in the book are mistaken. She modestly acknowledges this in her preface, by saying that she believes the book will be found to contain some errors, and she graciously invites those who discover the errors to set her straight. \citep[33-4]{Christensen2005}
\end{quote}

\noindent Christensen thinks such an author might be rational in every one of her beliefs, even though these are all inconsistent. Although he does not say this, nothing in his discussion suggests that he is using the irrelevance of some of the propositions in the author's defence. So here is an argument that we should abandon closure amongst relevant beliefs.

Christensen's discussion, like other discussions of the preface paradox, makes frequent use of the fact that examples like these are quite common. We don't have to go to fake barn country to find a counterexample to closure. But it seems to me that we need two quite strong idealisations in order to get a real counterexample here.

The first of these is discussed in forthcoming work by Ishani Maitra \citep{MaitraANG}, and is briefly mentioned by Christensen in setting out the problem. We only have a counterexample to closure if the author \textit{believes} every thing she writes in her book. (Indeed, we only have a counterexample if she reasonably believes every one of them. But we'll assume a rational author who only believes what she ought to believe.) This seems unlikely to be true to me. An author of a historical book is like a detective who, when asked to put forward her best guess about what explains the evidence, says ``If I had to guess, I'd say {\dots}'' and then launches into spelling out her hypothesis. It seems clear that she need not \textit{believe} the truth of her hypothesis. If she did that, she could not later learn it was true, because you can't learn the truth of something you already believe. And she wouldn't put any effort into investigating alternative suspects. But she can come to learn her hypothesis was true, and it would be rational to investigate other suspects. It seems to me (following here Maitra's discussion) that we should understand scholarly assertions as being governed by the same kind of rules that govern detectives making the kind of speech being contemplated here. And those rules don't require that the speaker believe the things they say without qualification. The picture is that the little prelude the detective explicitly says is implicit in all scholarly work.

There are three objections I know to this picture, none of them particularly conclusive. First, Christensen says that the author doesn't qualify their assertions. But neither does our detective qualify most individual sentences. Second, Christensen says that most people would describe our author as believing her assertions. But it is also natural to describe our detective as believing the things she says in her speech. It's natural to say things like ``She thinks it was the butler, with the lead pipe,'' in reporting her hypothesis. Third, Timothy \cite{Williamson2000-WILKAI} has argued that if speakers don't believe what they say, we won't have an explanation of why Moore's paradoxical sentences, like ``The butler did it, but I don't believe the butler did it,'' are always defective. Whatever the explanation of the paradoxicality of these sentences might be, the alleged requirement that speakers believe what they say can't be it. For our detective cannot properly say ``The butler did it, but I don't believe the butler did it'' in setting out her hypothesis, even though \textit{believing} the butler did it is not necessary for her to say ``The butler did it'' in setting out just that hypothesis.

It is plausible that for \textit{some} kinds of books, the author should only say things they believe. This is probably true for travel guides, for example. Interestingly, casual observation suggests that authors of such books are much less likely to write modest prefaces. This makes some sense if those books can only include statements their authors believe, and the authors believe the conjunctions of what they believe.

The second idealisation is stressed by Simon \citeauthor{Evnine1999} in his paper ``Believing Conjunctions''. The following situation does not involve me believing anything inconsistent. 

\begin{itemize*}
\item I believe that what Manny just said, whatever it was, is false. 
\item Manny just said that the stands at Fenway Park are green. 
\item I believe that the stands at Fenway Park are green. 
\end{itemize*}

\noindent If we read the first claim \textit{de dicto}, that I believe that Manny just said something false, then there is no inconsistency. (Unless I also believe that what Manny just said was that the stands in Fenway Park are green.) But if we read it \textit{de re}, that the thing Manny just said is one of the things I believe to be false, then the situation does involve me being inconsistent. The same is true when the author believes that one of the things she says in her book is mistaken. If we understand what she says \textit{de dicto}, there is no contradiction in her beliefs. It has to be understood \textit{de re} before we get a logical problem. And the fact is that most authors do not have \textit{de re} attitudes towards the claims made in their book. Most authors don't even remember everything that's in their books. (I'm not sure I remember how this section started, let alone this paper.) Some may argue that authors don't even have the capacity to consider a proposition as long and complicated as the conjunction of all the claims in their book. Christensen considers this objection, but says it isn't a serious problem.

\begin{quote}
It is undoubtedly true that ordinary humans cannot entertain book-length conjunctions. But surely, agents who do not share this fairly \textit{superficial} limitation are easily conceived. And it seems just as wrong to say of such agents that they are rationally required to believe in the inerrancy of the books they write. (38: my emphasis)
\end{quote}

\noindent I'm not sure this is undoubtedly true; it isn't clear that propositions (as opposed to their representations) have lengths. And humans can believe propositions that \textit{can} be represented by sentences as long as books. But even without that point, Christensen is right that there is an idealisation here, since ordinary humans do not know exactly what is in a given book, and hence don't have \textit{de re} attitudes towards the propositions expressed in the book.

I'm actually rather suspicious of the intuition that Christensen is pushing here, that idealising in this way doesn't change intuitions about the case. The preface paradox gets a lot of its (apparent) force from intuitions about what attitude we should have towards real books. Once we make it clear that the real life cases are not relevant to the paradox, I find the intuitions become rather murky. But I won't press this point. 

A more important point is that we believers in closure don't think that authors should think their books are inerrant. Rather, following \cite{Stalnaker1984}, we think that authors shouldn't unqualifiedly \textit{believe} the individual statements in their book if they don't believe the conjunction of those statements. Rather, their attitude towards those propositions (or at least some of them) should be that they are probably true. (As Stalnaker puts it, they accept the story without believing it.) Proponents of the preface paradox know that this is a possible response, and tend to argue that it is impractical. Here is Christensen on this point.

\begin{quote}
It is clear that our everyday binary way of talking about beliefs has immense practical advantages over a system which insisted on some more fine-grained reporting of degrees of confidence {\dots} At a minimum, talking about people as believing, disbelieving, or withholding belief has at least as much point as do many of the imprecise ways we have of talking about things that can be described more precisely. (96)
\end{quote}

\noindent Richard Foley makes a similar point.

\begin{quote}
There are \textit{deep} reasons for wanting an epistemology of beliefs, reasons that epistemologies of degrees of belief by their very nature cannot possibly accommodate. \citep[170, my emphasis]{Foley1993}
\end{quote}

It's easy to make too much of this point. It's a lot easier to triage propositions into TRUE, FALSE and NOT SURE and work with those categories than it is to work assign precise numerical probabilities to each proposition. But these are not the only options. Foley's discussion subsequent to the above quote sometimes suggests they are, especially when he contrasts the triage with ``indicat[ing] as accurately as I can my degree of confidence in each assertion that I defend.'' (171) But really it isn't \textit{much} harder to add two more categories, PROBABLY TRUE and PROBABLY FALSE to those three, and work with that five-way division rather than a three-way division. It's not clear that humans as they are actually constructed have a \textit{strong} preference for the three-way over the five-way division, and even if they do, I'm not sure in what sense this is a `deep' fact about them.

Once we have the five-way division, it is clear what authors should do if they want to respect closure. For any conjunction that they don't believe (i.e. classify as true), they should not believe one of the conjuncts. But of course they can classify every conjunct as probably true, even if they think the conjunction is false, or even certainly false. Still, might it not be considered something of an idealisation to say rational authors must make this five-way distinction amongst propositions they consider? Yes, but it's no more of an idealisation than we need to set up the preface paradox in the first place. To use the preface paradox to find an example of someone who reasonably violates closure, we need to insist on the following three constraints.

\begin{enumerate*}
\renewcommand{\labelenumi}{\alph{enumi})}
\item They are part of a research community where only asserting propositions you believe is compatible with active scholarship;
\item They know exactly what is in their book, so they are able to believe that one of the propositions in the book is mistaken, where this is understood \textit{de re}; but
\item They are unable to effectively function if they have to effect a five-way, rather than a three-way, division amongst the propositions they consider.
\end{enumerate*}

\noindent Put more graphically, to motivate the preface paradox we have to think that our inability to have \textit{de re} thoughts about the contents of books is a ``superficial constraint'', but our preference for working with a three-way rather than a five-way division is a ``deep'' fact about our cognitive system. Maybe each of these attitudes could be plausible taken on its own (though I'm sceptical of that) but the conjunction seems just absurd.

I'm not entirely sure an agent subject to exactly these constraints is even fully conceivable. (Such an agent is negatively conceivable, in David Chalmers's terminology, but I rather doubt they are positively conceivable.) But even if they are a genuine possibility, why the norms applicable to an agent satisfying that very gerrymandered set of constraints should be considered relevant norms for our state is far from clear. I'd go so far as to say it's clear that the applicability (or otherwise) of a given norm to such an odd agent is no reason whatsoever to say it applies to us. But since the preface paradox only provides a reason for just these kinds of agents to violate closure, we have no reason for ordinary humans to violate closure. So I see no reason here to say that we can have probabilistic coherence without logical coherence, as proponents of the threshold view insist we can have, but which I say we can't have \textit{at least when the propositions involved are salient}. The more pressing question, given the failure of the preface paradox argument, is why I don't endorse a much stronger closure principle, one that drops the restriction to salient propositions. The next section will discuss that point.

I've used Christensen's book as a stalking horse in this section, because it is the clearest and best statement of the preface paradox. Since Christensen is a paradox-mongerer and I'm a paradox-denier, it might be thought we have a deep disagreement about the relevant epistemological issues. But actually I think our overall views are fairly close despite this. I favour an epistemological outlook I call ``Probability First'', the view that getting the epistemology of partial belief right is of the first importance, and everything else should flow from that. Christensen's view, reduced to a slogan, is ``Probability First and Last''. This section has been basically about the difference between those two slogans. It's an important dispute, but it's worth bearing in mind that it's a factional squabble within the Probability Party, not an outbreak of partisan warfare.


\section{Too Little Closure?}

In the previous section I defended the view that a coherent agent has beliefs that are deductively cogent with respect to salient propositions. Here I want to defend the importance of the qualification. Let's start with what I take to be the most important argument for closure, the passage from Stalnaker's \textit{Inquiry} that I quoted above.

\begin{quote}
Reasoning in this way from accepted premises to their deductive consequences ($P$, also $Q$, therefore $R$) does seem perfectly straightforward. Someone may object to one of the premises, or to the validity of the argument, but one could not intelligibly agree that the premises are each acceptable and the argument valid, while objecting to the acceptability of the conclusion. \cite[92]{Stalnaker1984}
\end{quote}

\noindent Stalnaker's wording here is typically careful. The relevant question isn't whether we can accept $p$, accept $q$, accept $p$ and $q$ entail $r$, and reject $r$. As Christensen \citeyearpar[Ch. 4]{Christensen2005} notes, this is impossible even on the threshold view, as long as the threshold is above 2/3. The real question is whether we can accept $p$, accept $q$, accept $p$ and $q$ entail $r$, and \textit{fail }to accept $r$. And this is always a live possibility on any threshold view, though it seems absurd at first that this could be coherent.

But it's important to note how \textit{active} the verbs in Stalnaker's description are. When faced with a valid argument we have to \textit{object} to one of the premises, or the validity of the argument. What we can't do is \textit{agree} to the premises and the validity of the argument, while \textit{objecting} to the conclusion. I agree. If we are really \textit{agreeing} to some propositions, and \textit{objecting} to others, then all those propositions are salient. And in that case closure, deductive coherence, is mandatory. This doesn't tell us what we have to do if we haven't previously made the propositions salient in the first place.

The position I endorse here is very similar in its conclusions to that endorsed by Gilbert Harman in \textit{Change in View}. There Harman endorses the following principle. (At least he endorses it as true -- he doesn't seem to think it is particularly explanatory because it is a special case of a more general interesting principle.)

\begin{description*}
\item[Recognized Logical Implication Principle] One has reason to believe $P$ if one \textit{recognizes} that $P$ is logically implied by one's view. \cite[17]{Harman1986}
\end{description*}

\noindent This seems right to me, both what it says and its implicature that the reason in question is not a conclusive reason. My main objection to those who use the preface paradox to argue against closure is that they give us a mistaken picture of what we have \textit{to do} epistemically. When I have inconsistent beliefs, or I don't believe some consequence of my beliefs, that is something I have a reason to deal with at some stage, something I have to do. When we say that we have things to do, we don't mean that we have to do them \textit{right now}, or instead of everything else. My current list of things to do includes cleaning my bathroom, yet here I am writing this paper, and (given the relevant deadlines) rightly so. We can have the job of cleaning up our epistemic house as something to do while recognising that we can quite rightly do other things first. But it's a serious mistake to infer from the permissibility of doing other things that cleaning up our epistemic house (or our bathroom) isn't something to be done. The bathroom won't clean itself after all, and eventually this becomes a problem.

There is a possible complication when it comes to tasks that are very low priority. My attic is to be cleaned, or at least it could be cleaner, but there are no imaginable circumstances under which something else wouldn't be higher priority. Given that, should we really leave \textit{clean the attic} on the list of things to be done? Similarly, there might be implications I haven't followed through that it couldn't possibly be worth my time to sort out. Are they things to be done? I think it's worthwhile recording them as such, because otherwise we might miss opportunities to deal with them in the process of doing something else. I don't need to put off anything else in order to clean the attic, but if I'm up there for independent reasons I should bring down some of the garbage. Similarly, I don't need to follow through implications mostly irrelevant to my interests, but if those propositions come up for independent reasons, I should deal with the fact that some things I believe imply something I don't believe. Having it be the case that all implications from things we believe to things we don't believe constitute jobs to do (possibly in the loose sense that cleaning my attic is something to do) has the right implications for what epistemic duties we do and don't have.

While waxing metaphorical, it seems time to pull out a rather helpful metaphor that Gilbert \citeauthor{Ryle1949} develops in \textit{The Concept of Mind} at a point where he's covering what we'd now call the inference/implication distinction. (This is a large theme of chapter 9, see particularly pages 292-309.) Ryle's point in these passages, as it frequently is throughout the book, is to stress that minds are fundamentally active, and the activity of a mind cannot be easily recovered from its end state. Although Ryle doesn't use this language, his point is that we shouldn't confuse the difficult activity of drawing inferences with the smoothness and precision of a logical implication. The language Ryle does use is more picturesque. He compares the easy work a farmer does when sauntering down a path from the hard work he did when building the path. A good argument, in philosophy or mathematics or elsewhere, is like a well made path that permits sauntering from the start to finish without undue strain. But from that it doesn't follow that the task of coming up with that argument, of building that path in Ryle's metaphor, was easy work. The easiest paths to walk are often the hardest to build. Path-building, smoothing out our beliefs so they are consistent and closed under implication, is hard work, even when the finished results look clean and straightforward. Its work that we shouldn't do unless we need to. But making sure our beliefs are closed under entailment even with respect to irrelevant propositions is suspiciously like the activity of buildings paths between points without first checking you need to walk between them.

For a less metaphorical reason for doubting the wisdom of this unchecked commitment to closure, we might notice the difficulties theorists tend to get into all sorts of difficulties. Consider, for example, the view put forward by Mark Kaplan in \textit{Decision Theory as Philosophy}. Here is his definition of belief.

\begin{quote}
You count as believing P just if, were your sole aim to assert the truth (as it pertains to P), and you only options were to assert that P, assert that $\neg$P or make neither assertion, you would prefer to assert that P. (109)
\end{quote}

\noindent Kaplan notes that conditional definitions like this are prone to Shope's conditional fallacy. If my sole aim were to assert the truth, I might have different beliefs to what I now have. He addresses one version of this objection (namely that it appears to imply that everyone believes their sole desire is to assert the truth) but as we'll see presently he can't avoid all versions of it.

These arguments are making me thirsty. I'd like a beer. Or at least I think I would. But wait! On Kaplan's theory I can't think that I'd like a beer, for if my sole aim were to assert the truth as it pertains to my beer-desires, I wouldn't have beer desires. And then I'd prefer to assert that I wouldn't like a beer, I'd merely like to assert the truth as it pertains to my beer desires. 

Even bracketing this concern, Kaplan ends up being committed to the view that I can (coherently!) believe that $p$ even while regarding $p$ as highly improbable. This looks like a refutation of the view to me, but Kaplan accepts it with some equanimity. He has two primary reasons for saying we should live with this. First, he says that it only looks like an absurd consequence if we are committed to the Threshold View. To this all I can say is that \textit{I} don't believe the Threshold View, but it still seems absurd to me. Second, he says that any view is going to have to be revisionary to some extent, because our ordinary concept of belief is not ``coherent'' (142). His view is that, ``Our ordinary notion of belief both construes belief as a state of confidence short of certainty and takes consistency of belief to be something that is at least possible and, perhaps, even desirable'' and this is impossible. I think the view here interprets belief as a state less than confidence and allows for as much consistency as the folk view does (i.e. consistency amongst salient propositions), so this defence is unsuccessful as well.

None of the arguments here in favour of our restrictions on closure are completely conclusive. In part the argument at this stage rests on the lack of a plausible rival theory that doesn't interpret belief as certainty but implements a stronger closure principle. It's possible that tomorrow someone will come up with a theory that does just this. Until then, we'll stick with the account here, and see what its epistemological implications might be.