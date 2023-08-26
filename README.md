# PhotovoltaicModuleDiagnosis

As environmental awareness has been culminating for the past few decades, people have been switching towards renewable sources of energy such as solar energy, wind energy, and hydropower. Among these, solar energy seems to be largely used due to the availability of solar energy in abundance, which in turn, has led to a mass increase in the number of solar power plants. Nevertheless, these solar panels are left unattended due to difficulty in the maintenance of solar power plants in large areas and the manual work required. It is important to find and replace these defective panels in time before any severe event occurs. Detecting hotspots, cracking and various other malfunctions in the photovoltaic cell can lead to an increase in the life of the solar panels by 5-10 years. In this project, we propose a compact intelligent photovoltaic module diagnosis system based on a Deep Learning model that uses multilayer perceptron (MLP) to accurately identify and classify the faults in the photovoltaic module. We have achieved this by tweaking the VGG19 convolutional network architecture to detect three kinds of malfunctions: Hotspots, Cracking, Diode, and No-Anomaly for panels that are in good condition by using 2310 images for training, 665 for validation, and, 665 for testing. By using accuracy-score from sklearn.metrics, the model’s accuracy was estimated to be above 90 percent for classifying photovoltaic modules.

a) Cracking: When microcracks form in a solar panel, the affected solar cells will have trouble conducting electric currents, which lead to poor energy production and hot spots.<br>
b) PID: PID (Potential Induced Degradation) is a condition that may occur a few years after installation. It can be caused by humidity, heat, or voltage. The temperature of the malfunctioned cell is 
also higher than others and results in a larger and extremely hot area.<br>
c) Hot spot: A hot spot is the most common PV module defect. Hot spot results in a higher temperature and may be caused by many reasons, including short circuits, overhead objects, surface 
fouling, cell material defects, cell cracks, broken glass, and so on.


