# data-opener-hackathon
Building a specific how-to guide for opening datasets

Check the [wiki](https://github.com/NewportDataProject/data-opener-hackathon/wiki) for hackathon details.

## Directory Structure
The directory structure is setup for Jekyll to be hosted with GitHub Pages:  

### `/_includes` 
This directory is for components, like navbars and javascript.  

### `/_layouts` 
This directory is for basic layouts to create the pages.  

### `/_steps` 
This directory is a [collection](http://jekyllrb.com/docs/collections/) of files describing steps in the process. The steps should be in individual files with defined metadata to allow for easy rendering. This will make it easy to update the process.
  


## Preview locally with Jekyll
First, install Jekyll.  If you have windows, [these](https://labs.sverrirs.com/jekyll/) are good step by step instructions to get started. For other operating systems, follow [these](http://jekyllrb.com/docs/installation/) instructions.

Navigate to this repository on your machine in the console, and run `jekyll serve -w`. Open up a browser and go to `localhost:4000`, and you should see the site.