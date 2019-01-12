# ros_python_pkg_template

A [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) template to create a ROS package with the [recommended](http://wiki.ros.org/PyStyleGuide) python style for ROS.

The process of setting up a initial package strucuture in ROS that is also able to be build as a package can be hard for a beginner. To simplify this process and also provide a more pythonic interface for ROS this project provides a cookiecutter template to create a ROS package with the [recommended](http://wiki.ros.org/PyStyleGuide) python style.

## Usage
You need [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) to generate the template on your local machine. You can install it via pip for example:

```sh
pip install cookiecutter
```

After you installed cookiecutter, simply execute the following command in the folder where you want to generate your project:

```sh
cookiecutter https://github.com/sbhle/ros_python_pkg_template
```

The final step is to enter your project specifics and your package gets generated automatically.
