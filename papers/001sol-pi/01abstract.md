
1. As coding agents move from supervised code completion to unattended, around-the-clock exploration, their work expands from isolated predictions into long trajectories of reasoning, tool use, and feedback. 

[how reasoning is done?] [how tool use happens?] [what is a feedback?]

it's close to infinte loop untill goal is achieved or [terminal condition for stoping agents]

reason :[how I can achieve something,having this tools and results so far] 

tools : [use available tools ] 

environment : [ where our agent can act, affect environment]
    
feedback: [what did we observe from current actions, real world observations  we can make about our actions direct or proxy for evaluation of achieveing the  current goal]


2. Token efficiency therefore becomes important for scaling recursive self-improvement. 

[how to reduce number of tokens using ? ]


3. We take an RSI-inspired approach at the harness layer, scaling auto-research loops across increasingly numerous and diverse environments for harness rollouts.

[rsi] : recursive self improvement -> system uses prev experiment results to improve the next run experiment 
[harness layer] : all programs around llm -> all software around llm, which decide how agent reason/act/observe/memorize
[harness rollouts] : specific path traces with all produced artifacts produced by this harness[system/configuration] run agent 



