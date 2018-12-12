# Laravel API

```

Laravel 5.7 API uses the API resources, This is an API for an article CRUD app. 
Based on the one from Traversy Media.

https://www.youtube.com/watch?v=4pc6cgisbKE 

```

# Quick start

```

# Install Dependencies
composer install

# Run migrations with fake data
php artisan migrate --seed

# Add virutal host if needed

# if you get the encyption key error run
php artisan key:generate

```


# Endpoints

```
# List articles
GET / api/articles

# List single article
GET article/{id}

# Create new article
POST article // Needs a title and body

# Update article
PUT article  // Needs a id and title and body

# Delete article
DELETE article/{id}

```
