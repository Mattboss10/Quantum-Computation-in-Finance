Variational quantum eigensolvers (VQEs) are algorithms that use quantum computers to solve complex problems in chemistry and physics. 
They work by finding the lowest energy state, or ground state, of a given system using a trial wavefunction. 
The algorithm prepares this trial wavefunction(Ψ)-a mathematical function that describes the behavior of a particle, and measures its energy, and updates it until it converges to the ground state energy of the system. 
This can help solve problems that are too difficult for classical computers, such as simulating the behavior of complex molecules or materials, which has important applications in drug discovery, materials science, and other fields such as finance

-----
The strategy is focused on stock picking using Quadratic Unconstrained Binary Optimization (QUBO), solved with quantum-inspired methods like Variational Quantum Eigensolvers (VQE). It’s a portfolio optimization problem framed for quantum computers — minimizing risk (variance) for a given return target.

Compared to traditional quant strategies like factor investing, statistical arbitrage, or trend following:
	•	This is very experimental.
	•	It is not battle-tested like classical methods; it’s mostly academic or prototype-level today.
	•	Similar classical strategies: classical Markowitz portfolio optimization (mean-variance optimization) and convex optimization methods in quant finance.

Quantum versions are being researched, but they aren’t production-ready yet in the real trading world.

--------
To get historical market prices go to https://www.quandl.com/?modal=register and sign up for your API key.

Look for the part in the code that defines the quandl token and paste it there ,make sure that quotations are at the end.

----
Ogranzation
----
Each Block of code is in a seperate file, each block can be pasted in to a python notebook.
