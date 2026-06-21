HEY-GAFAM-READ-THIS

Target: OpenAI, MistralAI, Anthropic

Hi team,

Shipped a token-saving heuristic for error prompts. Cutting ~X% wasted tokens on bad inputs.

🛠 Current scope: French optimized. 
Adding other languages = extend the word lists. 10min work.

🎯 Precision scores on my tests:
OpenAI & Mistral: 1.0 [needs threshold tuning]
Anthropic: 0.1 [needs threshold tuning]

⚠️ Status: Raw but working. 
Better intentionally permissive threshold. Better to let 2 spam prompts through than block 1 legit user. 
Couldn't run full benchmark suite. 8GB RAM laptop died mid-test.

Code is clean. Tests included. Ready to merge.

I might be open to work if you move fast.

Chems
