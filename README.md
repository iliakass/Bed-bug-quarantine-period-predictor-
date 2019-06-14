# data-app

Team: Ilia Kassianenko, Luigi Clerici

Model Source : Regression model.ipynb

Model Output : Random_Forest_10.pkl

Github Directory : https://github.com/Clercy/webtest

Website Access : https://houseproj.herokuapp.com/

Files required to run website: app.py, index.html, results.html, Random_Forest_10.pkl

The data app consists of the Regression model.ipynb notebook which generates the model Random_Forest_10.pkl used in our application and located in /model.

    pickle.dump(model, open('Random_Forest_10.pkl','wb'))

Our application templates can be found in /templates and are named results.html and index.html.

The application is executed by running app.py.
