import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
gender=np.random.randint(18,60,size=90)
plt.hist(gender,bins=9,edgecolor="blue")
plt.xlabel("Gender")
plt.ylabel("Frequency")
plt.title("Gender Distribution")
plt.show()
