# Job_Satissfaction_Analysis
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

import warnings
warnings.filterwarnings("ignore")
How Happy are you in your Current Position with the following?

(Salary): How happy are you with your salary in your current position?

(Work/Life Balance): How satisfied are you with your work-life balance in your current position?

(Coworkers): How do you feel about your coworkers in your current role?

(Management): How happy are you with the management in your current position?

(Upward Mobility): Are you satisfied with the upward mobility opportunities in your current position?

(Learning New Things): How satisfied are you with your opportunities to learn new things in your role?

# Reading in the saved data
file_path = '/content/drive/MyDrive/biweekly assignment/Project_data.xlsx'
df = pd.read_excel(file_path)

# Display the first few rows to confirm successful reading
df.head()
df.isna().sum()
