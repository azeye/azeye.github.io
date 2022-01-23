## EasyRL
Implementations of basic RL algorithms with minimal lines of codes! (PyTorch based)

Each algorithm is complete within a single file.

Length of each file is up to 100~150 lines of codes.

Every algorithm can be trained within 30 seconds, even without GPU.

Envs are fixed to "CartPole-v1". You can just focus on the implementations.

# Algorithms
REINFORCE (67 lines)

Vanilla Actor-Critic (98 lines)

DQN (112 lines, including replay memory and target network)

PPO (119 lines, including GAE)

DDPG (145 lines, including OU noise and soft target update)

A3C (129 lines)

ACER (149 lines)

A2C (188 lines)

SAC (171 lines) added!!

PPO-Continuous (161 lines) added!!

Vtrace (137 lines) added!!

# Dependencies

PyTorch

OpenAI GYM
# Usage
```markdown
# Works only with Python 3.
# e.g.
python3 REINFORCE.py
python3 actor_critic.py
python3 dqn.py
python3 ppo.py
python3 ddpg.py
python3 a3c.py
python3 a2c.py
python3 acer.py
python3 sac.py
```



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/azeye/azeye.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/azeye/azeye.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
