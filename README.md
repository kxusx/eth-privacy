
In this work we assess the privacy shortcomings of Ethereum's account-based model. We collect and analyze a wide source of Etherum related data, including [Ethereum name service](https://ens.domains/), [Etherscan](https://etherscan.io/) blockchain explorer, [Tornado Cash](https://tornado.cash/) mixer contracts, and Twitter. By learning Ethereum address representations we deanonymize accounts that belong to the same user. 


# Installation

After cloning the repository you can install the **ethprivacy** package with `pip`.

```bash
git clone https://github.com/ferencberes/ethereum-privacy.git
cd ethereum-privacy
python setup.py install
pip install karateclub
```

# Data

Use this [link](https://dms.sztaki.hu/~fberes/eth/eth_privacy_2021-06-18.zip).


# Experiments

- By running the following script you can check your setup.
```bash
bash -e run_tests.sh
```