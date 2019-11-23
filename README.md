#Libraries used in the project:

import matplotlib.pyplot as plt<br>
<br>import matplotlib.axes as axes
%matplotlib inline<br>
import numpy as np<br>

from qiskit import BasicAer<br>
from qiskit.tools.visualization import plot_histogram<br>
from qiskit.aqua import run_algorithm<br>
from qiskit.aqua.input import EnergyInput<br>
from qiskit.aqua.algorithms import VQE, ExactEigensolver, QAOA<br>
from qiskit.aqua.components.optimizers import SPSA<br>
from qiskit.aqua.components.variational_forms import RY<br>
from qiskit.aqua import QuantumInstance<br>
from docplex.mp.model import Model<br>
from qiskit.aqua.translators.ising import docplex<br>
from pyqubo import Binary, solve_ising,Constraint<br>


import numpy as np<br>


# setup aqua logging
import logging<br>
from qiskit.aqua import set_qiskit_aqua_logging<br>
import time<br>
import matplotlib.pyplot as plt<br>
