---
layout: default
---

**PipeCash** is an automation framework designed specifically to handle automation for **Bitcoin** and other types of money.

**Bitcoin** is the future of money - a digital peer-to-peer cash system that is revolutionizing not only payments, but the internet itself. Read the [Bitcoin Whitepaper](/assets/pdf/bitcoin.pdf).

**PipeCash** lets you easily tap into the enormous potential of the blockchain.

![BSV & PipeCash](/assets/images/bsv-pipecash-1.png)


# AUTOMATE WITH EASE
> BECAUSE TIME IS PRECIOUS

PipeCash will not waste your time.
Automate your Bitcoin related tasks without writing any code.
PipeCash will run locally on your machine, giving you full control of your private keys and passwords.

**Money automation has never been this easy!**


#### Easy to Deploy
> A PipeCash configuration is just a text file. Deployment of a PipeCash node can be as simple as pressing a button.

#### Easy to Configure
> A visual configuration tool makes it possible for non-programmers to design and run their own automated system.

#### Highly Customizable
> Different plugins extend the system to enable it to handle all types of events and actions. It is easy to extend the system with new plugins.

#### A new Perspective
> With Bitcoin as programmable money, you have the ability to fully control your funds. The sky is the limit.



# Quick Start

Dowlnload PipeCash and the default collection of agents and wallets:

```shell
pip install --upgrade pipecash pipecashagents pipecashwallets
```

Run a scenario:

```shell
pipecash -s /path/to/scenario.json
```

If the scenario needs secret variables, generate them:

```shell
pipecash -s /path/to/scenario.json --createSecretsFile > secrets.json
```

Once the file is generated, open it and fill the secret variables. To run the scenario together with the secrets, use:

```shell
pipecash -s /path/to/scenario.json --secretsPath /path/to/secrets.json
```



# License

PipeCash is not friendly towards all cryptocurrencies.
While it is designed for integrations with Bitcoin, the regular PipeCash license strictly forbids any integration with other cryptocurrencies.

PipeCash will only integrate with **Bitcoin** and **Bitcoin SV**.

PipeCash will always respect both **proof of work** and the **original design** of Bitcoin.
For more information [read the license](https://github.com/Pipe-Cash/pipecash/blob/master/LICENSE).

# Subscribe

{%- include subscribe-form.html -%}