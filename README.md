## PyoFuel

PyoFuel is a project I came up with in my senior year of high school. 

In two earlier projects I had experimented with flux balance analysis on models of bacteria that had been modified with pathways to synthesize biofuel, and with wet-lab recombineering of the DHX35 gene using E.coli. The former was fun, quick, and easy; the latter was fun, slow, and painful. I wondered how one might help the other.

I came across Pathway Tools -- a collection of biological modeling tools with databases of organism models, metabolic flux analysis, and query and visualization tools. Pythoncyc is a Python programming interface to Pathway Tools. 

So I wanted to use Python to script Pathway Tools, to help find candidate biofuel pathways across organisms, identify the corresponding gene-edits to engineer biofuel-friendly E.coli, and evaluate how effective each engineered organism might be --as a precursor to more detailed modeling or wet-lab work.

The result was PyoFuel.

Here are some highlighted bits of the PythonCyc interface I used, an ipython notebook with initial experiments (later experiments are a bit of a code mess -- I will upload when cleaned up), and the poster that was accepted at a conference. 