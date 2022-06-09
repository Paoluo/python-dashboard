![](https://raw.githubusercontent.com/pplonski/python-dashboard/main/media/dashboard.jpg)

# Dashboard in Python 🐍

This project was created in Python. The dashboard was built in Jupyter Notebook. The data is fetched online from:
- Yahoo Finance service,
- Binance REST API,
- Open Meteo REST API.

The website and dashboard are served with <a href="https://github.com/mljar/mercuruy" target="_blank">Mercury</a> framework. It turns Jupyter Notebook to web application. It adds interactive widgets to notbook based on the YAML header (from the first raw cell in the notebook). 

The code for this website: [github.com/pplonski/python-dashboard](https://github.com/pplonski/python-dashboard).

The dashboard is available online at: [python-dashboard.mljar.com](https://python-dashboard.mljar.com).

Article: [Build dashboard in Python with automatic updates and email notifications](https://mljar.com/blog/python-dashboard/).

### Schedule ⏰

The dashboard is executed daily from Monday to Friday at 8.30 AM. The scheduled execution is controlled by `Mercury`. There is `schedule` parameter in the YAML with crontab string.

### Email notification 📨

The dashboard can send an email notification if conditions on monitored values are met. The email sending is written with `smtplib` library.


## Dashboards 📊

![](https://raw.githubusercontent.com/pplonski/python-dashboard/main/media/python-dashboard-running.png)

![](https://raw.githubusercontent.com/pplonski/python-dashboard/main/media/python-dashboard-scheduled.png)
