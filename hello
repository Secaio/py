import calmap
import pandas as pd
import numpy as np

# Create a random time series data
data = pd.Series(np.random.randint(0, 10, size=365), index=pd.date_range('1/1/2023', periods=365))

# Create the calendar heatmap
calmap.calendarplot(data, fig_kws={'dpi': 100}, yearlabel_kws={'color': 'black', 'fontsize': 14}, monthlabel_kws={'color': 'black', 'fontsize': 10}, daylabels_kws={'color': 'black', 'fontsize': 8}, cmap='YlGn', fillcolor='grey', linewidth=0.5, linecolor='grey')

# Add title and labels
plt.title('RC Contribution Chart - 2023', fontsize=16)
plt.xlabel('Day of the Week', fontsize=12)
plt.ylabel('Week Number', fontsize=12)

# Show the plot
plt.show()
