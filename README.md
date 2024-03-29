Group 11:
- [Bjørn Egil Øygarden](https://github.com/oygarden)
- [Bjørn-Sigurd Sælevik Fjose](https://github.com/TrainBear)

# Location-based wallpaper generation (DAT158 ML Assignment #2: Generative AI-powered application)

This is a script that generates a wallpaper based on your location, time, and weather.

Demo video can be found [here](https://www.youtube.com/watch?v=mz4rmKMZqrA).

Written report can be found [here](Report.pdf)

## Usage

To use the script you need to register an account with OpenAI and generate an API key. 

The openai package uses the environment variable `OPENAI_API_KEY` to authenticate requests (unless you set it manually). See the [OpenAI API documentation](https://platform.openai.com/docs/quickstart/account-setup) for more information.

To run the application, you can either run the app.py script in your IDE, or you can download the exectuable. This should give you a simple user interface where you can add some preferences for the generator to take into consideration. This is also where you add your `OPENAI_API_KEY`.
