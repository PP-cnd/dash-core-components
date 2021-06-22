
[English follows]
Ceci est une copie avec modification des composantes principales du code Dash. Les modifications sont pour rencontrer les normes web du gouvernement du Canada. Dash est utilisé pour les micro application [Alouette](https://github.com/asc-csa/AlouetteApp) et [SCISAT](https://github.com/asc-csa/Scisat-App).
Pour en savoir plus, voir [le code original](https://github.com/plotly/dash-core-components).

[Le Français précède]
## Overview
This is a modified copy of the main components of the Dash code. The changes are to meet Government of Canada web standards. Dash code is used for the [Alouette](https://github.com/asc-csa/AlouetteApp) and [SCISAT](https://github.com/asc-csa/Scisat-App) microapplication.
For more information, see [the original code](https://github.com/plotly/dash-core-components).
### Installation/Build Guide
To install the library follow the following steps:

1. Clone or download the repository to a location of your choice.
2. In terminal, enter the repository
	 > cd {Path to your chosen install location}/dash-core-components
3. Create a python virtual environment, for this guide we will use `venv`
	1. Install 'venv' if you don't have it
		> sudo apt-get install python3-venv
	2. Create the environment
		> sudo python3 -m venv venv
4.  Enter the virtual environment
	> . venv/bin/activate
5. Install the development requirements for python
	> sudo pip install dash[dev,testing]
6. Install the nodejs packages and run the node build script
	> npm i --ignore-scripts && npm run build
7. You should get this as the finial line of output if the build was successful
	> ES-Check: there were no ES version matching errors!  🎉

Once you have built the elements the generated python packs will be in the `dash-core-components ` folder. You can copy this entire directory into the python environment used for CKAN. If prompted to replace the existing directory select or enter yes.
