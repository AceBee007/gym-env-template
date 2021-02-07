# gym-env-template
A template of OpenAI gym enviroment

[Read about OpenAI environment](https://github.com/openai/gym/blob/master/docs/environments.md)

Read about [OpenAI: Creating your own Environment](https://github.com/openai/gym/blob/master/docs/creating-environments.md)

## how to use
run the generate script
```bash
mkdir my_gym_env && cd my_gym_env
curl -o tmp.py -fsSL https://raw.githubusercontent.com/AceBee007/gym-env-template/main/generate_env.py && python tmp.py && rm tmp.py

```

### notes
You will be asked about
- `env's name`, like `pacman`
  - module name of your env
- `stage number of your env`, (1,2,3,4...)
  - how many number of your env
- `stage name`
  - stage name, like `pacman_no_skip_frame` or `pacman_normal`
- need `setup.py`?
  - if your choose `y`, you can install your env using this `setup.py`
