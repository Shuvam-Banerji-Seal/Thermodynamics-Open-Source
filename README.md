---
author:
- Shuvam Banerji Seal
title: Thermo Notes with Deeper Intuition\... Hopefully
---

This is a series of notes, I am going to be making for my understanding
and if anyone finds anything wrong with any of these notes then they are
always free to contact me or contribute to this project of making the
thermodynamics more understandable for all. A huge chunk of these notes
have been inspired from the popular 20 lectures on thermodynamics by
Buchdahl. The main goal of these notes are to find a deeper
understanding of the thermodynamics frrom a more fundamental level
interms of more rigorous mathematical construction.

# Thermodynamic Systems

## Definition and Contrast with Mechanical Systems

What are we to understand here by a \"thermodynamic system\"? To answer
this question at last we wisely remind ourselves first of what we mean
by a \"mechanical system\", bearing in mind that we are not interested
in the dynamical description of any changes which it may undergo. As a
preliminary step, let us specifically contemplate a set of particles
mutually joined by straight elastic rods. The whole arrangement is at
first on a table before us, those particles which are in contact with
the table being supposed immovable. To describe it in detail we need to
give the values of a (finite) set of mutually independent variables,
$x_1, x_2, \ldots, x_n$, for example the coordinates of some of the
particles referred to Cartesian axes, together with the lengths of some
of the rods. Any such set of values is a configuration of the system. To
say that the system has undergone some change from one (equilibrium) or
another to another is merely to say that it has changed from one
configuration, $x_1, \ldots, x_n$, to another configuration
$x_1', \ldots, x_n'$. Any such change, then, consists in the
displacement of parts of the system relative to each other, that is to
say, it is a deformation of the system. Indeed, the fact that every
change of any one of the variables $x_1', \ldots, x_n'$ describes a
certain deformation of the system is sufficiently important to attach a
special name to variables which have this character: we call them
**coordinates**. Now, two identically constructed systems of the kind
just described above contain nothing happen to be the same as to all
forms and purposes indistinguishable. It is precisely this property
which characterizes the class of mechanical systems. In short, a system
is *mechanical*, and it relevant information about its equilibria is
contained merely in the values of a set of ***d-coordinates***.

## Sample Thermodynamic System

By way of contrast, we go on to consider a very simple example of a
(phenomenological) system---let us always refer to it as our *sample
system*---which will turn out to be non-mechanical. It consists merely
of a gas. Of course this has to be enclosed by a container; and since we
want the volume of this to be variable we may simply take it to a
cylinder permanently closed at one end and by a movable piston at the
other. Further, there shall be some kind of stirrer inside the cylinder
by means of which the gas can be agitated from without. Nevertheless,
the gas alone constitutes the system; that is to say, neither the
enclosure nor the stirrer are to be regarded as part of it.

## D-Coordinates and H-Coordinates

Now, this system too can be "deformed", namely by moving the piston.\

A d-coordinate is therefore naturally associated with it, the value of
which specifies the position of the piston. We denote it
indiscriminately by $x_i$ in particular it might, of course, be chosen
to be the volume $V$ occupied by the gas. No other non-redundant
d-coordinate can be defined. Nevertheless even the most elementary
observation shows that the equilibria of this system are not adequately
described by the values of $x_i$ alone. Indeed, we soon find that upon
touching the system we may burn our fingers on one occasion and not do
so on another. Clearly at least one other variable which is not a
d-coordinate must be introduced. I shall call any such variable an
***h-coordinate***. In the case of our sample system only one of them is
required, and it might, for instance, be taken to be the pressure $P$ of
the gas, but this choice is not mandatory.

### Key Distinctions: d vs. h Coordinates

                      **d-Coordinates**                  **h-Coordinates**
  ------------------- ---------------------------------- ----------------------------------------------
  **Nature**          Mechanical deformation variables   Non-mechanical equilibrium variables
  **Examples**        Volume $V$, position $x$, strain   Pressure $P$, temperature $T$, magnetization
  **Role**            Describe spatial configuration     Encode internal state
  **Work Relation**   Work $\delta W = P_k \delta x_k$   No direct work association

## Formal Definition of Thermodynamic Systems

The state of affairs just described leads us quite generally to the
understanding that a thermodynamic system is a system whose equilibria
are specified by the values of a finite number of coordinates (i.e.
variables) at least one of which is an h-coordinate. Although this
definition appears to be very general, it does imply restrictions on the
kind of physical systems which we admit for consideration. In
particular, no substances can be present whose properties at a given
time depend upon their previous histories. There is an infinity of such
histories, whereas we are restricted to a finite number of coordinates.

-   **Mechanical System**:

    -   Described entirely by *d-coordinates* (deformation coordinates),
        e.g., positions of particles or lengths of elastic rods.

    -   Equilibrium states depend *only* on these coordinates.

    -   Example: A system of particles connected by rods; configurations
        are fully defined by Cartesian coordinates
        $x_1, x_2, \ldots, x_n$.

-   **Thermodynamic System**:

    -   Requires *at least one* **h-coordinate** (hidden coordinate) in
        addition to d-coordinates.

    -   h-coordinates capture non-mechanical properties (e.g., pressure,
        temperature) essential for equilibrium description.

    -   Example: A gas in a piston-cylinder system. Here, volume $V$
        (d-coordinate) is insufficient; pressure $P$ (h-coordinate) is
        needed.

## Thermal Equilibrium And Temperature:

Consider a system defined by $f(P,V,M, Composition)$ (suppose a chamber
of gas)\
Generate an illustration of a chamber separated by a rigid wall, and
there are two pistons on both sides. The rigid wall is adiabetic.\
The gas 1 and gas 2 can co-exist for any ($P_1, V_1$) and $(P_2, V_2)$.\
If I do something on ($P_1, V_1$) then $(P_2, V_2)$ will also be
affected. Once they are connected by the diathermic wall, ($P_1, V_1$)
and $(P_2, V_2)$ are not independent variables anymore.\
But there, will be some relation $F(P_1, V_1,P_2, V_2) = 0$ ...will hold
only for the thermal equilibrium state.\
Thermal equilibrium is the state achieved by two or more systems
characterized by restricted set of parameters on having been separated
by a diathermic wall.

**What is characterizing this Thermal equilibrium State?** Defined such
that the thermal equilibrium state is going to be only defined by one
quantity ie temperature.

## Standard Systems and Their Constraints

To keep everything as simple as possible, our main purpose being to gain
insight into the subject, we shall very often impose a number of further
restrictions, some or all of which are often implicitly taken for
granted. The most important of these is that of the n coordinates
exactly one is an h-coordinate. We further require that the effects of
surface tension can be neglected and that likewise the effect of mutual
long-range interactions between parts of the system can be neglected.
The first of these assumptions is always satisfied if only the system is
large enough; the second would not be justified in the context of a
system so massive that the mutual gravitational attraction between its
parts is comparable with other discrete operating within the system.
Finally we require that when any one of the d-coordinates, $x_k$, say,
changes slowly enough by an amount $(\delta x_k)$, sufficiently small in
absolute value, then the work $\delta W$ done by the system on its
surroundings shall be proportional to $(\delta x_k)$, and the ratio
$P_k$, of $\delta W$ to $(\delta x_k)$, shall be a function of the
coordinates alone. The functions $P_1, \ldots, P_{n-1}$ are called the
*generalized forces* of the system.

A system which satisfies the various conditions just laid down will be
called a *standard system*. The large majority of systems considered in
more or less elementary treatments of thermodynamics are of this kind.
As which is sometimes not sufficiently emphasized. Our sample system is
certainly a standard system with two coordinates. At times it is helpful
to have a much less than 3 standard systems with n coordinates. Somewhat
naively perhaps, we might take this to consist of $n - 1$ sample
systems, any one of the cylinders (taken to be metallic) being in
contact with at least one of the others. Each sample system contributes
one d-coordinate, so that there are $n - 1$ of these and all. In
addition we therefore need just one h-coordinate and this we may, for
instance, choose to be the pressure $P$ in any one of the cylinders.
Occasionally the theory of a particular non-standard system can be
reduced to that of standard systems. The possibility of being able to do
so hinges on which particular defining condition of standard systems is
not satisfied. It is, for example, not difficult to allow for the
presence of surface tension when this is not negligible.

### Standard Thermodynamic Systems

A system is **standard** if:

1.  It has $n$ coordinates: $n-1$ d-coordinates and *exactly one*
    h-coordinate.

2.  Surface tension and long-range interactions (e.g., gravity) are
    negligible.

3.  Work done during infinitesimal deformation is linear:
    $$\delta W = \sum_{k=1}^{n-1} P_k \delta x_k$$ where $P_k$ are
    generalized forces (e.g., pressure, stress).

### Example: Gas in a Piston-Cylinder

-   **d-coordinate**: Volume $V$.

-   **h-coordinate**: Pressure $P$.

-   Work done: $\delta W = -P \delta V$ (convention: work done *by* the
    system).

## Coordinates and State Space

-   A **state** $\sigma$ is defined by a unique set of coordinates
    $(x_1, \ldots, x_{n-1}; h)$.

-   Equilibrium requires all coordinates to be well-defined.
    Non-equilibrium processes lack defined h-coordinates.

-   Coordinates must be *independent* and *finite*, excluding
    history-dependent variables (e.g., hysteresis).

### Generalized Forces and Work

For a quasi-static process:
$$\delta W = \sum_{k=1}^{n-1} P_k \delta x_k$$

-   $P_k$: Generalized force conjugate to $x_k$.

-   Example: For $x_k = V$, $P_k = -P$ (pressure).

-   Forces are state functions: $P_k = P_k(x_1, \ldots, x_{n-1}; h)$.

### Non-Standard Systems

Systems failing the standard criteria include:

-   **Multi-component systems**: Require additional coordinates (e.g.,
    chemical composition).

-   **Systems with long-range forces**: Gravitational or electromagnetic
    interactions dominate.

-   **Small-scale systems**: Surface tension effects become significant.

## Notes on System Composition

It remains to point out a small sin of emission. When referring to \"a
gas\" I have throughout said nothing about the nature of this; it might
well be a mixture of several gases, capable of reacting chemically with
each other. In such a situation the chemical would come to be vitally
interested in the proportions in which the various gases are present
under conditions of equilibrium. However, the additional variables which
must be introduced to describe the internal, i.e. physico-ehemical,
constitution of a given system do not enter directly into the
description of the interaction of the system with its surroundings. It
is therefore preferable to deal with the required generalization of the
theory after its general foundations have been laid.

## Non-Standard Systems {#non-standard-systems-1 .unnumbered}

Systems failing the standard criteria include:

-   **Multi-component systems**: Require additional coordinates (e.g.,
    chemical composition).

-   **Systems with long-range forces**: Gravitational or electromagnetic
    interactions dominate.

-   **Small-scale systems**: Surface tension effects become significant.

## Critical Notes {#critical-notes .unnumbered}

-   **Why h-coordinates?**: Mechanical coordinates alone cannot
    distinguish states with identical configurations but different
    internal energies (e.g., gas at same volume but different
    pressures).

-   **Irreversibility**: Standard systems assume no memory
    (path-independence), but real systems may exhibit hysteresis
    (addressed later).

-   **Generalization**: Chemical reactions or phase transitions require
    extending coordinates, but foundations first require mastering
    standard systems.

## Problems

1.  If the system is just a gas, can you think of an h-coordinate other
    than $P$?

2.  A system consists of a block of iron on which work can be done not
    merely by compressing it but also by the action of an external
    magnetic field. Is the block a standard system?

3.  Which, if any, of the following are standard systems: (i) the
    moon, (ii) a solution of rock salt in water, (iii) a gas consisting
    of oxygen and hydrogen, (iv) a rain drop? Discuss (iii) in detail.

# States and Transitions, Adiabatic Isolation, Irreversibility

## Definition of States

We are already familiar with the meaning of the two kinds of coordinates
of a thermodynamic system $K$. In future we shall call any particular
set of values of these a state $\mathcal{G}$ of $K$; for which reason
the coordinates themselves are often also called 'variables of state'.
Of course, unless equilibrium obtains, h-coordinates are not defined, in
the sense that experiment does not yield unique values which might be
assigned to them. (For example, there is no single well-defined pressure
which might be assigned to a gas in turbulent motion.) Accordingly it is
meaningless to speak of a 'non-equilibrium state': a system not in
equilibrium is simply in no state at all.

\

Concomitantly, since all quantitative statements of classical
thermodynamics are about states, any predictions about the outcome of
experiments involving non-equilibrium processes can be at best
qualitative.

## Types of Transitions

A change of any system $K$ from one state to another will be called a
transition of $K$. In the course of a transition $K$ may or may not be
in equilibrium. When it is, i.e., when $K$ goes through a continuous
sequence of states, the transition is called pseudo-static; a
terminology which reflects the fact that it must proceed 'at an
infinitesimal rate',

\
since otherwise the appearance of elastic waves, turbulence, and the
like would not counter to the equilibrium which is supposed to obtain.
If, further, in the course of a pseudo-static transition work is done by
the forces $P_k$ alone it is called quasi-static. (For example,
transitions of a sample system brought about solely by turning the
stirrer or alternatively solely by moving the piston, either process
occurring at an infinitesimal rate, or as pseudo-static and
quasi-static, respectively.) Finally, a transition such that $K$ is not
in equilibrium in the course of at least a part of it is called
non-static.

Special conditions are frequently imposed upon transitions which
restrict their generality. For example, when all d-coordinates of $A$
are kept fixed by prescription the transition is isometric; if we merely
require their final values to be the same as their initial values we
call it weakly isometric. Further, a transition is infinitesimal if the
final state, and in the case of a quasi-static transition every
intermediate state, is sufficiently close to, i.e., lies in the
neighbourhood of the initial state.

\
Again, a most prominent position is occupied in the theory of the class
of so-called adiabatic transitions. To define these we must first
clearly understand what is meant by adiabatic isolation.

## Adiabatic Isolation

To this end, let us first think about the homely example of an aluminium
container filled with water and ice cubes. Upon placing it in a
refrigerator we may find that after some time the water has also turned
into ice. On the other hand, they've placed the container over the flame
of a gas burner the ice cubes would have melted, the evaporation of some
or all of the water quite apart. Now contrast this behaviour with what
we observe when the aluminium container is replaced by a high-quality
thermos flask. True, the ultimate behaviour of the water ice mixture is
the same, yet an altogether different time scale is involved. For
instance, upon placing the flask in the refrigerator we may have to wait
for days for the water to freeze. It is therefore not unreasonable to
suppose that better and better 'thermos flasks' could be constructed
until we end up with one which is such that it is to all intents and
purposes altogether impossible to melt the ice or freeze the water
contained within it merely by placing it into appropriate surroundings.\
The only way to melt the ice is to some mechanical process, not by
shaking or stirring. The particular example just discussed leads us to
the following general definition: an enclosure is called adiabatic (a)
the equilibrium of a system contained within it can only be disturbed or
mechanical means. An enclosure which is not adiabatic is called
diathermic. Any doubt as to what constitutes 'mechanical means' is
removed by prescription; examples are shaking, stirring, the movement of
a piston (or more generally any deformation of the system), and the
passage of an electric current.

## Adiabatic Transitions and Work

A system which is contained within an adiabatic enclosure is
adiabatically isolated, and we represent it by the symbol $K_0$. The
transitions of $K_0$ are adiabatic transitions, whether quasi-static or
not. Here we should be clearly aware of the distinction between
isolation on the one hand and adiabatic isolation on the other. The
latter condition is the weaker of the two since it does not forbid
arbitrary mechanical interaction between the system and its
surroundings. In other words, a system can certainly make up work on its
surroundings in the course of an adiabatic transition. (We note in
passing that the 4-coordinates of an adiabatically isolated system can
still be varied at will.)

There are evidently two kinds of possible interactions between a system
and its surroundings. When it is adiabatically isolated, the interaction
must be mechanical, and it necessarily involves large-scale, observable
motions in the surroundings, such as the displacement of levers, pistons
and the like \[Note 7\]. In the absence of adiabatic isolation the
interaction may, however, be partly or wholly
non-mechanical---synonymously: adiabatic or thermal---and no such
observable, large-scale motions need occur.

## Reversibility and Irreversibility

It remains to talk about another division of transitions into two broad
classes, the distinction between which lies at the root of
thermodynamics. To this end we must first ask ourselves what one might
understand by the 'reversal' of a transition. We contemplate in the
first instance only adiabatic transitions. Then the reversal of a
transition of $K_0$ from a state $\mathcal{G}$ to a state $\mathcal{G}'$
simply means a subsequent transition which restores the system
(adiabatically) to its initial state $\mathcal{G}$. This may turn out to
be in fact impossible; in that case the original transition is called
irreversible, otherwise it is reversible. In the absence of adiabatic
isolation, reversal can clearly no longer mean the mere restoration of
$K$ to its initial state since this can always be achieved by allowing
it to interact suitably with its surroundings. Evidently an additional
condition must be satisfied. It is this: that after the restoration of
$K$ to its initial state no overall changes in the surroundings remain
as the result of the process as a whole. Of course it is not a priori
obvious that there are any irreversible transitions of an arbitrarily
selected system at all. That there are is, in effect, one of the central
laws of nature which will require us a good deal later on, especially in
the next lecture.

Although quasi-static transitions of a standard system $K$ are
reversible it is not at all obvious that all reversible transitions of
$K$ must be quasi-static. It is in fact an experimental result that they
are so in the overwhelming majority of cases. There are, however,
'abnormal systems' which behave differently in this and other respects.
We shall return to these at the end of the course.

## Problems

-   3.1 Describe what manifest differences there are between the
    outcomes of the following alternative transitions of our sample
    system, i.e. of a gas contained in an adiabatically enclosed
    cylinder supplied with a piston in the usual way: (i) the piston is
    moved to and fro very slowly at constant speed so that the volume of
    the gas is first doubled and then reduced to its initial value; (ii)
    the volume is first doubled by sudden withdrawal of the piston and
    then restored to its initial value. (The surroundings of $K_a$ may
    be thought of as some external mechanical device.)

-   3.2 In the case of the system of Problem 2.2, leaving hysteresis
    aside as irrelevant here, do you consider the interaction via the
    magnetic field to be mechanical or thermal?

-   3.3 A system consisting of a gas contained in an enclosure is being
    stirred by means of a clockwork mechanism powered by a spring. What
    is the number of coordinates whose values constitute a state at any
    given time?

-   3.4 Can a purely mechanical system undergo 'irreversible changes'?

-   3.5 A system $K$ consists of two gases each contained in an
    adiabatic enclosure, the two enclosures being in mutual contact. $K$
    is not a standard system. Why not?

# The Second Law, Entropy and The Entropy Principle

We regard the irreversibility of a given transition of a system as being
characteristic of the behaviour of the system as such, not of its
surroundings. To this extent the character of its interactions with the
surroundings is irrelevant. Both as a matter of principle and to aid our
understanding and insight we therefore temporarily contemplate only the
simplest kind, namely those which are mechanical. In short, we confine
our attention to adiabatic transitions.

Let us consider again our sample system and suppose that the
surroundings do work on this system $K_0$ for a certain time by means of
the stirrer. As a result the pressure of the gas will have
increased---this is merely a matter of observation---whilst the volume
has remained constant. To reverse the transition would require the
reduction of the pressure to its initial value, the volume than also
having its initial value. How is this to be done? It is useless to turn
the stirrer since irrespectively of whether we turn it this way or that,
fast or slowly, more work will be done on $K_0$ and the pressure will
increase further. We may, on the other hand, seek to reduce it by
withdrawing the piston but then we end up with an increased volume. Upon
restoring it to its original value by pushing the piston in we regain
either the intermediate value of the pressure, if the to-and-fro process
proceeded at an infinitesimal rate, or an even greater pressure if it
did not \[cf. Problem 3.1\]. In short, the original state of $K_0$
cannot be restored, i.e., the transition under discussion is
irreversible.

We can shift the emphasis a little by rephrasing this conclusion as
follows. Given some initial state $\mathcal{G}$ there is a whole class
of states of $K_0$ such that no transition from $\mathcal{G}$ to any one
of these states is possible. On particular, if $\mathcal{G}$ is the
state $V$, $P$ then certainly all those states $|V', P'$ such that
$V'=V,P'<P$ belong to the class of states in question, no matter how
small $|P-P'|$ may be). We can sum up the whole content of the
conclusion reached so far somewhat formally as follows: in any
neighbourhood of a given state $\mathcal{G}$ of $K_0$ there are states
$\mathcal{G}'$ inaccessible from $\mathcal{G}$.

\
Moreover, it is obvious in the case of the sample system under
discussion that if the state $\mathcal{G}'$ is adiabatically
inaccessible from $\mathcal{G}$, then $\mathcal{G}$ is (adiabatically)
accessible from $\mathcal{G}'$. Setting our special system aside now,
the results of innumerable experiments confirm that the two main
conclusions just stated hold quite generally for (standard) systems of
arbitrary complexity \[Note 8\].

## Empirical Entropy Function

Suppose now that $\mathcal{G}$ and $\mathcal{G}'$ are arbitrarily
selected states of some adiabatically isolated system $K_0$ such that
$\mathcal{G}$ is inaccessible from $\mathcal{G}'$ (and therefore
$\mathcal{G}'$ accessible from $\mathcal{G}$). This specification
evidently contains a time order in the following sense: given merely
that $K_0$ was in the state $\mathcal{G}$ at some time and in the state
$\mathcal{G}'$ at some other time we can say that $\mathcal{G}'$ was
necessarily the later state. With this idea of an ordering amongst the
states of $K_0$ in mind, let us contemplate some ungoedness set of
selected states $\mathcal{G}_1$, $\mathcal{G}_2$, ...of $K_0$. We first
represent $\mathcal{G}_1$ by an arbitrarily situated point $p_1$ on a
straight line. Next $\mathcal{G}_2$ is represented by a point $p_2$ of
which we merely require that it lie to the right of $p_1$ if
$\mathcal{G}_1$ is inaccessible from $\mathcal{G}_2$, to the left of
$p_1$ if $\mathcal{G}_2$ is inaccessible from $\mathcal{G}_1$, and that
it be coincident with $p_1$ if $\mathcal{G}_1$ and $\mathcal{G}_2$ are
mutually accessible. (The three cases respectively correspond to the
transition from $\mathcal{G}_1$ to $\mathcal{G}_2$ being irreversible,
impossible, and reversible.) We continue this construction by
representing the states $\mathcal{G}_3$, $\mathcal{G}_4$, ...by points
$p_3,p_4,\ldots$ in turn in such a way that, if $p_j$ and $p_k$ are any
two points, $p_k$ lies to the right of $p_j$ to the left of $p_j$, or
coincides with $p_j$ according as the transition from $\mathcal{G}_j$ to
$\mathcal{G}_k$ is irreversible, impossible or reversible, respectively.
Finally we attach to each such point a number which can be chosen at
will subject to the sole condition that these numbers increase
monotonically as we proceed from left to right. (Coincident points of
course take the same number.)

Each state is a set of values of the coordinates $x_1,\ldots,x_n$ of the
system. The procedure just described therefore amounts to the definition
of a certain state-function $s(x_1,\ldots,x_n)$ (or simply
$s(\mathcal{G})$), for this is only another way of saying that a
correspondence has been established between the set of states
$\mathcal{G}_1$, $\mathcal{G}_2$, ...and a set of numbers
$s_{1}, s_2\ldots$.

\
Any particular $\mathcal{G}_j$ is labelled by a number
$s_j=s(\mathcal{G}_j)$, this labeling having the fundamental property
that a transition from a state $\mathcal{G}_j$ to a state
$\mathcal{G}_k$ is possible if and only if $s_j\leq s_{k}$ (equally
implying reversibility). We call $s_j$ the *empirical entropy* of
$\mathcal{G}_j$ (or of $K$ in the state $s(\mathcal{G}_j)$ and
$s(\mathcal{G}_j)$ the *empirical entropy function* of $K$. Evidently if
$K_0$ undergoes a transition from $\mathcal{G}_j$ to $\mathcal{G}_k$,
the empirical entropy of the final state can never be less than that of
the initial state.

## Continuum of States and the Second Law

Now, however large the set of states $\mathcal{G}_1$, $\mathcal{G}_2$,
...may be---it may even be infinite---it certainly does not contain all
possible states in which $K_0$ may find itself; they form a continuum.

\
It is therefore impossible to construct a labeling of the states of
$K_0$ by the simple method adopted.

\
For the distinction between the continuum of states and a sufficiently
large set $\mathcal{G}_1$, $\mathcal{G}_2$, ...selected from another
then, however important mathematically, is physically vacuous. Being
loath to abandon the particular conceptual approach which led to easily
to an understanding of the idea of entropy we cut the Gordans knot by
simply declaring that such a good function $s(x_1,\ldots,x_n)$ \[Note
11\] with the required properties always exists. In short, we lay down
the following law, intended to be a formulation of the *Second Law of
Thermodynamics* (so called for historical reasons):

> ***There exists an ordering amongst the states of any thermodynamic
> system $K$, reflected in the existence of a function $s$ of the
> coordinates of $K$ such that if $s',s''$ are the values of $s$ for
> arbitrarily selected states $\mathcal{G}'$, $\mathcal{G}''$ of $K$,
> then $\mathcal{G}''$ is adiabatically inaccessible from $\mathcal{G}'$
> if and only if $s''<s'$.***

We call $s$ an *empirical entropy function* of $K$, as before, and that
it is a good function is left understood. It is not uniquely determined,
in as far as $\sigma(s)$ is an equally acceptable empirical entropy
function if $\sigma(s)$ is any good monotonically increasing function of
$s$. This arbitrariness runs precisely parallel with that which we
encountered when we were numbering a set of discrete representative
points on a line: the sole condition which these numbers had to satisfy
was that they should increase monotonically from left to right.
Nonetheless, there are preferred functions $\sigma$, but it is perhaps
better to deal with these later on. At any rate, from the outset the
Second Law in its present form places explicit emphasis upon the
existence of irreversible processes. In doing so, it directly attaches
an intuitively transperent meaning to entropy without the encumbrances
of having to take into account any of the other principal laws of
thermodynamics and the various quantites such as energy or heat, whose
definitions derive from them.

Finally, according to the Second Law the transition from $\mathcal{G}'$
to $\mathcal{G}''$ is possible only and only if $s''\leq s'$ i.e. *the
entropy of the state of an adiabatic transition is never less than that
of the initial state*. This is nothing other than the **Principle of
Increase of Entropy**, basically a rewording of the second law.

## Problems

-   4.1 Experiment shows that $PV^\gamma$ is constant during a
    reversible adiabatic transition of a certain gas ($\gamma$ is given
    constant $> 1$). What states are adiabatically inaccessible from the
    state $\mathcal{G}[P, V]$?

-   4.2 Is there any substantial reason why in the statement of the
    Second Law the inequality $s'' < s'$ could not be replaced by
    $s' > s''$?

-   4.3 Strictly speaking nor form of the Second Law contains an
    omission. Can you say what it is, bearing in mind what you know
    about mechanical systems?

# The First Law, Energy and Heat

We return briefly to mechanical systems. Given any configuration, we
know all about the forces which hold the system in equilibrium, such as
gravity, elastic forces in connecting rods, and the like. In a change
from one configuration to another, i.e. in the course of deforming the
system, a certain amount of work will, in general, have to be done
against these forces, and this depends solely on the initial and final
configurations.

\
We can put this in another way: for any mechanical system there exists a
function $E$ of its coordinates such that the work done on the system in
any change of configuration is equal to the increase in the value of
$E$. This function, called the energy of the system, is defined only to
within an arbitrary additive constant. Evidently if a particular change
of configuration is such that the work done happens to be zero, then the
initial and final values of $E$ are equal; this is what is meant here by
the conservation of energy. In short, the energy of every mechanical
system is conserved; but in saying this we must bear in mind that $E$ is
solely a function of $\infty$ coordinates.

\

## Thermodynamic Systems and Work

We now go over to thermodynamic systems. Work is done here, too, when
the $\infty$ coordinates vary. It is, however, not true that the amount
of work in a transition depends solely on the deformation it has
undergone, i.e. on the extent to which the $\infty$ coordinates have
varied. That this is so becomes obvious on reflecting that work can be
done on the system simply by stirring it, and in that process the values
of the $\infty$ coordinates do not change at all. Furthermore there is
reason why, in general, the final values of the $\infty$ coordinates
should differ from their initial values. As far as the system is
concerned, the work done on it has apparently simply 'disappeared'. At
first sight it therefore looks as if no energy function could usefully
be ascribed to a thermodynamic system. How is this unhappy situation to
be rescued?

## First Law of Thermodynamics

A possible answer to the preceding question suggests itself as soon as
we recall that a thermodynamic system $K$ can interact in two ways with
its surroundings, namely mechanically and thermally (i.e.
non-mechanically). Once again we are led to exclude thermal
interactions; that is to say we consider only adiabatic transitions for
the time being. In this situation the results of innumerable experiments
show that the amount of work done by a system in an adiabatic transition
depends on the terminal states alone.

This, indeed, is the so-called First Law of Thermodynamics. To leave our
room for doubt, let it be emphasized that according to this law the work
$W$ done does not depend on the manner in which the transition of $K_a$
between given states proceeds, i.e. whether it is reversible or not, and
so, in particular does not depend upon any intermediate states through
which $K_a$ may happen to pass in the course of the transition.

## Energy Function and Heat

Further progress is now quite straightforward. Not to be hindered by
mere appearances, we first simplify the notation a little by writing, in
appropriate circumstances, $x$ for the whole set $x_1, \ldots, x_m$ and
of course $y$ for $y_1, \ldots, y_m$ and so on. A state $\mathcal{G}^+$
is then a set of values $x^*$ of the coordinates $x$, and this is
occasionally made quite explicit by writing $\mathcal{G}$ \[$x$\] placed
$\mathcal{G}^+$ alone. Now, according to the First Law, the amount of
work done by a system in any adiabatic transition from a state
$\mathcal{G}^+[x^*]$ to a state $\mathcal{G}^-[x^*]$ is merely a
function $F(x^*, x^*)$ of these states (if depending of course on the
structure of the given system). Hence if $K_A$ undergoes a transition
from $\mathcal{G}[x]$ to $\mathcal{G}^+[x^*]$ and then a subsequent
transition from $\mathcal{G}^+[x^*]$ to $\mathcal{G}^-[x^*]$ the total
amount of work done by it is $F(x^*, x^*) + F(x^*, x^*)$. However, we
know from the outset that in any transition from $\mathcal{G}^+$ to
$\mathcal{G}^-$ the work done by $K_B$ is $F(x^*, x^*)$, so that the
identity $$F(x^*, x^*) + F(x^*, x^*) = F(x^*, x^*)$$ must be satisfied
for all values $x^*$ of the coordinates of the intermediate state. In
other words, in forming the sum on the left the $x^*$ must cancel out
and the only possible if $F(x^*, x^*)$ has the generic form
$$F(x^*, x^*) = U(x^*) - U(x^*)$$ where $U$ is a certain function which
is as usual assumed to be a good function. It is called the internal
energy function of $K$ or, more briefly, its energy. It is defined,
i.e., can be measured, only to within an arbitrary additive constant.
Thus, simply expressed, the First Law declares that an adiabatic
transition the work $W_0$ does by the system is equal to the decrease
$-\Delta U$ of its energy: $$W_0 + \Delta U = 0$$ We thus have a
situation which is strongly reminiscent of that encountered in the case
of mechanical systems.

Now let the condition of adiabatic inclusion be abandoned. When $K$
undergoes some transition between given states $\mathcal{G}^+$,
$\mathcal{G}^-$ the best we can do is to measure the amount of work $W$
actually done by $K_B$; there is no reason why it should be just $W_0$.
In other words, the quantity $W + \Delta U$ will in general fail to
vanish. It is therefore usual to introduce the abbreviation
$$Q = W + \Delta U$$ and for historical reasons one rather qualifies
calls $Q$ the 'heat absorbed by $K'$ in the transition. However, let us
be clear that this heat $Q$ is simply the difference between two
mechanical quantities, namely the difference between the amount of work
done by the system in the actual transition between given states and the
amount of work which would have been done in an adiabatic transition
between the same states \[Note 15\]. In particular, a transition is
adiabatic if and only if the least is translated between the system and
its surroundings in the course of it. This is of course not a
definition: it is merely a somewhat trivial consequence of the First
Law, and to state the latter we already had to know what we meant by an
adiabatic transition.

## Properties of Energy

We have already supposed that $U$ is a good function.

Apart from this, experiment shows that the energy of any given system
has a least value, i.e. it has a lower bound. On the other hand the
energy of the vast majority of systems has no upper bound. Unless the
contrary is stated explicitly, I shall therefore suppose throughout that
the energy of any system can be increased indefinitely, and that this
can indeed be done even by means of isometric processes alone.

## Perpetual Motion and Additivity

A 'perpetual motion machine of the first kind' is intended to be some
cyclic mechanism, however complex, which can continue indefinitely to do
work on its surroundings with which it can interact only mechanically.
However, at the end of any number of cycles, being again in its initial
state, $\Delta U = 0$ and, since $Q$ also vanishes, $W = 0$. There are
therefore no such mechanisms; and the failure of all attempts to
construct them is simply evidence of the validity of the First Law, or,
as one sometimes says, of the conservation of energy \[Note 15\].

Finally, a word about the additivity of energy. Suppose we consider two
systems $K_A$ and $K_B$ jointly and regard them as constituting a
compound system $K_C$. It does not matter whether $K_A$ and $K_B$ are in
mutual contact or not. If they are standard systems the work done by
$K_C$ in any transition is simply the sum of the amounts of work done
separately by $K_A$ and $K_B$; for on the one hand there are no surface
forces which might have to be taken into account when they disappear to
their contact, whilst on the other, their relative positions are
irrelevant because of the absence of mutual long-range interactions.
Since energy changes and subsequently heat are defined solely in terms
of the amounts of work done on the various systems under the appropriate
conditions, it follows at once that $Q_C = Q_A + U_B$ and
$Q_C = Q_A + Q_B$. In short, in this sense energy and heat are additive,
but we must not forget that we have only standard systems in mind.

## Problems

-   5.1 On any reasonable time scale the earth will continue
    indefinitely to revolve about the sun in a nearly elliptic orbit. Is
    this an example of a perpetual motion machine?

-   5.2 A rigid adiabatic enclosure is divided into two parts by means
    of an internal partition. Initially the first compartment contains a
    gas whilst the second is evacuated. The partition is subsequently
    removed so that the gas will fill the whole enclosure. What can you
    say about the value of $\Delta U$?

-   5.3 For the sake of argument, suppose that a system consists of a
    fluid contained in a rigid adiabatic enclosure. (The system is
    artificial in that there are no deformation coordinates. On the
    other hand, the usual stirrer is to be present.) Determine an
    empirical entropy function.

# Class Notes:

$$V = \frac{RT}{P} \sum_i n_i$$
$$\frac{\partial V}{\partial n_i } = \frac{RT}{p}= V_m = \frac{V}{\sum n_i}$$
$$\frac{\partial n_{j \neq i}}{n_i}= 1$$ In the ideal gas situation each
component finds the whole container available for it. It doesn't feel
that someone else is there.

$$P_i = \frac{n_i RT}{V}$$ $$P = \frac{\sum_i n_i RT}{V}$$
$$P_i = \chi_i P$$ Define a close system such that change in the number
of moles of any component is 0. $dn_i = 0 \forall i$ at const. T

Do remember that, $$dG = Vdp -Sdt + \sum_i \mu_idn_i$$
$$d\mu_i = V_idp -S_idt + \sum_i \frac{d\mu_i}{dn_i}dn_i$$

::: center
:::

So, at cont T and const. composition, $$d\mu_i = V_i dp$$
$$\Delta \mu_i = \mu_i (T, P_i) - \mu_i(T,P) = \int_P^{P_i} V_idp = \int_P^{P_i} \frac{RT}{P} dp = RT \ln{\chi_i}$$
Basically, any change in the chemical potential means that the only
change will occur in the mole fraction and vice-versa.
$$\mu_i (T,P, \chi_i) = \mu_i(T,P) + RT\ln{\chi_i}$$
$$\mu_i = \mu_i^* + RT\ln{\chi_i}$$ where, $\mu_i^*$ is the reference
state, maybe the ideal gas situation.

\
This means that suppose we have $P_{i_1} \rightarrow P_{i_2}$, then we
have the different refernce state,
$$\mu_{i_1}  = \mu_{i_2} + RT\ln{\frac{c_{i_2}}{c_{i_1}}}$$ This is an
alternate reference state. $$P_i = \frac{n_iRT}{V} = c_iRT$$
$$\frac{a_{i_2}}{a_{i_1}} = \frac{\chi_{i_2}}{\chi_{i_1}}$$ Change in
the mixture and not the $G_{mix}$, remember the later is a wrong
notation. So we have , $$\Delta_{mix} G = G_{T,P} +  G_{T,P}^*$$
$$= \sum_i n_i\mu_i - \sum_in_i\mu_i^*$$
$$= \sum_i n_i(\mu_i^* + RT\ln{\chi_i} - \sum_in_i\mu_i^*$$
$$\Delta_{mix} G = nRT\sum_i \chi_i\ln{\chi_i}$$ Consider a free
adiabetic expansion of ideal gas,, From $P,V,T \rightarrow P=0, 2V$ this
expansion is carried out at const temperature, $dq_{rev} = dw_{rev}$, so
we get the entropy change as $nR\ln{2}$

Remember, $$\frac{\partial G}{\partial T}|_{P,n} = \Delta_{mix} S$$
$$\Delta_{mix} H = \Delta G + T\Delta S = 0$$ This is an ideal mixture,
so there is no enthalpy change in the in the mixing.\
Find the followings:

$$\Delta V_{mix} = ?$$

$$\Delta A_{mix } = ?$$ Should there be any change in the entropy of the
surrounding? $$\Delta_{mix} S = -nR\sum_i \chi_i\ln{\chi_i}$$ Since this
is a const pressure process, then heat change is the enthalpy change and
since enthalpy change is 0, so the process is adiabetic.

Can we look at just the state variables of the process and just conclude
if the process be spontaneous? We just did that!!!\
**Any system that is capable of doing work at const temp and pressure
then the spontanaity is for only the non-expansion work.**\
**Question:**\
Pure liquid A with vapour pressure $P_A$, assume the vapour to be ideal
gas, the $\mu_A = \mu_0 + RT\ln{P_A^*}$, $P_A^*$ is the vapour pressure
relative the reference state $P_A^* = \frac{P_A}{P_0}$ , $\mu_A$
chemical potential of the vapour phase. Since the chemical eq.
guarantees that the $\mu_A = \mu_{liquid}$ meaning we can use the same
ideal gas law can be applied to the liquid, as long as it's in chem eq
and the vapour behaves ideally.\
Now, if I go from the pure liquid to a mixture of liquid, that might not
be solid. I am mixing 2 liquids. I am moving away from the pure state,
the eq may not be valid now.
$$\mu_{A_{mix}} = \mu_0  + RT\ln{P_{A_{mix}}'}$$
$$\mu_{A_{liq}} = \mu_0  + RT\ln{P_{A_{liq}}^*}$$ mix is the mixture of
A and B.

If we see the change in the chem potential,
$$\mu_{A_{mix}} - \mu_{A_{pure}} = RT\ln{\frac{P_{A, mix}}{P_{A,pure}}}$$
$$P_A' = \frac{P_{A,m}}{P_0}$$

$$\frac{P_A'}{P_A^*} = \frac{P_{A,mix}}{P_{A, pure}}$$

## Rault's Law

::: center
:::

$$P_{A, mix} = P_{A, pure}\chi_A$$ $$\frac{P_A}{P_{A, pure}} = \chi_A$$

Definition of an Ideal Solution: Such that the chem potential of A
summed to the $RT\ln{\chi_A}$

## Henry's Law

As $\chi_B \rightarrow0$,

$$P_B \propto \chi_B$$

Think of a solution in a closed vessel with components A and B, a
monogeneous mix, the rate of evaporation of A will be related to the
number of molecules of A or the mole fraction of A ie. $\chi_A$
$$\text{Rate of Evaporation} = k\chi_A$$
$$\text{Rate of Condensation} = k'P_A$$ $$P_A = \frac{k}{k'}\chi_A$$
Interactions deviate from the ideality, the molecules on the surface are
drastically different from the bulk molecules.

So, this law also makes you think about the ideality of the solution.

1.  The solute is not volatile, meaning you will only see the solvent.

2.  The dissolved solute will not be a part of the solid solvent.

**Nature of the graph:** $RT\ln{\chi_A}$ here $\chi_A \leq 1$ meaning
the chemical potential of the solvent of the mixture will always be less
than the pure solvent.

$$\text{Change in the Temp for freezing and boiling } \propto \chi$$

![Caption](images/chem_pot_collegative.png){#fig:enter-label
width="50%"}

$$\mu_{A,gas} = \mu_{A, liquid}$$
$$\mu_{A,gas}^* = \mu_{A,liquid}^* + RT\ln{\chi_A}$$

$$\ln{\chi_A} = \frac{\mu_{A,gas}^* - \mu_{A,liquid}^*}{RT} = \frac{\Delta G_{vap}}{RT}$$

$$\frac{d}{dt}(\ln{\chi_A}) = \frac{1}{R} \frac{d}{dt} \frac{\Delta G_{vap}}{T} = - \frac{\Delta H_{vap}}{RT^2}$$
$$\int_0^{\ln{\chi_A}} d(\ln{\chi_A}) = - \int_{T^*}^{T} \frac{\Delta H_{vap}}{RT^2} dT$$
$$\implies \ln{1-\chi_B} =  -\frac{\Delta H_{vap}}{R}\{\frac{1}{T^*}- \frac{1}{T}\}$$
$$\frac{\partial }{\partial T}(\frac{\Delta G}{T})_P = - \frac{\Delta H}{T^2}$$
$$\frac{\partial G}{\partial T}_P = \frac{G-H}{T}$$

$$\frac{\partial}{\partial T} \frac{\Delta G}{T} = -\frac{G}{T^2} + \frac{G-H}{T^2} = -\frac{\Delta H}{T^2}$$

# AI Trying to Summerize the Notes:
