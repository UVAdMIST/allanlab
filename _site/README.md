# dMIST Research Group Website

This is the website of the Data-driven Management for Interdependent Stormwater and Transportation systems (dMIST) research group.

If you would like to edit this website, please make sure that you install Ruby v 1.4.0 (you won't be able to preview the website with a newer version).

This website is powered by Jekyll and some Bootstrap, Bootwatch. It was forked from the <a herf="http://www.allanlab.org/"> Allen Lab at Leiden University</a> website which provides a copy that can be modified for your own purpose.

To build this webpage, follow these steps.

Install Jekyll. https://jekyllrb.com/docs/installation/

Clone repository.

In a terminal, type the following command to update bundler (first time only)

bundle update

Change to the website's root directory
cd {INSERT DIRECTORY}/group_website

In a terminal, type the following command to serve the site
bundle exec jekyll serve

This generates the site folder. Go to http://localhost:4000 to see the site

Edit files in the data, includes, layouts, and pages folders to edit the content and look of the site. Do not directly edit files in the site folder.

After making changes, to files in these folders, simple refresh the website to see the changes.

To deploy the site, first stop serving the website and then build the website using the following commands.

ctrl-c (stops serving)

bundle exec jekyll build

Copy the contents of the site folder to the website hosting the site.

Copyright Jon Goodall 2021. Code released under the MIT License.
