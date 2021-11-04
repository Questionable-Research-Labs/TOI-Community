![Logo](https://raw.githubusercontent.com/Questionable-Research-Labs/Govhack-2021/main/static/icons/icon%4032.png)
# TOI-Community
This is an override document for [Times of Interest (TOI)](https://toi.qrl.nz). This allows the inclusion of community pins.

## To Contribute:
Edit the `community.geojson`, and under the `features` property, add your own feature (you may need to look at the file history to get an idea of the info to include).

It is recommend to use `pre-commit` to validate your changes. To do so, install it `pip install -r requirements.txt`, and install it into git with `pre-commit install`. Now when you commit your changes it will automatically validate them, and stop you from committing if the changes would definitely break production.