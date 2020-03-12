# Combinatorial analysis of Baccarat

## Results

You can view the notebook directly on GitHub: [Combinatorial Analysis of Baccarat Odds](./baccarat_odds.ipynb)

**8 deck shoe:**

```
tie:    0.0951559680236402
banker: 0.458597422632763
player: 0.44624660934359683
```

**Infinite shoe:**

```
tie:    0.0954255699780124
banker: 0.458427917906012
player: 0.4461465121159756
```

Re-assuringly, the numbers match those on [Wizard Of Odds' baccarat
analysis](https://wizardofodds.com/games/baccarat/basics/).

## Install locally

Install Jupyter:

```bash
# install jupyter
pip install jupyter

# create virtualenv
pyenv virtualenv 3.7.0 baccarat-odds
pyenv local baccarat-odds
python -m ipykernel install --user --name=baccarat-odds
```

Start the Jupyter notebook:

```bash
jupyter notebook
```

Open `./baccarat_odds.ipynb`.
