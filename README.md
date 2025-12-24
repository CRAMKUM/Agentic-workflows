Different kinds of workflows:
1. Prompt chaining - In > LLM1> Gate > LLM2 > LLM3 > Out
2. Routing - In > LLM Router > LLM1 or LLM2 or LLM3 > Out
3. Parallelization - In > Coordinator > LLM1 and LLM2 and LLM3> Aggregator > Out
4. Orchestrator Worker - In > Orchestrator > the predefined code doesnt define the route, its the orchestrator that decides the route. This itself is the Agent > Synthesizer
6. Evaluator - Optimizer In > LLM generator > LLM evaluator for feedback > Out


Agents:
1.) Its open ended
2.) Feedback loops
3.) No fixed paths

Human > LLM call > Environment giving feedback and then Stop
