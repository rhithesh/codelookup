
On MacOS to set an alias


```bash
alias study="open -a 'Brave Browser' 'https://chat.openai.com' & open ~/Downloads/rnn_unit5.pdf"

How to publish a pip package

``# Remove old build files
rm -rf dist build *.egg-info

# Build the package
python -m build
# The username is always __token__ when using an API key
TWINE_USERNAME=__token__ TWINE_PASSWORD=pypi-YOUR_TOKEN_HERE twine upload dist/*
``
