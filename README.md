# cloud_weather_predictions
MSDS 434 Fall 2022

## Setup
* `make setup` will create a new Python virtual environment in the ~.venv/cloud_weather_predictions location. As mentioned in Pragmatic AI: An Introduction to Cloud-Based Machine 
Learning, First Edition by Noah Gift, "it is generally a good idea to create an alias that will source the environment and cd into it all at once", as below 

With Zsh, edit the `~/.zshrc` file, adding (for example):
```
alias cwp="cd ~/cloud_weather_predictions/cloud_weather_predictions && source ~/.venv/cloud_weather_predictions/bin/activate"
```
Don't forget to restart your shell or run the command `source ~/.zshrc` so you can use this alias
You can leave the venv session with the command `deactivate`
