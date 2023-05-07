# ZimGPT Plugin

This plugin provides a convenient way to generate text using ChatGPT. 
With this plugin, you can select a piece of text and instruct ChatGPT 
to generate additional text based on the selected content. 
The generated text can be used for a variety of purposes, such as 
completing a thought, generating new ideas, or expanding on a concept.

## Usage

To use the plugin, simply select the desired text and press the keyboard shortcut
```alt+shift+i``` to open a dialog box to enter your instruction. The keyboard shortcut
can be customized to suit your preferences using Zim\'s key bindings preferences.

# Setup

1. Put the `zimgpt.py` into the plugins folder `~/.local/share/zim/plugins/` in Linux.
2. Run pip to install the openai dependency:
```commandline
pip3 install openai
```
3. Enable the plugin in Zim via `Edit > Preferences > Plugins` and check mark the `ZimGPT` plugin.
