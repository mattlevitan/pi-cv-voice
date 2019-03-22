# PiCV

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. In brief, we are setting up a Python virtual environment symbolically linked to our local instance of OpenCV. While installation of OpenCV is possible via `pip` it is not recommended. While more difficult and time consuming, building OpenCV from the source is the only way to guarantee the specific functionality demonstrated in the repository . See this page for [more information].

[more information]:https://www.pyimagesearch.com/2018/09/19/pip-install-opencv/

### Prerequisites

Given the complex dependencies required to smoothly
develop, train, test, and deploy this type of project across multiple platforms utilizing a virtual environment is all but imperative.

A Virtual Environment, `virtualenv`, is a self-contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages.

Proper configuration of the environment `env` ensures that our script can be run within a Python installation tailored to its needs, even if those requirements conflict with other scripts on the same platform.

![virtualenv diagram](https://cdn-images-1.medium.com/max/1600/1*0qVCJMcjaKZEcFEyHDj2yg.jpeg)


```
$ pip install virtualenv virtualenvwrapper
```
Give the terminal some shortcuts to our newly installed 'virtualenv' tools by updating ~/.bash_profile:
```
$ echo -e "\n# virtualenv and virtualenvwrapper" >> ~/.bash_profile
$ echo "export WORKON_HOME=$HOME/.virtualenvs" >> ~/.bash_profile
$ echo "export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3" >> ~/.bash_profile
$ echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bash_profile
```
Make the updated `~/.bash_profile` accessible with source:
```
source ~/.bash_profile
```
Now we can create a virtual environment called PiCV for this project:
```
$ mkvirtualenv PiCV -p python3
```



### Installing

A step by step series of examples that tell you how to get a development env running

Now lets configure our environment:


```
$ workon PiCV

```

Our virtualenv will appear to the left of the terminal prompt. Install numpy into the virtualenv
```
(PiCV) $ pip install numpy
```



```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built Wit~~****~~h

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
