# Simple Built‑in ```venv``` (if you already have Python3)

1. Ensure you have Python 3 installed (either system or Homebrew).
2. Create a virtual environment:

bash
python3 -m venv myenv

3. Activate it:

bash
source myenv/bin/activate

4. Work inside the environment:

bash
python --version   # shows the venv Python
pip install your-packages

5. To deactivate:

bash
deactivate
