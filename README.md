# yana
DementiaHack 2015 Yana Team


# Setup

Under yana
```
bundle install
rake db:create
rake db:migrate
```

Under yana/tagServices
```
npm install
```

# Run
There are two servers
- Tag service for contextual tagging
- Rails application sever

Tag server
```
cd yana/tagService
node server.js
```

Rails server
```
cd yana
rails s
```
