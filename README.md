Hi team,

Shipped an opt-in heuristic guard that filters malformed/incoherent prompts before they hit the API — reduces wasted tokens on bad inputs.

Scope: French-optimized for now (action verbs + format keywords). Extending to other languages = extending the word lists, ~10min of work.

Status: functional, manually tested (guard off / valid prompt / malformed prompt), threshold calibrated to favor permissiveness — better to let an edge case through than block a legitimate request. Couldn't run the full benchmark suite (hardware failure mid-test), happy to follow up with more data if useful.

Open to feedback and happy to iterate based on review.

Chems
