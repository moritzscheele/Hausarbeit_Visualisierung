# Hausarbeit_Visualisierung

##Aufsetzen Dashboard Server

1. ssh -i ~/.ssh/id_rsa moritz@mail.tutorialfactory.org -p 553
2. Move to the right folder
3. git clone https://github.com/moritzscheele/Hausarbeit_Visualisierung
4. Create Environment: python 3 -m venv ./
5. Aktivierte das Environment: source bin/activate
6. Installation von hvplot und jupyterlab (JLab wird vielleicht nicht benötigt):pip3 install hvplot jupyterlab
7. Panel muss leider global wegen Bug installiert werden:
    1. deactivate
    2. pip3 install panel
8. Probieren: panel serve Interactive_dashboard-ms.ipynb
9. jupyter lab
