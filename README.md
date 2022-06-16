This application is a simulation version of dribbble.
### This app will have the following features:

- The ability to create, edit, and destroy "shots" as well as like and unlike individual shots.
- User roles and authentication
- Drag and drop functionality
- Commenting functionality
- View counts/analytics
- A custom responsive shot grid UI using CSS Grid

### Getting started

```bash
$ git clone https://github.com/ngocban284/dribble_clone.git
```

### Open folder and get Bundle gem

```bash
$ bundle install
```

### Run dribble clone

```bash
$ rails s
```

#### The Gem List

gem list has grown build.

- [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) + [Mini Magick](https://github.com/minimagick/minimagick) - For image uploads and optimization
- [Devise](https://github.com/plataformatec/devise) - User authentication and roles
- [Guard](https://github.com/guard/guard) - Doing work to files as they change - A task runner of sorts
- [Guard Livereload](https://github.com/guard/guard-livereload) - Reloads the browser when files change combined with the Live Reload extension on your favorite browser.
- [Better Errors](https://github.com/charliesome/better_errors) - Displays better errors during development.
- [Simple Form](https://github.com/plataformatec/simple_form) - Simpler forms in Rails
- [Bulma Rails](https://github.com/joshuajansen/bulma-rails) - My favorite CSS framework as of late based on Flexbox.
- [Impressionist](https://github.com/charlotte-ruby/impressionist) - We use this to get view counts on shots
- [Gravatar Image Tag](https://github.com/mdeering/gravatar_image_tag) - Easy way to grab a user's gravatar image based on their account email
- [Acts As Votable](https://github.com/ryanto/acts_as_votable) - Like and unlike shots
