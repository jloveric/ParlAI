## Some notes on running with pipenv (targeting blender)

I've added all dependencies to the pipenv file including torch so that the installation
is self contained.  Clone the git repository, run

```bash
pipenv install
```

to download the 3B parameter model

```bash
python -m parlai.scripts.safe_interactive -t blended_skill_talk -mf zoo:blender/blender_90M/model
```

