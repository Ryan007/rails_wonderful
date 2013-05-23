## need gems in your Gemfile

gem 'simple_form'
gem 'wice_grid'

* test in Rails 3.13

* to look nicer,install bootstrap
...

## install

    $ cd ~/Downloads
    $ git clone git://github.com/huacnlee/rails_templates.git
    $ cp -R rails_templates/* ~/you_rails_project/lib/
    
## usage:

modified by your favour,then Rails scaffold generator help you generate

    $ rails g scaffold Post title:string category_id:integer body:text
    $ rails g scaffold admin/posts title:string category_id:integer body:text
    $ rails g scaffold_controller admin/posts title:string category_id:integer body:text

