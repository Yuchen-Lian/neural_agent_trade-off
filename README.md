# The Effect of Efficient Messaging and Input Variability on Neural-Agent Iterated Language Learning 

This repository contains the code used for the experiments in the paper: 

"[The Effect of Efficient Messaging and Input Variability on Neural-Agent Iterated Language Learning](http://arxiv.org/abs/2104.07637)"\
Yuchen Lian, Arianna Bisazza, Tessa Verhoef. To appear at EMNLP 2021. 

Natural languages display a trade-off among different strategies to convey syntactic structure, such as word order or inflection. This trade-off, however, has not appeared in recent simulations of iterated language learning with neural network agents ([Chaabouni et al., 2019b](https://arxiv.org/abs/1905.12330)). 

We re-evaluate this result in light of three factors that play an important role in comparable experiments from the Language Evolution field: 
* (i) speaker bias towards efficient messaging, 
* (ii) non systematic input languages,
* (iii) learning bottleneck. 

Our simulations show that neural agents mainly strive to maintain the utterance type distribution observed during learning, instead of developing a more efficient or systematic language.

Our code is a modified version of the project [BRICA: Bias Research In Communicating Agents](https://github.com/facebookresearch/brica) by the paper:

"[Word-order biases in deep-agent emergent communication](https://arxiv.org/abs/1905.12330)"\
Rahma Chaabouni, Eugene Kharitonov, Alessandro Lazaric, Emmanuel Dupoux, Marco Baroni, ACL 2019.


# Citation
If you find this code or the ideas in the paper useful in your research, please consider citing the papers:
```
@article{lian2021effect,
  title={The Effect of Efficient Messaging and Input Variability on Neural-Agent Iterated Language Learning},
  author={Lian, Yuchen and Bisazza, Arianna and Verhoef, Tessa},
  journal={arXiv preprint arXiv:2104.07637},
  year={2021}
}

@inproceedings{Chaabouni2019,
    title={Word-order biases in deep-agent emergent communication},
    author={Chaabouni, Rahma and Kharitonov, Eugene and Lazaric, Alessandro and Dupoux, Emmanuel and Baroni, Marco},
    booktitle={ACL},
    year={2019}
}
```