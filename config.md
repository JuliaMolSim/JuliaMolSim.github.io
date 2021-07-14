<!--
Add here global page variables to use throughout your website.
-->
+++
author = "JuliaMolSim community"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = false
website_title = "JuliaMolSim: Molecular Simulation in Julia"
website_descr = "Molecular Simulation in Julia"
website_url   = "https://juliamolsim.github.io/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\braket}[2]{\left\langle #1 \middle| #2 \right\rangle}
