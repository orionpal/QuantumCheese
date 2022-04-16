OBJECTIVE:
A mouse is to find out where the cheese is placed in some maze while not giving in to the temptation of eating it.

EXPLANATION:
In the quantum minesweeper problem (repo found here: https://github.com/maria-violaris/quantum-paradoxes/blob/main/quantum-minesweeper-code.ipynb) we learn of how to detect bombs while having a low probability of "exploding" them.
I'm substituting the "explosion" condition of a qubit flipping to just be "Eating", and then I'm using the same photon that we're splitting to check multiple paths (representing our maze). This is meant to be a proof of concept that if we setup our problem in an intelligent way we should be able to find something in a maze without actually disturbing what it is we're trying to find.


SETUP:

virtual environment folder not included in repo but is recommended when running the notebook. To create virtual environment locally run the following:
python -m venv qisenv
source qisenv/Scripts/activate
pip install -r requirements.txt

"source qisenv/Scripts/activate" activates the virtual environment when using a bash shell, you may need another line for other consoles

then running the jupyter notebook should be sufficient