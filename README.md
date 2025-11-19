# pwd
The following packages needs to be imported

import os
import numpy as np
import pandas as pd
import fveqc as fv
import bvnweq as bv
import cmp as cm
import mcpldtmncs as cs

#file path goes here
fep = ''
ep = pd.read_csv(fep)
ep.columns = ep.columns.str.lower()

ep['paid'] = ep['mul'] + ep['fav']
ep['paid'].value_counts()



