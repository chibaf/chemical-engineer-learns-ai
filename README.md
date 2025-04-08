# chemical-engineer-learns-ai
ブログ『化学系エンジニアがAIを学ぶ』のリポジトリ
https://schemer1341.hatenablog.com

## installation pytorch on apple silicon mac
<pre>
  brew update<br>
  brew upgrade<br>
  python3 -m pip install --upgrade pip<br>
  pip3 install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu<br>
</pre>

<pre>
  python3 dispenser_QL.py<br>
  python3 dispenser_DQN.py<br>
</pre>
<img width="1100" alt="image" src="https://github.com/user-attachments/assets/d7672ac8-9c04-47d3-a18e-f6d3c90b8532" />


## references

深層強化学習(Deep Q Network, DQN)の簡単な例 - 化学系エンジニアがAIを学ぶ
https://schemer1341.hatenablog.com/entry/2019/05/04/002300

chemical-engineer-learns-ai/20190504_simple_example_of_DQN at master · nakamura-13/chemical-engineer-learns-ai https://github.com/nakamura-13/chemical-engineer-learns-ai/tree/master/20190504_simple_example_of_DQN

Reinforcement Learning (DQN) Tutorial — PyTorch Tutorials 2.6.0+cu124 documentation
https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html
