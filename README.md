ABC
======================================
ABC (AI Boosted Compiler Framework With Selecting Function-Level Optimizations) is the implementation of Chang, Jia-Rung's master thesis in [NCTU](http://www.nctu.edu.tw/).

To the best of our knowledges, ABC makes the following contributions:
* Exploring the possibilities of function-level optimization on modern compiler framework
and architectures.
* ABC is the first instrumentation based feature extraction for auto-tuning compiler framework
in public.
* ABC is the first compiler framework that adopt the reinforcement learning to schedule
optimizations
* During our experiments, we found out that the same combination (set) of compiler optimizations
may affect the same instruction set architecture from the same company with
different generations with evidence.
* Environment in ABC provides an OpenAI Gym compatible interface for researchers to
develop reinforcement learning algorithm for ABC framework easily.
* As far as we knew, ABC is the first open sourced compiler framework targeting function-level
optimization.

Details
-----------------------------------
* Design Philosophy
  * Please refer to Jia-Rung's thesis.

* Installation
  * There are several steps to setup, please refer to [ThesisTools](https://github.com/JaredCJR/ThesisTools).
  * We do not provide the trained model in the repo, please train it by yourself.
    * According the thesis, every CPU will need its own customized model.

About Author
===================================
* Taiwanese
* [LinkedIn](https://www.linkedin.com/in/jaredcjr/)
* email: `jaredcjr.tw@gamil.com`


License
====================================
Refer to [LICENSE](./LICENSE)
