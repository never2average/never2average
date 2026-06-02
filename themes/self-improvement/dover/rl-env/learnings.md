# Learnings

The first learning is that self-hosting is not the same as security competence. Running open models inside your own perimeter helps with data exposure and control, but it does not magically make those models good at finding authorization bugs, injection paths, unsafe defaults, or exploit chains.

The second learning is that open-source coding models need a training environment that looks like the work they will actually do. Security cannot be taught only through abstract labels or static examples. The model has to see code it generated, attacks against that code, and the specific reason the patch failed or held.

The third learning is that Dover's backend and the RL environment feed each other. The backend proves exploitability and fixes applications. The RL environment should turn those patterns into better future behavior from the coding agent.

The uncomfortable lesson is that the model can be excellent at code shape and still bad at security judgment. Dover RL exists because secure generation has to be trained, not assumed.
