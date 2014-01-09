
# Demo Rails App

Demo Rails App from [railstutorial.org](http://www.railstutorial.org)  

### Models:
* Users  
* Microposts

### Scaffolds:  
$ rails generate scaffold User name:string email:string  
$ bundle exec rake db:migrate

### git commands:
$ git commit -a -m "Improve the README file"  
`Add all modifications and commit`  

$ git push  
`Push changes to github origin master`

### notes:
## Model:
* Length validation: edit app/models/model_name.rb, and add:  
`validates :content, length: { maximum: 140 }`  
* has_many and belongs_to: edit app/models/model_name.rb, and add:
`has_many :microposts`
Edit 2nd model and add:
`belongs_to : user`

## Heroku:
[enigmatic-anchorage-4562.git](enigmatic-anchorage-4562.git)
