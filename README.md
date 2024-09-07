This project is a quick sample project that demonstrates the automation of the build, test, and deployment process of an application to a staging environment on push to the main branch. 

To adequately demonstrate the CI/CD pipeline, I will create a simple Python project with minimal code and then integrate it into GitHub Actions.

# Project File

I create a basic python application that I will use in the pipeline, you can find it [here](./app.py)

# Project Requirements

A typical project would have dependencies and in a python project they are usually defined in the `requirements.txt` file. 

This file will list any dependencies my project needs (in this case, none are required, but I added pytest for testing). Find it [here](./requirements.txt)

# Unit Test

I added a basic test file `test_app.py` to test the function in app.py. Find the unit test [here](./test_app.py).

# Pipeline

In my pip