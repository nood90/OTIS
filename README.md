# OTIS

This repository is used to host a Pages site, see [otis.leedsraspjam.co.uk](https://otis.leedsraspjam.co.uk) for the finished docs.

Built using [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html) + [Sphinx](https://www.sphinx-doc.org/en/master/). Make sure to move output from build/html to root before committing.
# Useful Files
 * [LICENSE.MD](LICENSE.MD) - Contains licensing info for this repo
 * [README.md](README.md) - This file
# Building Locally
1) First make sure you have ```sphinx```, ```sphinx-rtd-theme``` and ```sphinxembeddedvideos``` installed. If you haven't installed these you can run ```pip3 install [PACKAGE_NAME]```
2) Next navigate to the [sphinx-dir](sphinx-dir) and run ```make html```. This will build the site and put the finished HTML files in ```build/html```
3) You can then move the HTML files to the root of your web server
# Editing the files
 * All the source is located in [sphinx-dir/source](sphinx-dir/source), the index file is [sphinx-dir/source/index.rst](sphinx-dir/source/index.rst) and each step is labeled ```s[STEPNUM].rst```. The troubleshooting ages have a ```t``` after the number to signify it is a troubleshooting file
 * The project name, copyright info and author can be changed in [sphinx-dir/source/conf.py](sphinx-dir/source/conf.py) along with any new extensions that are needed.
