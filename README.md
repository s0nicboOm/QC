#Libraries used in the project:

import matplotlib.pyplot as plt<br>
import matplotlib.axes as axes
%matplotlib inline
import numpy as np

from qiskit import BasicAer
from qiskit.tools.visualization import plot_histogram
from qiskit.aqua import run_algorithm
from qiskit.aqua.input import EnergyInput
from qiskit.aqua.algorithms import VQE, ExactEigensolver, QAOA
from qiskit.aqua.components.optimizers import SPSA
from qiskit.aqua.components.variational_forms import RY
from qiskit.aqua import QuantumInstance
from docplex.mp.model import Model
from qiskit.aqua.translators.ising import docplex
from pyqubo import Binary, solve_ising,Constraint


import numpy as np


# setup aqua logging
import logging
from qiskit.aqua import set_qiskit_aqua_logging
import time
import matplotlib.pyplot as plt
