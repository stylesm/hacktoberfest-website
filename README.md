# Hacktoberfest Website

This website is a community website for everyone to be able to contribute to. Tech should be accessible to everyone and everyone should be included in the making of it. This site aims to help break down barriers and allow people to contribute to a project with whatever skills they have.

## How to contribute

You can contribute through the browser or from your favourite terminal. Go the [contributing guide](/contributing.md) to learn how.

## Getting The Site Running Locally

The site is built using [Jekyll](https://jekyllrb.com), a Ruby application, or **Gem**.

As such, you'll need Ruby installed (version `2.3.3` or newer).

This guide does include steps for installing Ruby, and other Jekyll dependencies, but you can always refer to Jekyll's own guide [here](https://jekyllrb.com/docs/installation/).

### Installing Ruby and other dependencies

#### Windows (native)

To install Ruby on Windows, you can

- Use **Chocolatey** (a Windows Package Manager)
    1. [Get Chocolatey](https://chocolatey.org)
    1. Open Command Prompt or Powershell
    1. `> choco install ruby -y`
- Download it from [RubyInstaller](https://rubyinstaller.org)
    1. Download **Ruby + Devkit**
    1. Run the installer

#### Linux / Windows Subsystem for Linux

For Ubuntu / Debian-based distributions:

`$ sudo apt install ruby ruby-dev build-essential -y`

### Installing Jekyll

Now that Ruby is installed, installing Jekyll (and other gems) should be platform agnostic.

- :information_source: you may need to run commands prefixed by `sudo` on non-Windows environments.
- :information_source: You may need to logout / restart your terminal window to refresh paths.

Install **Jekyll** as follows, from a terminal window:

`gem install jekyll bundler`

### Install site dependencies

To ensure the site has any other gems it depends on installed, make sure you're in the project folder root and run:

`bundle update`

### Running the site

Now that everything is set up, you can run the site locally.

1. Make sure you're in the project folder root and run:
    - `jekyll serve`.
1. Leave that terminal window open
1. Head to your favourite web browser

The local site can be reached here: [http://localhost:4000/](http://localhost:4000/)

Well done, you're up and running! :tada:

### Instructions not clear?

Raise a pull request with your changes!