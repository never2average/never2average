# Learnings

The first learning is that security tools are often optimized for proof that the tool ran, not proof that the application is safer. A long list of findings helps a vendor show activity, but it does not help a team shipping dozens of pull requests understand what is actually vulnerable.

The second learning is that enterprise buyers increasingly want continuous assurance, not annual compliance evidence. SOC 2 may prove a process existed, but it does not answer whether the thing deployed this afternoon is now exploitable.

The third learning is that the hard part is not only finding issues. It is proving exploitability inside a realistic application sandbox, then making the coding agent fix the thing without being fooled by the red-team loop. That red-team-agent loop trying to break the coding agent inside the sandbox was the ugliest technical part, because it forced the system to understand attack, repair, and verification at the same time.

The web app has to make that work visible. If the backend proves something but the UI collapses it into a generic severity badge, Dover becomes the same kind of tool it was built to escape.
