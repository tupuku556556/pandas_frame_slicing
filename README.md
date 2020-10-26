# pandas_frame_slicing
#it is just an easy way to slide a data frame using iloc
import pandas as pd
d = {'col1': [11,12,13,14,15,16], 'col2': [21,22,23,24,25,26],"col3":[31,32,33,34,35,36]}
df = pd.DataFrame(data=d)
df

z=df.iloc[0:3,0:2]
z
