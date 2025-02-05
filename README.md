# -K-Armed-Bandit-Environment
We will implement the K-Armed Bandit problem and experiment
with different methods and strategies.
Step 1: Implement the K-Armed Bandit Environment
• Create an environment simulating a K-Armed Bandit with k arms.
• Each arm has a fixed, unknown reward distribution (e.g., normal distribution with a specific mean and variance).
Step 2: Action Value Estimation
Implement both the sample average and incremental methods for estimating
action values.
Step 3: Action Selection Strategies
Implement the following strategies:
1. Greedy
2. Epsilon-Greedy
3. Epsilon-Greedy Decay (e.g., ϵt =
1
t+1 )
Step 4: Experiments
Run experiments with the following configurations:
• Different values of k (e.g., k = 5, 10, 20).
• Different values of ϵ (e.g., ϵ = 0.1, 0.01, 0.5).
2
• Compare the performance of the strategies over 1,000 plays and 2,000
plays.
Record the cumulative rewards and percentage of optimal actions selected
for each strategy.
Step 5: Analysis
- Compare the performance of the strategies based on the results.
- Discuss the effect of varying k and ϵ.
- Analyze the impact of the epsilon-decay strategy compared to fixed epsilon
values.
Output Requirements
- Provide plots showing the cumulative rewards and percentage of optimal actions selected over time for each strategy.
- Write a short report summarizing your findings and insights.
