# CURE
This notebook explores a model of decision making under a norm. Each individual has a strategy $x$ and value $v$, then when playing against a player with strategy $y$, chooses the strategy to maximize $$(1-v)p(x,y)+vf(x,y)$$ where $p(x,y)$ is the payoff and $f(x,y)$ is some function specifying the norm being followed. For simplicity, we consider payoffs coming from a single round of a symmetric two player, two action game, with memory zero strategies, which are just the probability of choosing the first action.

More details are available at the bioRxiv preprint https://arxiv.org/abs/2401.13015. 
