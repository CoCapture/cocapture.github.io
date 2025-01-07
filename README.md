# CoCap: Coordinated motion Capture for multi-actor scenes in outdoor environments

This is the repository that contains the source code for our paper website [_CoCap: Coordinated motion Capture for multi-actor scenes in outdoor environments_](https://cocapture.github.io/).
It has been adapted from the [Nerfies website](https://nerfies.github.io).


---

#### Local Setup (Legacy)

Assuming you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed on your system (*hint: for ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv)*), and also [Python](https://www.python.org/) and [pip](https://pypi.org/project/pip/) (*hint: for ease of managing python packages, consider using a virtual environment, like [venv](https://docs.python.org/pt-br/3/library/venv.html) or [conda](https://docs.conda.io/en/latest/). If you will use only `jupyter`, you can use [pipx](https://pypa.github.io/pipx/)*).

```bash
$ cd cocapture.github.io
$ bundle install
# assuming pip is your Python package manager
$ pip install jupyter
$ bundle exec jekyll serve --lsi
```

---

Please feel free to cite our work if you find it useful:

```
@misc{rauniyar2024cocapcoordinatedmotioncapture,
      title={CoCap: Coordinated motion Capture for multi-actor scenes in outdoor environments}, 
      author={Aditya Rauniyar and Micah Corah and Sebastian Scherer},
      year={2024},
      eprint={2412.20695},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2412.20695}, 
}
```

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
