# Options_Trading_Simulator_Montecarlo_Basic

Welcome. I made this program so my roomates and I could better predict the future value of option contracts for an investment project. The program uses aspects of the Black-Scholes differential equation to model the path of the option's predicted value:

 Information regarding the model and how it works can be found here:
 http://danielandrei.info/blackscholes.pdf
 https://www.youtube.com/watch?v=RETxgJcXBAY&ab_channel=Engineers.SG
 
 
The program runs the path in a Markov Chain Monte Carlo simulation over multiple iterations to determine an accurate future value. This stock option process can be modeled as a Markov Chain because it is discrete and has the Markov property,(https://en.wikipedia.org/wiki/Markov_property) which only considers the n and (n - 1) steps in calculating the next step ; therefore, the larger history of the value of the stock is irrelevant in calculating the probability of the value at timestep (n + 1) (https://en.wikipedia.org/wiki/Markov_property). We can observe distribution of the ending value of the random walk (where step values are iid) approaches normal as more iterations are used in the simulation. More calculations in overleaf on the way (EXPECTED VALKUE AND VARIENCE).
