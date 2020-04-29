``` bash
# clone the repo
$ git clone https://github.com/jithumajinu/Bootstrap4sass.git

# go into app's directory
$ cd Bootstrap4sass

# install app's dependencies
$ npm install

# install sass
$ sudo gem install sass

# compile sass to css 
$ sass main.scss main.css

```


Help tips

``` bash
https://getbootstrap.com/docs/4.0/getting-started/theming/


Importing
In your custom.scss, you’ll import Bootstrap’s source Sass files. You have two options: include all of Bootstrap, or pick the parts you need. We encourage the latter, though be aware there are some requirements and dependencies across our components. You also will need to include some JavaScript for our plugins.

Copy
// Custom.scss
// Option A: Include all of Bootstrap

@import "node_modules/bootstrap/scss/bootstrap";
Copy
// Custom.scss
// Option B: Include parts of Bootstrap

// Required
@import "node_modules/bootstrap/scss/functions";
@import "node_modules/bootstrap/scss/variables";
@import "node_modules/bootstrap/scss/mixins";

// Optional
@import "node_modules/bootstrap/scss/reboot";
@import "node_modules/bootstrap/scss/type";
@import "node_modules/bootstrap/scss/images";
@import "node_modules/bootstrap/scss/code";
@import "node_modules/bootstrap/scss/grid";
With that setup in place, you can begin to modify any of the Sass variables and maps in your custom.scss. You can also start to add parts of Bootstrap under the // Optional section as needed. We suggest using the full import stack from our bootstrap.scss file as your starting point.


https://getbootstrap.com/docs/4.0/components/forms/

```

source : https://getbootstrap.com/





