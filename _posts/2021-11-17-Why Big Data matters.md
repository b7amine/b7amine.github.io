# Big data: Why does it matter?

You might be surprised to learn that the theory behind many AI applications we see today was developed a long time ago. Here are a few key milestones:

- **Gradient Descent** (1847) [[1]](#ref1) – Developed by Augustin Louis Cauchy. Even earlier, Newton (yes, the gravity guy) invented a similar method for optimization.
- **1983** – The **Classification and Regression Tree (CART)** algorithm [[2]](#ref2) was developed by Leo Breiman and colleagues.
- **1995** – **AdaBoost** [[3]](#ref3), the first practical boosting algorithm, was introduced by Yoav Freund and Robert Schapire.
- **2001** – **Viola-Jones algorithm** [[4]](#ref4) for real-time face detection was created by Paul Viola and Michael Jones.

So why is AI only becoming such a big deal recently? The answer comes down to **two things**: **computing power** and **data**. We now have access to **huge amounts of data** (big data) and the **computing power** needed to process it. In fact, the rise in computing power is largely due to the need to process this growing data.

### Why is Big Data So Important?

To understand why big data matters, think about how we make sense of the world around us. We believe in gravity, not because there's a perfect mathematical proof, but because we've seen things fall countless times. Newton's equation **F = ma** is based on those observations, forming a model of how gravity works. Later, Einstein introduced **general relativity**, showing that Newton's model only works in everyday situations, but breaks down under extreme conditions like in space. This was because Newton's observations weren't enough to capture the full picture.

This is called **inductive reasoning** [[5]](#ref5), where we use a set of observations to come up with a general principle. The more observations we have, the better our model. That's why **big data** is so powerful. If you've only seen 10 cats in your life, your idea of what a cat looks like might be biased. But if you've seen millions of cats, it's unlikely a new cat will surprise you. Big data gives us a clearer, more accurate model.

### The Limits of Inductive Reasoning

But inductive reasoning has its limits. For example, some of my French friends think that most Moroccans are great at coding. This belief is based on their experience, but it’s biased. Most of the Moroccans they’ve met are students or professionals in tech fields, so the sample is not representative of the whole population. This is called **survivor bias** [[6]](#ref6).

Many philosophers question the reliability of inductive reasoning. If you're interested, look up the **Problem of Induction** [[7]](#ref7).

### Big Data and Patterns

Big data helps us spot patterns in what might seem random. For example, **Benford's Law** [[8]](#ref8) shows that in many real-world datasets, the first digits of numbers follow a specific distribution:
1: 30%
2: 18%
3: 12%
4: 10%
5: 8%
6: 7%
7: 6%
8: 5%
9: 4%

This pattern is useful in detecting fraud. In 1972, **Hal Varian** suggested that Benford’s Law could help spot fraud in economic data. People who make up numbers often distribute digits evenly, which doesn’t match the natural pattern.

To see this in action, I picked a dataset from Paris's open data platform: "Subsidies Paid: Appendix Administrative Account from 2018." I checked the distribution of the first digits in the "Prestation en nature" column. As I increased the sample size, the numbers followed Benford's Law more closely.

<video width="100%" height="400" controls>
  <source src="/videos/BENFORD.mp4" type="video/mp4">
</video>

### What Does Big Data Tell Us?

Big data gives us a better understanding of the world. It helps us see the mechanisms behind the patterns. Some might even ask, does everything follow patterns? Could what we think of as **free will** [[9]](#ref9) just be the result of not understanding these patterns?


## References

1. <a name="ref1"></a> **Gradient Descent** – [MIT article on Gradient Descent](https://ocw.mit.edu/courses/6-036-introduction-to-machine-learning-fall-2020/resources/gradient-descent/) and [Cauchy's contributions](https://mathshistory.st-andrews.ac.uk/Biographies/Cauchy/).

2. <a name="ref2"></a> **Classification and Regression Tree (CART)** – [CART by Leo Breiman](https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm) and [Overview of CART in machine learning](https://towardsdatascience.com/understanding-decision-trees-5d6a20952b47).

3. <a name="ref3"></a> **AdaBoost** – [AdaBoost original paper](https://cseweb.ucsd.edu/~yfreund/papers/Boosting.pdf) and [AdaBoost tutorial](https://towardsdatascience.com/understanding-adaboost-2f94f22d5bfe).

4. <a name="ref4"></a> **Viola-Jones Algorithm** – [Viola-Jones original paper](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf) and [Simplified explanation](https://towardsdatascience.com/face-detection-using-viola-jones-algorithm-842dc289c9d4).

5. <a name="ref5"></a> **Inductive Reasoning** – [Stanford article on inductive reasoning](https://plato.stanford.edu/entries/reasoning-inductive/) and [Explorable guide](https://explorable.com/inductive-reasoning).

6. <a name="ref6"></a> **Survivor Bias** – [Harvard Business Review on survivor bias](https://hbr.org/2016/04/survivorship-bias) and [Farnam Street guide](https://fs.blog/survivorship-bias/).

7. <a name="ref7"></a> **Problem of Induction** – [Stanford Encyclopedia of Philosophy on Problem of Induction](https://plato.stanford.edu/entries/induction-problem/) and [Britannica summary](https://www.britannica.com/topic/problem-of-induction).

8. <a name="ref8"></a> **Benford's Law** – [Benford’s Law scientific paper](https://link.springer.com/article/10.1007/BF02288367) and [Popular explanation](https://towardsdatascience.com/benfords-law-what-the-data-says-4d5ff18b2b2).

9. <a name="ref9"></a> **Free Will** – [Stanford article on free will](https://plato.stanford.edu/entries/freewill/) and [Discussion of determinism and free will](https://www.philosophybasics.com/branch_free_will.html).