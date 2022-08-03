# Invited Speakers

[back to program](index.md)

## Erika Abraham

**Title.** 
Probabilistic Hyperproperties

**Abstract.**
Four decades ago, Lamport used the notion of trace properties as a means 
to specify the correctness of individual executions of concurrent 
programs. This notion was later formalized and classified by Alpern and 
Schneider to safety and liveness properties. Temporal logics like LTL 
and CTL were built based on these efforts to give formal syntax and 
semantics to requirements of trace properties. Subsequently, 
verification algorithms were developed to reason about individual 
executions of a system.

However, it turns out that many interesting requirements are not trace 
properties. For example, important information-flow security policies 
(e.g. noninterference, observational determinism) or service level 
agreements (e.g. mean response time, percentage uptime) cannot be 
expressed as properties of individual execution traces of a system. 
Rather, they are properties of sets of execution traces, also known as 
hyperproperties. Temporal logics such as HyperLTL and HyperCTL∗ have 
been proposed to provide a unifying framework to express and reason 
about hyperproperties.

This talk is devoted to special class of hyperproperties: we ask the 
question what are hyperproperties in the context of systems with random 
behavior. We will discuss what are relevant probabilistic relations 
between independent executions of a system, how we can formally express 
them in a temporal logic, and how we can decide the truth of such 
statements.


## Kuldeep S. Meel 

**Title.** Distribution Testing and Probabilistic Programming: A Match made in Heaven   

**Abstract.**
The field of distribution testing seeks to test whether a given distribution satisfies a property of interest. While there have been deep technical developments in the field of distribution testing, the field has somehow been confined to theoretical studies. I will discuss our work on development practical algorithmic frameworks based on distribution testing, and its relationship to probabilistic program verification. In particular, I will show that the problem of measuring distance between straight line probabilistic programs is #P-hard. As expected, the theoretical hardness shouldn’t deter us and I will discuss our success in using distribution testing-based frameworks to design efficient samplers. 



## Andrzej Wasowski

**Title.**
Quantifying Leakage in Privacy Risk Analysis using Probabilistic Programming

**Abstract.**
Disclosure of data analytics results has important scientific and commercial justifications. However, no data shall be disclosed without a diligent investigation of risks for privacy of subjects. Privug is a tool-supported method to explore information leakage properties of data analytics and anonymization programs. In Privug, we reinterpret a program probabilistically, using off-the-shelf tools for Bayesian inference to perform information-theoretic analysis of the information flow. For privacy researchers, Privug provides a fast, lightweight way to experiment with privacy protection measures and mechanisms.


## Sylvie Putot

**Title.** Uncertainty propagation in discrete-time systems using probabilistic forms

**Abstract.**
We consider the problem of rigorously quantifying the uncertainty in the states of a dynamical system due to the influence of initial state uncertainties and stochastic disturbance inputs. We use ideas from interval arithmetic and its variations such as affine arithmetic or Taylor expansions to rigorously represent the state variables at time t as a function of the initial state variables and noise symbols that model the random exogenous inputs. We also show how concentration of measure inequalities can be employed to prove rigorous bounds on the tail probabilities of these state variables.

[back to program](index.md)
