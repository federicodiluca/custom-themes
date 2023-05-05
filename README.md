# Oh My Posh - Custom Themes

Here's my custom themes for [oh-my-posh](https://ohmyposh.dev/).

[fedl95 theme](fdl95.omp.json):

![fedl95-theme](https://user-images.githubusercontent.com/68862675/236401698-230b598b-ea2b-4607-8bbe-3e5112fa4eaa.png)

## How to
Just clone this repo inside `<YOUR-POSH-PATH>\themes`.

Then:

```bash
notepad $PROFILE
```

Adjust the first line as follow:

```bash
oh-my-posh init pwsh --config '<YOUR-POSH-PATH>\themes\custom-themes\fdl95.omp.json' | Invoke-Expression
```
