# Notice
Base repository is not maintained anymore. This fork is merely created to keep using Prismic for Laravel 9 projects.

It's not using the official [prismicio/php-kit](https://github.com/prismicio/php-kit/) package as this is the actual blocker of upgrading due to it's Guzzle and PHP version dependencies (at the time of writing). Instead a fork of the SDK is used, created to use the Prismic API with recent PHP frameworks: [elgentos/prismic-php-sdk](https://github.com/elgentos/prismicio-php-kit). See [issue PR190 at prismicio/php-kit](https://github.com/prismicio/php-kit/pull/190#issuecomment-1242801946)

# Prismic Eloquent
Use the Prismic Api in a more (friendly) eloquent like way.

- Runs on the latest Prismic api (v2)
- Easy query writing
- Relationship resolving with hasOne and hasMany
- Support eager loading with the Prismic fetchLinks

### Documentation
[https://prismic-eloquent.gitbook.io/docs/](https://prismic-eloquent.gitbook.io/docs/)

### Example project
[https://prismic-eloquent-blog.herokuapp.com/](https://prismic-eloquent-blog.herokuapp.com/)

[https://github.com/robindrost/prismic-eloquent-blog](https://github.com/robindrost/prismic-eloquent-blog)
