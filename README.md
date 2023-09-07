# 2SP_RiskChance
In this paper, we study optimal procurement and inventory decisions for a supply chain with a single perishable product  under demand uncertainty. To control risk, on the one hand, we use a risk-averse objective, and on the other hand, we  utilize a chance constraint to satisfy demand with a high probability.

## Problem Statement
We consider a supply chain for a single perishable product, consisting of a set $\mathcal{I}$ of suppliers, a set $\mathcal{J}$ of DCs, and a set $\mathcal{K}$ of retailers. We assume that the operation of this supply chain is modeled as a network flow problem on a complete graph containing nodes $\mathcal{V}:=\mathcal{I} \cup \mathcal{J} \cup \mathcal{K}$. Consumers' demands may be satisfied immediately at retailers, provided that the product is available. We do not explicitly define a set of consumers and assume that each retailer represents a group of consumers and their demands. Moreover, we consider a set $\mathcal{T}:=\{1,\ldots, T\}$  of time periods and assume that the demand at different time periods and retailers is uncertain. We assume a short shelf-life of $\gamma$ time periods and consider fixed travel times $\tau_1$ and  $\tau_2$ between a supplier and a DC, and a DC and a retailer, respectively, such that $\gamma > \tau_1 + \tau_2$.

## Code implementation
1. Download an instance of the demand file.
2. Download the parameter files.
3. Download the algorithm code and keep it in the same folder.
4. State the number of scenarios in the algorithm code  __init__ function inside Relaxed_Master class.
5. State the risk parameter setting $\lambda$ (and $\alpha if mean_CVaR) in the objective function inside Relaxed_Master class and also in the end while updating the bounds.
6. State the value of $\epsilon$.
7. State the name of demand file inside the Relaxed_Master class.
8. Run the code.
