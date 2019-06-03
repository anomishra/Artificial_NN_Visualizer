# Artificial_NN_Visualizer
Repo for visualizing the neural network in the model
<br>
Steps:<br>
1. Install these libraries using pip<br>
   pip install keras<br>
   pip install ann_visualizer<br>
   pip install graphviz<br>
2. In your .py file just add these 2 lines: <br>
   from ann_visualizer.visualize import ann_viz;<br>
   ann_viz(model, view=True, filename="network.gv", title="MyNN graph")<br>
   <br>
   model - The Keras Sequential model<br>
   view - If True, it opens the graph preview after executed<br>
   filename - Where to save the graph. (.gv file format)<br>
   title - A title for the grap<br>
   <br>
You will get your NN structure visuals.   <br><br>
For more, kindly visit this official github link: https://github.com/Prodicode/ann-visualizer
   
   
