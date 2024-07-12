# How to build 

./scripts/install.sh

cd packages/jupyter-ai-magics
pip install -e . -vvv

cd packages/jupyter-ai
pip install -e . -vvv

## Copying generated artifacts

In the ./dist directories for both the packages, find the following
jupyter_ai-2.18.1-py3-none-any.whl
jupyter_ai-2.18.1.tar.gz

jupyter_ai_magics-2.18.1-py3-none-any.whl 
jupyter_ai_magics-2.18.1.tar.gz

## Can be pip intalled in docker images
pip install jupyter_ai_magics-2.18.1-py3-none-any.whl 
pip install jupyter_ai-2.18.1-py3-none-any.whl
