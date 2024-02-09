# Ad-Selection (Reinforcement Learning - Upper Confidence Bound)

Using upper confidence bound reinforcement learning to determine the most effective advert in a dataset.

## Upper Confidence Bound

In reinforcement learning, the Upper Confidence Bound (UCB) is a strategy used to balance exploration and exploitation. The fundamental idea behind UCB is to select actions that either have been successful in the past or have the potential to yield high rewards, while also ensuring that less explored actions are given a chance to be tried out.

1. Exploration - UCB ensures that the agent explores different actions by assigning each action an upper confidence bound based on its estimated value and uncertainty. Actions with higher uncertainty are given higher bounds, encouraging exploration.

2. Exploitation - At the same time, UCB favors actions that have yielded high rewards in the past. This is achieved by considering the estimated value of each action, which is typically calculated using methods such as the average reward obtained from that action.

3. Balancing exploration and exploitation - The balance between exploration and exploitation is determined by a parameter called the exploration-exploitation trade-off. This parameter governs the degree to which the agent prioritizes exploration over exploitation.

Mathematically, the upper confidence bound for each action can be calculated using various methods, such as the UCB1 algorithm. This algorithm often utilizes the average reward obtained from an action, the number of times the action has been selected, and a confidence interval that typically grows logarithmically with the number of times the action has been tried.

Overall, UCB helps reinforcement learning agents make decisions that maximize cumulative reward by efficiently exploring the action space while also exploiting actions that are likely to yield high rewards based on past experience.

## Model Performance

<p style="text-align: center;">
  <img src="https://github.com/Neill-Erasmus/ad-selection/assets/141222943/7b78b24b-459a-45a0-a8e1-fca9d471edc3" alt="output">
</p>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
