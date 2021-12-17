# covid-19_dashboard
ntroduction:
this program generates a covid dashboard that allows the user to see the top news articles aswell as view covid data. the covid data includes statistics such as the local and national 7 day infection rate hospital cases and cumulative deaths. the program can be modifed by the user to best suit thier needs. They are able to change the location of the local data by altering the config file slightly. the user is also able to deleate news articles aswell as schedule and remove updates.

prerequisites:
in order for the program to work you must install the following modules

flask
pytest
requests
uk-covid19 When the project is run, it will open the dash board. The user needs to enter http://127.0.0.1:5000/ in thier browser for the dash board to appear.
installation:
in order for the program to work you must install some modules.you do this by typing the following commands into the command prompt

pip install uk-covid19
pip install requests
pip install flask
pip install pytest
getting started tutorial:
firstly the user must have all the modules above installed. if the user wishes to change the default geographical location of the data from 'exeter' they can do this by altering the config.json file. they would need to change the values of local_location and location_type to other valid values in the source code.

in order to run the program the user must first type the following comand into the comand line

python -m main_covid_19
they then should open http://127.0.0.1:5000/ in a web browser. if all is working correctly the user will no be able to see and interact with the dashboard the user can remove articles by clicking the x symbol on the corrosponding widget. the user can schedule updates by filling in the time, naming the update and selecting the peramiters for the update using the provided tick boxes. the user can remove updates by clicking the x symbol on the corrosponding widget.

testing:
enter the following into the comand line

pytest
developers documentation:
documentation can be found under 'docs/build/html'

details:
Author - Dora Napier
index.html file Author - Matt Collison
source code can be found here- https://github.com/Dora-Napier/covid-19_dashboard
license- MIT
