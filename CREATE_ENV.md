# How to create a pip env

First, as we are using Anaconda, install pip.

Create your virtual environment **env** (this is just the name we are using as an example) using the command line. Indicating your desired python version, here I use python 3.6 (but use the one you need/prefer)

```bash
conda create --name env python=3.6
```

Activate your new virtual environment

```bash
source activate env # activate your environment.
```

If it worked, your command line should look like:

```bash
(env) -bash-4.2$
```