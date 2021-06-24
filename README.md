# Hydroponic Analytics & Automation :leafy_green:
## Joshua Park - Fullstack Developer, Software Engineer
### Gathering valuable insights and meaningful metrics from manually built hydroponic sources


### Overview :evergreen_tree:

- Initial set up of the hydroponic environment will be done and variables such as growth (visual), water temperature, pH, etc. will
be recorded and logged into a csv. 
- Upon one successful lifecycle of the hydroponic system, I will begin automation.
- Automation will include building the API, database, integrating custom ORM, etc. essentially using an API-first approach for the project itself.
- Upon completion of the API, database schema, and deployment onto Heroku/GitHub Pages, the project will be expanded and ML optimization techniques will be
applied in the interest of developing a model that will successfully reduce overhead related to water consumption, excess pH fluid, redundant heating, etc.

### Roadmap :rocket:

- July - September 2021: Testing of the hydroponic lifecycle and recording of data.
- October - December 2021: API-first development and deployment of the analytics application.
- January - March 22: Model optimization and hypothesis testing.

### Environment Variables :partly_sunny:

- Water volume (mL)
- Water temperature (celsius)
- Water pH (0-14)
- Container measurements (cm)
- Pot margin (cm)
- Weather (Rainy - Sunny)

### Plant Variables :seedling:

- Plant initial seed date and time (UTC)
- Data Log date and time (UTC)
- Plant type (species name)
- Plant growth (image)

### Technology & Tools :hammer_and_wrench:

Hardware
- Raspberry Pi 3.0

Software
- Python, NumPy, Pandas, MatPlotLib, Sklearn
- Django, REST API
- SQL, PostGresQL, Custom ORM
