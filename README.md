# Stable Diffusion Easylized

Want to try out Stable Diffusion but your computer is potato? Don't worry, because this notebook is here to help. "Borrow" Google's Colab servers and run it there.

___Note that this kind of use is currently restricted by Google / Kaggle if you don't have a paid plan. Although no bans are planned, your session may be terminated / deleted at any time.___
___For more information on this, please refer to [here](https://github.com/googlecolab/colabtools/issues/3591) and [here](https://twitter.com/thechrisperry/status/1649189902079381505).___

## Usage

### Google Colab

1. Open [this notebook on Google Colab](https://colab.research.google.com/github/UjhhgtgTeams/sd-easylized-colab/blob/master/Stable_Diffusion_Easylized_(Google_Colab_Version).ipynb).
2. Log in to your Google account.
3. Tweak the options.
4. Click `Runtime->Run All` in the menu bar.
5. (Grant the notebook your Google Drive's access if necessary.)
6. Wait until a link pops up in the code output and open it. (it will take a few ten seconds for the link to be reachable.)

### Kaggle

1. Go to [Kaggle](https://www.kaggle.com).
2. Log in to your Kaggle account.
3. Click `Create`.
4. In the menu bar, click `File->Import Notebook->GitHub`.
5. Fill in `UjhhgtgTeams/sd-easylized-colab` and `stable-diffusion-easylized-kaggle-version.ipynb`.
6. Click `Import`.
7. Tweak the options.
8. Click `Run All` in the menu bar.
9. Wait until a link pops up in the code output and open it. (it will take a few ten seconds for the link to be reachable.)

## Known Bugs

- It takes years for Colab to compile xformers (which is used to speed up image generation) so this procedure is currently disabled. \
Solution: You can install it from PyPi for now (available in the config).
- Kaggle will not enable GPUs, the Internet, package updates and data persistence for notebooks by default. \
Solution: In the bar on the right, look for `Notebook Options` and set the options as below:

```none
Accelerator: GPU T4 * 2
Language: Python
Persistence: Variables and Files
Environment: Always use latest environment
Internet: On
```

If you couldn't find the options to enable GPUs and the Internet, [verify your phone number](https://www.kaggle.com/settings/account).

## Contributing

If you would like to help me improve this project or fix bugs, feel free to raise an [issue](https://github.com/UjhhgtgTeams/sd-easylized-colab/issues) or make a [PR](https://github.com/UjhhgtgTeams/sd-easylized-colab/pulls). Thanks!
