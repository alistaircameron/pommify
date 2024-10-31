# pommify

Built to work with a .tex file and switch to/from English/American.

Ignores all latex commands and curly brackets, so your \{itemize} commands won't become \{itemise}. Captures capitalised words. Ignores everything prior to \begin{document} and everything after \end{document}.

Gratefully using @hyperreality's dict: https://raw.githubusercontent.com/hyperreality/American-British-English-Translator/master/data/british_spellings.json

Usage: pommify(filepath/to/tex, to_british=True/False)
Output: new .tex file with British/American spelling.

# TODO: 
- make it run natively within overleaf.
