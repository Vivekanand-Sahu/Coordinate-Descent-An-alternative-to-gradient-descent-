🚀 An alternative to Gradient descent ?! 🚀

Hey Everyone! 👋
I tried designing an algorithm 'All-feature Coordinate Descent' as an alternative to the Gradient Descent for some special cases, and I'm thrilled to share the progress! 🌟

Advantages:
1️⃣ Unknown differentiation: Unlike Gradient Descent, this algorithm does not need the differentiation equation of the loss function to update the weights. It only needs the loss function to be convex for achieving convergence.
2️⃣ Overshooting: There are 2 hyper-parameters (learning rate and reduction factor) that ensure that the model will never overshoot/diverge for any hyper-parameter values.

Disadvantages:
1️⃣ Computation: May not outperform gradient descent's computation efficiency because unlike gradient descent, it updates the weights after calculating the change in loss for each weight.
2️⃣ Multiple Hyper-parameters: Requires adjustment of 2 hyper-parameters for optimal performance.

To demonstrate, I used the UC Irvine's Wine dataset for logistic regression. I also tried 2 additional variants of the algorithm and computed their performance. GitHub: https://lnkd.in/gVNGqJ9n

I'm eager to hear your thoughts and insights! Let's engage in a discussion and explore potential collaborations. Your expertise matters! 🤝💡
Drop your comments, or feel free to connect for a more in-depth conversation. Let's innovate together! 🚀🔍


![Game Screenshot](https://your-image-url.com/algorithm.jpeg)
