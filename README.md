## Hi there!

My name is Sam Blechman and I am a data scientist and master's student in [Dr. Erik Wright's lab](https://wrightlabscience.com/) in the [Department of Biomedical Informatics](https://www.dbmi.pitt.edu/) at the University of Pittsburgh. I will complete my master's degree in May of 2025 and am pursuing roles in data science, data analytics, and bioinformatics.

In my current role, I mine and analyze electronic health record (EHR) data to study the effect of antibiotic resistance and antibiotic treatment across a large and diverse health system ([UPMC](https://www.upmc.com/)). I use causal machine learning (think causal inference but shinier!) to identify subpopulations that are responsive to an alternative antibiotic treamtent or that are particular sensitive to the effect of antibiotic resistance.

Modeling, inference, and prediction are really cool and are ultimately the ways that we derive insights from data. However, I am passionate about simple but important components of data science as ways of understanding the data and letting it guide you. Namely, **looking at the raw data** and **visualizations**. I strive to be a scientist first, and data scientist second. I strive to lead with my brain rather than my fancy modeling tools.

Check out some of my repositories:
- [SequenceToMutations](https://github.com/WrightLabScience/SequenceToMutations) holds code from my previous time in the wet lab. The code refers to a pipeline that ingests raw whole genome (short-read) sequencing data and outputs a list of mutations in the context of a Lenski-esque experimental evolution project. I wrote a paper about the results of my [VRSA experment](https://doi.org/10.1371/journal.ppat.1012422)!
- [CausalDiscovery](https://github.com/WrightLabScience/CausalDiscovery) holds code from an *attempt* at using causal discovery ([heard of Tetrad?](https://www.cmu.edu/dietrich/philosophy/tetrad/)) as a confounder selection method prior to causal inference. Given the different ways of slicing and dicing my data, as well as the many causal discovery algorithms and parameter combinations, I ran a large grid search-type experiment on the Open Science Grid. It turns out that in general causal discovery is far too conservative to return a meaningful set of confounders, and given the risk of bias from not including confounders during inference, I decided to abandon this approach. However, the repo contains some fun things, such as a [bash script that conditionally builds a command](https://github.com/WrightLabScience/CausalDiscovery/blob/main/job_files/search.sh) to run [tetrad on the command line](https://bd2kccd.github.io/docs/causal-cmd/) depending on the input parameters.
- [YahtzeeData](https://github.com/samblechman/YahtzeeData) - still under construction! - holds code and raw data to ingest, parse, and analyze the score sheets from the nearly 200 Yahtzee my wife and I have played over the last year and a half. Wondering why she is beating me 109 wins to my 83? She gets the upper bonus way more often than me! Am I bad or is she lucky? I plan to turn the analyses here into an interactive dashboard.

<!--
**samblechman/samblechman** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
