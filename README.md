# Artificial_NN_Visualizer
Repo for visualizing the neural network in the model
<br>
Steps:
1. Install these libraries using pip
   pip3 install keras
   pip3 install ann_visualizer
   pip install graphviz
2. In your .py file just add these 2 lines: 
   from ann_visualizer.visualize import ann_viz;
   ann_viz(model, view=True, filename="network.gv", title="MyNN graph")
You will get your NN structure visuals.   
For more, kindly visit this official github link: https://github.com/Prodicode/ann-visualizer
   
   
