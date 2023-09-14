# Murphy's Laws for Machine Learning & Neural Networks

In the spirit of "Anything that can go wrong will go wrong", these laws capture the quirks and challenges of working with ML and Neural Networks in the real world.

## 📜 The Laws

1. **Law of Critical Application**: The more critical the application, the more likely the neural network will fail to generalize.
2. **Law of Excessive Complexity**: The complexity of a neural network will always exceed the available data.
3. **Law of Premature Deployment**: A neural network model that takes weeks to train will have a bug discovered within minutes of deployment.
4. **Law of Interpretability's Inverse**: The most accurate model will be the least interpretable.
5. **Law of Hyperparameter Inconsistency**: Hyperparameters that worked best in your last project will be the worst for your current project.
6. **Law of Layered Confusion**: The more layers you add, the less you understand.
7. **Law of Validation Oversight**: A 99% accuracy on your validation set usually means you’ve forgotten to include a critical class of data.
8. **Law of Blind Architecture**: If you don't understand the architecture, adding more layers will not help.
9. **Law of Model Obsolescence**: The moment you deploy your state-of-the-art model, a new paper will come out rendering it obsolete.
10. **Law of Misplaced Confidence**: A neural network's confidence in its prediction is inversely proportional to its accuracy at the most critical moments.
11. **Law of GPU's Last Gasp**: The GPU will crash minutes before the end of a weeks-long training session.
12. **Law of Random Tweaking**: The more you tweak a neural network, the closer it gets to being a random number generator.
13. **Law of Training Duration's Deception**: The model that took days to train will be outperformed by a simpler model that took minutes.
14. **Law of Documentation Lag**: The documentation for the latest neural network framework will always be one version behind.
15. **Law of Model Complexity Irony**: Your most complex model will achieve similar performance as a linear regression on the same data.
16. **Law of Hyperparameter Hindsight**: The best hyperparameters are always found after you stop searching.
17. **Law of Reproduction Anxiety**: The moment you can't replicate your results is when your boss asks for them.
18. **Law of Unexpected Inputs**: Every neural network has a special set of inputs that will make it behave unexpectedly, and you will only discover them in production.
19. **Law of Simple Mistakes**: No matter how advanced the model, its errors will always appear to be foolishly simple to humans.
20. **Law of Depth**: The deeper the network, the more elusive the vanishing gradient problem until deployment.
21. **Law of Recurrence**: Your RNN will remember everything, except the one sequence pattern that's critical.
22. **Law of Gated Memory**: The moment you decide LSTMs have solved your sequence problems, your data will evolve to prove you wrong.
23. **Law of Bidirectionality**: When a BiLSTM starts to make sense, your sequences will demand attention elsewhere.
24. **Law of Convolution**: The most critical feature will always be just outside your CNN's receptive field.
25. **Law of Local Reception**: After painstakingly optimizing your CNN's kernel size, a change in input resolution will make it irrelevant.
26. **Law of Attention**: Your model will attend to everything in a sequence except the most relevant part.
27. **Law of Self-Attention**: The one time a Transformer fails, it'll be on the input you least expected it to.
28. **Law of Transfer Learning**: The more specific your task, the less transferable a pre-trained model will be.
29. **Law of Reinforcement**: Your agent will master every strategy, except the one that maximizes reward in the real world.
30. **Law of Environment Dynamics**: The one time your RL model seems perfect, the environment will suddenly turn non-stationary.
31. **Law of Large Models**: The bigger the model, the more embarrassing its simplest mistake.
32. **Law of Over-parametrization**: Your most overfitted model will generalize perfectly during testing but fail miserably in the real world.
33. **Law of Gradient Flow**: The layer where you need the gradient the most is where it will vanish.
34. **Law of Modality Adaptation**: The moment you fine-tune a CNN for non-image data, you'll find a dataset where a simple ANN outperforms it.
35. **Law of Dynamic Architecture**: The more dynamic your network, the harder it will be to explain its sudden failures.
36. **Law of Adversarial Robustness**: The adversarial attack you didn't prepare for will be the first one you encounter.
37. **Law of Multimodality**: Whenever you combine data types, the network will excel in one and fail spectacularly in the other.
38. **Law of Sparsity**: Your most pruned network will miss the one connection that's critical.
39. **Law of Neural Plasticity**: The day after you repurpose a neural network is when it will yearn for its original task.
40. **Law of Supervised Illusion**: In supervised learning, the more precisely your model fits the training data, the more it believes it understands the world—until it meets the real-world data.

## 🤝 Contributions

Feel free to submit a PR if you've encountered another "law" in your experience or if you have any suggestions or improvements. Let's grow this list together and bring a little humor to our daily ML struggles.

## 📄 License

This repository is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgements

- Inspired by Murphy's Law and the collective wisdom (and pain) of Machine Learning practitioners everywhere.
- Special thanks to the ML community for the shared experiences and insights.
- Inspired by Murphy's laws collection at [Angelo State University's blog](https://www.angelo.edu/faculty/kboudrea/cheap/cheap3_murphy.htm#Computers).


